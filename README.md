# 🌐 Apache Web Server: Reverse Proxy & Load Balancer Setup

This guide explains how to install and configure the **Apache HTTP Server** on various Linux distributions and use it as a **Reverse Proxy** or **Load Balancer**.

---

## 📦 Installation

### 🔸 Amazon Linux

```bash
sudo yum install httpd -y
sudo systemctl start httpd
sudo systemctl enable httpd
