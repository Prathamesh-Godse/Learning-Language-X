# Operators

## 🔹 1. **Arithmetic Operators**

Used to perform basic mathematical operations.

|Operator|Description|Example|
|---|---|---|
|`+`|Addition|`a + b`|
|`-`|Subtraction|`a - b`|
|`*`|Multiplication|`a * b`|
|`/`|Division|`a / b`|
|`%`|Modulo (remainder)|`a % b`|

---

## 🔹 2. **Assignment Operators**

Used to assign values to variables.

|Operator|Description|Example|
|---|---|---|
|`=`|Assign|`a = b`|
|`+=`|Add and assign|`a += b`|
|`-=`|Subtract and assign|`a -= b`|
|`*=`|Multiply and assign|`a *= b`|
|`/=`|Divide and assign|`a /= b`|
|`%=`|Modulo and assign|`a %= b`|

---

## 🔹 3. **Relational (Comparison) Operators**

Used to compare two values.

|Operator|Description|Example|
|---|---|---|
|`==`|Equal to|`a == b`|
|`!=`|Not equal to|`a != b`|
|`>`|Greater than|`a > b`|
|`<`|Less than|`a < b`|
|`>=`|Greater or equal to|`a >= b`|
|`<=`|Less or equal to|`a <= b`|

---

## 🔹 4. **Logical Operators**

Used to perform logical operations (mainly in `if`, loops, etc.).

|Operator|Description|Example|
|---|---|---|
|`&&`|Logical AND|`a > 0 && b < 5`|
|`||`|
|`!`|Logical NOT|`!(a > 0)`|

---

## 🔹 5. **Unary Operators**

Operate on a single operand.

|Operator|Description|Example|
|---|---|---|
|`+`|Unary plus|`+a`|
|`-`|Unary minus|`-a`|
|`++`|Increment (prefix/postfix)|`++a`, `a++`|
|`--`|Decrement (prefix/postfix)|`--a`, `a--`|
|`!`|Logical NOT|`!flag`|

---

## 🔹 6. **Bitwise Operators**

Operate on bits of integers.

|Operator|Description|Example|
|---|---|---|
|`&`|Bitwise AND|`a & b`|
|`|`|Bitwise OR|
|`^`|Bitwise XOR|`a ^ b`|
|`~`|Bitwise Complement|`~a`|
|`<<`|Left shift|`a << 2`|
|`>>`|Right shift|`a >> 2`|
|`>>>`|Zero-fill right shift|`a >>> 2`|

---

## 🔹 7. **Ternary Operator**

A shorthand for `if-else`.

```java
condition ? value_if_true : value_if_false
```

**Example:**

```java
int result = (a > b) ? a : b;
```

---

## 🔹 8. **Instanceof Operator**

Checks if an object is an instance of a class or subclass.

```java
if (obj instanceof String) {
    // do something
}
```

---

## 🔹 9. **Type Cast Operator**

Used to convert one data type into another.

```java
int x = (int) 3.14; // explicit casting
```
