# 🚀 NVMe-CLI Internship Guide

Welcome to the **NVMe-CLI Internship at IBM**!  
This guide contains all essential links, credentials, setup steps, development tooling, and terminal commands you will use throughout your internship.

---

## ⚠️ Critical HR & Administrative Tasks

### ⏱️ Weekly Time Logging (REQUIRED)
**Log your hours every Friday before Noon**

- 🔗 https://sf-wz-prd-p2-4snxii8t.workzonehr.cfapps.us10.hana.ondemand.com/site#workzone-home&/home?source=from_menu  
- 📍 Navigation: `HR Zone → Record Your Time → Apply Planned Time`  
- 📅 Frequency: Weekly  
---

### 🎯 Internship Journey Tool (REQUIRED)
- 🔗 https://yourlearning.ibm.com/activity/PLAN-FA5EE89ABD92  
- ⏳ Complete before internship ends  


---

### 📝 Blueprint Form
- 🔗 https://ibm.ent.box.com/file/2235842852817?s=0djl2oyw2t841zv71jnwpz07igaa7ufm&sb=/boxai  
   

---

## 🏢 IBM Internal Resources

### 🌐 General IBM Resources 
- https://w3.ibm.com  
- https://w3.ibm.com/w3publisher/new-hire-community  
- https://w3.ibm.com/w3publisher/bob/  

---

### 🛠️ Tools & Software
- https://w3.ibm.com/#/support/article/microsoft_copilot/copilot_overview  
- https://ftp3.linux.ibm.com/  

---

### 🎓 Education & Training
- https://ibm.ent.box.com/notes/2231661297345?s=49iv15yknblusp74wjexdby8940787uz  

---

## 🔐 Technical Access & Credentials

### 🧪 Lab Access
- 🔗 https://prod.stela.dal.app.cirrus.ibm.com/plab/nims  
- 📘 Used to retrieve lab passwords  
- 🔒 Do NOT share credentials  

---

### 🖥️ HMC (Hardware Management Console)
- 🌐 https://ltcvhmc9b.ltc.tadn.ibm.com/hmc/connect  
- 👤 Username: `hscroot`  
- 🔑 Password: Lab password  
- 📘 Used for system and hardware management  

---

## 💻 More Important Links
⚙️ NIM (Network Installation Management)
🔗 https://pages.github.ibm.com/Halbedaiwi/nim-installation/

📅 Intern Plan & Schedule

🔗 https://github.ibm.com/drc/2026-intern-plans/blob/main/nvme-cli-coverity/INTERN-SCHEDULE.md

🧩 NVMe-CLI Project Repository

🔗 https://github.com/linux-nvme/nvme-cli


### 🔐 Important Commands (System-Level Access)
```bash
ssh root@<ipaddress>
ex - ssh fhassan@ltcrain119-lp6.ltc.tadn.ibm.com
ssh <your_username>@<lpar_hostname>
ex - ssh root@ltcrain65-lp4.ltc.tadn.ibm.com
ibm-dnf.sh - important subscription resource

pwd             # Show current directory
cd <dir>        # Change directory
cd ..           # Go back one directory
cd ~            # Go to home directory
cat <file>      # View file contents
less <file>     # Scroll file
vim <file>      # Advanced editor
nano <file>     # Beginner editor
ls              # List files
ls -la          # Detailed list
mkdir <dir>     # Create directory
rm <file>       # Remove file
cp <src> <dst>  # Copy file
mv <src> <dst>  # Move/rename
hostname -I     # Show IP address
whoami          # Current user
df -h           # Disk usage
top             # Running processes

CLANG tools (once lpar is set up)
cd /root/nvme-cli

rm -rf .build
CC=clang CXX=clang meson setup .build
ninja -C .build scan-build
