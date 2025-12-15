# Edge Profile Manager (C# Edition)

> **No backup, no sympathy.**

A lightweight, portable Windows tool for managing Microsoft Edge profiles. Originally developed as a PowerShell script, this tool has been fully ported to C# (Windows Forms) to run as a standalone `.exe` without any external dependencies.

![License](https://img.shields.io/badge/license-MIT-green)
![Platform](https://img.shields.io/badge/platform-Windows-blue)
![Language](https://img.shields.io/badge/language-C%23-purple)

## 🚀 Features

* **Create Profile:** Creates new Edge profiles based on the standard ('Default') profile.
* **Backup:** Backs up complete profiles, including a JSON manifest, into compact `.zip` files.
* **Restore:** Restores profiles from backups (with automatic name detection).
* **Delete:** Safely removes profiles (includes a safeguard for the 'Default' profile).
* **Portable:** Runs as a single `.exe` file (images and icons are embedded).
* **Multi-language:** Switchable between **German** 🇩🇪 and **English** 🇬🇧.
* **Safety:** Detects running Edge processes and prompts you to close them to prevent data loss.

## 🛠️ Prerequisites

* Windows Operating System (Windows 10/11 recommended).
* .NET Framework 4.5 or higher (pre-installed on almost all modern Windows PCs).
* **Administrator privileges** (recommended, as Edge stores data in protected system directories).

## 📥 Installation & Usage

Since this is a portable application, no installation is required:

1.  Download `EdgeProfilManager.exe` (see [Releases](#)).
2.  Run the file (Right-click -> *Run as administrator* is recommended).
3.  Select your language in the top right corner.
