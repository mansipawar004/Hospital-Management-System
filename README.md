# 🏥 Hospital Management System

## 📌 Project Overview

The **Hospital Management System** is a menu-driven Python application developed using Object-Oriented Programming (OOP) concepts. It helps manage basic hospital operations such as doctor records, patient records, appointments, billing, payments, pharmacy, laboratory tests, and feedback.

The project demonstrates how Python OOP concepts can be used to develop a simple real-world management system.

## 🎯 Project Objectives

- Manage doctor and patient information.
- Book doctor appointments.
- Generate patient bills.
- Provide multiple payment methods.
- Manage pharmacy and laboratory details.
- Collect patient feedback.
- Demonstrate Python Object-Oriented Programming concepts.

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Concepts:** Object-Oriented Programming (OOP)
- **Libraries:** `abc` (Abstract Base Class)
- **Tools:** VS Code / Python IDLE

## 📚 OOP Concepts Implemented

| OOP Concept | Implementation |
|---|---|
| Class and Object | Person, Doctor, Patient, Billing |
| Inheritance | Doctor and Patient inherit Person |
| Encapsulation | Private `__amount` variable in Billing |
| Abstraction | Payment abstract class |
| Polymorphism | CashPayment, UPIPayment, CardPayment |
| Constructor | `__init__()` method |
| Super Keyword | `super().__init__()` |

## ⚙️ Project Modules

### 1. Admin Login
- Username: `admin`
- Password: `123`
- Provides access to the main menu.

### 2. Doctor Management
- Add doctor details.
- View doctor information.
- Store doctor specialization.

### 3. Patient Management
- Add patient details.
- View patient information.
- Store patient disease information.

### 4. Appointment Management
- Book appointments.
- Display patient name, doctor name, and appointment date.

### 5. Billing Management
- Generate bills.
- Store bill amount using encapsulation.
- Display total bill.

### 6. Payment Management
Supports three payment methods:
- Cash Payment
- UPI Payment
- Debit/Credit Card Payment

### 7. Pharmacy Management
- Enter medicine name.
- Enter medicine price.
- Display pharmacy details.

### 8. Laboratory Management
- Enter laboratory test name.
- Display test details.

### 9. Feedback Management
- Collect feedback.
- Display feedback messages.

## 📂 Project Structure

```text
Hospital-Management-System/
│
├── hospital_management.py
│
└── README.md
```

## ▶️ How to Run the Project

**Step 1:** Install Python on your system.

**Step 2:** Clone the repository.

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

**Step 3:** Open the project folder.

```bash
cd Hospital-Management-System
```

**Step 4:** Run the Python file.

```bash
python hospital_management.py
```

**Step 5:** Enter the login credentials.

```text
Username: admin
Password: 123
```

**Step 6:** Select an option from the main menu.

## 📋 Main Menu Options

| Choice | Functionality |
|---|---|
| 1 | Add Doctor |
| 2 | Add Patient |
| 3 | View Doctor |
| 4 | View Patient |
| 5 | Book Appointment |
| 6 | Generate Bill |
| 7 | Payment |
| 8 | Pharmacy |
| 9 | Laboratory |
| 10 | Feedback |
| 11 | Exit |

## 🚀 Future Enhancements

- Add database connectivity using MySQL.
- Store multiple doctor and patient records.
- Add appointment scheduling and cancellation.
- Generate detailed billing reports.
- Add role-based login for doctors and patients.
- Develop a graphical user interface (GUI).

## 🎓 Learning Outcomes

Through this project, I learned:

- How to implement OOP concepts in Python.
- How inheritance reduces code duplication.
- How encapsulation protects class data.
- How abstraction defines common methods.
- How polymorphism allows different payment implementations.
- How to develop a menu-driven Python application.

## 👩‍💻 Author

**Mansi Pawar**

## 📄 License

This project is developed for educational and learning purposes.
