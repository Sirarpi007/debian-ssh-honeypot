# debian-ssh-honeypot
This project is a simulated Debian-based SSH honeypot that mimics interactive behavior of a real Linux system. It's designed to log attacker behavior or provide safe environments for research and training.

## 🔧 Features

- Emulates SSH service and commands like `ls`, `ip a`, `ss`, `docker ps`, `id`, etc.
- Regex-based command matching and handler response system.
- Simulates a Debian 12 (Bookworm) environment running in VirtualBox.
- Includes fake network interfaces, logs, and Docker errors.
- Realistic output for `journalctl`, `lsblk`, `ss -tuln`, etc.

## 🧪 Example Usage

```bash
ssh root@honeypot
