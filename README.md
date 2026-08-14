# Java Exception Handling

A simple Java program demonstrating how to handle errors using exception handling in Java.

## 📌 Topics Covered

* `try` block
* `catch` block
* `ArithmeticException`
* Exception handling
* Program execution after an exception

## 📂 Project Structure

```text
java-exception-handling/
│
├── ExceptionHandling.java
└── README.md
```

## 💻 Program

The `ExceptionHandling.java` program demonstrates how to handle an `ArithmeticException` when attempting to divide a number by zero.

## 🔹 What is Exception Handling?

**Exception handling** is a mechanism used to handle runtime errors so that the program can continue or terminate gracefully instead of stopping unexpectedly.

## 🔹 try Block

The `try` block contains code that may cause an exception.

```java
try {
    int result = a / b;
}
```

## 🔹 catch Block

The `catch` block handles the exception.

```java
catch (ArithmeticException e) {
    System.out.println("Error: Cannot divide by zero.");
}
```

## 📊 Common Keywords

| Keyword   | Description                                 |
| --------- | ------------------------------------------- |
| `try`     | Contains code that may cause an exception   |
| `catch`   | Handles an exception                        |
| `finally` | Executes whether an exception occurs or not |
| `throw`   | Used to explicitly throw an exception       |
| `throws`  | Declares exceptions that a method may throw |

## ▶️ How to Run

### Compile

```bash
javac ExceptionHandling.java
```

### Run

```bash
java ExceptionHandling
```

## 🖥️ Sample Output

```text
Error: Cannot divide by zero.
Program continues...
```

## 🎯 Purpose

This project is designed for Java beginners to understand the basics of exception handling and how to prevent runtime errors from stopping a program unexpectedly.

## 👨‍💻 Author

K.Leelasri

## 📄 License

This project is for educational purposes.
# -java-exception-handling
