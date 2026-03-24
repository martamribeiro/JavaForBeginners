# **Lesson 2: Introduction to Java**
    
### Summary

- **Concepts**: Learn about Java's history, features, JVM, JRE, JDK, and the basic structure of a Java program.
- **Practice**: Write simple Java programs to print messages, include comments, and personalize output.

### Watch Lesson 2: [Java For Beginners #2 - What is Java? Basic Syntax & Structure Explained](https://www.youtube.com/watch?v=chaxSYshPxY)

---

### Concepts

#### Java Overview

1. Java Overview
    - History and features of Java
        - **History**: Java was developed by James Gosling at Sun Microsystems (which has since been acquired by Oracle) and released in 1995. It was designed to have the "write once, run anywhere" capability, making it highly portable.
        - **Features**:
            - **Object-Oriented**: Java uses object-oriented programming (OOP) principles, allowing for modular, flexible, and extensible code.
            - **Platform-Independent**: Code is compiled into bytecode, which can run on any device equipped with a Java Virtual Machine (JVM).
            - **Robust and Secure**: Strong memory management, exception handling, and a secure execution environment.
            - **High Performance**: Just-In-Time (JIT) compilers enable high performance by converting bytecode to native machine code at runtime.
            - **Multithreaded**: Java supports multithreading, which allows concurrent execution of two or more threads.
    - JVM, JRE, and JDK
        - **JVM (Java Virtual Machine)**: An abstract machine that enables your computer to run Java programs. It converts Java bytecode into machine code.
        - **JRE (Java Runtime Environment)**: Includes the JVM and the necessary libraries and components to run Java applications.
        - **JDK (Java Development Kit)**: A complete toolkit that includes the JRE and development tools such as the Java compiler (javac).
    - Platform independence and Java Virtual Machine
        - **Platform Independence**: Java code is written once and can be run anywhere without modification. This is achieved through the use of bytecode and the JVM.
        - **Java Virtual Machine (JVM)**: The JVM executes Java bytecode and enables the same Java program to run on different platforms.

#### Java Language Syntax and Structure

2. Java Language Syntax and Structure
    - Basic structure of a Java program
        - A simple Java program consists of:
            - **Class Definition**: Java programs are organized into classes.
            - **Main Method**: The entry point of any Java application.
            - Example:
                
                ```java
                public class HelloWorld {
                    public static void main(String[] args) {
                        System.out.println("Hello, World!");
                    }
                }
                ```
                
    - Explanation of main method and basic syntax
        - **Main Method**: `public static void main(String[] args)`
            - **public**: Accessible from anywhere.
            - **static**: Belongs to the class rather than any instance of the class.
            - **void**: Does not return any value.
            - **main**: Name of the method.
            - **String[] args**: Parameter to the main method, an array of strings.
        - **Basic Syntax**: Java is case-sensitive, uses curly braces `{}` to define blocks of code, and statements end with a semicolon `;`.
    - Comments and documentation
        - **Single-Line Comments**: Begin with `//`.
            
            ```java
            // This is a single-line comment
            
            ```
            
        - **Multi-Line Comments**: Enclosed between `/*` and `/`.
            
            ```java
            /* This is a
               multi-line comment */
            ```
            
        - **Documentation Comments**: Begin with `/**` and end with `/`. Used to generate documentation using Javadoc.
            
            ```java
            /**
             * This is a documentation comment.
             * @param args Command line arguments
             */
            ```

---

### Practice

#### Exercise 1

1. Write a simple program to print "Hello, World!".
    1. Open IntelliJ IDEA and create a new Java project.
    2. Create a new Java class named `HelloWorld`.
    3. Write the following code in the `HelloWorld` class:
        
        ```java
        public class HelloWorld {
            public static void main(String[] args) {
                System.out.println("Hello, World!");
            }
        }
        ```
        
    4. Run the program to see the output.

#### Exercise 2

2. Modify the program to include multi-line and single-line comments.
    1. Add comments to the `HelloWorld` program:
        
        ```java
        public class HelloWorld {
            public static void main(String[] args) {
                // This is a single-line comment
                System.out.println("Hello, World!"); // Print Hello, World!
        
                /* This is a
                   multi-line comment */
            }
        }
        ```
        
    2. Run the program to ensure it still works correctly.

#### Exercise 3

3. Write a program that prints a welcome message with your name.
    - Create a new Java class named `Welcome`.
    - Write the following code in the `Welcome` class:
        
        ```java
        public class Welcome {
            public static void main(String[] args) {
                System.out.println("Welcome to Java programming, [Your Name]!");
            }
        }
        ```
        
    - Replace `[Your Name]` with your actual name.
    - Run the program to see the output.

---

[Back to Course Overview](../README.md)