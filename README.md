# Simple-Python-Calculator-with-History

# 🧮 Simple Python Calculator with History

This is a command-line calculator built in Python that allows users to perform basic arithmetic operations and maintains a history of all calculations in a local text file.

---

## 📁 Project Information

- **Project Name:** Simple Python Calculator with History  
- **Author:** Vedant Thakare  
- **Language:** Python 3  
- **Main File:** `calculator.py`  
- **History File:** `file.txt`

---

## 🚀 Features

- ✅ Perform operations: Addition (`+`), Subtraction (`-`), Multiplication (`*`), Division (`/`), Modulus (`%`)
- 💾 Automatically saves each calculation in `file.txt`
- 📜 View previous calculations using the `history` command
- 🧹 Clear the saved history using the `clear` command
- ❌ Handles invalid inputs and division by zero errors

---

## 🛠️ How to Run

### 1. Clone or Download the Project

```bash
git clone https://github.com/yourusername/calculator-project.git
cd calculator-project

python calculator.py

💡 Usage Instructions
Once the program starts, follow the prompts:

Enter an arithmetic expression (e.g., 8 * 5)

Type history to view previous calculations

Type clear to delete all history

Type exit to quit the program

🖥️ Sample Interaction

------------ Simple Calculator -------------
Type 'history' to view, 'clear' to clear history, 'exit' to quit.

Enter the equation to solve (e.g. 5 + 6): 10 / 2
Result = 5

Enter the equation to solve: history
10 / 2 = 5

Enter the equation to solve: clear
History deleted successfully

Enter the equation to solve: exit
Thank you for using the calculator.
