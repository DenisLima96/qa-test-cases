# 🧪 QA Test Cases

This repository contains manual test cases created as part of my QA learning journey.

---

## 🌍 Note

This content is written in English to follow industry standards.

---

## 📌 Tested Feature: User Registration

### ✅ Scenario: Successful registration

**Given** the user is on the registration page
**When** the user fills all required fields correctly
**Then** the account should be created successfully

---

### ❌ Scenario: Missing required field

**Given** the user is on the registration page
**When** the user leaves a required field empty
**Then** the system should display a validation error

---

### 🔒 Scenario: Invalid email format

**Given** the user is on the registration page
**When** the user enters an invalid email
**Then** the system should show an error message

---

## 📌 Tested Feature: Login

### ✅ Scenario: Valid login

**Given** the user is on the login page
**When** the user enters valid credentials
**Then** the user should access the system

---

### ❌ Scenario: Incorrect password

**Given** the user is on the login page
**When** the user enters an incorrect password
**Then** the system should deny access

---

💬 These scenarios are based on common system behaviors and QA practices.
