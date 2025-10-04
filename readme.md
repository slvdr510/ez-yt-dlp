# 🎶 ez-yt-dlp 🎬

A simple, interactive bash script that makes downloading videos and audio from YouTube (and other platforms) easy and organized.

## Features

- **Interactive Menu**: Simple command-line interface with clear options
- **Multiple Audio Formats**: Download audio in FLAC, MP3, M4A/AAC, or OPUS formats
- **Multiple Video Formats**: Download videos in MP4 or WebM formats
- **Auto-Organization**: Automatically saves audio files to `~/music` and videos to `~/videos`
- **Continuous Mode**: Download multiple files in a single session
- **Safe Filenames**: Uses restricted filenames to avoid filesystem issues

## Requirements

- `yt-dlp` must be installed and available in your PATH
- Bash shell

## Usage

1. Make the script executable:
   ```bash
   chmod +x ez-yt-dlp
   ```

2. Run the script:
   ```bash
   ./ez-yt-dlp
   ```

3. Follow the interactive prompts:
   - Enter a video URL
   - Choose your preferred format (1-6)
   - The file will be automatically downloaded to the appropriate folder

4. Press ENTER without entering a URL to exit

## Format Options

### Audio Formats (saved to ~/music)
- **FLAC**: Lossless quality, largest file size
- **MP3**: Most compatible, moderate quality/size  
- **M4A/AAC**: Better quality than MP3, Apple devices
- **OPUS**: Best compression, smallest files, modern codec

### Video Formats (saved to ~/videos)
- **MP4**: Most compatible, works everywhere
- **WebM**: Smaller files, newer browsers only

## Installation

1. Clone this repository
2. Ensure `yt-dlp` is installed on your system
3. Make the script executable and run it

The script will automatically create the `~/music` and `~/videos` directories if they don't exist.