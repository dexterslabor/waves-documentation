# Функции

Функция должна возвращать значение. Тип возвращаемого значения в сигнатуре функции не указывается.

Функция должна быть объявлена выше места ее использования.

Функция может быть [аннотирована](/ride/functions/annotations.md).

В RIDE есть множество [встроенных функций](/ride/functions/built-in-functions.md).

При объявлении функции справа от знака "=" должно находиться [выражение](/ride/base-concepts/expression.md). Значение функции — [результат выражения](/ride/base-concepts/expression.md#expression-result).

## Примеры

Определение функции без параметров, которая возвращает целое число:

``` ride
func main() = {
   3
}
```

Определение функции с двумя параметрами:

``` ride
func main(amount: Int, name: String) = {
   throw()
}
```
