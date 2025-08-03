
# Hello World!

## ✅ Code 

```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

---

## 🧠 **Detailed Explanation – Line by Line**

---

### 🔹 `public class HelloWorld {`

- `class` → A **class** is the building block of Java programs.  
    It defines a **blueprint** from which objects are created.
    
- `HelloWorld` → This is the **name** of the class.
    
    - Must match the filename (`HelloWorld.java`) exactly.
        
    - Java is **case-sensitive**, so `helloworld` or `HELLOWORLD` would be considered different.
        
- `public` → This is an **access modifier**.
    
    - It means this class is **accessible from anywhere** in your program.
        
    - Without `public`, the class would only be accessible from inside its package.
        

> 🧠 Summary: You're defining a public class named `HelloWorld`. Java expects every application to have at least one class.

---

### 🔹 `public static void main(String[] args) {`

This is the **entry point** of any Java program.

Let’s break it into parts:

#### 🔸 `public`

- Makes the method accessible from **outside the class**.
    
- Required by Java so the runtime (JVM) can **find and run** it.
    

#### 🔸 `static`

- Means this method belongs to the **class**, not an object.
    
- You don't need to create an instance of `HelloWorld` to run `main`.
    

#### 🔸 `void`

- The method **returns nothing**.
    
- `void` means it completes its task (like printing), but **does not return a value**.
    

#### 🔸 `main`

- This is the **main method**.
    
- The **Java Virtual Machine (JVM)** looks for this method to start the program.
    

#### 🔸 `(String[] args)`

- The method accepts an **array of Strings** as input.
    
- These are **command-line arguments** passed when the program is run.
    
    - Example: `java HelloWorld foo bar`  
        → `args[0] = "foo"`  
        → `args[1] = "bar"`
        

> 🧠 Summary: This method is **static**, **public**, and **void** so the Java interpreter can run it directly without an object and without expecting a return value. It's where your program starts.

---

### 🔹 `System.out.println("Hello, World!");`

This line prints the message `"Hello, World!"` to the console.

#### Breaking it down:

- `System` → A **built-in class** in Java from the `java.lang` package.
    
    - It provides access to system-level utilities.
        
- `out` → A **static member** of `System`.
    
    - It's an object of class `PrintStream`.
        
    - Used to output text to the **console** (standard output).
        
- `println()` → A method of the `PrintStream` class.
    
    - It prints the given text and **adds a newline** after it.
        
- `"Hello, World!"` → A **String literal** — the message to be printed.
    

> 🧠 Summary: This line tells Java to **print text** to the screen and **move to the next line** afterward.

---

### 🔹 Closing Braces `}`

- These close the `main` method and the `HelloWorld` class.
    
- Every opening `{` must have a matching `}`.
    
- Java uses **braces to define blocks** of code.
    

---

## 🧾 Recap (for notes)

|Part|Explanation|
|---|---|
|`public class HelloWorld`|Declares a public class named `HelloWorld`|
|`public static void main(String[] args)`|Defines the entry point of the program|
|`System.out.println("Hello, World!");`|Prints the message to the screen with a newline|
|`{` and `}`|Define the beginning and end of class and method blocks|
