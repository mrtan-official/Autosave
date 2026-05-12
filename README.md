# AutoSaver Tool

## 📌 Description

**AutoSaver** is a smart and lightweight automation tool designed specifically for **Windows PC** users. It automatically saves your active work in applications that do not support built-in auto-save, such as Notepad, WordPad, Paint, and similar desktop software.

The tool works by simulating the `Ctrl + S` keyboard shortcut at a fixed interval, helping prevent accidental data loss during work sessions.

This version includes:

- 🔐 Secure license verification
- 🤖 Telegram key registration system
- 🌐 Internet connectivity monitoring
- 💻 Fully standalone `.exe` support
- ⚡ No Python installation or external dependencies required

---

# ⚙️ Features

- 🧠 Automatically saves active work periodically
- ⏰ Custom save interval support
- 🌐 Internet connectivity checking
- 🔐 Secure device-based license validation
- 🤖 Telegram bot integration for automatic key submission
- 💻 Designed only for Windows PC
- 📦 Portable `.exe` version — no setup required
- 🎨 Modern Rich Console UI Dashboard
- 📊 Live monitoring and save statistics

---

# 🚀 How It Works

1. The tool generates a unique device key using:
   - System username
   - MAC address

2. The license system validates the device.

3. Once verified:
   - The user key is automatically sent to the developer via Telegram bot.
   - AutoSaver starts monitoring your system.

4. Based on the selected interval:
   - The tool automatically triggers `Ctrl + S`
   - Saves your active document or project continuously

---

# 🖥️ Supported Applications

AutoSaver works best with applications that support the standard `Ctrl + S` save shortcut, including:

- Notepad
- WordPad
- Paint
- VS Code
- Sublime Text
- Photoshop
- Many other Windows desktop applications

---

# 📦 Usage

## Step 1 — Run the Application

Open the compiled executable:

```bash
AutoSave.exe
```

---

## Step 2 — Register Operator Name

When prompted, enter your name:

```bash
REGISTER OPERATOR NAME >>
```

---

## Step 3 — Set Save Interval

Choose how often AutoSaver should save your work:

```bash
SET SAVE INTERVAL (SECONDS) >>
```

Minimum allowed interval:

```bash
3 seconds
```

---

## Step 4 — Start Monitoring

Once started, AutoSaver will:

- Monitor internet connectivity
- Run in live dashboard mode
- Automatically save your work continuously

---

# 🧠 Dashboard Information

The live dashboard displays:

| Section | Description |
|---|---|
| OPERATOR | Registered user name |
| PLATFORM | Current Windows version |
| NETWORK | Internet connection status |
| SAVES | Total successful save cycles |
| ENGINE | Current AutoSaver status |
| CLOCK | Real-time system clock |

---

# 🔐 License System

Each machine receives a unique key generated using:

- Windows username
- MAC address

Example:

```bash
username-00:1A:2B:3C:4D:5E
```

This helps prevent unauthorized usage and ensures secure activation.

---

# 🤖 Telegram Integration

After successful verification, AutoSaver automatically sends:

- User name
- Generated key
- Operating system
- Registration time

to the developer Telegram bot.

---

# 🌐 Internet Requirement

AutoSaver requires internet access for:

- License validation
- Telegram registration
- Connectivity monitoring

After validation, the tool continues running normally.

---

# 📊 Example Console Output

```bash
 █████╗ ██╗   ██╗████████╗ ██████╗ ███████╗ █████╗ ██╗   ██╗███████╗██████╗ 
██╔══██╗██║   ██║╚══██╔══╝██╔═══██╗██╔════╝██╔══██╗██║   ██║██╔════╝██╔══██╗
███████║██║   ██║   ██║   ██║   ██║███████╗███████║██║   ██║█████╗  ██████╔╝
██╔══██║██║   ██║   ██║   ██║   ██║╚════██║██╔══██║╚██╗ ██╔╝██╔══╝  ██╔══██╗
██║  ██║╚██████╔╝   ██║   ╚██████╔╝███████║██║  ██║ ╚████╔╝ ███████╗██║  ██║
╚═╝  ╚═╝ ╚═════╝    ╚═╝    ╚═════╝ ╚══════╝╚═╝  ╚═╝  ╚═══╝  ╚══════╝╚═╝  ╚═╝

[+] OPERATOR : Mr Tan
[+] PLATFORM : Windows 11
[+] NETWORK  : CONNECTED
[+] SAVES    : 15 cycles
[+] ENGINE   : MONITORING

Next Save: ████████████░░░░░░ 12s
```

---

# ⚠️ Important Notes

- Works only on Windows PC
- Android is NOT supported
- Do not modify internal files
- Requires keyboard shortcut support (`Ctrl + S`)
- Recommended to keep internet enabled

---

# 🛡️ Security Notice

This software uses a unique hardware-based identification system for secure verification and anti-abuse protection.

Unauthorized modification, redistribution, or tampering may result in license failure.

---

# 🧑‍💻 Credits

**Developer:** Mr Tan  
**Version:** 5.0 Ultra  
**Technology:** Python + Rich Console + Telegram Bot API

---

# 🔗 License Verification Source

GitHub Repository:
https://github.com/mrtan-official/server

---

# 📘 GitHub Repository Description

> A powerful standalone Windows AutoSaver tool that automatically saves progress in applications without built-in auto-save support. Features include live monitoring dashboard, Telegram key registration, internet status checking, and secure license verification.

---

# 🪪 License

This project is distributed for:

- Educational purposes
- Personal use only

Unauthorized redistribution, resale, or modification is prohibited without developer permission.
