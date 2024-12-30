# Music Player 🎵

A sleek and responsive web-based music player built using **jPlayer** and **jQuery**. It features a dynamic playlist, volume control, and progress tracking with an intuitive user interface.

Try the Live demo here: Music Player[https://musicplayersuga.netlify.app/]

## Features 🚀

- **Interactive Controls**:
  - Play, pause, next, and previous track navigation.
  - Volume slider with mute/unmute functionality.
  - Seekable progress bar for precise playback control.

- **Dynamic Playlist**:
  - Displays the current playlist with metadata (title, artist, and album art).
  - Highlights the currently playing track.

- **Customizable Design**:
  - Easily modify styles to suit your needs with `styles.css`.

- **Multi-Format Support**:
  - Plays MP3, OGG, and M4A formats out-of-the-box.

- **Responsive Layout**:
  - Optimized for all screen sizes.

---

## Installation 🔧

1. **Clone the Repository**:
   ```bash
[  [ git clone https://github.com/your-username/music-player.git]
](https://github.com/sugapriya-k/Music-Player.git)   
cd music-player
2. **Dependencies**Make sure the following libraries are included:
- jQuery
- jQuery UI
- jPlayer
3. **Run the Player**:
Open the index.html file in your browser to launch the player.

---

## Installation 🔧

music-player/
├── index.html         # Main HTML file
├── styles.css         # Custom CSS for styling
├── script.js          # JavaScript for functionality
└── README.md          # This file

---

## Configuration ⚙️

# Playlist
Update the playlist array in script.js to include your tracks. Each track should have the following structure:

var playlist = [
  {
    title: "Hidden",
    artist: "Miaow",
    mp3: "http://www.jplayer.org/audio/mp3/Miaow-02-Hidden.mp3",
    oga: "http://www.jplayer.org/audio/ogg/Miaow-02-Hidden.ogg",
    poster: "https://i.imgur.com/sCbrzQa.png"
  },
  {
    title: "Cro Magnon Man",
    artist: "The Stark Palace",
    mp3: "http://www.jplayer.org/audio/mp3/TSP-01-Cro_magnon_man.mp3",
    oga: "http://www.jplayer.org/audio/ogg/TSP-01-Cro_magnon_man.ogg",
    poster: "https://i.imgur.com/lXvsuBu.png"
  }
];

## Dependencies 📦

The project relies on the following external libraries:

jQuery: [https://jquery.com/]
jQuery UI: [https://jqueryui.com/]
jPlayer: [https://jplayer.org/]
These libraries are loaded via CDN in index.html


