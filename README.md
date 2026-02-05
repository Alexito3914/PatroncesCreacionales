# 🏗️ Creational Design Patterns

A clean and schematic overview of the **Creational Design Patterns** from the *Gang of Four (GoF)*, with example code for learning and reference purposes.

---

## 📌 About This Repository

This repository contains **example implementations of Creational Design Patterns**.

> ⚠️ **Important note**  
> The code in this repository is **NOT originally written by me**.  
> It has been adapted and organized from **external educational sources** for **learning, study, and reference purposes only**.  
> All credit for the original implementations belongs to their respective authors.

---

## 🎯 What Are Creational Design Patterns?

Creational patterns focus on **how objects are created**, rather than how they are used.  
They help make systems **more flexible, reusable, and easier to maintain** by controlling object creation logic.

---

## 🧩 Included Patterns (High-Level Overview)

### 🔹 Singleton
- Ensures a class has **only one instance**
- Provides a **global access point** to that instance  
- Useful for configuration, logging, or shared resources

---

### 🔹 Factory Method
- Defines an interface for creating objects
- Lets subclasses decide **which class to instantiate**
- Promotes loose coupling between creator and concrete products

---

### 🔹 Abstract Factory
- Creates **families of related objects**
- Ensures compatibility between created objects
- Common in UI frameworks or cross-platform systems

---

### 🔹 Builder
- Separates object construction from its representation
- Useful for creating **complex objects step by step**
- Improves readability when many parameters are involved

---

### 🔹 Prototype
- Creates new objects by **cloning existing ones**
- Useful when object creation is costly
- Relies on copying rather than instantiation

---

## 🧠 Why Use Creational Patterns?

✔ Better control over object creation  
✔ Reduced coupling between classes  
✔ Improved scalability and maintainability  
✔ Cleaner and more expressive code  

---

## 📂 Repository Structure (Example)

```text
📁 creational-patterns
 ├── singleton/
 ├── factory-method/
 ├── abstract-factory/
 ├── builder/
 └── prototype/
