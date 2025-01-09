# 🚀 MyAnsibleScripts

Welcome to **MyAnsibleScripts**, a collection of Ansible playbooks designed to automate and simplify various system tasks. Whether you're troubleshooting, installing Docker, or gathering system information, these playbooks have you covered! 🛠️

---

## 📜 Playbooks Overview

Here’s a quick summary of the playbooks in this repository:

### 1. `apt_troubleshoot.yml` 🐧
- **Purpose**: Troubleshoots and resolves common `apt` package manager issues on Debian-based systems.
- **Key Features**:
  - 🧹 Cleans package caches.
  - 🔗 Fixes broken dependencies.
  - 📦 Updates and upgrades system packages.

---

### 2. `install_docker.yml` 🐳
- **Purpose**: Automates the installation and setup of Docker and Docker Compose.
- **Key Features**:
  - 🔧 Installs Docker CE.
  - 👤 Configures Docker for non-root users.
  - 🛠️ Installs Docker Compose for container orchestration.

---

### 3. `ping.yml` 📡
- **Purpose**: Verifies Ansible connectivity to target hosts.
- **Key Features**:
  - ✅ Pings target machines to ensure connection.
  - 🖧 Confirms Ansible setup is working.

---

### 4. `system_info.yml` 📊
- **Purpose**: Gathers detailed system information from target hosts.
- **Key Features**:
  - 📋 Collects OS details, uptime, and hardware specs.
  - 🖥️ Useful for inventory management and monitoring.

---

### 5. `system_update.yml` 🔄
- **Purpose**: Updates the system to ensure it’s running the latest software.
- **Key Features**:
  - 🆕 Updates package repositories.
  - 📦 Upgrades installed packages.

---

### 6. `update_and_install.yml` ⚙️
- **Purpose**: Combines system updates with software installation.
- **Key Features**:
  - 🔄 Updates the system.
  - 🛠️ Installs predefined software packages in one go.

---

## 🛠️ Requirements

- Ansible version 2.9+ installed on your control node.
- SSH access to the target hosts.
- Sudo privileges on the target machines (if required by the playbooks).

---

## 🚀 Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/PKHarsimran/MyAnsibleScripts.git
