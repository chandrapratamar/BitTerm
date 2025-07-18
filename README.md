# [bitTerm] - WebTorrent Client

A modern, terminal-styled WebTorrent client built with WebTUI CSS framework. Experience the power of WebTorrent with an authentic terminal user interface (TUI) aesthetic.


## ✨ Features

- **WebTorrent Integration**: Full WebTorrent client functionality running entirely in the browser
- **WebTUI Styling**: Authentic terminal user interface with monospace fonts and character cell units
- **Real-time Stats**: Live download/upload speeds, progress bars, and peer information
- **File Management**: Individual file download controls 
- **Theme Support**: Multiple color themes including Catppuccin, Nord, Dark,and Light.
- **WebRTC Support**: Peer-to-peer connections without server-side torrent handling

## 🚀 Quick Start

### Prerequisites

- Node.js 18.0.0 or higher
- Modern web browser with WebRTC support

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/chandrapratamar/BitTerm/
   cd BitTerm
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000`

## 🎨 Themes

The client supports multiple WebTUI themes:

- **Catppuccin Mocha** (default)
- **Nord** 
- **Dark** 
- **Light**


## 📁 Project Structure

```
TOOR/
├── index.html              # Main application file
├── server.js               # Express server for hosting
├── package.json            # Node.js dependencies
├── public/                 # Static assets
│   ├── favicon.ico        # Browser favicon
│   └── favicon.svg        # SVG favicon
├── css/                    # WebTUI CSS framework
├── theme-*/                # Theme directories
│   ├── catppuccin/        # Catppuccin theme
│   ├── nord/              # Nord theme
└── plugin-nf/             # Nerd Fonts plugin
```

## 🔧 Usage

### Adding Torrents

1. **Magnet Links/Torrent URL**: Paste a magnet link/torrent URL into the input field and press Enter

### Managing Downloads

- **Download Files**: Click the download button (💾) next to individual files
- **View Progress**: Real-time progress bars show download completion
- **Peer Information**: See connected peers and transfer speeds
- **Remove Torrents**: Click the remove button to stop and remove torrents


## 🙏 Acknowledgments

- [WebTorrent](https://webtorrent.io/) - Browser-based BitTorrent client
- [WebTUI](https://webtui.ironclad.sh/) - Terminal user interface CSS framework

---

**Made with ❤️ and WebTUI styling** 
