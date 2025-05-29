# Queue FM

**Queue FM** is a Spotify-powered radio station system that maintains a single, continuously updated playlist. It offers both automated playlist management through [spotify-dj](https://github.com/splinesreticulating/spotify-dj) and manual control via [spotify-jukebox](https://github.com/splinesreticulating/spotify-jukebox).

## Components

- **[spotify-dj](https://github.com/splinesreticulating/spotify-dj)**: Automatically curates and updates the playlist based on predefined criteria.
- **[spotify-jukebox](https://github.com/splinesreticulating/spotify-jukebox)**: Allows users to manually add and manage tracks in the playlist.

## Features

- Seamless integration with Spotify's API for real-time playlist updates.
- Dual-mode operation: automated DJ and manual jukebox control.
- Designed for continuous playback, emulating a traditional radio station experience.

## Getting Started

1. **Clone the repositories**:

   ```bash
   git clone https://github.com/splinesreticulating/spotify-dj.git
   git clone https://github.com/splinesreticulating/spotify-jukebox.git
   ```

2. **Set up your environment**:

   - Ensure you have Node.js and npm installed.
   - Obtain Spotify API credentials and set them as environment variables.

3. **Install dependencies**:

   ```bash
   cd spotify-dj
   npm install
   cd ../spotify-jukebox
   npm install
   ```

4. **Run the applications**:

   ```bash
   npm start
   ```

## Configuration

- **Environment Variables**:
  - `SPOTIFY_CLIENT_ID`
  - `SPOTIFY_CLIENT_SECRET`
  - `SPOTIFY_REDIRECT_URI`

Ensure these are set appropriately in both applications.

## License

This project is licensed under the MIT License.
