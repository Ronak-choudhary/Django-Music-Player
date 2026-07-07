# 🎵 Django Music Player

A full-stack music player built with Django that allows users to stream songs, browse music, display album artwork, and view synchronized lyrics while playback is in progress.

---

## Project Overview

This project was developed to understand Django's Model-View-Template (MVT) architecture by building a functional web-based music player.

The application integrates backend media management with a custom frontend interface to deliver an interactive music listening experience.

---

## Features

- 🎵 Play audio files directly in the browser
- 🖼 Display album artwork
- 🎤 Display synchronized song lyrics
- ⏯ Play / Pause controls
- ⏭ Navigate between songs
- 📚 Manage songs using Django Admin
- 📱 Responsive music player interface
- 💾 Store songs using SQLite and Django ORM

---

## Tech Stack

### Backend

- Django
- Python
- SQLite

### Frontend

- HTML
- CSS
- JavaScript

### Media

- HTML5 Audio
- MediaElement.js

---

## Project Workflow

Admin Panel

↓

Upload Song

↓

Store Metadata in Database

↓

Display Song Library

↓

Audio Playback

↓

Synchronized Lyrics

---

## Project Structure

```text
App/

├── models.py
├── views.py
├── urls.py
├── templates/
├── static/
└── migrations/
```

## Demo

A demonstration video of the application is available named Music-Player_Functioning.mp4.

---

## Database Model

Each song contains:

- Title
- Artist
- Album Artwork
- Audio File
- Lyrics
- Duration

---

## Future Improvements

- Playlist support
- User authentication
- Search songs
- Favorite songs
- Dark / Light mode
- Volume presets
- Recently played history

---

## Author

Ronak Choudhary
