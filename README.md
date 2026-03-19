# 🔐 RevPasswordManager-P2

A secure, full-stack **Password Manager Web Application** built using **Spring Boot**.  
This application enables users to safely store, manage, and generate passwords for their online accounts with advanced security features like encryption, master password protection, and two-factor authentication.

---

## 🚀 Application Overview

The Password Manager is a **monolithic web application** that provides a secure vault for storing credentials.  

Users can:
- Create an account with a **master password**
- Generate strong passwords
- Store credentials in an **encrypted vault**
- Manage passwords through an intuitive UI

The application emphasizes **security, usability, and performance**.

---

## ✨ Core Features

### 🔑 Authentication & Account Management

- User registration with email, username, and master password
- Security questions setup (minimum 3)
- Login using username/email and master password
- Dashboard with:
  - Total passwords
  - Weak passwords
  - Recently added entries
- Profile management (name, email, phone)
- Change master password (with verification)
- Password recovery via security questions
- Two-Factor Authentication (2FA simulation)
- Secure logout

---

### 🔐 Password Vault Management

- View all stored passwords (list/grid)
- Search by account name, website, or username
- Filter by category:
  - Social Media
  - Banking
  - Email
  - Shopping
  - Work
  - Other
- Sort by:
  - Name
  - Date added
  - Date modified
- View password details (requires master password re-entry)
- Add / Update / Delete password entries
- Mark passwords as **favorites**
- View favorite passwords

---

### 🔧 Password Generator

- Generate strong random passwords with:
  - Length (8–64 characters)
  - Uppercase / Lowercase letters
  - Numbers
  - Special characters
  - Exclude similar characters
- Password strength indicator:
  - Weak / Medium / Strong / Very Strong
- Copy password to clipboard
- Save generated password directly to vault
- Generate multiple options

---

### 🛡️ Security Features

- Encrypted password storage
- Master password re-verification for sensitive actions
- Verification code system (email simulation)
- Code expiration mechanism
- Password strength analysis
- Security alerts for:
  - Weak passwords
  - Reused passwords
- Security audit report:
  - Weak passwords
  - Old passwords
- Export encrypted vault backup
- Import encrypted vault

---

### ❓ Security Questions Management

- Add security questions during registration
- Minimum 3 required
- View configured questions
- Update answers (requires authentication)

---

## 🛠️ Tech Stack

- **Backend:** Java, Spring Boot
- **Frontend:** HTML, CSS, Thymeleaf
- **Build Tool:** Maven
- **Testing:** JUnit
- **Architecture:** Monolithic

---


---

## ⚙️ How to Run

### 1️⃣ Clone Repository

```bash
git clone https://github.com/Gudivaka-Dijendra-Pavan-Kumar/RevPasswordManager-P2.git

cd revPasswordmanager

mvn spring-boot:run

http://localhost:8080

mvn test


📊 Definition of Done

✅ Fully functional web application

✅ Secure password storage & encryption

✅ GitHub repository with complete code

✅ README documentation

✅ Testing implementation

✅ Security features implemented


👨‍💻 Author

Pavan Kumar Gudivaka

GitHub: https://github.com/Gudivaka-Dijendra-Pavan-Kumar


⭐ Support

If you found this project useful, please ⭐ the repository!

