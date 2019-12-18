# Функции объединения

| # | Name | Description | Complexity |
| :--- | :--- | :--- | :--- |
| 1 | [extract(T&#124;Unit): T](#extract) | Возвращает значение из параметра типа данных [объединение](/ride/data-types/union.md).<br>Выбрасывает исключение, если параметром является [unit](/ride/data-types/unit.md) | 13 |
| 2 | [isDefined(List[T]&#124;Unit): Boolean](#isDefined) | Проверяет, относится ли значение параметра к типу [unit](/ride/data-types/unit.md) | 1 |
| 3 | [value(T&#124;Unit): T](#value) | Возвращает значение из параметра типа данных [объединение](/ride/data-types/union.md).<br>Выбрасывает исключение, если параметром является [unit](/ride/data-types/unit.md) | 13 |
| 4 | [valueOrErrorMessage(T&#124;Unit, String): T](#value-error) | Возвращает значение из параметра типа данных [объединение](/ride/data-types/union.md).<br>Если параметром является [unit](/ride/data-types/unit.md), возвращает сообщение об ошибке, заданное во втором параметре | 13 |

## extract(T|Unit): T<a id="extract"></a>

Возвращает значение из параметра типа данных [объединение](/ride/data-types/union.md).

Выбрасывает исключение, если параметром является [unit](/ride/data-types/unit.md).

``` ride
extract(a: T|Unit): T
```

### Параметры

#### `a`: T|Unit

Параметр типа данных [объединение](/ride/data-types/union.md).

## isDefined(List[T]|Unit): T<a id="isDefined"></a>

Проверяет, относится ли значение параметра к типу [unit](/ride/data-types/unit.md).

```ride
isDefined(a: List[T]|Unit): Boolean
```

### Параметры

#### a: T|Unit

Проверяемое значение.

### Пример

```ride
let value = getString(this, "some key")
if isDefined(value) then
    value.extract() == "expected value"
else
    throw("data entry with key 'some key' doesn't exist")
```

## value(T|Unit): T<a id="value"></a>

Возвращает значение из параметра типа данных [объединение](/ride/data-types/union.md).

Выбрасывает исключение, если параметром является [unit](/ride/data-types/unit.md).

``` ride
value(a: T|Unit): T
```

### Параметры

#### a: T|Unit

Параметр типа данных [объединение](/ride/data-types/union.md).

## valueOrErrorMessage(T|Unit, String): T<a id="value-error"></a>

Возвращает значение из параметра типа данных [объединение](/ride/data-types/union.md).

Если параметром является [unit](/ride/data-types/unit.md), возвращает сообщение об ошибке, заданное во втором параметре.

``` ride
valueOrErrorMessage(a: T|Unit, msg: String): T
```

### Параметры

#### a: T|Unit

Параметр типа данных [объединение](/ride/data-types/union.md).

#### msg: String

Сообщение об ошибке.
