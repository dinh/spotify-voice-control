﻿<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/nexxel/spotify-voice-control">
    <img src="https://i.imgur.com/MFthi3e.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Spotify Voice Control</h3>

  <p align="center">
    A voice control utility for Spotify
    · 
    <a href="https://github.com/nexxeln/spotify-voice-control/issues">Report Bug</a>
    ·
    <a href="https://github.com/nexxeln/spotify-voice-control/issues">Request Feature</a>
  </p>
</div>

<p align="right">Logo Credit: soph</p>

![play](https://github.com/nexxeln/spotify-voice-control/blob/main/screenshots/play_dnd.gif)

*Demo video will be added soon*

### Built With

* [Python](https://python.org/)
* [spotipy - Spotify api wrapper](https://github.com/plamere/spotipy)
* [speech_recognition](https://github.com/Uberi/speech_recognition)

<p align="right">(<a href="#top">back to top</a>)</p>

### Prerequisites
- [Python 3.6+](https://www.python.org/downloads/)
- [Spotify Premium](https://www.spotify.com/premium/)



### Installation

1. Make a free application at [https://developer.spotify.com](https://developer.spotify.com)
2. Add a Redirect URI to the application and set is as `http://localhost:8888/callback`
3. Clone this repository (`git clone https://github.com/nexxeln/spotify-voice-control`)
4. Install all dependencies (`pip install -r requirements.txt`)
5. Set two environment variables, `SPOTIFY_CLIENT_ID` and `SPOTIFY_CLIENT_SECRET` 
6. Authenticate by running `main.py`
7. Run `main.py` to use

<p align="right">(<a href="#top">back to top</a>)</p>

### Usage

1. Have some music playing thorough Spotify in the device you want to listen in.
2. Run `main.py`
3. Say `play {track name}` to play a track
4. Say `album {album name}` to play an album
5. Say `artist {artist name}` to play songs of an artist
6. Say `pause` to pause the music
7. Say `resume` to resume the music
8. Say `skip` to skip to the next track
9. Say `volume {number}` to set the volume to a number between 0 and 100
10. Say `repeat` to put the current track in on repeat
11. Say `shuffle {ON/OFF}` to turn shuffle on or off
12. Sometimes the speech_recognition library doesn't understand some names. For this there is a presets feature
      - Go to `settings.json` and add your own presets
      - See `presets_example.json` for an example
      - Make your own in `settings.json`
      - Presets can only be one word so make it meaningful
      - Now you can say `{preset}` to play a preset
13. Say `quit` to quit the program

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>
