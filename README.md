# 🧾 IT Support Queue Case Study – Multi-Level Troubleshooting
**CMIT 265 | Fundamentals of Networking**

 📄 **Full Lab Report:**  
👉 [Click here to open the complete lab report](https://github.com/Pelumi-Johnson/BYOD-Security-Assessment-Device-Compliance-Project/blob/main/hfabyodregistrationformtemplate%20(1)%20(1).pdf)

---

### 🎧 Tiered Help Desk Ticket Analysis & Resolution
Hands-on troubleshooting project simulating real-world IT support tickets across **Level 1, Level 2, and Level 3**, applying structured diagnostic thinking based on the CompTIA troubleshooting methodology.

---

## 🎯 Project Objective
This project demonstrates the ability to:
- Analyze user-reported IT issues
- Apply systematic troubleshooting steps
- Identify root causes across hardware, software, and networking
- Recommend and document clear, professional solutions

The scenarios mirror real **help desk and desktop support environments**, emphasizing clear documentation and escalation awareness.

---

## 🧩 Troubleshooting Framework Used
Each ticket followed the CompTIA-style process:
1. Identify the problem  
2. Establish a theory of probable cause  
3. Test the theory  
4. Establish and implement a solution  
5. Document findings and outcomes  

---

## 🟢 Level 1 Support Tickets

### 🖨️ Ticket 1001 — Printer Ink Smearing
**Issue Identified**
- Printouts showed smearing
- Cyan toner leaking onto paper

**Root Cause Analysis**
- Likely defective or leaking cyan toner cartridge
- Possible fuser or incorrect paper type

**Resolution**
- Inspected and replaced cyan cartridge
- Cleaned excess toner
- Tested with correct paper type
- Prepared contingency plan if fuser replacement is required

**Skill Areas**
- Peripheral troubleshooting
- Print hardware diagnostics
- Preventive maintenance awareness

---

### 🖱️ Ticket 1002 — Mouse Not Working
**Issue Identified**
- Mouse unresponsive
- Not detected in Device Manager

**Root Cause Analysis**
- Possible faulty USB port, driver issue, or failed device

**Resolution**
- Tested mouse on alternate ports and systems
- Verified USB functionality
- Recommended driver reinstallation or device replacement if needed

**Skill Areas**
- Hardware isolation
- USB diagnostics
- Device Manager usage

---

## 🟡 Level 2 Support Tickets

### 🖥️ Ticket 2002 — Dell System Beep Code (1-3-2)
**Issue Identified**
- System failed to boot
- Audible beep pattern: 1-3-2

**Root Cause Analysis**
- BIOS diagnostic code indicating RAM issue

**Resolution**
- Powered down system
- Reseated memory modules
- Tested individual RAM sticks
- Escalated to hardware repair if unresolved

**Skill Areas**
- BIOS/UEFI diagnostics
- Hardware-level troubleshooting
- Escalation judgment

---

### 🌐 Ticket 2005 — Cannot Access Shared Drive
**Issue Identified**
- No access to shared network resources
- IP address in 169.254.x.x range (APIPA)

**Root Cause Analysis**
- DHCP failure
- Possible cable, NIC, or switch port issue

**Resolution**
- Checked physical connectivity
- Renewed IP lease using `ipconfig`
- Verified NIC status
- Escalated to network support if DHCP issue persisted

**Skill Areas**
- Network fundamentals
- IP addressing & DHCP
- Layer 1–3 troubleshooting

---

## 🔴 Level 3 Support Tickets

### 🌍 Ticket 3001 — No Internet Connectivity
**Issue Identified**
- Internet inaccessible despite local connection
- Missing default gateway in IPv4 settings

**Root Cause Analysis**
- Manual IP configuration incomplete

**Resolution**
- Added correct default gateway
- Alternatively enabled DHCP
- Verified connectivity via ping and browser tests

**Skill Areas**
- TCP/IP configuration
- Routing fundamentals
- DNS vs gateway understanding

---

### 💽 Ticket 3003 — Frozen Computer / 100% Disk Usage
**Issue Identified**
- System freezing
- SSD at 100% utilization

**Root Cause Analysis**
- Possible SSD failure
- Heavy background processes
- Corrupted file system

**Resolution**
- Backed up critical data
- Checked disk health (SMART, chkdsk)
- Isolated background services
- Planned SSD replacement if hardware fault confirmed

**Skill Areas**
- Storage diagnostics
- Performance troubleshooting
- Risk mitigation

---

## 🧠 Reflection & Lessons Learned
One of the most impactful lessons came from diagnosing the **missing default gateway** issue. Seeing how a single missing configuration value could completely break internet access reinforced how critical attention to detail is in networking.

Interpreting **BIOS beep codes** was another key learning moment. Identifying that a 1-3-2 pattern pointed to a memory issue strengthened my confidence in hardware-level diagnostics.

This project emphasized the importance of:
- Slowing down
- Documenting every step
- Avoiding assumptions
- Following a repeatable troubleshooting process

