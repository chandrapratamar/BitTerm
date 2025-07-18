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
   git clone <your-repo-url>
   cd TOOR
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

- **Catppuccin Mocha** (default) - Warm, cozy dark theme
- **Nord** - Arctic-inspired color palette
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

1. **Magnet Links**: Paste a magnet link into the input field and press Enter
2. **Torrent Files**: Drag and drop `.torrent` files onto the page
3. **Info Hash**: Enter a torrent info hash to start downloading

### Managing Downloads

- **Download Files**: Click the download button (💾) next to individual files
- **View Progress**: Real-time progress bars show download completion
- **Peer Information**: See connected peers and transfer speeds
- **Remove Torrents**: Click the remove button to stop and remove torrents

### Keyboard Shortcuts

- **Enter**: Add torrent from input field
- **Click**: Select torrent for detailed view
- **Download buttons**: Download individual files

## 🌐 Deployment

### Railway.app Deployment

1. **Connect your repository** to Railway
2. **Set environment variables** (if needed)
3. **Deploy automatically** on push to main branch

The app is ready for Railway deployment with the included `server.js` Express server.

### Other Platforms

The client can be deployed to any static hosting service:
- Vercel
- Netlify
- GitHub Pages
- Any web server

## 🛠️ Development

### Local Development

```bash
# Start development server
npm run dev

# Or use the start script
npm start
```

### Customization

- **Themes**: Add new themes in the `theme-*/` directories
- **Styling**: Modify WebTUI CSS classes in `index.html`
- **Functionality**: Extend WebTorrent features in the JavaScript section

## 🔒 Privacy & Security

- **No Server Storage**: Torrents are processed entirely in the browser
- **WebRTC Only**: Uses peer-to-peer connections for data transfer
- **No Logging**: No torrent activity is logged on the server
- **Client-Side**: All torrent operations happen locally

## 📦 Dependencies

- **Express.js**: Web server for hosting
- **WebTorrent**: Browser-based BitTorrent client
- **WebTUI**: Terminal user interface CSS framework

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [WebTorrent](https://webtorrent.io/) - Browser-based BitTorrent client
- [WebTUI](https://webtui.ironclad.sh/) - Terminal user interface CSS framework
- [Nerd Fonts](https://www.nerdfonts.com/) - Icon font for terminal applications

## 📞 Support

- **Issues**: Report bugs and feature requests on GitHub
- **Discussions**: Join community discussions
- **Documentation**: Check the WebTUI and WebTorrent documentation

---

**Made with ❤️ and WebTUI styling** 