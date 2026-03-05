# Exercise 1 — Higher-Order Functions in Kotlin

A simple Kotlin program that demonstrates how to build and use your own Higher-Order Function called `processList`.

## What it does
- Implements a custom `processList(numbers, predicate)` function from scratch
- Takes a list of integers and a lambda `(Int) -> Boolean`
- Returns only the elements that satisfy the predicate
- Tests the function with multiple different lambdas (even, odd, divisible by 3, range check, etc.)

## How to Run
1. Open the project folder in **IntelliJ IDEA**
2. Wait for Gradle to sync
3. Open `src/main/kotlin/Main.kt`
4. Click the green ▶ **Run** button next to `fun main()`

## Sample Output
```
even = processList(nums) { it % 2 == 0 }
Result: [2, 4, 6]

Even numbers        → [2, 4, 6, 8, 10, 12, 20, 30]
Odd numbers         → [1, 3, 5, 7, 9, 11, 15, 25]
Greater than 10     → [11, 12, 15, 20, 25, 30]
Divisible by 5      → [5, 10, 15, 20, 25, 30]
```

## Tech Stack
- Kotlin 1.9.24
- Gradle 8.8
- JDK 17
