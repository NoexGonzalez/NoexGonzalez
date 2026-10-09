# 🐧 Noe Gonzalez Ornelas | Enterprise Linux & Security Infrastructure

> **Linux Systems & Security Trainee** | Business Operations Specialist mastering Red Hat Enterprise Linux (RHCSA) and CompTIA Security via Skillsoft Enterprise.

---

### 🛡️ Profile & Certification Badges

[![LinkedIn](https://img.shields.io/badge/LinkedIn-noexgonzalez-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/noexgonzalez)
![Red Hat](https://img.shields.io/badge/Target-Red_Hat_RHCSA-EE0000?style=for-the-badge&logo=redhat&logoColor=white)
![Linux](https://img.shields.io/badge/OS-RHEL_Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![CompTIA](https://img.shields.io/badge/Certifications-CompTIA_Path-000000?style=for-the-badge&logo=comptia&logoColor=FF0000)
![Skillsoft](https://img.shields.io/badge/Platform-Skillsoft_Enterprise-1E293B?style=for-the-badge)

---

## 🎯 Current Roadmap & Technical Focus

* 🔴 **Primary Track (Active):** Red Hat Certified System Administrator (RHCSA / RHEL) via Skillsoft Enterprise
* 🛡️ **Secondary Track (Up Next):** CompTIA Network+ & Security+ Certification Modules
* 🎓 **Education:** Computer Science Studies at Portland Community College
* ⚡ **Goal:** Building deep Linux CLI fluency, system administration competence, and network security concepts to transition into Enterprise Systems & Security Operations.

---

## 💼 Background & Operational Edge

Coming from a background in **business operations, contracting logistics, and project management**, I bring real-world discipline, risk awareness, and execution to IT infrastructure.

* 🛠️ **Hands-On Linux:** Daily command-line lab work in Red Hat Enterprise Linux (RHEL 9), storage provisioning, permission models, and service management.
* 📈 **Operational Accountability:** Experienced in regulatory compliance, scope estimation, and process management—skills that directly apply to audit trails, access controls, and system hardening.
* 🎯 **Structured Progression:** Systematically mastering core RHEL system administration before advancing into network architecture and threat mitigation.

---

## 📊 Certification & Skill Progress

| Certification Track | Provider | Progress | Status | Primary Focus |
| :--- | :--- | :--- | :--- | :--- |
| **RHEL System Administration (RHCSA)** | Skillsoft Enterprise | `██████░░░░` 60% | Active Study | User/Group Mgmt, LVM Storage, SELinux, CLI |
| **CompTIA Network+ / Security+** | Skillsoft Enterprise | `████░░░░░░` 40% | Up Next | OSI Model, Subnetting, Ports, IAM Principles |
| **Linux CLI & System Hardening** | Hands-On Labs | `████████░░` 80% | Daily Practice | File Permissions, SSH Hardening, Systemd, Vim |

---

## 📚 Active Coursework Modules

### 🔴 Track 1: Red Hat Certified System Administrator (RHCSA / RHEL)
* **Platform:** Skillsoft Enterprise
* **Status:** 🟡 Active Modules
* **Lab Checklist:**
  - [x] RHEL Installation, Shell Navigation & File System Hierarchy
  - [x] User Accounts, Group Administration & File Permissions (`chmod`, `chown`, ACLs)
  - [x] Storage Partitioning & Logical Volume Management (`lvm`, `xfs`, `ext4`)
  - [ ] SELinux Enforcement Modes, Context Relabeling & Boolean Flags
  - [ ] Systemd Service Management, Boot Targets & Process Control
  - [ ] Enterprise Firewall Configuration (`firewalld`) & SSH Hardening

---

### 🛡️ Track 2: CompTIA Core Infrastructure (Network+ & Security+)
* **Platform:** Skillsoft Enterprise
* **Status:** ⏳ Scheduled Next
* **Lab Checklist:**
  - [x] TCP/IP Protocol Suite & OSI Model Fundamentals
  - [x] IPv4 Subnetting & Network Diagnostic Utilities (`ip`, `ss`, `ping`, `traceroute`)
  - [ ] Port Security, Network Firewalls & Traffic Filtering
  - [ ] Identity & Access Management (IAM) & Principle of Least Privilege
  - [ ] Vulnerability Scanning, System Hardening & Threat Mitigation

---

## 🛠️ Featured Lab: RHEL Storage & LVM Management

> 💡 **Lab Objective:** Provisioning Logical Volume Manager (LVM) storage pools and mounting persistent filesystems on RHEL.

```bash
# 1. Inspect block storage devices and active volume groups
vgs
lvs

# 2. Initialize physical volume and extend storage pool
pvcreate /dev/sdb1
vgextend app_vg /dev/sdb1

# 3. Create a 10G logical volume formatted with XFS
lvcreate -L 10G -n app_lv app_vg
mkfs.xfs /dev/app_vg/app_lv

# 4. Attach mount point to filesystem and verify configuration
mkdir -p /mnt/app_data
mount /dev/app_vg/app_lv /mnt/app_data
df -hT /mnt/app_data
[github.com/noexgonzalez](https://github.com/noexgonzalez)
[linkedin.com/in/noexgonzalez](https://linkedin.com/in/noexgonzalez)
