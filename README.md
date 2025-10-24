# AutoSaver Tool

**Description:**
AutoSaver is a lightweight and smart auto-save tool designed for **Windows PC**. It automatically saves your active work in applications that **don’t have a built-in auto-save feature**, such as Notepad, WordPad, Paint, and similar programs. The tool simulates the `Ctrl + S` shortcut periodically to ensure your work is never lost. It includes built-in license validation and user key registration. This version is fully self-contained and runs as an **.exe file**, meaning **no external Python modules or dependencies are required**.

---

## ⚙️ Features

* 🧠 Automatically saves work in applications without default auto-save.
* ⏰ Periodic save interval (default: every 60 seconds).
* 🌐 Internet check to ensure connectivity.
* 🔐 License verification via secure server.
* 🤖 Telegram bot integration to send user key automatically to developer.
* 💻 Works only on **Windows PC** (not Android).
* 🚫 No additional installation or dependencies required.

---

## 🚀 How It Works

1. The tool verifies your license using your system username and MAC address.
2. If the license is valid, it sends your unique key to the developer Mr Tan
3. It checks your internet connection.
4. Every 60 seconds, it triggers `Ctrl + S` and `Enter` to auto-save your active document or project.

---

## 🖥️ Usage

1. Download and run the `AutoSave.exe` file.
2. When prompted, enter your name.
3. The tool will automatically verify your license and send the key to the admin bot.
4. Once verified, AutoSaver will continuously monitor your system and auto-save your work.

> ⚠️ Do not modify the `.exe` or any internal system files; doing so may break license verification.

---

## 🧩 Configuration

The save interval is set to **60 seconds by default**. If you need a different version with a customized interval, contact the developer.

---

## 🧾 Example Console Output

```
# AutoSaver running... Every 60 seconds.
Next save in 01 seconds...
1. Autosave successful!
Next save in 59 seconds...
2. Autosave successful!
```

---

## 🧱 Notes

* Works **only on Windows PC**.
* **No Python installation required.**
* Requires an active internet connection for the first license validation.
* Once authorized, AutoSaver will operate silently and efficiently in the background.

---

## 🔐 Security Notice

Each device key is generated based on your system username and MAC address. This ensures that every machine has a unique identity and prevents unauthorized use.

---

## 🧑‍💻 Credits

**Created by:** Mr Tan
**License Verification Source:** [GitHub Repository](https://github.com/mrtan-official/server)

---

## 📘 Repository Description (for GitHub)

> A standalone Windows AutoSaver tool (.exe) that automatically saves progress in non-auto-saving applications. Includes license verification, Telegram key registration, and internet connectivity monitoring. Ideal for apps like Notepad or Paint where manual saving is required.

---

## 🪪 License

This project is distributed for educational and personal use only. Redistribution or modification without permission is strictly prohibited.
