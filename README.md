# Spotify-Like Web Player

A web-based music player that mimics Spotify's interface and functionality. This project allows users to browse albums, play music tracks, control playback, and interact with a dynamic and responsive UI.

## Features

- **Dynamic Album Display**: Automatically fetches albums and metadata (title, description, cover image).
- **Playlist Management**: Displays songs dynamically for the selected album.
- **Playback Controls**:
  - Play/Pause
  - Next/Previous Track
  - Seekbar for scrubbing through tracks
- **Volume Control**: Adjust volume levels or mute/unmute the player.
- **Responsive Sidebar**: Hamburger menu for seamless navigation.
- **Real-Time Updates**: Displays current playback time and duration.


## Technologies Used 

- **HTML5**: For the structure of the web player.
- **CSS3**: Styling with focus on responsiveness and interactivity.
- **JavaScript (ES6)**: For dynamic functionalities such as fetching songs, managing playback, and UI updates.
- **Fetch API**: For fetching songs and album metadata.
- 
## Project Structure

/
├── css/
│   ├── style.css           # Main styles
│   └── utility.css         # Utility classes for reusable styles
├── img/                    # Icons and assets (e.g., play, pause, volume)
├── js/
│   └── script.js           # Core JavaScript functionality
├── songs/                  # Folder containing albums and songs
│   ├── <album_name>/
│   │   ├── song1.mp3
│   │   ├── song2.mp3
│   │   ├── cover.jpeg      # Album cover
│   │   └── info.json       # Album metadata (title, description)
├── index.html              # Main HTML file
└── README.md               # Documentation

## Setup and Installation
Clone this repository:
````bash
git clone https://github.com/SabreenaFatimah-git/Spotify-Like-Web-Player.git
````
## Organize your songs inside the /songs/ folder:

/songs/
    /<album_name>/
        - song1.mp3
        - song2.mp3
        - info.json
        - cover.jpeg
        
## Start a local server:

Use any static server tool like http-server in Node.js:
```bash
npx http-server

```
Or use the built-in server in VS Code.

## Open index.html in a browser.

## Future Enhancements:

Add a search bar to find songs or albums easily.
Support for user-created playlists.
Implement a dark mode toggle.
Integrate a back-end API for dynamic data storage.
Add visualizations like an equalizer during playback.
 
