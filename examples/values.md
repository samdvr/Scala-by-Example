### Values

Values are defined using the 'val' keyword:

```Scala
val name: String = "Sherlock"
```
Result:
```Scala
name: String = Sherlock
```


Unlike Variables in Scala, Values cannot change once declared.
Reassignment of values will cause a compile time error.

```Scala
name = "John"
error: reassignment to val
       name = "John" 
```

Hence, Values in Scala are immutable.
