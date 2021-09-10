# Polymorphism practice: IncrementerSynchronizer

## Repo
**GitHub repo:** [ebd-polymorphism-interfaces-incrementer-synchronizer](https://github.com/LambdaSchool/ebd-polymorphism-interfaces-incrementer-synchronizer)

## Background

In this activity we will get more practice writing polymorphic code. We
will write a class that will manage an `ArrayList` of `Incrementable` objects,
and a `main()` method to interact with the `ArrayList`.


## Instructions
### Create the class

Create a new class called `IncrementerSynchronizer` in the
`src/com/amazon/ata/interfaces/increment` directory.

### Create the constructor

We want our constructor to accept an `ArrayList` of `Incrementable` objects,
and save it to an internal field. This is the list of
incrementers that the `IncrementerSynchronizer` will be managing.

### Write a method to report the current value for each incrementer

Define a method `void reportValues()` that iterates over the
incrementers and prints out each incrementer's value.

Example output: 

  Incrementer 0 - Value: 0
  Incrementer 1 - Value: 2
  Incrementer 2 - Value: 34

### Write a `main()` method to interact with your class

Define an empty `main()` method:
```
public static void main(String[] args) {

}
```

### Call your `reportValues()` method

Inside your `main()` method, create an instance of
`IncrementerSynchronizer`. This will require you to first create the
data that the `IncrementerSynchronizer` constructor requires. Include at
least three unique incrementers in your `ArrayList`. You may use any of
the incrementers that you have created in class (and have verified that
they work as expected).

Once you have your `IncrementerSynchronizer` object, add a call to
`reportValues()`. Run `main()` and verify that the initial state of your
incrementers is correct, depending on if you started them at the default
start value or a different specified start value.

### Add an `incrementAll()` method

Define a method `void incrementAll()` in `IncrementerSynchronizer` that
iterates over the incrementers and increments each one. Add a call to
`incrementAll()` in your `main()` method and then call `reportValues()`
again to validate that the updated incrementers' states match your
expectations. Once you have this working, update your main method to
make a few calls to `incrementAll()`, reporting the incrementers values
after each.

## Doneness

You are done when:
- Your `IncrementerSynchronizer` has at least three `Incrementable`s
  in its list
- Your `main()` method reports the correct incrementer values before and
  after several calls to `incrementAll()`
- You feel a little more comfortable with polymorphism and using variables
  that are declared to be of interface types. (If not, ask your group for
  help!)

## Commit & Push

Commit your changes and push to remote.
