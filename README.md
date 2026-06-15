# E-Commerce Website End-to-End Manual Testing Project

An end-to-end manual testing portfolio focused on structural test design, boundary value analysis (BVA), and defect tracking for an E-Commerce platform.

---

## 📊 Project Artifacts
📌 **[Click Here to View the Full Test Cases & Bug Report Sheet]
https://docs.google.com/spreadsheets/d/12fm0MPnpXeKChswO3fvknaY8gvJ3HOxnpQWwmwCL2xI/edit?usp=sharing

---

## 🔍 Key Modules Tested
* **User Authentication:** Registration, Login, and Password Change mechanisms.
* **Product Search & Filtering:** Case-insensitivity, empty state handling, and special character sanitization.

## 🛠️ Testing Techniques Applied
* **Boundary Value Analysis (BVA) & Equivalence Partitioning (EP):** Applied on the age verification field (18-60 range) and password lengths.
* **Negative Testing:** Tested the system behavior against empty form submissions and mismatching passwords.
* **Error Guessing & Exploratory Testing:** Identified critical bugs in the registration UI.

---

## 📉 Test Execution Summary
* **Total Test Cases Executed:** 17
* **Passed:** 15
* **Failed (Bugs Found):** 2

### 🐛 Defects Identified (Bug Log)
1. **BUG_001 [Major]:** Account created successfully even when "Password" and "Confirm Password" fields do not match.
2. **BUG_002 [Major]:** System displays a blank white screen instead of validation errors upon blank form submission.
