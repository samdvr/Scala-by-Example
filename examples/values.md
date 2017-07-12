### Values

Values are defined using the 'val' keyword:

```scala
val name: String = "Sherlock"
```
Result:
```scala
name: String = Sherlock
```


Unlike Variables in Scala, Values cannot change once declared.
Reassignment of values will cause a compile time error.

```scala
name = "John"
error: reassignment to val
       name = "John"
```

Hence, Values in Scala are immutable.
