### Hello World

Let's create our first program!
We first create a file named ```HelloWorld.scala```

with the following content:

```scala
object HelloWorld {
  def main(args: Array[String]): Unit = {
    println("Hello, world!")
  }
}
```

Compile the file using:

```scalac HelloWorld.scala```

Now let's run the bytecode.

``` scala HelloWorld ```

Result:
```
Hello, world!
```