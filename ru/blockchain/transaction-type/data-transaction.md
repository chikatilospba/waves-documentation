# Транзакция данных

**Транзакция данных** — [транзакция](/blockchain/transaction.md), которая записывает данные в [хранилище данных аккаунта](/blockchain/account/account-data-storage.md).

У каждой транзакции данных есть **массив данных**, который содержит данные для записи. В [JSON-представлении транзакции](#json-representation) массив данных — поле `data`.

## Массив данных

Максимальная длина массива — 100 элементов.

Максимальный размер массива — 150 килобайт.

Каждый элемент массива представляет собой объект, у которого есть 3 поля — `key`, `type`, `value`.

Массив не может содержать элементы с одинаковым значением поля key.

### Поле `key`

Поле `key` — непустая строка в кодировке [UTF-8](https://ru.wikipedia.org/wiki/UTF-8).

На этапе [валидации транзакции](/blockchain/transaction/transaction-validation.md) поле `key` конвертируется из кодировки UTF-8 в [UTF-16](https://ru.wikipedia.org/wiki/UTF-16). Размер получившегося массива 16-битных слов не должен превышать 100 элементов. Таким образом, размер ключа должен быть от 1 до 200 байтов включительно.

При отправке ключа без `type` и `value` выполняется удаление записи по ключу.

> Эта возможность доступна с версии ноды 1.2.0. Возможность включается с активацией на ноде функциональности "Ride V4 and multiple attached payments for Invoke Script Transaction" (№16).
На данный момент версии 1.2.x доступны на [stagenet](/blockchain/blockchain-network/stage-network.md)

При удалении ключа с использованием JSON-представления транзакции в качестве `type` и `value` ключа используется `null`. В одной транзакции данных возможно использование ключей как для записи, так и для удаления.

### Поле `type`

Поле type определяет тип поля value:

- binary
- boolean
- integer
- string

### Поле `value`

Размер поля `value` может составлять от 0 до 32767 байт.

## Бинарный формат

Смотрите страницу [Бинарный формат транзакции данных](/blockchain/binary-format/transaction-binary-format/data-transaction-binary-format.md).
