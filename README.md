## Conditional Statements in Java

Conditional statements in Java allow you to control the flow of your program based on certain conditions. The primary conditional statements in Java are `if`, `if-else`, and nested `if-else`.

### 1. `if` Statement

The `if` statement in Java is used to execute a block of code only if a specified condition is true. It has the following syntax:

```java
if (condition) {
    // code to be executed if the condition is true
}
```
Example:

```java
int x = 10;
if (x > 5) {
    System.out.println("x is greater than 5");
}
```

### 2. else if Statement
The else if statement allows you to specify a new condition if the previous condition is false. It allows for multiple conditions to be checked. It has the following syntax:

```java
if (condition1) {
    // code to be executed if condition1 is true
} else if (condition2) {
    // code to be executed if condition2 is true
} else {
    // code to be executed if all conditions are false
}
```
Example:

```java
int y = 20;
if (y > 10) {
    System.out.println("y is greater than 10");
} else if (y < 10) {
    System.out.println("y is less than 10");
} else {
    System.out.println("y is equal to 10");
}
```

### 3. else Statement
The else statement is used to execute a block of code if the condition of the if statement is false. It has the following syntax:

```java
if (condition) {
    // code to be executed if the condition is true
} else {
    // code to be executed if the condition is false
}
```
Example:

```java
int z = 5;
if (z > 10) {
    System.out.println("z is greater than 10");
} else {
    System.out.println("z is not greater than 10");
}
```

### 4. Nested if-else Statement
Nested if-else statements allow you to include one if-else statement inside another. This allows for more complex conditional logic. It has the following syntax:

```java
if (condition1) {
    // code to be executed if condition1 is true
    if (condition2) {
        // code to be executed if both condition1 and condition2 are true
    } else {
        // code to be executed if condition1 is true and condition2 is false
    }
} else {
    // code to be executed if condition1 is false
}
```
Example:

```java
int z = 5;
if (z > 10) {
    System.out.println("z is greater than 10");
} else if (z < 10) {
    System.out.println("z is less than 10");
} else {
    System.out.println("z is equal to 10");
}
```
## Contribution

Contributions to this project are welcome. If you have any suggestions for improvements or new features, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

