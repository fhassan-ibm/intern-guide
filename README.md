# 🚀 NVMe-CLI Internship Guide

Welcome to the **NVMe-CLI Internship at IBM**!  
This guide contains all essential links, credentials, setup steps, development tooling, and terminal commands you will use throughout your internship.

---

## 📚 Table of Contents
- #-critical-hr--administrative-tasks  
- #-ibm-internal-resources  
- #-technical-access--credentials  
- #-development-environment  
- #-project-specific-resources  
- #-useful-terminal-commands  

---

## ⚠️ Critical HR & Administrative Tasks

### ⏱️ Weekly Time Logging (REQUIRED)
**Log your hours every Friday before Noon**

- 🔗 https://sf-wz-prd-p2-4snxii8t.workzonehr.cfapps.us10.hana.ondemand.com/site#workzone-home&/home?source=from_menu  
- 📍 Navigation: `HR Zone → Record Your Time → Apply Planned Time`  
- 📅 Frequency: Weekly  
- ❗ Importance: Missing logs may affect your internship  
---

### 🎯 Internship Journey Tool (REQUIRED)
- 🔗 https://yourlearning.ibm.com/activity/PLAN-FA5EE89ABD92  
- ⏳ Complete before internship ends  
- 📘 Tracks your learning progress  

---

### 📝 Blueprint Form
- 🔗 https://ibm.ent.box.com/file/2235842852817?s=0djl2oyw2t841zv71jnwpz07igaa7ufm&sb=/boxai  
- 📘 Used for project planning and documentation  

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

## 💻 Terminal & LPAR Access

⚙️ NIM (Network Installation Management)
🔗 https://pages.github.ibm.com/Halbedaiwi/nim-installation/

📅 Intern Plan & Schedule

🔗 https://github.ibm.com/drc/2026-intern-plans/blob/main/nvme-cli-coverity/INTERN-SCHEDULE.md
📘 Used for:

OS provisioning
System setup
Environment configuration

### 🔐 Root Access (System-Level Access)
```bash
ssh root@<ipaddress>
ex - ssh fhassan@ltcrain119-lp6.ltc.tadn.ibm.com
ex - ssh root@ltcrain65-lp4.ltc.tadn.ibm.com
ssh <your_username>@<lpar_hostname>
ibm-dnf.sh
