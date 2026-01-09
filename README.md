# 🎮 JZminSetup - Minecraft Server Auto-Setup Tool
setup your server in less than a minute
<div align="center">

![Minecraft](https://img.shields.io/badge/Minecraft-Java%20%7C%20Bedrock-brightgreen)
![Python](https://img.shields.io/badge/Python-3.6+-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-success)

**Automatic Minecraft Server Setup Tool - Easy and Fast**

</div>

---

# Installation and Running JZminSetup
```bash
# Download
wget https://raw.githubusercontent.com/WeJZTeam/Minecraft-Server-Auto-Setup/main/JZminSetup

# Give permissions
chmod +x JZminSetup

# Run
./JZminSetup
```
# Running Minecraft server
```bash
When JZminSetup is closed, it will give you a command to start the server.
ex:
  cd <your-server=folder> && java -Xmx1024M -Xms1024M -jar <your-server-file> nogui
  cd server_paper_1.21.4 && java -Xmx1024M -Xms1024M -jar paper-1.21.4.jar nogui
```
## 📋 Table of Contents

- [🎯 Overview](#-overview)
- [✨ Features](#-features)
- [🚀 Installation and Usage](#-installation-and-usage)
- [📦 Supported Server Types](#-supported-server-types)
- [⚙️ Requirements](#️-requirements)
- [🔧 Usage](#-usage)
- [📁 Project Structure](#-project-structure)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## 🎯 Overview

**JZminSetup** is an advanced Python tool for automatically setting up Minecraft servers. It's designed to simplify the process of creating and managing Minecraft servers of all types (Java and Bedrock) with an interactive, colorful, and easy-to-use interface.

### 🎨 Visual Features
- Interactive colored interface with ANSI codes
- Clear and understandable messages in English
- Visual progress for download and build operations

---

## ✨ Features

### 🔥 Core Features
- **Automatic setup** for all types of Minecraft servers
- **Automatic download** of latest server versions
- **Automatic building** of Spigot and Bukkit servers using BuildTools
- **Interactive interface** easy to use
- **Multi-language support** (English/Arabic)

### 🛠️ Technical Features
- **Version management** - choose from latest available versions
- **Smart download** - automatic retry on download failure
- **Smart building** - use BuildTools when needed
- **Automatic EULA setup**
- **Saved startup commands**

---

## 🚀 Installation and Usage

### 📋 Basic Requirements

#### For Linux/macOS/Windows:
```bash
# Ubuntu/Debian
sudo apt update
sudo apt install python3 python3-pip openjdk-8-jdk

# macOS (using Homebrew)
brew install python3 openjdk@8

# Windows
# Download Python from: https://www.python.org/downloads/
# Download Java JDK from: https://adoptium.net/
```

### 🔧 Installation

1. **Clone the project:**
```bash
git clone https://github.com/WeJZTeam/JZminSetup.git
cd JZminSetup
```

2. **Run the tool:**
```bash
python JZminSetup.py
```

---

## 📦 Supported Server Types

### 🟢 Java Edition Servers

| Type | Description | Features |
|------|-------------|----------|
| **Vanilla** | Official Mojang server | - Stable and reliable<br>- No modifications<br>- Suitable for beginners |
| **Paper** | Performance-optimized server | - Enhanced performance<br>- Plugin support<br>- Fast updates |
| **Spigot** | Popular plugin server | - Wide plugin support<br>- Large community<br>- Good performance |
| **Bukkit** | Base server | - Foundation for most servers<br>- Plugin support<br>- High flexibility |

### 🔵 Bedrock Edition Servers

| Type | Description | Features |
|------|-------------|----------|
| **Bedrock** | Official Windows server | - Mobile device support<br>- Enhanced performance<br>- Automatic updates |

---

## ⚙️ Requirements

### 💻 System Requirements
- **Operating System:** Windows 10/11, Linux, macOS
- **Python:** Version 3.6 or later
- **Java:** JDK 8 or later (for Java servers)
- **Memory:** 2GB RAM minimum
- **Storage:** 1GB free space

### 🌐 Network Requirements
- **Stable internet connection**
- **Download speed** 5 Mbps minimum
- **Open ports** (25565 for Java, 19132 for Bedrock)

---

## 🔧 Usage

### 🎯 Basic Steps

1. **Run the tool:**
```bash
./JZminSetup
```

2. **Choose server type:**
   - Java Edition
   - Bedrock Edition

3. **Choose server type (for Java):**
   - Vanilla
   - Paper
   - Spigot
   - Bukkit

4. **Choose version:**
   - Latest 5 available versions will be displayed

5. **Wait for automatic setup:**
   - Download files
   - Build server (if needed)
   - Setup EULA
   - Initial startup

### 📁 Created Files

```
server_[type]_[version]/
├── server.jar (or paper-*.jar, spigot-*.jar, etc.)
├── eula.txt
├── server.properties
├── START_COMMAND.txt
└── logs/
```

### 🚀 Running the Server

After setup, you can run the server using:

```bash
# For Java servers
java -Xmx1024M -Xms1024M -jar server.jar nogui

# For Bedrock servers
bedrock_server.exe
```

---

## 📁 Project Structure

```
JZminSetup/
├── JZminSetup.py          # Main tool file
├── JZminSetup             # Executable file (Linux/macOS)
├── README.md              # Documentation file
├── LICENSE                # Project license
└── examples/              # Usage examples
    ├── server_configs/    # Server configurations
    └── scripts/           # Helper scripts
```

### 🔧 Main Files

| File | Description |
|------|-------------|
| `JZminSetup.py` | Main tool code |
| `JZminSetup` | Executable for Unix-like systems |
| `README.md` | Comprehensive documentation |

---

## 🛠️ Advanced Technical Features

### 🔄 Version Management
- **Automatic updates** to latest versions
- **Support for old versions** for compatibility
- **Compatibility checking** between versions

### 🏗️ Server Building
- **Automatic BuildTools** for Spigot/Bukkit
- **Performance optimization** during building
- **Smart error handling**

### 📊 Monitoring and Tracking
- **Visual progress** for operations
- **Detailed logs** for operations
- **Detailed error reports**

---

## 🤝 Contributing

We welcome your contributions! Here's how to contribute:

### 📝 How to Contribute

1. **Fork the project**
2. **Create a new branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to branch** (`git push origin feature/AmazingFeature`)
5. **Create Pull Request**

### 🐛 Reporting Bugs

If you find a bug, please:
1. Open a new Issue
2. Describe the problem in detail
3. Attach error logs
4. Specify reproduction steps

### 💡 Feature Suggestions

To suggest new features:
1. Open a new Issue
2. Describe the requested feature
3. Explain its benefits
4. Suggest implementation method

---

## 📄 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

```
MIT License

Copyright (c) 2025 JZminSetup

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🙏 Acknowledgments

- **Mojang Studios** - for developing Minecraft
- **PaperMC Team** - for Paper server
- **SpigotMC Team** - for Spigot server
- **Bukkit Team** - for Bukkit server
- **Minecraft Community** - for continuous support

---

## 📞 Support and Contact

- **GitHub Issues:** for bug reports and feature suggestions
- **Discord:** for direct support and chat
- **Email:** for general inquiries

---

<div align="center">

**⭐ If you like the project, don't forget to give it a star! ⭐**

**🎮 Enjoy playing Minecraft with your friends! 🎮**

</div> 


