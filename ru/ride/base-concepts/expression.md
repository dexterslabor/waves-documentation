# Выражение

**Выражение** — комбинация из одной или более [констант](/ride/constants.md), [переменных](/ride/variables.md), [операторов](/ride/operators.md) и _вызовов_ [функций](/ride/functions.md).

RIDE интерпретирует выражение и вычисляет его _результат_.

<a id="expression-result"></a>
**Результат выражения** — значение, которое получается при [свертке](https://en.wikipedia.org/wiki/Fold_%28higher-order_function%29) [синтаксического дерева](https://ru.wikipedia.org/wiki/Абстрактное_синтаксическое_дерево) выражения.

<a id="expression-type"></a>
**Тип выражения** — [тип данных](/ride/data-types.md) результата выражения.

## Примеры

Выражение, которое состоит из одной константы.

``` ride
7
```

Выражение, которое состоит из одной переменной.

``` ride
x
```

Выражение, которое состоит из константы `7`, операторов `+` и `*`, переменной `x` и вызова функции `size`.

``` ride
7 + x * size("apple")
```
