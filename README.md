# 🎵 Spotify Playlist Downloader

<p align="center">
  <img src="https://img.shields.io/badge/python-3.6+-blue.svg" alt="Python Version">
  <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License">
  <img src="https://img.shields.io/badge/spotify-API-1DB954.svg" alt="Spotify API">
</p>

<p align="center">
  Download entire Spotify playlists with metadata in just a few simple steps!
</p>

## ✨ Features

- 📥 **Complete Downloads** - Save entire Spotify playlists with a single command
- 🎧 **High Quality Audio** - Converts to high-quality MP3 format
- 📊 **Progress Tracking** - Visual progress bars to monitor your downloads
- 🔍 **Smart Search** - Intelligent matching for best audio source
- 📁 **Rich Metadata** - Preserves all playlist information in JSON format

## 🚀 Quick Start

### Prerequisites

- Python 3.6+
- Spotify Developer account

### Installation

#### 1. Clone the repository

```bash
git clone https://github.com/yourusername/spotify-playlist-downloader.git
cd spotify-playlist-downloader
```

#### 2. Install dependencies

```bash
pip install -r requirements.txt
```

#### 3. Set up Spotify API credentials

1. Visit the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/)
2. Create a new application
3. Copy your Client ID and Client Secret
4. Create a `.env` file in the project directory:

```
SPOTIFY_CLIENT_ID=your_client_id_here
SPOTIFY_CLIENT_SECRET=your_client_secret_here
```

## 💻 Usage

### Basic Usage

```bash
python spotify_playlist_downloader.py "https://open.spotify.com/playlist/37i9dQZEVXbMDoHDwVN2tF"
```

### Specify Output Directory

```bash
python spotify_playlist_downloader.py "https://open.spotify.com/playlist/37i9dQZEVXbMDoHDwVN2tF" --output "C:\Music\MyPlaylist"
```

## 🔍 How It Works

<p align="center">
  <img src="https://via.placeholder.com/600x200?text=Workflow+Diagram" alt="Workflow Diagram">
</p>

1. **Authentication** - Securely connects to the Spotify API
2. **Metadata Retrieval** - Collects complete playlist information
3. **Smart Search** - Finds the best audio source for each track
4. **Download & Conversion** - Saves high-quality audio files
5. **Organization** - Structures files with proper naming and metadata

## ⚠️ Legal Notice

This tool is for **personal use only**. Please respect copyright laws and artists' rights. Support the artists by using official platforms for regular listening.

## 🔧 Troubleshooting

| Problem | Solution |
|---------|----------|
| Authentication errors | Verify Spotify API credentials in .env file |
| Download failures | Check internet connection or try again later |
| Missing tracks | Some tracks may not be available through search |
| Rate limiting | Add delays between requests if you hit API limits |

## 📚 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

<p align="center">
  Made with ❤️ for music lovers
</p>
