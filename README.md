![GitHub all releases](https://img.shields.io/github/downloads/rakanbakir/XTREME-IPTV-PLAYER/total?color=blue&label=Downloads&logo=github)
![GitHub release (latest by date)](https://img.shields.io/github/downloads/rakanbakir/XTREME-IPTV-PLAYER/latest/total?color=purple&label=Latest%20Release%20Downloads&logo=github)

# XTREME IPTV PLAYER by Rakan Bakir

A powerful, cross-platform IPTV player built with Python and PyQt5. Supports M3U_plus playlists and Xtream Codes API for seamless streaming of live TV channels, movies, and series.

## ✨ Features

### 🎬 Media Support
- **Live TV Channels**: Stream live television with EPG (Electronic Program Guide) support
- **Movies & Series**: Browse and play on-demand content with resume functionality
- **M3U_plus Playlists**: Full support for M3U_plus formatted playlists
- **Xtream Codes API**: Direct integration with Xtream Codes servers

### 🎮 User Interface
- **Modern Dark/Light Themes**: Toggle between dark and light themes
- **System Tray Integration**: Minimize to tray with media controls and notifications
- **Categorized Navigation**: Organized tabs for Live TV, Movies, and Series
- **Search Functionality**: Find channels, movies, and series quickly
- **Favorites System**: Save and manage your favorite content
- **Context Menus**: Right-click options for sorting and managing content

### 🔧 Advanced Features
- **Resume Playback**: Automatically resume from where you left off
- **External Player Support**: Use VLC or other media players
- **EPG Integration**: View program schedules and current shows
- **Series Navigation**: Browse seasons and episodes with detailed information
- **Performance Optimized**: Fast loading with background processing
- **Cross-Platform**: Works on Windows, macOS, and Linux

### 🛠️ System Integration
- **System Tray Controls**: Play/Pause, Stop, Mute from tray menu
- **Desktop Notifications**: Login status and EPG updates
- **Keyboard Shortcuts**: Full keyboard control support
- **Auto-save Settings**: Remembers your preferences and playback positions

## 📋 Requirements

- **Python 3.7+**
- **PyQt5** (GUI framework)
- **Qt5** (for system tray and media playback)
- **VLC Media Player** (recommended for best playback)

### Dependencies
```
requests==2.31.0
python-dateutil==2.8.2
PyQt5==5.15.9
lxml==4.9.3
qdarkstyle==3.2.3
```

## 🚀 Installation

### Linux (Ubuntu/Debian)
```bash
# Clone the repository
git clone https://github.com/rakanbakir/XTREME-IPTV-PLAYER.git
cd XTREME-IPTV-PLAYER

# Make install script executable and run
chmod +x install.sh
./install.sh --run --desktop
```

### Linux (Other Distributions)
The installer supports:
- Ubuntu/Debian/Linux Mint/Pop!_OS
- Fedora/RHEL/CentOS/Rocky/AlmaLinux
- Arch Linux/Manjaro/EndeavourOS
- openSUSE

### Windows/macOS
```bash
# Install Python 3.7+ from python.org
# Install dependencies
pip install -r requirements.txt

# Run the application
python xtreme_iptv_player.py
```

### Manual Installation
```bash
# Install system dependencies
# Ubuntu/Debian:
sudo apt install python3-pyqt5 vlc ffmpeg

# Fedora:
sudo dnf install python3-qt5 vlc ffmpeg

# Arch:
sudo pacman -S python-pyqt5 vlc ffmpeg

# Install Python dependencies
pip install -r requirements.txt
```

## 🎯 Usage

### First Time Setup
1. **Launch the Application**: Run `python xtreme_iptv_player.py` or use the desktop shortcut
2. **Login Options**:
   - **Xtream Codes**: Enter server URL, username, and password
   - **M3U_plus**: Paste your M3U_plus URL
3. **Load Content**: The app will automatically load your channels, movies, and series

### Navigation
- **Live TV Tab**: Browse live channels with EPG information
- **Movies Tab**: Browse and play movies with detailed information
- **Series Tab**: Navigate through series, seasons, and episodes
- **Favorites Tab**: Access your saved favorite content

### System Tray
- **Minimize to Tray**: Click the minimize button to hide to system tray
- **Tray Menu**: Right-click tray icon for quick controls
- **Double-click**: Restore the main window
- **Media Controls**: Control playback without opening the main window

### Keyboard Shortcuts
- `Ctrl+Up`: Volume Up
- `Ctrl+Down`: Volume Down
- `Space`: Play/Pause
- `Escape`: Exit fullscreen
- `Double-click video`: Toggle fullscreen

## 🔧 Configuration

The application stores settings in `config.ini` and credentials in `credentials.ini`. These files are created automatically on first run.

### Settings Options
- **Theme**: Dark/Light mode toggle
- **Debug Mode**: Enable/disable debug logging
- **HTTP Method**: GET/POST for API requests
- **Font Size**: Adjust interface font size
- **EPG Loading**: Enable/disable Electronic Program Guide

## 🐛 Troubleshooting

### Common Issues

**Application won't start:**
- Ensure Python 3.7+ is installed
- Check that all dependencies are installed: `pip install -r requirements.txt`
- On Linux, ensure Qt5 is available: `sudo apt install python3-pyqt5`

**No video playback:**
- Install VLC media player
- Try switching to external player mode
- Check your system's video drivers

**System tray not working:**
- On Linux, ensure you have a system tray (like KDE/Unity/GNOME with extensions)
- On Windows, system tray should work by default

**EPG not loading:**
- Check your internet connection
- Ensure your IPTV provider supports EPG
- Wait a few moments for EPG data to download

### Debug Mode
Enable debug mode in settings to see detailed logs in the console.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit issues, feature requests, or pull requests.

### Development Setup
```bash
git clone https://github.com/rakanbakir/XTREME-IPTV-PLAYER.git
cd XTREME-IPTV-PLAYER
pip install -r requirements.txt
python xtreme_iptv_player.py
```

## 📄 License

This project is open source. See LICENSE file for details.

## 🙏 Acknowledgments

- **Original Author**: My-1 (https://github.com/Cyogenus/XTREME-IPTV-PLAYER-by-MY-1)
- **Enhanced by**: Rakan Bakir
- **Built with**: Python, PyQt5, Qt5

## 📞 Support

If you encounter any issues or have questions:
- Create an issue on GitHub
- Check the troubleshooting section above
- Ensure you're using the latest version

---

**Enjoy streaming with XTREME IPTV PLAYER!** 📺✨
