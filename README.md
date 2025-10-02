# 🧪 Oracle DBA Lab Portfolio – `oracle-lab-x`

A hands-on, real-world Oracle DBA lab environment designed to simulate production workloads. Built with **Oracle 23c**, **Linux**, **Bash**, and optionally **Docker** or **Oracle Cloud (OCI)**, this lab showcases essential skills for database administration, automation, performance tuning, and cloud migration.

---

## 🚀 Features

- 🧑‍💻 Multi-schema Oracle DB (e.g. `dev_user`, `analyst_user`)
- 💾 Automated backups via Bash + cron
- 🐚 Shell scripts for health checks, log analysis, space monitoring
- 📈 Performance insights using dynamic `V$` views
- ☁️ Portable with Docker Compose or deployable to Oracle Cloud ATP
- 🔐 OS + DB security hardening examples

---

## 🧪 Lab Preview

### Users

- `dev_user` – Developer schema with full object privileges  
- `analyst_user` – Read-only access to shared views and reports

### Sample Scripts

- `db_backup.sh` – Full export with `expdp`  
- `listener_check.sh` – Check Oracle listener status  
- `space_monitor.sh` – Tablespace alert script  
- `schema-create.sql` – Setup sample tables, users, and data

---

## 📦 Quick Start (Docker)

> 🐳 Run the full lab locally using Docker Compose.

```bash
git clone https://github.com/crispusomollo/oracle-lab-x.git
cd oracle-lab-x/docker
docker-compose up -d



## 🧠 Technologies

- Oracle 23c Free / XE
- Oracle Linux (WSL + Cloud)
- SQL\*Plus + SQL Developer
- Bash scripting
- Docker (optional)
- Terraform / OCI CLI (optional)

## 📂 Project Structure

See [lab-scripts/](./lab-scripts) and [docker/](./docker) for core files.

## 📸 Screenshots

<img width="1896" height="1063" alt="image" src="https://github.com/user-attachments/assets/c269308e-33a1-417e-a7d9-10d6eeffbc37" />

<img width="1902" height="1064" alt="image" src="https://github.com/user-attachments/assets/466afa25-bc84-47bc-9af9-376f74f64916" />

<img width="1899" height="1074" alt="image" src="https://github.com/user-attachments/assets/301a3825-70de-4ad2-8e13-1ed411344219" />


## 📃 Certificates

- ✅ Oracle OCA Certified (23c) - Ongoing
- ☁️ OCI Associates 2025
- 🐧 Linux+

## 📄 Resume

See [Resume](./resume/oracle_dba_resume.pdf)

---
