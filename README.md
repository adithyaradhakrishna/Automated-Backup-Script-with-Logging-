# 🗃️ Automated Backup Script with Logging — Python CLI Tool

A lightweight Python script that **automates file and folder backups** by compressing them into **timestamped ZIP archives**. It also maintains a detailed **log file (`backup.log`)** recording every backup action — perfect for personal, academic, or server-side backup automation.

---

## 📝 Description

This script is designed to:

- Automatically back up important directories
- Compress files/folders into `.zip` format
- Append timestamps to backup filenames for clarity
- Maintain a log of every backup performed

It’s fully built with **Python’s standard library**, so it requires **no external dependencies**.

---

## ✨ Features

- 🗂️ Backup entire folders or single files
- 🕒 Automatically adds timestamps to backup filenames
- 📝 Creates/updates `backup.log` with:
  - Backup filename
  - Source path
  - Backup time
- 🔧 Easy to configure source/destination paths
- 💾 Reliable and **runs offline**

---

## 💻 Technologies Used

- **Python 3.x**
- Standard Library Only:
  - `os`
  - `shutil`
  - `zipfile`
  - `datetime`
  - `logging`

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/automated-backup-script.git
cd automated-backup-script
