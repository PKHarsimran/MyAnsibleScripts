# 🚀 MyAnsibleScripts

Welcome to **MyAnsibleScripts**, a collection of Ansible playbooks designed to automate and simplify various system tasks. Whether you're troubleshooting, installing Docker, or gathering system information, these playbooks have you covered! 🛠️

---

## 📜 Playbooks Overview

Here’s a quick summary of the playbooks in this repository:

### 1. `apt_troubleshoot.yml` 🐧

**Purpose**: Resolves `apt` lock issues by identifying and clearing lock files, reconfiguring `dpkg`, and ensuring smooth package updates.

**Key Features:**
- Identifies and kills processes holding `apt` locks.
- Removes lock files.
- Reconfigures `dpkg` for interrupted installations.

---

### 2. `install_docker.yml` 🐳

**Purpose**: Automates the installation of Docker and Docker Compose for containerized application deployment.

**Key Features:**
- Installs prerequisites.
- Configures Docker GPG key and repository.
- Installs Docker CE, CLI, and Docker Compose plugin.
- Enables and starts Docker on boot.

---

### 3. `ping.yml` 📡

**Purpose**: Tests Ansible's connectivity to target hosts by sending a simple ping.

**Key Features:**
- Verifies Ansible connectivity and setup.

---

### 4. `system_info.yml` 📊

**Purpose**: Collects and displays detailed system information including hardware, network, and OS details.

**Key Features:**
- Displays hostname, IP, OS, and kernel version.
- Shows uptime, CPU details, memory usage, and disk space.
- Lists active network interfaces and listening ports.

---

### 5. `system_update.yml` 🔄

**Purpose**: Updates and upgrades all system packages to their latest versions.

**Key Features:**
- Updates the package list.
- Performs a distribution upgrade.

---

### 6. `update_and_install.yml` 🛠️

**Purpose**: Updates system packages and installs essential tools.

**Key Features:**
- Updates and upgrades all packages.
- Installs packages like `git`, `curl`, and `vim`.

---
