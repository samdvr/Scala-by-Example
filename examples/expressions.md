### Expressions

Expressions are blocks of code that return a value once they are executed.

Consider the following:

```scala
val myNumber: Int = 21

val squared = myNumber * myNumber
```

The value of squared has been evaluated after executing the expression
```scala
myNumber * myNumber
```

and it will have the result:

```scala
squared: Int = 441
```

Expressions can have many lines. The value of the last line is returned as the resulting value of the expression:

```scala
val cubeIsGreaterThanTen: Boolean = {
  val cubed = myNumber * myNumber * myNumber
  cubed > 10
}

```

Result:

```scala
cubeIsGreaterThanTen: Boolean = true
```
