# Basic Syntax

## ✅ 1. **Structure of a Java Program**

```java
// This is a comment

package mypackage;         // (optional) package declaration

import java.util.Scanner;  // (optional) import statements

public class MyClass {     // class declaration
    public static void main(String[] args) {  // main method
        System.out.println("Hello, World!");  // statement
    }
}
```

---

## ✅ 2. **Main Components of Java Syntax**

|**Component**|**Description**|
|---|---|
|`class`|Java is class-based. Everything must be inside a class.|
|`main()` method|Entry point of any Java application.|
|`System.out.println()`|Prints output to the console.|
|`;`|Every statement ends with a semicolon.|
|`{}`|Curly braces define a block (class, method, loop, etc.).|
|`//` or `/* */`|Comments. `//` is single-line; `/* */` is multi-line.|

---

## ✅ 3. **Variables & Data Types**

```java
int age = 25;
double price = 19.99;
char grade = 'A';
boolean isJavaFun = true;
String name = "Alice";
```

---

## ✅ 4. **Operators**

Arithmetic: `+ - * / %`  
Comparison: `== != < > <= >=`  
Logical: `&& || !`

---

## ✅ 5. **Control Flow Statements**

#### If-Else

```java
if (age >= 18) {
    System.out.println("Adult");
} else {
    System.out.println("Minor");
}
```

### Switch

```java
switch (grade) {
    case 'A':
        System.out.println("Excellent");
        break;
    default:
        System.out.println("Invalid Grade");
}
```

### Loops

```java
for (int i = 0; i < 5; i++) {
    System.out.println(i);
}

while (condition) {
    // repeat
}

do {
    // run once, then check
} while (condition);
```

---

## ✅ 6. **Methods (a.k.a Functions in Java)**

```java
public static int add(int a, int b) {
    return a + b;
}
```

---

## ✅ 7. **Classes & Objects**

```java
class Car {
    String color = "red";      // field
    void drive() {             // method
        System.out.println("Driving");
    }
}

public class Main {
    public static void main(String[] args) {
        Car myCar = new Car(); // object/instance
        myCar.drive();         // calling method
    }
}
```

---

## ✅ 8. **Access Modifiers**

- `public`: accessible everywhere.
    
- `private`: only inside the same class.
    
- `protected`: same package + subclasses.
    
- _(no modifier)_: package-private (default).
    

---

## ✅ 9. **Packages**

```java
package myapp.utilities;
```

Packages group related classes together and avoid name conflicts.

---

## ✅ 10. **Comments**

```java
// Single-line

/*
 Multi-line
 Comment
*/
```

---

## ✅ 11. **String Handling**

```java
String s = "Hello";
System.out.println(s.length());
```

---

## ✅ 12. **Exception Handling**

```java
try {
    int x = 5 / 0;
} catch (ArithmeticException e) {
    System.out.println("Can't divide by zero!");
} finally {
    System.out.println("Done");
}
```

---

## ✅ 13. **Arrays**

```java
int[] numbers = {1, 2, 3, 4};
System.out.println(numbers[0]);
```

---

## ✅ 14. **Input from User**

```java
import java.util.Scanner;

Scanner sc = new Scanner(System.in);
String name = sc.nextLine();
```
