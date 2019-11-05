# Summary

## Начало работы

* [Новости](README.md)
* [Руководство пользователя](getting-started/getting-started-for-users.md)
* [Руководство разработчика](getting-started/getting-started-for-developers.md)

## Блокчейн

* [Аккаунт](blockchain/account.md)
  * [dApp](blockchain/account/dapp.md)
  * [Адрес](blockchain/account/address.md)
  * [Баланс аккаунта](blockchain/account/account-balance.md)
  * [Псевдоним](blockchain/account/alias.md)
  * [Смарт-аккаунт](blockchain/account/smart-account.md)
  * [Хранилище данных аккаунта](blockchain/account/account-data-storage.md)
* [Бинарный формат](blockchain/binary-format.md)
  * [Бинарный формат адреса](blockchain/binary-format/address-binary-format.md)
  * [Бинарный формат ордера](blockchain/binary-format/order-binary-format.md)
  * [Бинарный формат псевдонима](blockchain/binary-format/alias-binary-format.md)
  * [Бинарный формат транзакции](blockchain/binary-format/transaction-binary-format.md)
    * [Бинарный формат транзакции вызова скрипта](blockchain/binary-format/transaction-binary-format/invoke-script-transaction-binary-format.md)
    * [Бинарный формат транзакции выпуска](blockchain/binary-format/transaction-binary-format/issue-transaction-binary-format.md)
    * [Бинарный формат транзакции генезиса](blockchain/binary-format/transaction-binary-format/genesis-transaction-binary-format.md)
    * [Бинарный формат транзакции данных](blockchain/binary-format/transaction-binary-format/data-transaction-binary-format.md)
    * [Бинарный формат транзакции довыпуска](blockchain/binary-format/transaction-binary-format/reissue-transaction-binary-format.md)
    * [Бинарный формат транзакции лизинга](blockchain/binary-format/transaction-binary-format/lease-transaction-binary-format.md)
    * [Бинарный формат транзакции массового перевода](blockchain/binary-format/transaction-binary-format/mass-transfer-transaction-binary-format.md)
    * [Бинарный формат транзакции обмена](blockchain/binary-format/transaction-binary-format/exchange-transaction-binary-format.md)
    * [Бинарный формат транзакции отмены лизинга](blockchain/binary-format/transaction-binary-format/lease-cancel-transaction-binary-format.md)
    * [Бинарный формат транзакции перевода](blockchain/binary-format/transaction-binary-format/transfer-transaction-binary-format.md)
    * [Бинарный формат транзакции сжигания токена](blockchain/binary-format/transaction-binary-format/burn-transaction-binary-format.md)
    * [Бинарный формат транзакции создания псевдонима](blockchain/binary-format/transaction-binary-format/alias-transaction-binary-format.md)
    * [Бинарный формат транзакции спонсирования](blockchain/binary-format/transaction-binary-format/sponsor-fee-transaction-binary-format.md)
    * [Бинарный формат транзакции установки скрипта ассета](blockchain/binary-format/transaction-binary-format/set-asset-script-transaction-binary-format.md)
    * [Бинарный формат транзакции установки скрипта](blockchain/binary-format/transaction-binary-format/set-script-transaction-binary-format.md)
* [Биржевая заявка](blockchain/order.md)
* [Блок](blockchain/block.md)
  * [Блок генезиса](blockchain/block/genesis-block.md)
  * [Временная метка блока](blockchain/block/block-timestamp.md)
  * [Высота блока](blockchain/block/block-height.md)
  * [Генерация блока](blockchain/block/block-generation.md)
    * [Базовая цель](blockchain/block/block-generation/base-target.md)
  * [Подпись блока](blockchain/block/block-signature.md)
* [Блокчейн](blockchain/blockchain.md)
  * [Высота блокчейна](blockchain/blockchain/blockchain-height.md)
  * [Типы данных блокчейна](blockchain/blockchain/blockchain-data-types.md)
* [Комиссия матчера](blockchain/matcher-fee.md)
* [Лизинг](blockchain/leasing.md)
* [Майнинг](blockchain/mining.md)
  * [Вознаграждение за майнинг](/blockchain/mining/mining-reward.md)
  * [Майнер](blockchain/mining/miner.md)
  * [Майнящий аккаунт](blockchain/mining/mining-account.md)
* [Нода](blockchain/node.md)
  * [Валидирующая нода](blockchain/node/validating-node.md)
  * [Майнящая нода](blockchain/node/mining-node.md)
* [Оракул](blockchain/oracle.md)
* [Сеть блокчейна](blockchain/blockchain-network.md)
  * [Байт сети](blockchain/blockchain-network/chain-id.md)
  * [Основная сеть](blockchain/blockchain-network/main-network.md)
  * [Тестовая сеть](blockchain/blockchain-network/test-network.md)
* [Тип транзакции](blockchain/transaction-type.md)
  * [Транзакция вызова скрипта](blockchain/transaction-type/invoke-script-transaction.md)
  * [Транзакция выпуска](blockchain/transaction-type/issue-transaction.md)
  * [Транзакция генезиса](blockchain/transaction-type/genesis-transaction.md)
  * [Транзакция данных](blockchain/transaction-type/data-transaction.md)
  * [Транзакция довыпуска](blockchain/transaction-type/reissue-transaction.md)
  * [Транзакция закрытия лизинга](blockchain/transaction-type/lease-cancel-transaction.md)
  * [Транзакция лизинга](blockchain/transaction-type/lease-transaction.md)
  * [Транзакция массового перевода](blockchain/transaction-type/mass-transfer-transaction.md)
  * [Транзакция обмена](blockchain/transaction-type/exchange-transaction.md)
  * [Транзакция перевода](blockchain/transaction-type/transfer-transaction.md)
  * [Транзакция сжигания токена](blockchain/transaction-type/burn-transaction.md)
  * [Транзакция создания псевдонима](blockchain/transaction-type/alias-transaction.md)
  * [Транзакция установки скрипта](blockchain/transaction-type/set-script-transaction.md)
  * [Транзакция установки скрипта ассета](blockchain/transaction-type/set-asset-script-transaction.md)
* [Токен](blockchain/token.md)
  * [ID токена](blockchain/token/token-id.md)
  * [WAVELET](blockchain/token/wavelet.md)
  * [WAVES](blockchain/token/waves.md)
  * [WCT](blockchain/token/wct.md)
  * [Не взаимозаменяемый токен](blockchain/token/non-fungible-token.md)
  * [Смарт-ассет](blockchain/token/smart-asset.md)
* [Транзакция](blockchain/transaction.md)
  * [ID транзакции](blockchain/transaction/transaction-id.md)
  * [Байты тела транзакции](blockchain/transaction/transaction-body-bytes.md)
  * [Валидация транзакции](blockchain/transaction/transaction-validation.md)
  * [Версия транзакции](blockchain/transaction/transaction-version.md)
  * [Временная метка транзакции](blockchain/transaction/transaction-timestamp.md)
  * [Комиссия за транзакцию](blockchain/transaction/transaction-fee.md)
  * [Подпись транзакции](blockchain/transaction/transaction-signature.md)
  * [Подтверждение транзакции](blockchain/transaction/transaction-proof.md)

## Client

* [Установка Waves приложения](waves-client/install-waves-client.md)
* [Заметки о безопасности](waves-client/security-notes.md)
* [Управление аккаунтом](waves-client/account-management.md)
  * [Создание аккаунта](waves-client/account-management/creating-an-account.md)
  * [Восстановление аккаунта](waves-client/account-management/restore-an-account.md)
  * [Ledger Nano S в Waves приложении](waves-client/account-management/ledger-nano.md)
  * [Waves Keeper](waves-keeper/how-to-use-waves-keeper.md)
  * [Вход в аккаунт](waves-client/account-management/signing-in-to-your-account.md)
  * [Ваш Waves адрес](waves-client/account-management/waves-address.md)
  * [Создание персонального Псевдонима](waves-client/account-management/creating-an-alias.md)
  * [Лизинг Waves токенов](waves-client/account-management/waves-leasing.md)
* [Переводы и шлюзы](waves-client/wallet-management.md)
  * [Переводы Waves](waves-client/transfers-and-gateways/waves-transfers.md)
  * [Переводы Waves Enterprise](waves-client/transfers-and-gateways/waves-enterprise-transfers.md)
  * [Переводы ассетов](waves-client/transfers-and-gateways/asset-transfers.md)
  * [Переводы Bitcoin](waves-client/transfers-and-gateways/bitcoin-transfers.md)
  * [Переводы Ethereum](waves-client/transfers-and-gateways/ethereum-transfers.md)
  * [Переводы Litecoin](waves-client/transfers-and-gateways/litecoin-transfers.md)
  * [Переводы Zcash](waves-client/transfers-and-gateways/zcash-transfers.md)
  * [Переводы Bitcoin Cash](waves-client/transfers-and-gateways/bitcoin-cash-transfers.md)
  * [Переводы Dash](waves-client/transfers-and-gateways/dash-transfers.md)
  * [Переводы Monero](waves-client/transfers-and-gateways/monero-transfers.md)
  * [Переводы Bitcoin SV](waves-client/transfers-and-gateways/bitcoin-sv-transfers.md)
  * [Переводы Ergo](waves-client/transfers-and-gateways/ergo-transfers.md)
  * [Переводы Bancor](waves-client/transfers-and-gateways/bancor-transfers.md)
  * [Перевод EUR и USD](waves-client/transfers-and-gateways/eur-usd-transfers.md)
  * [Покупка Waves с банковской карты](waves-client/transfers-and-gateways/buying-waves-using-card.md)
* [Управление ассетами](waves-client/assets-management.md)
  * [Создание токена](waves-client/assets-management/issue-an-asset.md)
  * [Перевыпуск токена](waves-client/assets-management/reissue-an-asset.md)
  * [Закрытие перевыпуска](waves-client/assets-management/reissuable-nonreissuable.md)
  * [Сжигание токена](waves-client/assets-management/burn-an-asset.md)
  * [Распределение токена](waves-client/assets-management/mass-transfer.md)
  * [Спонсорские транзакции](waves-client/assets-management/sponsored-transaction.md)
  * [Спонсорская комиссия](waves-client/assets-management/sponsored-fee.md)
* [Расширенные возможности](waves-client/advanced_features.md)
  * [Script транзакция](waves-client/advanced_features/script_transaction.md)
  * [JSON подтверждение](waves-client/advanced_features/json_confirmation.md)
* [Мобильные приложения](waves-client/mobile-apps.md)
  * [Мобильное приложение для iOS устройств](waves-client/mobile-apps/iOS.md)
    * [Управление аккаунтом (iOS)](waves-client/mobile-apps/iOS/account-management.md)
      * [Создание аккаунта (iOS)](waves-client/mobile-apps/iOS/account-management/creating-an-account.md)
      * [Восстановление аккаунта (iOS)](waves-client/mobile-apps/iOS/account-management/restore-an-account.md)
      * [Вход в аккаунт (iOS)](waves-client/mobile-apps/iOS/account-management/signing-in-to-your-account.md)
      * [Ваш Waves адрес (iOS)](waves-client/mobile-apps/iOS/account-management/waves-address.md)
      * [Создание персонального Псевдонима (iOS)](waves-client/mobile-apps/iOS/account-management/creating-an-alias.md)
      * [Лизинг Waves токенов (iOS)](waves-client/mobile-apps/iOS/account-management/waves-leasing.md)
    * [Управление ассетами (iOS)](waves-client/mobile-apps/iOS/assets-management.md)
      * [Сжигание токена (iOS)](waves-client/mobile-apps/iOS/assets-management/burn-an-asset.md)
    * [Переводы и шлюзы (iOS)](waves-client/mobile-apps/iOS/wallet-management.md)
      * [Переводы Waves (iOS)](waves-client/mobile-apps/iOS/transfers-and-gateways/waves-transfers.md)
      * [Переводы Waves Enterprise (iOS)](waves-client/mobile-apps/iOS/transfers-and-gateways/waves-enterprise-transfers.md)
      * [Переводы ассетов (iOS)](waves-client/mobile-apps/iOS/transfers-and-gateways/asset-transfers.md)
      * [Переводы Bitcoin (iOS)](waves-client/mobile-apps/iOS/transfers-and-gateways/bitcoin-transfers.md)
      * [Переводы Ethereum (iOS)](waves-client/mobile-apps/iOS/transfers-and-gateways/ethereum-transfers.md)
      * [Переводы Litecoin (iOS)](waves-client/mobile-apps/iOS/transfers-and-gateways/litecoin-transfers.md)
      * [Переводы Zcash (iOS)](waves-client/mobile-apps/iOS/transfers-and-gateways/zcash-transfers.md)
      * [Переводы Bitcoin Cash (iOS)](waves-client/mobile-apps/iOS/transfers-and-gateways/bitcoin-cash-transfers.md)
      * [Переводы Dash (iOS)](waves-client/mobile-apps/iOS/transfers-and-gateways/dash-transfers.md)
      * [Переводы Monero (iOS)](waves-client/mobile-apps/iOS/transfers-and-gateways/monero-transfers.md)
      * [Переводы Bitcoin SV (iOS)](waves-client/mobile-apps/iOS/transfers-and-gateways/bitcoin-sv-transfers.md)
      * [Покупка Waves с банковской карты](waves-client/mobile-apps/iOS/transfers-and-gateways/buying-waves-using-card.md)
    * [Waves DEX (iOS)](waves-client/mobile-apps/iOS/waves-dex/about-waves-dex.md)
      * [Использование биржи DEX (iOS)](waves-client/mobile-apps/iOS/waves-dex/start-trading-on-the-waves-dex.md)
  * [Мобильное приложение для Android устройств](waves-client/mobile-apps/android.md)
    * [Управление аккаунтом (Android)](waves-client/mobile-apps/android/account-management.md)
      * [Создание аккаунта (Android)](waves-client/mobile-apps/android/account-management/creating-an-account.md)
      * [Восстановление аккаунта (Android)](waves-client/mobile-apps/android/account-management/restore-an-account.md)
      * [Вход в аккаунт (Android)](waves-client/mobile-apps/android/account-management/signing-in-to-your-account.md)
      * [Ваш Waves адрес (Android)](waves-client/mobile-apps/android/account-management/waves-address.md)
      * [Создание персонального Псевдонима (Android)](waves-client/mobile-apps/android/account-management/creating-an-alias.md)
      * [Лизинг Waves токенов (Android)](waves-client/mobile-apps/android/account-management/waves-leasing.md)
    * [Управление ассетами (Android)](waves-client/mobile-apps/android/assets-management.md)
      * [Сжигание токена (Android)](waves-client/mobile-apps/android/assets-management/burn-an-asset.md)
    * [Переводы и шлюзы (Android)](waves-client/mobile-apps/android/wallet-management.md)
      * [Переводы Waves (Android)](waves-client/mobile-apps/android/transfers-and-gateways/waves-transfers.md)
      * [Переводы Waves Enterprise (Android)](waves-client/mobile-apps/android/transfers-and-gateways/waves-enterprise-transfers.md)
      * [Переводы ассетов (Android)](waves-client/mobile-apps/android/transfers-and-gateways/asset-transfers.md)
      * [Переводы Bitcoin (Android)](waves-client/mobile-apps/android/transfers-and-gateways/bitcoin-transfers.md)
      * [Переводы Ethereum (Android)](waves-client/mobile-apps/android/transfers-and-gateways/ethereum-transfers.md)
      * [Переводы Litecoin (Android)](waves-client/mobile-apps/android/transfers-and-gateways/litecoin-transfers.md)
      * [Переводы Zcash (Android)](waves-client/mobile-apps/android/transfers-and-gateways/zcash-transfers.md)
      * [Переводы Bitcoin Cash (Android)](waves-client/mobile-apps/android/transfers-and-gateways/bitcoin-cash-transfers.md)
      * [Переводы Dash (Android)](waves-client/mobile-apps/android/transfers-and-gateways/dash-transfers.md)
      * [Переводы Monero (Android)](waves-client/mobile-apps/android/transfers-and-gateways/monero-transfers.md)
      * [Переводы Bitcoin SV (Android)](waves-client/mobile-apps/android/transfers-and-gateways/bitcoin-sv-transfers.md)
      * [Покупка Waves с банковской карты (Android)](waves-client/mobile-apps/android/transfers-and-gateways/buying-waves-using-card.md)
    * [Waves DEX (Android)](waves-client/mobile-apps/android/waves-dex/about-waves-dex.md)
      * [Использование биржи DEX (Android)](waves-client/mobile-apps/android/waves-dex/start-trading-on-the-waves-dex.md)

* [Часто задаваемые вопросы](waves-client/faq.md)
  * [Подозрительные транзакции](waves-client/security/spam-transactions.md)
  * [Один Seed - Один Waves адрес](waves-client/frequently-asked-questions-faq/account-management/one-seed.md)
  * [Что такое SEED фраза?](waves-client/frequently-asked-questions-faq/account-management/seed-phrase.md)
  * [У меня есть достаточно Waves, но я не могу открыть ордер](waves-client/frequently-asked-questions-faq/account-management/waves-fee.md)
  * [Как получить достаточно Waves для оплаты комиссии?](waves-client/frequently-asked-questions-faq/waves-dex/enough-waves.md)
  * [Время исполнения ордера](waves-client/frequently-asked-questions-faq/waves-dex/order-time.md)
  * [Поиск токена на бирже DEX используя Asset ID](waves-client/frequently-asked-questions-faq/waves-dex/asset-id.md)
  * [Что такое платежный шлюз?](waves-client/frequently-asked-questions-faq/transfers-and-gateways/payment-gateway.md)
  * [Обработка Ethereum платежей и смарт-контракты](waves-client/frequently-asked-questions-faq/transfers-and-gateways/ethereum-smartcontract-transfers.md)
  * [Что такое эйрдроп \(Airdrop\)?](waves-client/frequently-asked-questions-faq/transfers-and-gateways/airdrop.md)
  * [Активация Ночного режима?](waves-client/frequently-asked-questions-faq/account-management/dark-mode.md)

## DEX

* [О Waves DEX](waves-dex/about-waves-dex.md)
* [Использование биржи DEX](waves-dex/start-trading-on-the-waves-dex.md)

## Explorer

* [О Waves Explorer](waves-explorer/about-waves-explorer.md)
* [Пополнение баланса аккаунта в тестовой сети](waves-explorer/account-balance-top-up-in-the-test-network.md)

## Keeper

* [О Waves Keeper](waves-keeper/about-waves-keeper.md)
* [Начало работы с Waves Keeper](waves-keeper/how-to-use-waves-keeper.md)

## RIDE

* [О RIDE](ride/about-ride.md)
* [Базовые понятия](ride/base-concepts.md)
  * [Выражение](ride/base-concepts/expression.md)
  * [Определение](ride/base-concepts/definition.md)
  * [Сложность](ride/base-concepts/complexity.md)
* [Исключения](ride/exceptions.md)
* [Комментарии](ride/comments.md)
* [Константы](ride/constants.md)
* [Операторы](ride/operators.md)
* [Переменные](ride/variables.md)
  * [Встроенные переменные](ride/variables/built-in-variables.md)
* [Скрипт](ride/script.md)
  * [Директивы](ride/script/directives.md)
  * [Контекст скрипта](ride/script/script-context.md)
  * [Стандартная библиотека](ride/script/standard-library.md)
  * [Тело скрипта](ride/script/script-body.md)
  * [Типы скриптов](ride/script/script-types.md)
    * [dApp-скрипт](ride/script/script-types/dapp-script.md)
    * [Скрипт аккаунта](ride/script/script-types/account-script.md)
    * [Скрипт ассета](ride/script/script-types/asset-script.md)
* [Структуры](ride/structures.md)
  * [Общие структуры](ride/structures/common-structures.md)
    * [Address](ride/structures/common-structures/address.md)
    * [Alias](ride/structures/common-structures/alias.md)
    * [Asset](ride/structures/common-structures/asset.md)
    * [AssetPair](ride/structures/common-structures/asset-pair.md)
    * [AttachedPayment](ride/structures/common-structures/attached-payment.md)
    * [BlockInfo](ride/structures/common-structures/block-info.md)
    * [DataEntry](ride/structures/common-structures/data-entry.md)
    * [Invocation](ride/structures/common-structures/invocation.md)
    * [Order](ride/structures/common-structures/order.md)
    * [ScriptResult](ride/structures/common-structures/script-result.md)
    * [ScriptTransfer](ride/structures/common-structures/script-transfer.md)
    * [Transfer](ride/structures/common-structures/transfer.md)
    * [TransferSet](ride/structures/common-structures/transfer-set.md)
    * [WriteSet](ride/structures/common-structures/write-set.md)
  * [Структуры транзакций](ride/structures/transaction-structures.md)
    * [BurnTransaction](ride/structures/transaction-structures/burn-transaction.md)
    * [CreateAliasTransaction](ride/structures/transaction-structures/create-alias-transaction.md)
    * [DataTransaction](ride/structures/transaction-structures/data-transaction.md)
    * [ExchangeTransaction](ride/structures/transaction-structures/exchange-transaction.md)
    * [GenesisTransaction](ride/structures/transaction-structures/genesis-transaction.md)
    * [InvokeScriptTransaction](ride/structures/transaction-structures/invoke-script-transaction.md)
    * [IssueTransaction](ride/structures/transaction-structures/issue-transaction.md)
    * [LeaseCancelTransaction](ride/structures/transaction-structures/lease-cancel-transaction.md)
    * [LeaseTransaction](ride/structures/transaction-structures/lease-transaction.md)
    * [MassTransferTransaction](ride/structures/transaction-structures/mass-transfer-transaction.md)
    * [ReissueTransaction](ride/structures/transaction-structures/reissue-transaction.md)
    * [SetAssetScriptTransaction](ride/structures/transaction-structures/set-asset-script-transaction.md)
    * [SetScriptTransaction](ride/structures/transaction-structures/set-script-transaction.md)
    * [TransferTransaction](ride/structures/transaction-structures/transfer-transaction.md)
* [Типы данных](ride/data-types.md)
  * [Boolean](ride/data-types/boolean.md)
  * [ByteVector](ride/data-types/byte-vector.md)
  * [Int](ride/data-types/int.md)
  * [List](ride/data-types/list.md)
  * [String](ride/data-types/string.md)
  * [Unit](ride/data-types/unit.md)
  * [Тип данных объединения](ride/data-types/union.md)
* [Функции](ride/functions.md)
  * [Аннотации](ride/functions/annotations.md)
  * [Встроенные функции](ride/functions/built-in-functions.md)
    * [Математические функции](ride/functions/built-in-functions/math-functions.md)
    * [Функции блокчейна](ride/functions/built-in-functions/blockchain-functions.md)
    * [Функции верификации](ride/functions/built-in-functions/verification-functions.md)
    * [Функции декодирования](ride/functions/built-in-functions/decoding-functions.md)
    * [Функции исключения](ride/functions/built-in-functions/exception-functions.md)
    * [Функции кодирования](ride/functions/built-in-functions/encoding-functions.md)
    * [Функции конвертации](ride/functions/built-in-functions/converting-functions.md)
    * [Функции массива байтов](ride/functions/built-in-functions/byte-array-functions.md)
    * [Функции объединения](ride/functions/built-in-functions/union-functions.md)
    * [Функции списка](ride/functions/built-in-functions/list-functions.md)
    * [Функции строки](ride/functions/built-in-functions/string-functions.md)
    * [Функции транзакции данных](ride/functions/built-in-functions/data-transaction-functions.md)
    * [Функции хеширования](ride/functions/built-in-functions/hashing-functions.md)
    * [Функции хранилища данных аккаунта](ride/functions/built-in-functions/account-data-storage-functions.md)
  * [Вызываемая функция](ride/functions/callable-function.md)
  * [Функция-верификатор](ride/functions/verifier-function.md)

## Программирование

* [Инструменты](smart-contracts/tools.md)
  * [REPL](smart-contracts/tools/repl.md)
  * [Waves IDE](smart-contracts/tools/waves-ide.md)
* [Что такое смарт-ассет](smart-contracts/what-is-smart-asset.md)
* [Что такое dApp](smart-contracts/what-is-a-dapp.md)
* [Написание dApps](smart-contracts/writing-dapps.md)
* [Простое голосование на блокчейне Waves](smart-contracts/simple-voting-on-the-waves-blockchain.md)
* [Статьи о dApps](smart-contracts/articles-on-dapps.md)

## Node

* [Node API](waves-node/node-api.md)
* [Предварительные требования](waves-node/prerequisites.md)
  * [Требования к аппаратному обеспечению](waves-node/prerequisites/hardware-requirements.md)
* [Запуск Waves Node в Яндекс.Облаке](waves-node/running-waves-node-in-yandex-cloud.md)
* [Ограничения API пула публичных нод](waves-node/api-limitations-of-the-pool-of-public-nodes.md)
* [Расширения](waves-node/extensions.md)
  * [gRPC Server](waves-node/extensions/grpc-server.md)
    * [Установка gRPC Server](waves-node/extensions/grpc-server/grpc-server-installation.md)
  * [Матчер](waves-node/extensions/matcher.md)
    * [Установка матчера на Ubuntu из deb-пакета](/waves-node/extensions/matcher/matcher-install-ubuntu-deb.md)
* [Обновление Ноды Waves](waves-node/upgrading.md)  

## API and SDK

* [Клиентские библиотеки](waves-api-and-sdk/client-libraries.md)

## Oracles

* [О Waves Oracles](waves-oracles/about-waves-oracles.md)
* [Создание карточки оракула при помощи Waves Oracle](waves-oracles/create-an-oracle-card-with-waves-oracle.md)
* [Создание карточки оракула при помощи транзакции данных](waves-oracles/create-an-oracle-card-with-a-data-transaction.md)
* [Карточка оракула](waves-oracles/oracle-card.md)
* [Обновление карточки оракула](waves-oracles/updating-oracle-card.md)
* [Инструмент отправки транзакций данных](/waves-oracles/data-transaction-tool.md)
* [Как создать оракул](waves-oracles/how-to-create-an-oracle.md)

## Token Rating

* [О Waves Token Rating](waves-token-rating/about-waves-token-rating.md)
* [Интерфейс пользователя](waves-token-rating/user-interface.md)
* [Формула рейтинга](waves-token-rating/rating-formula.md)
* [Транзакция данных с оценкой пользователя](waves-token-rating/data-transaction-with-user-s-rate.md)
* [Транзакция данных оракула Token Rating](waves-token-rating/data-transaction-of-the-token-rating-oracle.md)
* [Управление токеном](waves-token-rating/token-management.md)

## Разное

* [Компоненты платформы](overview/platform-components.md)
* [Протокол активации](platform-features/activation-protocol.md)
* [Assets Custom Tokens](platform-features/assets-custom-tokens.md)
* [Децентрализованная биржа (DEX)](platform-features/decentralized-cryptocurrency-exchange-dex.md)
* [Fair Pos](platform-features/fair-pos.md)
* [Leased Proof Of Stake (Lpos)](platform-features/leased-proof-of-stake-lpos.md)
* [Официальные ресурсы](overview/waves-official-resources.md)
* [Архив новостей](miscellaneous/news-archive.md)

### Глоссарий

* [Глоссарий](glossary/glossary.md)