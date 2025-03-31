# JAVA BASIC TUTORIAL

## 1. Java - Overview
Java is a high-level, object-oriented programming language developed by **Sun Microsystems** (now owned by Oracle). It is widely used for building applications, from web and mobile apps to large-scale enterprise systems. Java is **platform-independent**, meaning it can run on different operating systems using the **JVM (Java Virtual Machine)**.

## 2. Java - History
- Created by **James Gosling** in **1995**.
- Originally called *Oak*, later renamed **Java**.
- Designed to be **simple, secure, and platform-independent**.
- Became one of the most popular programming languages globally.

## 3. Java - Features
Java offers several key features:
- **Platform Independent** – Runs on any OS with JVM.
- **Object-Oriented** – Uses classes and objects.
- **Secure** – Provides runtime security features.
- **Multithreading** – Supports concurrent execution.
- **Automatic Memory Management** – Uses **Garbage Collection** to free unused memory.

## 4. Java vs C++
| Feature   | Java | C++ |
|-----------|------|-----|
| Platform Independence | Yes (JVM) | No |
| Memory Management | Automatic (Garbage Collection) | Manual |
| Multiple Inheritance | Not Supported (Uses Interfaces) | Supported |
| Pointers | Not Used | Used |
| Security | High | Moderate |

## 5. JVM (Java Virtual Machine) Architecture
The **JVM** converts Java code into **bytecode**, which can be executed on any system with a JVM installed.
### Components:
1. **Class Loader** – Loads class files.
2. **Runtime Memory Areas** – Stores method data, heap, and stack.
3. **Execution Engine** – Converts bytecode into machine code.
4. **Garbage Collector** – Manages memory automatically.

## 6. Difference Between JDK, JRE, and JVM
- **JDK (Java Development Kit)** – Includes **JRE + development tools** (compiler, debugger, etc.).
- **JRE (Java Runtime Environment)** – Contains JVM + libraries required to run Java applications.
- **JVM (Java Virtual Machine)** – Executes Java bytecode and ensures portability.

## 7. Java - Hello World Program
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```
### Explanation:
- `public class HelloWorld` → Defines a class.
- `public static void main(String[] args)` → Entry point of Java program.
- `System.out.println("Hello, World!")` → Prints text to the console.

## 8. Java - Environment Setup
To start coding in Java:
1. **Download and Install JDK** from [Oracle](https://www.oracle.com/java/technologies/javase-downloads.html).
2. **Set up Environment Variables**:
   - Add JDK bin path to `PATH` variable.
3. **Verify Installation**:
   - Open terminal and run:
   ```sh
   java -version
   ```
4. **Use an IDE** like IntelliJ IDEA, Eclipse, or VS Code for better development experience.

Happy Coding! 🚀
