### If/Else Expressions

The basic structure of if/else conditionals in Scala is:

```scala
if (condition) {
  expression to execute when condition is true
} else {
  expression to execute when condition is false
}

```
Consider the following example:

```scala
val x = 10
val y = 30
val max = if (x > y) {
    x
  } else {
    y
  }

```
Because the conditionals are expression in Scala it is possible to assign them
to values.
Each branch of the condition and also the condition x > y is also an expression.
We can omit curly braces for expressions with one line.

```scala
val max = if (x > y) x  else y
```
