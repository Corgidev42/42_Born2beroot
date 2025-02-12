# 🖥️ 42_Born2BeRoot

## Introduction
42_Born2BeRoot is a project designed to introduce students to the basics of system administration. The goal is to configure a virtual machine (VM) with specific security and configuration requirements.

## 🏗️ Objectives
- Install and configure a Linux-based operating system on a VM.
- Implement essential security measures.
- Understand and apply fundamental system administration concepts.

## ⚙️ macOS-Specific Configuration
Since I am working on **macOS**, I had to use **UTM** to virtualize Debian, as Parallels Desktop has certain restrictions on ARM architecture.
This project was completed using **Debian**, emulated via UTM on my MacBook Pro (M1 Pro).

## 📝 Project Steps
1. **Operating System Installation**: Setting up a Debian VM using UTM.
2. **User and Group Management**: Creating and configuring accounts with appropriate permissions.
3. **SSH Security**: Strengthening remote access configurations.
4. **Firewall Setup**: Installing and configuring `ufw` to filter connections.
5. **Password Policies**: Enforcing strict password rules with `pam_pwquality`.
6. **Service Management**: Securing and managing active services.
7. **Monitoring and Logging**: Setting up system monitoring and logging.

## ✅ Evaluation
The project will be evaluated based on:
- Proper installation and configuration of the system.
- Effective implementation of security measures.
- Accurate management of users, groups, and services.
- Efficient system monitoring and logging.

## 🔗 Useful Resources
- [Linux Documentation](https://www.kernel.org/doc/html/latest/)
- [Debian Administration Handbook](https://debian-handbook.info/)
- [Ubuntu Server Guide](https://ubuntu.com/server/docs)
- [UTM Documentation](https://mac.getutm.app/)

## 🎯 Conclusion
42_Born2BeRoot allowed me to gain hands-on experience in Linux system administration while also considering the specificities of macOS and virtualization via UTM. This project serves as a solid foundation for managing and securing a Linux-based server environment.
