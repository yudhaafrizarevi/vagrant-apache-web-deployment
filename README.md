# 🚀 Vagrant Apache Web Deployment

![Vagrant](https://img.shields.io/badge/Vagrant-2.x-1868F2?style=for-the-badge&logo=vagrant&logoColor=white)
![VirtualBox](https://img.shields.io/badge/VirtualBox-7.x-183A61?style=for-the-badge&logo=virtualbox&logoColor=white)
![CentOS](https://img.shields.io/badge/CentOS_Stream_9-262577?style=for-the-badge&logo=centos&logoColor=white)
![Apache](https://img.shields.io/badge/Apache_HTTP_Server-2.4-D22128?style=for-the-badge&logo=apache&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-Shell-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

---

## 📌 Project Overview

This project demonstrates the implementation of **Infrastructure as Code (IaC)** using **Vagrant** to automatically provision a **CentOS Stream 9** virtual machine.

During provisioning, Apache HTTP Server (**httpd**) is installed and configured automatically. A responsive website is then deployed, allowing the complete web server environment to be recreated consistently using a single command.

```bash
vagrant up
```

This project highlights infrastructure automation, repeatable deployments, and environment consistency using Vagrant and shell provisioning.

---

# 🎯 Objectives

- Demonstrate Infrastructure as Code (IaC)
- Automate Apache Web Server deployment
- Create a repeatable development environment
- Eliminate manual server configuration
- Showcase basic DevOps provisioning workflow

---

# ✨ Features

- Automated VM provisioning
- Automated Apache HTTP Server installation
- Automatic website deployment
- Private network configuration
- Shell-based provisioning
- One-command deployment (`vagrant up`)
- Consistent and reproducible environment

---

# 🏗 Architecture

```text
                  Host Machine
                       │
          Vagrant + VirtualBox
                       │
                       ▼
            CentOS Stream 9 VM
                       │
                 Apache HTTPD
                       │
              Responsive Website
```

---

# ⚙️ Technology Stack

| Technology | Purpose |
|------------|---------|
| Vagrant | Virtual machine provisioning |
| VirtualBox | Virtualization platform |
| CentOS Stream 9 | Operating System |
| Apache HTTP Server | Web Server |
| Bash | Provisioning Script |

---

# 📂 Repository Structure

```text
vagrant-apache-web-deployment/
│
├── Vagrantfile
├── README.md
├── LICENSE
└── screenshots/
    ├── website.png
    ├── apache-status.png
    └── vagrant-up.png
```

---

# 🚀 Getting Started

## Prerequisites

Install the following software before running this project:

- Vagrant
- VirtualBox

---

## Clone Repository

```bash
git clone https://github.com/yudhaafrizarevi/vagrant-apache-web-deployment.git

cd vagrant-apache-web-deployment
```

---

## Provision Infrastructure

```bash
vagrant up
```

Vagrant will automatically:

- Create a CentOS Stream 9 virtual machine
- Configure networking
- Install Apache HTTP Server
- Deploy the website
- Start the Apache service

---

## Verify Deployment

Check the VM status:

```bash
vagrant status
```

Access the VM:

```bash
vagrant ssh
```

Verify Apache:

```bash
sudo systemctl status httpd
```

---

## Access the Website

Open your browser and visit:

```
http://192.168.56.23
```

---

# 🔄 Provisioning Workflow

```text
vagrant up
      │
      ▼
Create Virtual Machine
      │
      ▼
Configure Network
      │
      ▼
Install Apache HTTP Server
      │
      ▼
Deploy Website Files
      │
      ▼
Enable Apache Service
      │
      ▼
Website Ready
```

---

# 📸 Screenshots

## Vagrant Provisioning

![Provisioning](screenshots/vagrant-up.png)

---

## Apache HTTP Server Status

![Apache Status](screenshots/apache-status.png)

---

## Website

![Website](screenshots/website.png)

---

# 📖 Infrastructure as Code

This project follows the **Infrastructure as Code (IaC)** approach by defining infrastructure provisioning in code instead of manually configuring servers.

Using Vagrant provisioning provides several benefits:

- Repeatable deployments
- Consistent environments
- Faster setup
- Easier maintenance
- Reduced manual configuration errors

---

# 💡 Future Improvements

- Replace Shell Provisioning with Ansible
- Add Nginx Reverse Proxy
- Deploy using Docker
- Configure HTTPS with Let's Encrypt
- Add GitHub Actions for CI
- Deploy on AWS EC2 using Terraform

---

# 👨‍💻 Author

**Yudha Afriza Revi**

Final-year Computer Engineering Student at Telkom University

Interested in:

- DevOps Engineering
- Cloud Computing
- Linux System Administration
- Infrastructure Engineering

GitHub:

https://github.com/yudhaafrizarevi

---

# 📄 License

This project is licensed under the **MIT License**.

---

⭐ If you found this project useful, consider giving it a **Star**.
