# Loops

## 1. **`for` Loop**

Use when the number of iterations is known.

```java
for (int i = 0; i < 5; i++) {
    System.out.println("i = " + i);
}
```

**Output:**

```
i = 0
i = 1
i = 2
i = 3
i = 4
```

---

## 2. **`while` Loop**

Use when the number of iterations is **not known** and depends on a condition.

```java
int i = 0;
while (i < 5) {
    System.out.println("i = " + i);
    i++;
}
```

---

## 3. **`do-while` Loop**

Same as `while`, but the loop **executes at least once** before checking the condition.

```java
int i = 0;
do {
    System.out.println("i = " + i);
    i++;
} while (i < 5);
```

---

## 4. **Enhanced `for-each` Loop**

Used to iterate over arrays or collections.

```java
int[] numbers = {1, 2, 3, 4, 5};
for (int num : numbers) {
    System.out.println(num);
}
```

---

## Loop Control Statements

- **`break`** – exit the loop.
    
- **`continue`** – skip the current iteration and move to the next.
    

```java
for (int i = 0; i < 5; i++) {
    if (i == 3) break;       // exits loop when i = 3
    if (i == 1) continue;    // skips iteration when i = 1
    System.out.println(i);
}
```
