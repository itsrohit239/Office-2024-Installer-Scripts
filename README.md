# 📦 Office 2024 Installer Scripts

Automated batch scripts to silently install **Microsoft Office 2024 ProPlus Volume Edition** for both **64-bit** and **32-bit** systems using the official Office Deployment Tool.

---

## 🧑‍💻 Developed By

**Rohit Vadher**  
GitHub: [@itsrohit239](https://github.com/itsrohit239)

---

## 📁 Files Included

| File Name                          | Description                                      |
|-----------------------------------|--------------------------------------------------|
| `Office_2024_Installer_64bit.bat` | Installs Office 2024 64-bit silently             |
| `Office_2024_Installer_32bit.bat` | Installs Office 2024 32-bit silently             |
| `README.md`                       | Documentation and usage instructions             |

---

## ⚙️ Features

- ✅ Silent installation using Office Deployment Tool  
- ✅ Supports both 64-bit and 32-bit editions  
- ✅ Auto-downloads and extracts setup files  
- ✅ Creates configuration XML automatically  
- ✅ Logs installation progress to a file  
- ✅ Cleans up temporary files after install
- ✅ Completely malware and virus free — safe to run on Windows 10 and 11  

---

## 🖥️ Supported Operating Systems

These scripts are compatible with:

- **Windows 10** (Home, Pro, Enterprise)
- **Windows 11** (Home, Pro, Enterprise)

> 💡 Make sure your system is up to date and has administrator privileges.

---

## 🚀 How to Use

### Step-by-Step Instructions

1. **Download or clone** this repository:
   ```bash
   [git clone https://github.com/itsrohit239/office-2024-installer.git](https://github.com/itsrohit239/Office-2024-Installer-Scripts.git)
   ```

2. **Choose the correct installer**:
   - Use `Office_2024_Installer_64bit.bat` for 64-bit systems.
   - Use `Office_2024_Installer_32bit.bat` for 32-bit systems.

3. **Run the script as Administrator**:
   - Right-click the `.bat` file.
   - Select **"Run as administrator"**.

4. The script will:
   - Download the Office Deployment Tool from Microsoft.
   - Extract setup files to a temporary folder.
   - Create a configuration XML file for Office installation.
   - Run the setup silently.
   - Log progress to:  
     ```
     %TEMP%\OfficeInstall\InstallLog.txt
     ```

5. After installation, temporary files are automatically deleted.

---

## 📌 Requirements

- Windows 10 or 11 with administrator privileges  
- Internet connection to download setup files  

---
## 🔑 Activation Help

If you do not have an activation key, you can find a script for activation on my GitHub profile:  
👉 [https://github.com/itsrohit239](https://github.com/itsrohit239)

---


## 🛠 Troubleshooting

- If the script fails to download or extract:
  - Check your internet connection.
  - Ensure antivirus/firewall isn’t blocking the download.
  - Run the script with elevated privileges.

- If installation fails:
  - Review the log file at `%TEMP%\OfficeInstall\InstallLog.txt`.
  - Make sure your system meets Office 2024 requirements.

---

## 📄 License

This project is released under the MIT License
Feel free to modify and distribute with attribution.

---


## 🙌 Support

If you find this useful, give it a ⭐ on GitHub!  
For issues or suggestions, feel free to open an issue. 

---
