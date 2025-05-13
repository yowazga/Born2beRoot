# Born2beroot

## 🧾 Project Description

** Born2beroot ** is a 42-project designed to introduce students to system administration and virtualization. The goal is to configure a secure and functional virtual machine using Debian (or Rocky Linux), set up encrypted partitions, implement strict user and password policies, and automate system monitoring.

---

## 📌 Project Objectives

- Install and configure a virtual machine without a graphical interface.
- Use LVM with at least 2 encrypted partitions.
- Secure SSH access on port **4242**.
- Set up a **non-root user** with sudo access and custom logging.
- Configure **UFW** (or **firewalld** for Rocky).
- Apply a strong **password policy**.
- Implement and schedule a **monitoring script** that displays system metrics every 10 minutes.
- [Optional] Configure a **WordPress server** and additional services for bonus.

---

## 🧠 Skills Gained

- Linux Server Setup (Debian/Rocky)
- Disk partitioning with LVM + Encryption
- User and group management
- SSH, firewall, and sudo configuration
- Shell scripting and cron scheduling
- SELinux/AppArmor basics
- Secure password and authentication policies

---

## 🔧 Technologies Used

- Debian 11 (or Rocky Linux)
- VirtualBox / UTM
- Bash
- UFW / firewalld
- OpenSSH
- Sudo
- LVM
- Cron

---

## 📜 How to Use

1. Clone this repository
2. Open your virtual machine
3. Configure the server as described in `project.pdf`
4. Run and test the `monitoring.sh` script:
   ```bash
   sudo bash /path/to/monitoring.sh
5. Edit your crontab to schedule the script:
  ```sudo crontab -e```
#Add the line:
 ```*/10 * * * * bash /path/to/monitoring.sh```
---

## 🧩 Directory Structure

```born2beroot/
│
├── monitoring.sh         # Monitoring script
├── setup_notes.md        # Personal installation notes
├── signature.txt         # VM disk SHA1 signature
├── screenshots/          # Evaluation screenshots (optional)
└── README.md             # This file
```
---

## 📚 Useful Resources
[Linux Journey]

Debian Wiki

Bash scripting guide

Crontab Guru

UFW

Firewalld

LVM Encryption



# Born2beroot

## 🧾 Project Description

** Born2beroot ** is a 42-project designed to introduce students to system administration and virtualization. The goal is to configure a secure and functional virtual machine using Debian (or Rocky Linux), set up encrypted partitions, implement strict user and password policies, and automate system monitoring.

---

## 📌 Project Objectives

- Install and configure a virtual machine without a graphical interface.
- Use LVM with at least 2 encrypted partitions.
- Secure SSH access on port **4242**.
- Set up a **non-root user** with sudo access and custom logging.
- Configure **UFW** (or **firewalld** for Rocky).
- Apply a strong **password policy**.
- Implement and schedule a **monitoring script** that displays system metrics every 10 minutes.
- [Optional] Configure a **WordPress server** and additional services for bonus.

---

## 🧠 Skills Gained

- Linux Server Setup (Debian/Rocky)
- Disk partitioning with LVM + Encryption
- User and group management
- SSH, firewall, and sudo configuration
- Shell scripting and cron scheduling
- SELinux/AppArmor basics
- Secure password and authentication policies

---

## 🔧 Technologies Used

- Debian 11 (or Rocky Linux)
- VirtualBox / UTM
- Bash
- UFW / firewalld
- OpenSSH
- Sudo
- LVM
- Cron

---

## 📜 How to Use

1. Clone this repository
2. Open your virtual machine
3. Configure the server as described in `project.pdf`
4. Run and test the `monitoring.sh` script:
   ```bash
   sudo bash /path/to/monitoring.sh
5. Edit your crontab to schedule the script:
  ```sudo crontab -e```
#Add the line:
 ```*/10 * * * * bash /path/to/monitoring.sh```
---

## 🧩 Directory Structure

```born2beroot/
│
├── monitoring.sh         # Monitoring script
├── setup_notes.md        # Personal installation notes
├── signature.txt         # VM disk SHA1 signature
├── screenshots/          # Evaluation screenshots (optional)
└── README.md             # This file
```
---

## 📚 Useful Resources
[Linux Journey]

Debian Wiki

Bash scripting guide

Crontab Guru

UFW

Firewalld

LVM Encryption


## Acknowledgements

 - [Linux Journey](https://linuxjourney.com/)
 - [Debian Wiki](https://wiki.debian.org/)
 - [Bash scripting guide](https://ryanstutorials.net/bash-scripting-tutorial/)
 - [Crontab Guru](https://crontab.guru/)
 - [UFW](https://help.ubuntu.com/community/UFW)
 - [Firewalld](https://firewalld.org/documentation/)
 - [LVM Encryption](https://www.digitalocean.com/community/tutorials/how-to-use-luks-to-encrypt-drives-on-ubuntu)

