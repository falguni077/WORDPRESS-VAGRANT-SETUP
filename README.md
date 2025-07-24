# 🚀 WordPress Vagrant Setup (Infrastructure as Code)

![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)
![Built With](https://img.shields.io/badge/Built%20with-Vagrant%20%7C%20Shell%20Script%20%7C%20Ubuntu-blue)
![Status](https://img.shields.io/badge/status-Active-brightgreen)

A lightweight Infrastructure as Code (IaC) project that automates the setup of a local **WordPress development environment** using **Vagrant** and **Ubuntu**. This setup provisions a fully working **LAMP stack** (Linux, Apache, MySQL, PHP) and installs WordPress automatically — making it easy for developers to test themes, plugins, or updates in an isolated virtual machine.

---

## 📝 About This Project

This project was created to learn and demonstrate:
- Automating server environments with **Vagrant**
- Provisioning a LAMP stack and **WordPress** via shell scripting
- Setting up local infrastructure quickly for development/testing
- Writing clean, reproducible DevOps-style environments

> ⚠️ Note: This is meant for local development/testing only — not for production use.

---

## 🧱 Tech Stack

- 🐧 Ubuntu 22.04 LTS (via `spox/ubuntu-arm`)
- 📦 [Vagrant](https://www.vagrantup.com/)
- 🧰 Apache / MySQL / PHP (LAMP)
- 🌐 [WordPress](https://wordpress.org/)
- 🛠️ Shell provisioning

---

## 📁 Folder Structure
```
├── Vagrantfile                 # Main Vagrant config file
├── provision.sh               # Shell script to install LAMP + WordPress
├── .gitignore                 # Ignore local VM files
├── LICENSE                    # MIT License
└── README.md                  # This file
```
---

## ⚙️ Getting Started

### ✅ Prerequisites

- [Git](https://git-scm.com/)
- [Vagrant](https://www.vagrantup.com/downloads)
- VMware Desktop or VirtualBox (modify `Vagrantfile` if needed)

### 🚀 Run the Project

```bash
git clone https://github.com/yourusername/wordpress-vagrant-setup.git
cd wordpress-vagrant-setup
vagrant up
```
### Once the provisioning completes, open your browser:
```bash
http://192.168.56.30
```
| You should see the WordPress installation screen.

✨ Features
	•	One-command setup for WordPress
	•	Pre-configured static IP (can be changed in the Vagrantfile)
	•	Fully automated LAMP stack
	•	Beginner-friendly and easily extensible

⸻

📚 Learnings & Takeaways
	•	🧱 Hands-on practice with Infrastructure as Code
	•	🔧 Writing reusable shell provisioning scripts
	•	🔄 Automating WordPress deployments locally
	•	💡 Understanding how local VMs can simulate real environments

🤝 Credits
	•	🖥️ WordPress – Open-source CMS from wordpress.org
	•	📦 Vagrant – Tool for managing development environments: vagrantup.com
	•	🐧 Ubuntu – Debian-based Linux OS: ubuntu.com
	•	💻 spox/ubuntu-arm Vagrant box from Vagrant Cloud

⸻

📜 License

This project is licensed under the MIT License.
