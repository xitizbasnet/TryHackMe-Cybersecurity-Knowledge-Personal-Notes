# 🔴 Offensive Security Introduction

> *Hack your first website (legally) and experience the role of an ethical hacker.*

***

## 🧪 Room No: 1 — Offensive Security Intro

***

## 🧠 Task 1: Think Like a Hacker!

**Description:**  
Offensive Security involves thinking like an attacker to identify vulnerabilities **before real hackers exploit them**.

In this task, you ethically hack a website within a **safe and legal environment** to understand how attackers operate.

### ✅ Question

**Which term describes simulating a hacker's actions to find system vulnerabilities?**

*   Offensive Security
*   Defensive Security

### ✔️ Answer

    Offensive Security

***

## 🚀 Task 2: Starting the Lab

**Environment:**  
This room uses a **virtual desktop** to simulate a real system.

### Steps

1.  Click **View Site**
2.  A fake banking application called **FakeBank** launches
3.  The application runs inside your browser

### ✅ Question

**What is the bank account number shown in the FakeBank application?**

### ✔️ Answer

    8881

***

## 🔍 Task 3: Find Hidden Pages

**Goal:**  
Identify hidden and unprotected pages on the FakeBank website.

### 🔧 Tool Used

*   **Terminal**
*   **DIRB** (Directory Brute‑Forcing Tool)

### Instructions

1.  Click **View Site**
2.  Open the terminal
3.  Run the following command:

```bash
dirb http://fakebank.thm
```

> ℹ️ Any result starting with `+` indicates a discovered page.

### ✅ Findings

DIRB reveals **two hidden URLs**:

*   `http://fakebank.thm/images`
*   `http://fakebank.thm/bank-transfer`

### ✅ Question

**What is the other hidden URL (besides `/images`)?**

### ✔️ Answer

    http://fakebank.thm/bank-transfer

***

### 📝 Explanation (How to Proceed)

1.  Open terminal
2.  Run:
    ```bash
    dirb http://fakebank.thm
    ```
3.  Observe the discovered URLs
4.  Identify `/bank-transfer` as the admin‑related page

***

## 💥 Task 4: Attack the Admin Page

**Objective:**  
Exploit the hidden admin panel to manipulate account balances.

### Steps

1.  Click **View Site**
2.  In the browser address bar, append:
        /bank-transfer
3.  Full URL:
        http://fakebank.thm/bank-transfer
4.  Select **Account Number: 8881**
5.  Deposit **$2000 or more**
6.  Click **Deposit Money**

### ✅ Result

A success pop‑up with **green text** appears.

### ✅ Question

**Enter the green words shown (ALL CAPS)**

### ✔️ Answer

    BANK-HACKED

***

 

## 📌 Summary

| Area               | Key Takeaway                                     |
| ------------------ | ------------------------------------------------ |
| Offensive Security | Identify and exploit vulnerabilities ethically   |
 
