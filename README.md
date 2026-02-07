# AI Code Reviewer – CLI Module

This repository contains the Command-Line Interface (CLI) module for the AI-Powered Code Reviewer project.

## 📌 Module Description
The CLI acts as the execution layer of the project.  
It allows users and automation tools to interact with the code review system using simple terminal commands.

## 🚀 Features
The CLI supports the following commands:

- **scan** – Scans a project directory and identifies Python files
- **review** – Reviews a selected Python file and displays detected issues
- **apply** – Applies selected fixes suggested during review
- **report** – Generates a summary report of the review results
- **diff** – Shows differences between original and updated code

## 🛠️ How to Run

Clone the repository:
```bash
git clone https://github.com/Rishitha-32/ai-code-reviewer-cli.git



Navigate to the project folder and run commands like:
python cli/main.py scan .
python cli/main.py review sample.py
python cli/main.py apply
python cli/main.py report
python cli/main.py diff

project structure
ai-code-reviewer-cli/
 └── cli/
     └── main.py

