# 🚀 GitGen

**GitGen** is a lightweight Bash utility that simplifies setting up SSH keys for GitHub. With just one command, it generates a secure SSH key, adds it to the SSH agent, copies the public key to your clipboard (if `xclip` is installed), and provides you with the GitHub SSH settings page link for quick setup.

---

## ✨ Features
- 🔐 **Secure SSH Key Generation**: Automatically generates a key using your GitHub email.
- 🚀 **Streamlined Setup**: Adds the key to your SSH agent for immediate use.
- 📋 **Clipboard Copy**: Copies your public key to the clipboard if `xclip` is installed.
- 🌐 **Quick Navigation**: Provides a direct link to the GitHub SSH settings page for easy addition.

---

## ⚡ Quick Start

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/gitgen.git
cd gitgen
```

### 2️⃣ Run the Script
```bash
./gitgen
```

---

## 🛠 Requirements
Ensure you have the following installed on your system:
- **`xclip`**: For copying the public key to your clipboard.  
  Install with:
  ```bash
  sudo apt install xclip
  ```
- **Google Chrome (optional)**: For easy navigation to the GitHub SSH setup page, but you can use any browser.

---

## 📖 Usage
1. Run the script:
   ```bash
   ./gitgen
   ```
2. Enter your GitHub email when prompted.
3. The script will generate an SSH key, add it to the SSH agent, and either copy the key to your clipboard (if `xclip` is installed) or print it for manual copying.
4. Visit the GitHub SSH setup page using the provided link and paste the public key.

---

## 🛡 Notes
- Keep your **private key (`~/.ssh/id_ed25519`)** secure. Never share it.
- The script only interacts with your **public key**, ensuring privacy and security.

---

Enjoy hassle-free SSH setup with **GitGen**! 😊
