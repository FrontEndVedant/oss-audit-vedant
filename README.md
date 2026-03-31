# OSS Capstone Project — Linux Kernel Audit

**Student Name:** Vedant Patil  
**Roll Number:** 24MIM10110  
**Course:** Open Source Software  
**Chosen Software:** Linux Kernel  
**Date:** 30 March 2026  

---

##  About the Project
This repository contains five Bash scripts developed as part of the Open Source Software Capstone Project. The project focuses on analyzing and interacting with the Linux Kernel through practical scripting. All scripts were tested on **Ubuntu 24.04.3 LTS** running **Linux Kernel 6.14.0-35-generic**.

---

##  Scripts Overview

**🔹 Script 1 — System Identity Report**  
Displays kernel version, logged-in user, system uptime, and GPL v2 license information.

**🔹 Script 2 — FOSS Package Inspector**  
Checks if the Linux kernel package is installed, displays version and license details, and includes a `case` statement for an open-source philosophy note.

**🔹 Script 3 — Disk and Permission Auditor**  
Scans important directories and reports permissions, ownership, and directory sizes using a `for` loop.

**🔹 Script 4 — Log File Analyzer**  
Reads log files line by line, counts keyword occurrences, and displays the last 5 matching lines using a `while` loop and counter.

**🔹 Script 5 — Open Source Manifesto Generator**  
Takes three user inputs and generates a personalized open-source philosophy statement saved to a `.txt` file.

---

##  Usage (Setup + Execution)

To run this project, ensure you have a Linux environment (Ubuntu/Debian recommended) with Bash and sudo access.

Clone the repository and navigate into it:
```bash
git clone https://github.com/FrontEndVedant/oss-audit-vedant.git
cd oss-audit-vedant
```

Make all scripts executable:
```bash
chmod +x script1_system_identity.sh
chmod +x script2_package_inspector.sh
chmod +x script3_disk_auditor.sh
chmod +x script4_log_analyzer.sh
chmod +x script5_manifesto_generator.sh
```

Run the scripts:
```bash
./script1_system_identity.sh
./script2_package_inspector.sh
./script3_disk_auditor.sh
sudo ./script4_log_analyzer.sh /var/log/syslog error
./script5_manifesto_generator.sh
```

---

##  Requirements & Dependencies

- Ubuntu / Debian-based Linux system  
- Bash shell  
- `lsb_release` (pre-installed on Ubuntu)  
- `dpkg` (pre-installed)  
- `sudo` privileges (required for Script 4)  

---

##  License

This project is submitted as part of the **VITyarthi OSS NGMC Capstone Project** by  
**Vedant Patil (24MIM10110)**.