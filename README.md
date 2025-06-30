# Task 4: Firewall Configuration

# Objective
To configure Windows Firewall to block Telnet traffic (port 23) and gain practical experience with basic firewall rule management.

# Tools Used
- Windows Defender Firewall with Advanced Security (GUI)

---

# Actions Performed

1. Opened Windows Firewall using `wf.msc`.
2. Navigated to **Inbound Rules** in the left sidebar.
3. Clicked **New Rule** → Selected:
   - **Rule Type:** Port  
   - **Protocol:** TCP  
   - **Port:** 23  
   - **Action:** Block the connection  
   - **Profile:** Domain, Private, Public  
   - **Name:** `Block_TELNET_Port_23`
4. Verified that the rule was listed and active in Inbound Rules.
5. Took a screenshot as evidence.
6. Removed the rule after testing.

---

# Screenshot
- `firewall_telnet_block.png` – shows the blocked Telnet rule in the firewall.
- `cmd_test.png` - shows connection to port 23 failed
- `new_rule.png` - adding a new rule page

---

## 🧠 Summary
- Telnet (port 23) is outdated and transmits data in plaintext.
- Blocking it improves system security.
- This task demonstrates how Windows Firewall filters network traffic and enforces inbound rules.

---

## 📘 Outcome
Successfully created, tested, and managed a firewall rule in Windows to block Telnet traffic, demonstrating understanding of inbound rules and traffic filtering.
