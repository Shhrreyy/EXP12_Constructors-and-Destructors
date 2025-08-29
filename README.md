# 🏗️ EXP-12: Constructors and Destructors in Cpp

## 🎯 Aim

To implement different types of **constructors** and **destructors** in C++ in order to understand object initialization and cleanup mechanisms.

---

## 📚 Theory

- **Constructor**  
  A special member function of a class that is automatically called when an object is created.  
  - Same name as the class.  
  - No return type.  
  - Used for initializing data members.  

  Types of constructors:  
  1. **Default Constructor** – Takes no parameters, initializes values with defaults.  
  2. **Parameterized Constructor** – Takes parameters and initializes values accordingly.  
  3. **Copy Constructor** – Creates a new object as a copy of an existing object.  

- **Destructor**  
  A special member function that is automatically invoked when an object goes out of scope.  
  - Same name as the class preceded by `~`.  
  - No parameters, no return type.  
  - Used for cleanup (freeing memory, closing files, etc.).

---

## 🧮 Algorithms / Steps

### 1. **Default Constructor (`default_constructors.cpp`)**
- Define a class with a default constructor.  
- Initialize member variables inside the constructor.  
- Create an object and display initialized values.

### 2. **Parameterized Constructor (`parametrized_constructor.cpp`, `parametrized_constructors.cpp`)**
- Define a class with a constructor that accepts parameters.  
- Pass values while creating the object.  
- Display values to verify initialization.  

### 3. **Copy Constructor (`copy_constructor.cpp`)**
- Define a class with a copy constructor.  
- Initialize a new object by copying another object.  
- Show that values are copied successfully.

### 4. **Constructor Defined Inside Class (`defining_inside.cpp`)**
- Define constructor function inside the class body.  
- Create an object and verify initialization.

### 5. **Constructor Defined Outside Class (`defining_outside.cpp`)**
- Declare constructor inside class but define it outside using scope resolution operator `::`.  
- Demonstrate object creation and initialization.

### 6. **Destructor (`destructor.cpp`)**
- Define a destructor in the class using `~ClassName()`.  
- Display a message when object goes out of scope to show destructor execution.  

---

## ✅ Conclusion

This experiment helps understand how **constructors** simplify object initialization and how **destructors** handle cleanup automatically.  
They are essential for effective memory management and avoiding resource leaks in C++.

---

## 🧵 Topics Covered

- Default Constructor  
- Parameterized Constructor  
- Copy Constructor  
- Constructors defined inside & outside class  
- Destructor  
- Object lifecycle in C++ (creation and destruction)  
