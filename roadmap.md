# 🗺️ Oracle DBA Learning & Project Roadmap

This roadmap outlines the full learning path, tasks, and deliverables that power the [`oracle-dba-lab-portfolio`](https://github.com/crispusomollo/oracle-dba-lab-portfolio) project.

Designed for hands-on learners, this plan simulates real DBA work across Oracle, Linux, scripting, automation, and cloud.

---

## ✅ Prerequisites (Before Day 1)

Make sure your system is ready:

- [ ] Oracle 23c Free installed (Docker or WSL Oracle Linux)
- [ ] Can connect with SQL\*Plus and SQL Developer
- [ ] Oracle listener running (`lsnrctl status`)
- [ ] Environment variables set (`ORACLE_SID`, `ORACLE_HOME`)
- [ ] Basic Linux CLI skills (bash, vim, permissions)

---

## 📅 30-Day Roadmap Summary

| Week   | Focus Area                 | Key Topics Covered                      |
|--------|----------------------------|-----------------------------------------|
| Week 1 | Linux + Shell Basics       | Navigation, users, processes, packages  |
| Week 2 | Oracle DB Foundations      | SQL\*Plus, startup, users, tablespaces  |
| Week 3 | Automation & Scripting     | Backups, `cron`, env vars, logs         |
| Week 4 | Security + Performance     | Hardening, monitoring, AWR views        |
| Final  | Capstone + Deployment      | Cloud migration, resume, GitHub project |

---

## 📖 Weekly Breakdown

### 🔹 Week 1: Linux Foundations

| Day | Topics                            |
|-----|-----------------------------------|
| 1   | CLI basics: `cd`, `ls`, `man`     |
| 2   | Files/dirs: `mkdir`, `tree`, `rm` |
| 3   | Text editing: `nano`, `vim`       |
| 4   | File perms: `chmod`, `chown`      |
| 5   | Processes: `ps`, `top`, `kill`    |
| 6   | Users/groups: `sudo`, `adduser`   |
| 7   | Packages: `dnf`, `yum`, `rpm`     |

---

### 🔹 Week 2: Oracle DBA Core

| Day | Topics                         |
|-----|--------------------------------|
| 8   | Oracle env + SID, listener     |
| 9   | SQL\*Plus basics               |
| 10  | Startup/shutdown DB            |
| 11  | Parameters, V$ views           |
| 12  | Create users, grants, roles    |
| 13  | Tablespaces, quotas            |
| 14  | TNS config + SQL Developer     |

---

### 🔹 Week 3: Automation & Scripting

| Day | Topics                         |
|-----|--------------------------------|
| 15  | Bash scripting basics          |
| 16  | Export env vars, `.bashrc`     |
| 17  | Crontab jobs                   |
| 18  | `expdp` full backup            |
| 19  | `impdp` schema restore         |
| 20  | Log + disk usage checks        |
| 21  | Monitor CPU/disk impact        |

---

### 🔹 Week 4: Hardening & Performance

| Day | Topics                         |
|-----|--------------------------------|
| 22  | SQL Developer GUI workflows    |
| 23  | Security: OS + DB              |
| 24  | Bash functions + error checks  |
| 25  | Autostart with systemd         |
| 26  | Remote access, SSH tunneling   |
| 27  | Troubleshooting (ORA errors)   |
| 28  | Query tuning, session views    |
| 29  | Self-review + quiz             |
| 30  | Package + present lab          |

---

## 🧪 Final Capstone Tasks

These tasks bring it all together.

### 1. Multi-Schema Simulation

- Create 3+ users with roles + quotas
- Shared views across schemas
- Backup scripts + auto exports
- Performance tracking with V$ views

### 2. Security Hardening

- Lock system accounts  
- Enforce password profiles  
- SSH key access only  
- Enable auditing + firewall rules

### 3. Dockerized Lab Setup

- Use Oracle 23c XE container  
- Scripts auto-load schemas/data  
- Connect via SQL Developer (localhost)

### 4. Cloud Migration (Optional)

- Migrate to OCI ATP using export/import  
- Optionally deploy with Terraform  
- Store backups in OCI Object Storage  

### 5. GitHub Portfolio Packaging

- Add screenshots, sample data, logs  
- Include resume and certifications  
- Polish `README.md`  
- Add project badge, deployment instructions

---

## 🧠 Bonus Learning Areas

- ☁️  OCI CLI + Terraform (Infra as Code)
- 🧮 Simulated AWR reports from V$ views
- 📬 Email alert scripts with `mailx`
- 🧼 Log rotation and archive scripts
- 🧾 SQL interview challenge workbook *(coming soon)*

---

## 🏁 Outcome

By the end of this roadmap, you’ll be able to:

- ✔️  Administer Oracle DBs with confidence
- 🐧 Use Linux like a power user
- 🛠️ Automate DBA tasks with Bash
- 🧠 Tune queries and analyze DB performance
- ☁️  Migrate and run workloads on Oracle Cloud
- 💼 Package your work for job applications

---

## 💬 Need Help?

Open an [Issue](https://github.com/crispusomollo/oracle-dba-lab-portfolio/issues) or reach out via GitHub Discussions.

---

> 🧠 *"This lab isn't just practice — it's your proof of work."*

