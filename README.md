# Delivery-Status-Management-System-
A Python-based delivery management system developed as part of the **SmartBizCrux Technologies Python Study Group**.

The project simulates a logistics workflow where delivery records are validated, analyzed, and classified based on delivery status, delivery time, and delivery attempts.

## 📌 Project Overview

The system is designed to:

- Validate delivery information
- Determine delivery performance
- Assign delivery priority
- Recommend appropriate actions
- Process multiple delivery records
- Generate a structured delivery report

## 🛠️ Technologies & Concepts

**Tools:**
- Python
- Jupyter Notebook

**Python Concepts:**
- Variables and data types
- Conditional statements (`if`, `elif`, `else`)
- Comparison and logical operators
- `for` and `while` loops
- Functions, parameters, and return values
- Lists and dictionaries
- Boolean validation
- Local and global variable scope

## ⚙️ Key Features

### Delivery Performance
Classifies deliveries as:
- On Time
- Delayed
- Completed
- Cancelled
<img width="1352" height="420" alt="Screenshot 2026-09-04 143650" src="https://github.com/user-attachments/assets/a649e8c3-ebf3-40bc-8530-28ed5cd49c71" />


### Delivery Priority
Assigns:
- Urgent
- High
- Normal
- Low
<img width="1364" height="415" alt="Screenshot 2026-09-04 143736" src="https://github.com/user-attachments/assets/1a697225-08f5-4e5b-b3ed-091dc7a3cf8a" />

### Recommended Actions
The system recommends actions based on the delivery priority, such as investigating delays, monitoring deliveries, or escalating urgent cases.
<img width="1335" height="413" alt="Screenshot 2026-09-04 144149" src="https://github.com/user-attachments/assets/f2c87e88-dee6-4e47-91c0-d2aa9ca01de5" />

### Data Validation
Checks delivery IDs, customer information, delivery status, delivery duration, package weight, and delivery attempts.
<img width="1348" height="436" alt="Screenshot 2026-09-04 144300" src="https://github.com/user-attachments/assets/c0c27b73-290b-4555-a3b2-1ca23b1fa2e0" />


## Sample Output
The system generates a structured report showing the delivery information, performance, priority, recommended action, and validation status.

<img width="873" height="798" alt="Screenshot 2026-09-04 142423" src="https://github.com/user-attachments/assets/bf86da74-344a-43d6-a6f5-65bebfdf0985" />
<img width="876" height="681" alt="Screenshot 2026-09-04 144454" src="https://github.com/user-attachments/assets/7fe16af7-2a6e-4355-a515-6a5268c4b7d2" />
<img width="872" height="660" alt="Screenshot 2026-09-04 144512" src="https://github.com/user-attachments/assets/0d8a6935-26bf-4864-99af-a34a612b3fd7" />
<img width="881" height="666" alt="Screenshot 2026-09-04 144527" src="https://github.com/user-attachments/assets/acffb186-8595-40ab-8208-814da030a096" />

## Business Logic

The system uses delivery information to make decisions:

- Days Since Order ≤ Expected Delivery Days → **On Time**
- Days Since Order > Expected Delivery Days → **Delayed**
- Delayed + 2 or more attempts → **Urgent**
- Delayed + at least 1 attempt → **High**
- On Time + at least 1 attempt → **Normal**
- On Time + 0 attempts → **Low**

## How to Run

1. Clone this repository.
2. Open `Delivery_Status_Management_System.ipynb` in Jupyter Notebook or Google Colab.
3. Run the cells sequentially.
4. Follow the prompts where user input is required.

## 🎯 Key Learning

This project helped me apply Python fundamentals to a practical business scenario and strengthened my understanding of **problem-solving, conditional logic, loops, functions, validation, and structured programming**.
