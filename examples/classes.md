# Classes

Classes are a blueprint for creating objects. 

## Defining a Class

```scala
class Book(name: String, author: String) {
  def title = name + " by " + author
}

```

## Creating an Object

Object Instantiation is done using the new keyword

```scala
val myBook = new Book("Sherlock Holmes", "Arthur Conan Doyle")

myBook.title

```

Result:

```scala
res0: String = Sherlock Holmes by Arthur Conan Doyle
```
