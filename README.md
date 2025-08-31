# FUZZER

## Overview
**FUZZER** is a project for automated testing of software applications by generating unexpected, random, or malformed inputs to identify bugs, crashes, or security vulnerabilities. This project is part of a **group project**, where we also built a **mini compiler** as part of the testing targets. This tool helps improve software robustness and security by detecting edge-case errors.

---

## Project Files
- `project.l` — Lexer definitions for the mini compiler
- `project.y` — Parser definitions for the mini compiler
- `runner.sh` — Script to run fuzzing tests

---

## About AFL++
**AFL++ (American Fuzzy Lop Plus Plus)** is a powerful fuzz testing tool that automatically generates test cases to discover software bugs and security vulnerabilities. It uses instrumentation and feedback-guided fuzzing to maximize code coverage and find crashes efficiently.  

---

## Setup Instructions (Linux)

### Step 1: Install Flex and Bison
```bash
sudo apt update
sudo apt install flex bison
```
### Step 2: Install AFL (American Fuzzy Lop)
```bash
sudo apt update
sudo apt install afl++
```
### Step 3: Ensuring files directory  
```bash
project.l
project.y
runner.sh
```
### Step 4: RUN in SHELL  
```bash
./runner.sh
```

## STRUCTURE
FUZZER/
│
├── project.l          # Lexer definitions
├── project.y          # Parser definitions
├── runner.sh          # Fuzzer execution script
└── README.md          # Project documentation
## Authors & Contributions

- **Priyanshu Mittal** 
- **Jiya**  
- **Param An**
- **Gagan**

---

## License
This project is licensed under the **MIT License**. You are free to use, modify, and distribute the project as per the terms of the license.
