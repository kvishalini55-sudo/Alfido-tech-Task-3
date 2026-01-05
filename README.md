# Alfido-tech-Task-3
# System Utility – Simple Command Runner (C++)

## Objective
To build a small system utility using C++ that demonstrates process creation
and command execution. The utility executes system commands, handles errors
gracefully, and exits cleanly.

---

## Description
This project implements a simple shell-like command runner in C++.
The program continuously accepts user input, executes valid system commands
using the operating system, and displays appropriate error messages for invalid
or unknown commands. The utility terminates when the user enters `exit`.

---

## Features
- Executes system commands entered by the user
- Interactive command prompt
- Graceful error handling for invalid commands
- Continuous execution until exit command
- Clean and safe termination

---

## Technologies Used
- Language: C++
- Compiler: g++ (MinGW-w64)
- Operating System: Windows
- Terminal: PowerShell

---

## Command Log (`log.txt`)
```text
Executed command: dir
Executed command: echo Hello
Executed command: wrongcommand
