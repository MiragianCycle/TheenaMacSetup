<p align="center">
  <h1 align="center">🚀 MacDevKit</h1>
</p>

<p align="center">
  <img src="docs/brand.webp" alt="MacDevKit Logo" width="200">
</p>

<p align="center">
  <strong>The Ultimate Toolkit for Setting Up macOS Development Environment in One Click</strong>
</p>

<p align="center">
  <a href="#-features">✨ Features</a> •
  <a href="#-installation">🔧 Installation</a> •
  <a href="#-usage">📖 Usage</a> •
  <a href="#-included-tools">🛠️ Included Tools</a> •
  <a href="#-customization">⚙️ Customization</a> •
  <a href="#-contributing">👥 Contributing</a> •
  <a href="#-license">📄 License</a>
</p>

<p align="center">
  <a href="https://github.com/jarvislin94/MacDevKit/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/jarvislin94/MacDevKit" alt="License">
  </a>
  <img src="https://img.shields.io/badge/platform-macOS-lightgrey" alt="Platform">
  <img src="https://img.shields.io/badge/shell-bash-4EAA25" alt="Shell">
  <img src="https://img.shields.io/badge/macOS-Monterey%20|%20Ventura%20|%20Sonoma-blue" alt="macOS">
</p>

_[中文文档](README.md) | English_

---

## ✨ Features

MacDevKit is a comprehensive macOS development environment setup toolkit designed for developers, capable of setting up a new Mac development environment in minutes.

- 🚀 **One-Click Installation** - Set up all development tools and configurations with a single command
- 🎨 **Beautiful Interface** - Colorful output and clear progress indicators
- 🔄 **Idempotent Operations** - Can be safely run multiple times without duplicate installations
- 🔧 **Comprehensive Toolset** - Includes all tools needed for frontend, backend, mobile, and cloud development
- 🎛️ **Interactive Options** - Choose which applications and configurations to install
- 💻 **Support for Intel and Apple Silicon** - Automatically detects and adapts to different Mac chips
- 🔒 **Secure and Reliable** - Uses official sources and secure installation methods

<p align="center">
  <img src="https://user-images.githubusercontent.com/12573233/236685568-5b4c9ae5-f222-4fdb-b1bf-b536d2cc0c0d.gif" alt="MacDevKit Demo" width="600">
</p>

## 🔧 Installation

Download init.sh and run MacDevKit:

```bash
# Download the script
curl -fsSL https://raw.githubusercontent.com/jarvislin94/MacDevKit/main/init.sh -o init.sh

# Make the script executable
chmod +x init.sh

# Run the script directly to ensure interactive commands work properly
./init.sh
```

## 📖 Usage

After running the script, you'll see an interactive interface guiding you through the entire setup process:

1. The script will first install basic tools like Homebrew, Git, and Xcode Command Line Tools
2. Then, it will set up your Git configuration and generate SSH keys
3. Next, it will install development tools like VS Code, Node.js, Docker, etc.
4. You can choose to install additional applications like Chrome, Slack, Postman, etc.
5. Finally, you can choose to configure macOS system settings to optimize your development experience

The script displays colorful output, clearly indicating current progress and success/failure status.

## 🛠️ Included Tools

MacDevKit includes the following development tools and applications:

### Basic Tools

- **Homebrew** - macOS package manager
- **Git** - Version control system
- **Xcode Command Line Tools** - Basic development tools

### Development Environment

- **NeoVim**
- **Emacs** (Mac Optimized) 
- **Visual Studio Code** - Code editor with common extensions
- **Kitty** - Terminal emulator
- **Oh My Zsh** - Zsh configuration framework with Powerlevel10k theme and plugins

### Programming Languages and Runtimes

- **Node.js** (via NVM) - JavaScript runtime
- **Python** - Programming language
- **Go** - Programming language
- **Rust** - Programming language
- **Common Lisp** - Programming Language 

### Database Tools

- **SQLite** - Lightweight database


### Command Line Tools

- **jq** - JSON processor
- **ripgrep** - Fast search tool
- **fd** - Fast find tool
- **bat** - Enhanced cat command
- **exa** - Enhanced ls command
- **htop** - Process viewer
- **tmux** - Terminal multiplexer
- **fzf** - Fuzzy finder
- And more...

### Optional Applications

- **Google Chrome** - Web browser
- **Firefox** - Web browser
- **Yabai** - Window manager
- **Alfred** - Productivity tool

## ⚙️ Customization

You can customize the installation process by editing the `init.sh` file:

- Add or remove tools and applications to install
- Modify Git configuration and SSH key generation
- Adjust VS Code extensions
- Change macOS system settings

Future versions will support more flexible customization through configuration files.

## 👥 Contributing

Contributions are welcome! If you have suggestions for improvements or have found issues, please:

1. Fork this repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Create a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <sub>Made with ❤️ by <a href="https://github.com/jarvislin94">jarvislin94</a></sub>
</p>
