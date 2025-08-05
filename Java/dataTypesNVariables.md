# Data Types and Variables
## 🔹 **Variables in Java**

- A **variable** is a container that holds data during program execution.
    
- Java is **statically typed** — you must declare the type of a variable before using it.
    
- Syntax: `dataType variableName = value;`
    

---

## 🔹 **Java Data Types**

### 🟠 **Primitive Data Types** (8 total)

These are built-in types not objects.

|Type|Size|Example|Description|
|---|---|---|---|
|`byte`|1 byte|`byte b = 10;`|Small integers (-128 to 127)|
|`short`|2 bytes|`short s = 1000;`|Larger integers (-32,768 to 32,767)|
|`int`|4 bytes|`int x = 50000;`|Default for whole numbers|
|`long`|8 bytes|`long l = 123456789L;`|Very large integers (append `L`)|
|`float`|4 bytes|`float f = 5.75f;`|Decimal numbers (append `f`)|
|`double`|8 bytes|`double d = 19.99;`|Default for decimal numbers|
|`char`|2 bytes|`char c = 'A';`|A single 16-bit Unicode character|
|`boolean`|1 bit|`boolean isOn = true;`|Only `true` or `false`|

### 🟢 **Non-Primitive Data Types**

- Created by the programmer or built-in classes.
    
- Always **referenced by objects** (not stored directly).
    
- Examples:
    
    - `String name = "Java";`
        
    - Arrays: `int[] nums = {1, 2, 3};`
        
    - Custom Classes, Interfaces, Enums
        

---

## 🔹 **Variable Types**

- **Local variables** – declared inside methods.
    
- **Instance variables** – declared in a class but outside any method; tied to an object.
    
- **Static variables** – shared among all instances; declared with `static` keyword.
    

---

## 🔹 **Type Conversion**

- **Widening (Implicit)**: smaller to larger (e.g., `int` → `double`)
    
- **Narrowing (Explicit)**: larger to smaller (needs cast)  
    Example: `int i = (int) 3.14;`
    

---

## 🔹 **Constants**

- Use `final` keyword to declare a variable whose value **cannot be changed**.  
    Example: `final int MAX = 100;`
    
