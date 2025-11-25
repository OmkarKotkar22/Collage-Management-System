<h1 align="center">
  🎓 College Management System (Java OOP)
</h1>

<p align="center">
  A Java console application demonstrating key Object-Oriented Programming (OOP) concepts by modeling and managing entities within a college environment (Students, Faculty, and Persons).
</p>

---

<p align="center">
  <img src="https://img.shields.io/badge/Language-Java-007396?style=for-the-badge&logo=java" />
  <img src="https://img.shields.io/badge/Concept-Inheritance%20%26%20Classes-4169E1?style=for-the-badge" />
  <img src="https://img.shields.io/badge/repo%20size-10%20KB-32CD32?style=for-the-badge" /> 
  <img src="https://img.shields.io/badge/Last%20Commit-2%20days%20ago-32CD32?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Type-Console%20Application-8A2BE2?style=for-the-badge" />
</p>

---

## 📌 **Key Features & OOP Concepts**

### **1. Core Entity Modeling (Classes)**
* Uses dedicated classes (`Student`, `Faculty`, `Person`) to model real-world entities.

### **2. Demonstrates Inheritance**
* The `Student` and `Faculty` classes likely inherit common attributes and methods from a base **`Person` class**, showcasing the **Inheritance** principle of OOP.

### **3. Centralized Application Logic**
* The `College_App.java` file handles the main program execution, including creating objects and demonstrating relationships/methods.

### **4. Modular and Maintainable**
* Clear separation of data models and application logic, making the code clean and easy to extend.

---

## 🛠 Tech Stack

### 💻 Core Technology
- <img src="https://img.icons8.com/color/30/java-coffee-cup-logo--v1.png" width="22" /> **Java** (JDK 8+)
- **OOP** (Object-Oriented Programming)

### 🧱 Architecture
- **Console Application** structure.

---

## 📂 **Project Folder Structure**

<p align="center">
  <img src="https://img.shields.io/badge/Structure-Standard%20Java%20Package-90EE90?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Package-src%2FCollege-FFA07A?style=for-the-badge" />
</p>

The project uses a standard Java structure, with the source code residing in the `src/College/` package.

| File Name | Description | Role |
| :--- | :--- | :--- |
| `Person.java` | **Base Class** for all individuals (likely contains name, ID, address). | **Parent Model** 👤 |
| `Student.java` | **Child Class** extending `Person` (adds student-specific data like major, GPA). | **Entity Model** 🧑‍🎓 |
| `Faculty.java` | **Child Class** extending `Person` (adds faculty-specific data like department, salary). | **Entity Model** 🧑‍🏫 |
| `College_App.java` | Main file containing the `main` method to run the system demo. | **Driver/Main Logic** ⚙️ |

## 📂 **File Structure**
College-Management-System/ 
│  
├── bin/   
├── src/  
│      └── College/   
│        ├── College_App.java   
│        ├── Faculty.java    
│        ├── Person.java    
│        └── Student.java    
│    
├── .classpath  
└── .project  

---

## ⚙️ **Installation and Setup**

To run this project locally, you need a Java Development Kit (JDK) installed on your system.
### **1. Clone the repository**
```bash
git clone [Your Repository URL]
```

## Navigate to the source directory
```
cd College-Management-System/src/College
```

## Compile the Java files
```
javac FileName.java
```

## Run the Java File
```
java College_App
```

