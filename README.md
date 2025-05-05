# 🌐 Apache Web Server: Reverse Proxy & Load Balancer Setup

This guide explains how to install and configure the **Apache HTTP Server** on various Linux distributions and use it as a **Reverse Proxy** or **Load Balancer**.

---

## 📦 Installation

### 🔸 Amazon Linux

```bash
sudo yum install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd
```
`For stop, reload and restart`

```bash
sudo systemctl stop httpd
sudo systemctl reload httpd
sudo systemctl restart httpd
```

### 🟢 Ubuntu/Debian

```bash
sudo apt update
sudo apt install apache2 -y
sudo systemctl start apache2
sudo systemctl enable apache2
```
`For stop, reload and restart`

```bash
sudo systemctl stop apache2
sudo systemctl reload apache2
sudo systemctl restart apache2
```

