# Vagrant Apache Web Deployment

This project demonstrates the implementation of **Infrastructure as Code (IaC)** using **Vagrant** to automatically provision a **CentOS Stream 9** virtual machine. During provisioning, **Apache HTTP Server (httpd)** is installed, configured, and used to deploy a responsive website automatically.

---

## 🚀 Features

- Automated virtual machine provisioning using Vagrant
- Automatic Apache HTTP Server (httpd) installation
- Automated website deployment
- Private network configuration
- Shell-based provisioning
- One-command deployment with `vagrant up`

---

## 🛠 Technologies Used

- Vagrant
- VirtualBox
- CentOS Stream 9
- Apache HTTP Server (httpd)
- Bash

---

## 📂 Project Structure

```text
vagrant-apache-web-deployment/
├── Vagrantfile
├── README.md
├── LICENSE
└── screenshots/
    ├── website.png
    ├── apache-status.png
    └── vagrant-up.png
```

---

## ▶️ Getting Started

### Prerequisites

Before running this project, make sure you have installed:

- Vagrant
- VirtualBox

### Clone the Repository

```bash
git clone https://github.com/yudhaafrizarevi/vagrant-apache-web-deployment.git
cd vagrant-apache-web-deployment
```

### Start the Virtual Machine

```bash
vagrant up
```

### Access the Website

Open your browser and visit:

```
http://192.168.56.23
```

---

## 📸 Screenshots

### Website

![Website](screenshots/website.png)

### Apache HTTP Server Status

![Apache Status](screenshots/apache-status.png)

### Vagrant Provisioning

![Vagrant Provisioning](screenshots/vagrant-up.png)

---


## 📄 License

This project is licensed under the MIT License.
