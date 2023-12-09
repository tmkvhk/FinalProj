# Loops in Swift

## Overview

Loops are essential control flow structures in programming, allowing you to repeat a set of instructions multiple times. In Swift, there are two primary types of loops: `for-in` and `while`. Let's explore each of them.

## For-In Loop

The `for-in` loop in Swift is used to iterate over a sequence, such as a range of numbers, an array, or a string. Its basic syntax is as follows:

```swift
for item in sequence {
    // Code to execute for each item
}

The while loop continues to execute a block of code as long as a specified condition is true. Its syntax is as follows:
while condition {
    // Code to execute while the condition is true
}

EXAMPLE
var count = 0

while count < 5 {
    print("Current count is \(count)")
    count += 1
}


