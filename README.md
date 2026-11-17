# Spotify Clone 🎵

A Spotify-inspired web music player built using HTML, CSS, and JavaScript. The application dynamically loads songs and albums from local folders and provides audio playback controls through the browser's Audio API.

## ✨ Features

- Spotify-inspired user interface.
- Sidebar navigation.
- Dynamic playlist and album cards.
- Dynamic song loading from local directories.
- Audio playback using JavaScript Audio API.
- Play and pause controls.
- Next and previous song navigation.
- Song duration display.
- Interactive seekbar.
- Volume adjustment.
- Mute and unmute functionality.
- Responsive layout for different screen sizes.
- Mobile sidebar navigation.

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Fetch API
- Async/Await
- DOM Manipulation
- JavaScript Audio API
- CSS Flexbox
- CSS Grid
- Media Queries

## 📂 Project Structure

```text
spotify-clone/
│
├── index.html
│
├── css/
│   ├── style.css
│   └── utility.css
│
├── js/
│   └── script.js
│
├── img/
│   └── Images and SVG icons
│
└── songs/
    ├── cs/
    │   ├── song.mp3
    │   ├── cover.jpg
    │   └── info.json
    │
    └── other-albums/
        ├── song.mp3
        ├── cover.jpg
        └── info.json
```

## 🚀 How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/spotify-clone.git
```

2. Navigate to the project directory.

3. Start a local development server from the project root.

4. Open the application through the local server URL in your browser.

**Important:** The application relies on server directory listings to discover song and album folders. Opening `index.html` directly using `file://` will not work correctly.

## 🎧 Album Configuration

Each album folder should contain:

- Audio files (`.mp3`)
- `cover.jpg`
- `info.json`

Example `info.json`:

```json
{
    "title": "My Playlist",
    "description": "A collection of favourite songs"
}
```

## 📌 Note

This is an educational frontend project inspired by Spotify's interface. It is not an official Spotify application and does not provide Spotify authentication or streaming services.

## 👨‍💻 Author

**Priyanshu Kumar Singh**

BSc Computer Science & Data Analytics  
IIT Patna
