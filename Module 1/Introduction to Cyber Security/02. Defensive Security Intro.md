# 🔵 Defensive Security Introduction

> *Learn how to protect systems and stop attacks in real time.*

***

## 🧪 Room No: 2 — Defensive Security Intro

***

## 🛡️ Task 1: Think Like a Defender

**Description:**  
Defensive Security focuses on:

*   Monitoring systems
*   Detecting threats
*   Investigating suspicious activities
*   Responding **before damage occurs**

> ⚠️ Unlike offensive security, defenders **do NOT attack systems**.

### ✅ Question

**What is the main goal of defensive security?**

*   Detect and respond to attacks
*   Attack systems to find flaws

### ✔️ Answer

    Detect and respond to attacks

***

## 🚨 Task 2: Detect Suspicious Activity

**Scenario:**  
Joe, a SOC analyst, notices suspicious alerts on the monitoring dashboard.

### Actions Required

1.  Open the monitoring dashboard
2.  Review recent alerts
3.  Identify the suspicious **source IP**

### ✅ Alert Observed

*   **Web Discovery Attack**
*   **Automated directory enumeration detected**
*   **Source IP:** `32.122.195.63`

### ✅ Question

**Which source IP address is generating the suspicious traffic?**

### ✔️ Answer

    32.122.195.63

***

## 🧩 Task 3: Identify the Attack

**Objective:**  
Determine *what the attacker is trying to access*.

### Actions

1.  Open the monitoring dashboard
2.  Navigate to **URL Discovery Attempts**
3.  Review the latest entry

### ✅ Observation

The attacker is probing for hidden admin pages.

### ✅ Question

**Copy the latest URL the attacker tried to find**

### ✔️ Answer

    https://fakebank.com/admin

***

## 🛑 Task 4: Stop the Attack

**Objective:**  
Contain the attack and secure the system.

### Steps

1.  Review existing security actions (two already applied)
2.  Add a firewall rule:
    *   **Source IP:** `32.122.195.63`
    *   **Action:** `BLOCK`
3.  Click **Apply**
4.  Click **Complete**

### 🔐 Defensive Measures Explained

*   🚫 **Block IP Address** — Stops attacker immediately
*   ⏱️ **Rate Limiting** — Prevents brute‑force access
*   🔒 **Security Rule Updates** — Restricts access to hidden pages

### ✅ Question

**Copy the success flag displayed**

### ✔️ Answer

    THM{FAKEBANK-SECURED}

***

## ✅ Final Result

🎉 **FakeBank successfully secured and attack contained!**

**Final Flag:**

    THM{FAKEBANK-SECURED}

***

## 📌 Summary

| Area               | Key Takeaway                                     |
| ------------------ | ------------------------------------------------ |
| Offensive Security | Identify and exploit vulnerabilities ethically   |
| Defensive Security | Detect, investigate, and stop attacks            |
| Key Tools          | DIRB, Monitoring Dashboards, Firewall Rules      |
| Skills Gained      | Ethical hacking, SOC analysis, incident response |

***
 
