# Password Management System
This repository contains the implementation for **Milestone 1** of the Password Management Application.  
The project is divided into two main components:

1. **Password Strength Analyzer**
2. **Login System Implementation**

Both parts were developed using Python and designed for use within a **Jupyter Notebook** environment.

---

## 📌 Part 1: Password Strength Analyzer

### **Description**
A tool that evaluates the strength of user-generated passwords based on several security criteria.

### **Features**
- Computes **password complexity**.
- Analyzes:
  - Length  
  - Character variety (uppercase, lowercase, digits, special characters)
  - Common patterns (e.g., "123", "abc", "password")
- Assigns a strength label:
  - **Weak**
  - **Moderate**
  - **Strong**
- Provides **real-time feedback** to guide users toward creating stronger passwords.
- Enforces password strength requirements (weak passwords are rejected during sign-up).

---

## 📌 Part 2: Login System Implementation

### **Description**
A simplified (non-UI) login system implementing core authentication features.

### **Features**

### 🔐 **1. Sign-Up System**
- Saves a username and password.
- Uses the password policy from Part 1.
- Rejects weak passwords automatically.

---

### 🔑 **2. Login System**
- Verifies username + password correctness.
- Implements **password expiry after 5 valid logins** (attempt-based expiry).
- Implements **account lockout after 3 failed login attempts**.
- Lockout counter resets after a successful login.

---

### 🔄 **3. Random Strong Password Generator**
- Generates a password that automatically passes the “Strong” criteria in Part 1.
- Ensures that generated passwords meet length, character variety, and pattern requirements.

---

## 🛠️ Technologies Used
- **Python 3**
- Standard libraries:
  - `re`
  - `random`
  - `string`
  - `datetime`

---

## 🚀 How to Run
1. Open the Jupyter Notebook.
2. Run each block sequentially.
3. Test the system using the sample test cases provided at the bottom of the notebook.
4. Use the interactive input sections to experiment with your own passwords and login attempts.

---

## 📘 Project Requirements Summary

This project satisfies **all Milestone 1 requirements**:

### ✔️ Password Strength Analyzer
- Computes complexity  
- Analyzes length, character variety, and patterns  
- Gives real-time feedback  
- Enforces strong passwords  

### ✔️ Login System
- Sign-up with password validation  
- Login with lockout policy  
- Login with password expiry (attempt-based)  
- Random password generator  

---

## 📄 License
This project was created for academic purposes at the **German University in Cairo (GUC)** as part of the **Information Security course (BINF 711)**.

Feel free to explore, clone, and improve upon the system.

---

## 👤 Author
**Ahmed Hassan**  
**Ziad Ekramy**
Faculty of Business Informatics    
German University in Cairo  
