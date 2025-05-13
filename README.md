# 📦 Vagrant Deployments

This repository contains Vagrant configurations to automate the provisioning of virtual machines for local development, testing, or lab environments.

---

## 📂 What's Inside

| File/Folder         | Description                                  |
|---------------------|----------------------------------------------|
| `Vagrantfile`       | Main configuration for VM setup              |
| `provision.sh`      | Shell script to provision software/settings  |
| `scripts/`          | Additional provisioning or utility scripts   |
| `configs/`          | Sample config files (e.g., NGINX, MySQL)     |

---

## 🧰 Requirements

- [Vagrant](https://www.vagrantup.com/) 2.2+
- [VirtualBox](https://www.virtualbox.org/) or another supported provider
- Optional: Git, Ansible, Docker, etc., depending on your provisioning

---

## 🚀 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/vagrant-deploy.git
   cd vagrant-deploy
