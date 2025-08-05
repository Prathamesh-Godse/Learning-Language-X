# Arrays

## 🔹 What Is an Array?

An **array** is a **container object** that holds a **fixed number of elements of the same type**.

---

## 🔹 Declaring an Array

```java
// Syntax
dataType[] arrayName;
```

```java
// Example
int[] numbers;
String[] names;
```

---

## 🔹 Creating and Initializing an Array

```java
int[] numbers = new int[5]; // creates an array of size 5 with default value 0

// Or initialize directly
int[] scores = {90, 85, 88, 95, 100};
String[] fruits = {"apple", "banana", "mango"};
```

---

## 🔹 Accessing Array Elements

```java
System.out.println(scores[0]); // 90
scores[2] = 89; // changing the third element
```

> ⚠️ Indexing starts from 0 in Java.

---

## 🔹 Array Length

```java
System.out.println(scores.length); // prints 5
```

> `.length` is a property of arrays, not a method.

---

## 🔹 Iterating Over an Array

**Using `for` loop:**

```java
for (int i = 0; i < scores.length; i++) {
    System.out.println(scores[i]);
}
```

**Using `for-each` loop:**

```java
for (int score : scores) {
    System.out.println(score);
}
```

---

## 🔹 Multidimensional Arrays

```java
int[][] matrix = {
    {1, 2, 3},
    {4, 5, 6}
};

System.out.println(matrix[1][2]); // prints 6
```

---

## 🔹 Default Values

|Type|Default|
|---|---|
|int|0|
|double|0.0|
|boolean|false|
|String|null|
