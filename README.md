# Windows 11 IT Security Lab – Small Business Environment

This project demonstrates hands-on experience securing a simulated small business
Windows 11 Pro environment using a virtual machine. The focus is on endpoint
security, user access control, networking basics, and help desk troubleshooting.

---

## 🧰 Environment
- Windows 11 Pro (Virtual Machine)
- Local user accounts (1 admin, 4 standard users)
- NAT networking
- Built-in Windows security tools

---

## 🎯 Objectives
- Apply least-privilege user access
- Secure a Windows workstation using built-in tools
- Configure firewall and password policies
- Perform backup and recovery testing
- Simulate real help desk tickets

---

## 🛠️ Technologies Used
- Windows 11 Pro
- Windows Defender (Real-time, Cloud, Tamper Protection)
- BitLocker Drive Encryption
- Windows Firewall
- Local Security Policy & Group Policy
- TCP/IP Networking

---

## 👥 User Account Configuration
- Created one administrator account and four standard user accounts
- Disabled Guest account
- Renamed default Administrator account to reduce attack surface
- Enforced least-privilege access

---

## 🔐 Password & Account Security
- Minimum password length: 10 characters
- Password complexity requirements enabled
- Maximum password age: 60 days

These settings reduce the risk of brute-force and credential reuse attacks.

---

## 🛡️ Endpoint Protection
- Enabled Windows Defender real-time protection
- Enabled cloud-delivered protection
- Enabled Tamper Protection to prevent security bypass
- Performed full malware scan

---

## 🔒 Disk Encryption
- Enabled BitLocker on the system drive
- Securely stored BitLocker recovery key

BitLocker protects data in the event of device loss or theft.

---

## 🌐 Network Configuration
- Documented IPv4 address, subnet mask, default gateway, and DNS servers
- Reviewed inbound and outbound firewall rules
- Disabled File and Printer Sharing for security

Inbound rules control traffic entering the device, while outbound rules control
traffic leaving the device.

---

## 🧑‍💼 Local Group Policy Configuration
- Set machine inactivity limit to 300 seconds
- Restricted user access to Control Panel

These policies reduce unauthorized access and misconfiguration.

---

## 💾 Backup & Recovery
- Enabled OneDrive or File History backup
- Created and deleted a test file
- Successfully restored the file from backup

Backups protect against accidental deletion and ransomware incidents.

---

## 🎫 Help Desk Ticket 

### Ticket 001 – Software Restriction Policies
**User:** user2  
**Issue:** Unable to install software  
**Diagnosis:** Standard user account lacks administrator privileges  
**Resolution:** Installed software using Local-IT-Admin account  
**Status:** Resolved  
<img width="879" height="954" alt="Screenshot 2026-01-29 230521" src="https://github.com/user-attachments/assets/bec39170-eb27-4960-8330-6efae421978c" />
<img width="1082" height="768" alt="Screenshot 2026-01-29 225207" src="https://github.com/user-attachments/assets/01b11ba1-eaab-48ac-a42d-2da714c96341" />
<img width="1069" height="713" alt="Screenshot 2026-01-29 225754" src="https://github.com/user-attachments/assets/fa1699bf-a427-4268-bd55-9291bf8ab7f3" />
<img width="949" height="682" alt="Screenshot 2026-01-29 225805" src="https://github.com/user-attachments/assets/97a02cfb-ccef-40ba-8e82-459deadc65b0" />

---

### Ticket 002 – Firewall Blocking Application
**User:** user3  
**Issue:** Application unable to access network  
**Diagnosis:** Windows Firewall inbound rule restriction  
**Resolution:** Created allow rule for trusted application  
**Status:** Resolved  


---

## 🧾 Resume Entry
**IT Security Lab – Windows 11 (Virtual Machine)**  
Built and secured a simulated small business Windows 11 Pro environment by
implementing least-privilege user accounts, password and security policies,
BitLocker encryption, Windows Defender protection, firewall configuration,
backup and recovery testing, and troubleshooting common end-user issues.

---

## 📌 Key Skills Demonstrated
- IT Support / Help Desk fundamentals
- Endpoint security
- User account management
- Windows networking basics
- Troubleshooting and documentation
- Virtual machine usage
