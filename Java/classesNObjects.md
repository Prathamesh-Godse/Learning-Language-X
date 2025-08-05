# Classes and Objects

## 🔹 What is a Class?

A **class** is a **blueprint or template** for creating objects. It defines the **data (fields)** and **behavior (methods)** of an object.

```java
public class Car {
    // Fields (data members)
    String color;
    int speed;

    // Constructor (initializes objects)
    Car(String c, int s) {
        color = c;
        speed = s;
    }

    // Method (behavior)
    void drive() {
        System.out.println("The " + color + " car is driving at " + speed + " km/h.");
    }
}
```

---

## 🔹 What is an Object?

An **object** is an **instance** of a class. It occupies memory and has a state and behavior defined by its class.

```java
public class Main {
    public static void main(String[] args) {
        Car myCar = new Car("Red", 100);  // Creating an object
        myCar.drive();                    // Calling method
    }
}
```

**In the above:**

- `Car` is the class.
    
- `myCar` is the object.
    
- `new Car(...)` constructs (creates) the object.
    
- `myCar.drive()` invokes a method on the object.
    

---

## 🔹 Anatomy of a Class

|Component|Purpose|
|---|---|
|Fields|Variables that hold object state|
|Methods|Functions inside the class to define behavior|
|Constructor|Special method to initialize objects|
|Nested Class|Class declared within another class|

Example:

```java
public class Laptop {
    String brand;
    int ram;

    // Constructor
    Laptop(String brand, int ram) {
        this.brand = brand;
        this.ram = ram;
    }

    // Method
    void displaySpecs() {
        System.out.println("Brand: " + brand + ", RAM: " + ram + "GB");
    }

    // Nested Class
    class Battery {
        int capacity = 4000;
    }
}
```

---

## 🔹 Summary

- A **class** defines structure.
    
- An **object** is a real-world entity created from that structure.
    
- Classes can have:
    
    - Fields (variables)
        
    - Methods (functions)
        
    - Constructors (initializers)
        
    - Nested classes (for grouping or helper logic)
        
