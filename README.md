# Instruction Set Simulator

A Java-based Instruction Set Simulator that converts arithmetic expressions from infix to postfix notation and generates different instruction formats used in computer architecture.

## 📌 Description

This project demonstrates how arithmetic expressions are represented using different instruction formats. The program accepts an infix expression, converts it into postfix notation, and generates:

- 3-Address Instructions
- 2-Address Instructions
- 1-Address Instructions
- 0-Address Instructions

This project was developed as part of a Computer Organization and Architecture coursework to understand how processors represent and execute arithmetic operations.

## ✨ Features

- Converts infix expressions to postfix.
- Supports arithmetic operators:
  - `+`
  - `-`
  - `*`
  - `/`
- Generates:
  - 3-Address Instructions
  - 2-Address Instructions
  - 1-Address Instructions
  - 0-Address Instructions
- Simple Java implementation.
- Beginner-friendly code.

## 🛠️ Technologies Used

- Java
- Java Collections Framework (Stack)
- Scanner Class

## 📂 Project Structure

```
InstructionSimulator.java
README.md
```

## ▶️ How to Run

1. Clone the repository.

```bash
git clone https://github.com/yourusername/Instruction-Set-Simulator.git
```

2. Open the project in any Java IDE (IntelliJ IDEA, Eclipse, VS Code, NetBeans) or use the command line.

3. Compile the program.

```bash
javac InstructionSimulator.java
```

4. Run the program.

```bash
java InstructionSimulator
```

## 💻 Example

### Input

```
(A+B)*C
```

### Output

```
Postfix Expression: AB+C*

3-Address Instructions
T1 = A + B
T2 = T1 * C

2-Address Instructions
MOV R, A
ADD R, B
MOV R, R
MUL R, C

1-Address Instructions
LOAD A
ADD B
STORE TEMP
LOAD TEMP
MUL C
STORE TEMP

0-Address Instructions
PUSH A
PUSH B
ADD
PUSH C
MUL
```

## 📚 Concepts Used

- Infix to Postfix Conversion
- Stack Data Structure
- Expression Parsing
- Address Instruction Formats
- Computer Organization
- Instruction Set Architecture (ISA)

## 🎯 Learning Outcomes

- Understand how arithmetic expressions are processed.
- Learn the difference between various instruction formats.
- Understand the role of stacks in expression conversion.
- Gain basic knowledge of Instruction Set Architecture.

## 👨‍💻 Author

**Garvit Chaudhary**

Computer Organization Project
