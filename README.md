# **C++ Experiment 1: Hello World and Calculator Application**

# **Aim**

To:

* Display a basic "Hello, World!" message using a simple C++ program.
* Create a calculator that executes basic arithmetic operations based on user input.

# **Tool Used**

* Visual Studio Code (VS Code)

# **Objectives**

* Understand the structure of a C++ program.
* Learn how to use `#include` directives for library inclusion.
* Apply `cin` and `cout` for handling input and output.
* Implement basic arithmetic operations in C++.
* Grasp key syntax elements like `using namespace std;`, function definition, and data types.
* Use `//` to add comments for better code clarity and readability.

# **Theory**

C++ is a powerful, high-level programming language derived from C. It supports object-oriented programming, strong type checking, and a broad library collection. C++ is widely used in system-level programming, embedded systems, and applications demanding high performance.

# **Why C++ is Superior to C**

C++ offers several improvements over C, making it better suited for modern development:

* Supports Object-Oriented Programming (OOP) including classes, inheritance, polymorphism, and objects—allowing improved code structure and reusability.
* Enables function and operator overloading to handle multiple implementations with different parameters.
* Provides the Standard Template Library (STL) for efficient use of built-in data structures like vectors, stacks, queues, lists, maps, and more.
* Enforces stronger type safety, helping catch more errors at compile time.
* Offers encapsulation and abstraction, improving modularity and manageability.
* Enhances memory management using constructors, destructors, and RAII (Resource Acquisition Is Initialization).
* Utilizes namespaces to avoid naming conflicts in large-scale projects by grouping logically related code.

These advantages make C++ more robust, scalable, and developer-friendly than C, especially for complex applications.

# **Program Structure in C++**

* `#include <iostream>` includes the standard I/O stream library that provides access to `cin`, `cout`, and `endl`.
* `using namespace std;` allows access to standard library elements without the `std::` prefix.
* `int main()` is the starting point of any C++ program. All executable C++ code begins here.
* `cout` is used for output display; `cin` is used to receive user input.
* Conditional statements like `if` and `else` allow logical decision-making.
* Arithmetic operators (+, -, \*, /) perform mathematical operations.
* Data types such as `int`, `float`, and `double` specify the nature of data stored in variables.
* `return 0;` signifies that the program has executed successfully.
* Comments using `//` help explain the logic and are ignored during compilation.

# **Program Description**

**Part 1: Hello World**

* A simple program that outputs “Hello, World!” to the console.
* Demonstrates core syntax elements: header files, main function, and console output.

**Part 2: Calculator Program**

* This program prompts the user to input two numbers.
* It performs the following arithmetic operations:

  * Addition
  * Subtraction
  * Multiplication
  * Division
* The results of each operation are displayed using `cout`.
* It makes use of arithmetic operators, variables, and console input/output functions.

# **Concepts Used**

* **Header Files:** `#include <iostream>`
* **Namespace:** `using namespace std;`
* **Input/Output:** `cin`, `cout`
* **Function:** `main()`, `return 0;`
* **Data Types and Variables:** `int`, `float`, `double`
* **Operators:** `+`, `-`, `*`, `/`
* **Conditional Logic:** `if`, `else`
* **Comments:** `//`

# **Sample Output**

```cpp
Hello, World!

Enter first number: 12  
Enter second number: 4  

Addition: 16  
Subtraction: 8  
Multiplication: 48  
Division: 3
```

