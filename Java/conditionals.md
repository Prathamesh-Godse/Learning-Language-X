# Conditionals

## 🔹 1. `if`, `else if`, `else`

### ➤ Syntax:

```java
if (condition) {
    // code block runs if condition is true
} else if (anotherCondition) {
    // runs if the above is false and this is true
} else {
    // runs if none of the above conditions are true
}
```

### ➤ Example:

```java
int number = 10;

if (number > 0) {
    System.out.println("Positive");
} else if (number == 0) {
    System.out.println("Zero");
} else {
    System.out.println("Negative");
}
```

#### ✅ Points to Remember:

- Condition must be a boolean expression (true/false).
    
- Curly braces `{}` are optional for single statements, but always recommended.
    

---

## 🔹 2. Nested `if`

You can put one `if` inside another:

```java
int age = 25;
boolean hasLicense = true;

if (age >= 18) {
    if (hasLicense) {
        System.out.println("Can drive");
    } else {
        System.out.println("No license");
    }
} else {
    System.out.println("Too young to drive");
}
```

---

## 🔹 3. Ternary Operator (`? :`) – Short `if-else`

```java
String result = (age >= 18) ? "Adult" : "Minor";
```

---

## 🔹 4. `switch` Statement

Used to test a variable against multiple values.

### ➤ Syntax:

```java
switch (expression) {
    case value1:
        // code
        break;
    case value2:
        // code
        break;
    default:
        // code
}
```

### ➤ Example:

```java
int day = 3;

switch (day) {
    case 1:
        System.out.println("Monday");
        break;
    case 2:
        System.out.println("Tuesday");
        break;
    case 3:
        System.out.println("Wednesday");
        break;
    default:
        System.out.println("Invalid day");
}
```

#### ✅ Points to Remember:

- `switch` expression must be a constant or variable of:
    
    - `byte`, `short`, `int`, `char`, `enum`, `String`
        
- `break` prevents _fall-through_ to next case.
    
- `default` is optional and runs if no match is found.
    

---

## 🔸 `switch` in Java 14+ (New Syntax)

Java 14 introduced a more expressive form:

```java
String result = switch (day) {
    case 1 -> "Monday";
    case 2 -> "Tuesday";
    case 3 -> "Wednesday";
    default -> "Invalid day";
};
```
