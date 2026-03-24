# **Lesson 1: Environment Setup**
    
### Summary

- **Concepts**: Learn about JDK, its installation, environment setup, and IDE usage.
- **Practice**: Verify JDK installation, create and run a Java program in IntelliJ IDEA, and set up a project structure.

### Watch Lesson 1: [Java For Beginners #1 - Setup JDK & IntelliJ (Start Coding in 10 Minutes)](https://youtu.be/sqt_cWeNsR4)

---

### Concepts

#### Java JDK

1. Installing Java JDK
    - Explanation of JDK and its importance
        - **Java Development Kit (JDK)**: A software development environment used for developing Java applications.
        - **Importance**: Provides the necessary tools (compiler, debugger, etc.) to write, compile, and run Java programs.
    - Steps to download and install JDK from Oracle’s website
        - Open a web browser and go to the [Oracle JDK download page](https://www.oracle.com/java/technologies/downloads/).
        - Select the appropriate version for your operating system (Windows, macOS, Linux).
        - Download the installer and run it.
        - Follow the installation prompts to complete the installation.
    - Setting up environment variables (JAVA_HOME, PATH)
        - **Windows**:
            1. Open the Start menu, search for "Environment Variables", and select "Edit the system environment variables".
            2. In the System Properties window, click on "Environment Variables".
            3. Under System Variables, click "New" and add `JAVA_HOME` with the path to the JDK installation directory (e.g., `C:\Program Files\Java\jdk-14`).
            4. Find the `Path` variable, click "Edit", and add `%JAVA_HOME%\bin` to the list.
        - **macOS/Linux**:
            1. Open the terminal.
            2. Edit the `.bash_profile` or `.zshrc` file using a text editor (e.g., `nano ~/.bash_profile`).
            3. Add the following lines:
                
                ```bash
                export JAVA_HOME=/path/to/jdk
                export PATH=$JAVA_HOME/bin:$PATH
                ```
                
            4. Save the file and run `source ~/.bash_profile` or `source ~/.zshrc`.

#### IntelliJ IDEA

2. Installing an IDE (IntelliJ IDEA)
    - Explanation of IDE and why we use it
        - **Integrated Development Environment (IDE)**: A software application that provides comprehensive facilities to computer programmers for software development.
        - **Importance**: Simplifies coding, debugging, and testing by providing tools and features like code editors, compilers, debuggers, and project management.
    - Steps to download and install IntelliJ IDEA
        - Open a web browser and go to the [IntelliJ IDEA download page](https://www.jetbrains.com/idea/download/).
        - Select the Community Edition (free) for your operating system (Windows, macOS or Linux).
        - Download the installer and run it.
        - Follow the installation prompts to complete the installation.
    - Basic tour of the IDE interface: projects, editors, menus
        - **Projects**: Contains the files and folders of your Java project.
        - **Editors**: Where you write and edit your Java code.
        - **Menus**: Provides access to various tools and settings, such as file management, code navigation, refactoring, and debugging.

---

### Practice

#### Exercise 1

1. Verify JDK installation by compiling and running a simple Java program via command line.
    - Open a text editor and write a simple Java program:
        
        ```java
        public class HelloWorld {
            public static void main(String[] args) {
                System.out.println("Hello, World!");
            }
        }
        ```
        
    - Save the file as `HelloWorld.java`.
    - Open a command line terminal.
    - Navigate to the directory where you saved `HelloWorld.java`.
    - Compile the program using `javac HelloWorld.java`.
    - Run the program using `java HelloWorld`.

#### Exercise 2

2. Create and run a "Hello World" program in IntelliJ IDEA.
    - Open IntelliJ IDEA.
    - Create a new Java project.
    - In the project structure, right-click on `src` and select `New -> Java Class`.
    - Name the class `HelloWorld`.
    - Write the "Hello World" program in the editor:
        
        ```java
        public class HelloWorld {
            public static void main(String[] args) {
                System.out.println("Hello, World!");
            }
        }
        ```
        
    - Run the program by clicking the Run button or right-clicking in the editor and selecting `Run 'HelloWorld.main()'`.

#### Exercise 3

3. Set up a project structure in IntelliJ IDEA.
    - Create a new project in IntelliJ IDEA.
    - Familiarize yourself with the project structure: `src` folder for source files, `out` or `build` folder for compiled files.
    - Add a package within the `src` folder (right-click `src` -> New -> Package).
    - Create a new Java class within the package (right-click package -> New -> Java Class).
    - Write a simple Java program and run it to ensure everything is set up correctly.
        - In the editor, replace the default code with the following:
        
        ```java
        package com.example;
        
        public class Main {
            public static void main(String[] args) {
                System.out.println("Hello, IntelliJ IDEA!");
            }
        }
        ```

---

[Back to Course Overview](../README.md)