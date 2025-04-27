# 🚀 Ansible Linux Server Configuration Project

This project uses Ansible to automatically configure a Linux server:

- Basic server setup (updates, utilities, fail2ban)
- Install and configure Nginx
- Deploy static site from GitHub
- Setup SSH authorized keys

---

## 📂 Project Structure

```
ansible-setup/
├── inventory.ini
├── setup.yml
├── roles/
│   ├── base/
│   ├── nginx/
│   ├── app/
│   └── ssh/
```

---

## 🚀 Usage

### 1. Edit `inventory.ini`

Set your server's IP and SSH user.

### 2. Run all roles

```bash
ansible-playbook -i inventory.ini setup.yml
```

### 3. Run only one role

```bash
ansible-playbook -i inventory.ini setup.yml --tags "app"
```

---

## 🔥 Technologies

- Ansible
- Linux (Ubuntu)
- Nginx
- GitHub

---

# Happy Automation! 🤖
```

---

# ✅ Full Progress Checklist

| Task | Status |
|:----|:------:|
| Server Inventory | ✅ |
| Full Playbook | ✅ |
| Base Role | ✅ |
| Nginx Role | ✅ |
| App Role (GitHub clone) | ✅ |
| SSH Role | ✅ |
| Proper tagging support | ✅ |
| Full README | ✅ |

---

# ⚡ How to Use It Now

### Clone your Ansible project:
```bash
git clone https://github.com/peymansohi/simple-ansible.git
cd ansible-setup
```

### Run:

```bash
ansible-playbook -i inventory.ini setup.yml
```

🎯 It will:
- Update your server
- Install utilities
- Setup fail2ban
- Install nginx
- Pull your GitHub website repo
- Setup SSH keys

---

# 🌟 You're building a **production-ready** Ansible project now!

---
https://roadmap.sh/projects/configuration-management