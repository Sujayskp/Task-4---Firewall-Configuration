# 🔐 Task 4 - Firewall Configuration

## ✅ Objective
To configure and test basic firewall rules using Windows Firewall to understand how firewalls filter network traffic and block insecure services like Telnet.

---

## 💻 My System Details
- **Operating System:** Windows 11 Home Single Language (Version 24H2)
- **OS Build:** 26100.4061
- **Installed On:** 16 December 2024

---

## 🛠️ Tools Used
- **Windows Defender Firewall** (Advanced Settings)

---

## 🧪 Steps Performed

### 1. Opened Firewall Settings
- Navigated to:  
  `Control Panel > System and Security > Windows Defender Firewall > Advanced Settings`

### 2. Listed Current Rules
- Checked **Inbound Rules** and **Outbound Rules** in the Firewall Management Console.

### 3. Blocked Telnet (Port 23)
- Created a **New Inbound Rule**:
  - Rule Type: Port
  - Protocol: TCP
  - Port Number: 23
  - Action: Block the connection
  - Applied to: Domain, Private, Public
  - Name: `Block Telnet`

### 4. Tested the Rule
- Attempted to connect to Telnet (Port 23) — connection was blocked as expected.

### 5. Removed the Rule
- Deleted the `Block Telnet` rule from the **Inbound Rules** to restore the original firewall state.

---

## 📸 Screenshots

![Screenshot 2025-05-30 203459](https://github.com/user-attachments/assets/5a54cbcb-2f64-433b-a3a0-c17bb9b810e4)
![Screenshot 2025-05-30 203424](https://github.com/user-attachments/assets/c6c3f2f2-d1e5-4f68-8ab2-85e9d26df517)
![Screenshot 2025-05-30 203405](https://github.com/user-attachments/assets/797b872c-e06d-4d9e-9e31-ac1c3bbfa07a)
![Screenshot 2025-05-30 203347](https://github.com/user-attachments/assets/63b5e899-f64c-42ac-8f0c-84f1831e261d)
![Screenshot 2025-05-30 203329](https://github.com/user-attachments/assets/3ca8af3f-0e65-46f2-ac4b-e05c39dab7f7)

---

## 🧠 What I Learned
- How to configure Windows Firewall using GUI.
- Importance of blocking insecure ports like Telnet (Port 23).
- How firewalls help control inbound and outbound traffic.
- How to safely manage and revert firewall rules.

---

## 📁 Files in this Repository
- `README.md` (this file)
- Screenshots of each step (added in the repo)




