# Swift Functions Tutorial
[Home](README.md)

## Writing Functions in Swift

### Overview
In Swift, functions are a fundamental building block for organizing and structuring your code. They allow you to encapsulate a set of instructions and reuse them throughout your program. This tutorial will guide you through the process of creating functions in Swift.

### Prerequisites
Make sure you have a basic understanding of Swift syntax and how to work with Xcode or any Swift-compatible development environment.

### Writing Your First Function
Let's start by creating a simple function that prints a greeting message.

```swift
func greet() {
    print("Hello, Swift!")
}

// Call the function
greet()

Function with Parameters
Functions can also take parameters to receive input values. Let's create a function that greets a specific person.
func greet(name: String) {
    print("Hello, \(name)!")
}

// Call the function with an argument
greet(name: "Alice")
****

