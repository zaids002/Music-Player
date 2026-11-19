# Music Player

A modern, interactive web-based **Music Player** built with pure HTML, CSS, and Vanilla JavaScript. It comes preloaded with a default track and lets users import any local music folder from their computer to browse and play tracks in a clean playlist interface.

## Features

- **Full Playback Controls:** Play, pause, skip to the next or previous track, and automatically advance when a song finishes.
- **Interactive Seek Bar:** Custom-styled progress slider that updates in real time and lets you scrub to any point in a track.
- **Slide-Over Playlist Panel:** Toggle the playlist drawer from the top menu to view all loaded tracks, see the active song highlighted, and jump to any track with one click.
- **Local Folder Import ("Select Folder"):** Load an entire folder of audio files (`.mp3`, `.wav`, `.ogg`, `.m4a`, `.aac`, `.flac`, `.webm`) directly in the browser without uploading files to a server.
- **Automatic Title & Artist Parsing:** Automatically extracts the song title and artist name from files formatted as `Title - Artist.mp3`.

## Tech Stack

- **HTML5** – Audio element, file/directory input (`webkitdirectory`), and player structure
- **CSS3** – Custom slider thumb styling, Flexbox layout, shadows, and pink/dark card theme
- **JavaScript (ES6+)** – Audio playback state, dynamic playlist rendering, Blob URL object loading, and metadata parsing
- **Font Awesome 6** – Playback, navigation, and playlist UI icons

## Project Structure

```text
├── index.html          # Main player layout, playlist drawer, and JavaScript logic
├── style.css           # Player card styling, custom range slider, and button styles
└── media/
    ├── Go-NEFFEX.mp3   # Default preloaded audio track
    └── thumbnail.png   # Default circular album artwork
```

## Getting Started

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/zaids002/music-player.git](https://github.com/zaids002/music-player.git)
   cd music-player
   ```

2. **Run the project:**
   Open `index.html` in your web browser, or launch it with the **Live Server** extension in VS Code.

3. **Load your own music:**
   - Click the **menu icon (`☰`)** in the top-right corner of the player to open the playlist.
   - Click **Select Folder** and choose any folder on your computer containing audio files.

## Author

- **Zaid Syed** – [@zaids002](https://github.com/zaids002)
