
# Theena's Mac Setup 

## ✨ Features

This is an experimental script to help init any new Mac device. 

- 🚀 **One-Click Installation** - Set up all development tools and configurations with a single command
- 🎨 **Beautiful Interface** - Colorful output and clear progress indicators
- 🔄 **Idempotent Operations** - Can be safely run multiple times without duplicate installations
- 🔧 **Comprehensive Toolset** - Includes all tools needed for frontend, backend, mobile, and cloud development
- 🎛️ **Interactive Options** - Choose which applications and configurations to install
- 💻 **Support for Intel and Apple Silicon** - Automatically detects and adapts to different Mac chips
- 🔒 **Secure and Reliable** - Uses official sources and secure installation methods


## 🔧 Installation

Download init.sh and run MacDevKit:

```bash

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
4. You can choose to install additional applications like Chrome or a web browser of your choice (I use Arc and Zen). Also includes a variety of lightweight PDF readers (such as Skim, Zathura)
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
- **skhd** - Simple hotkey daemon for macOS
- **Karabiner-Elements** - Keyboard configuration tool for fine-tuned keyboard-first control of the Mac device 
- **Raycast** - Productivity tool
- **Zathura and Skim** - PDF Readers 

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

## CREDIT 

I forked [Jarvislin94](https://github.com/jarvislin94) original init script and modified it for my needs. 
---

<p align="center">
  <sub>Made with ❤️ by <a href="https://github.com/jarvislin94">jarvislin94</a></sub>
</p>
