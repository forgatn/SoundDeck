# SoundDeck
Sound Deck board with legendary catchphrases from Movies. It is build as simple HTML page with Tile design. Each tile has mp3 attached. Whenever button is pressed the sound is played.

## Project structure

**assets**
> folder where all stored JS / CSS / Image files / ... etc

**sound**
> folder where all mp3 media used in project are stored

**sound_deck.html**
> main file you can run via web browser


## How you contribute to project
You are more then Welcome to contribute to this project

1) Pull the `main` branch from repository
2) Create your own branch (push directly to `main` branch is prohibited)
3) Add new *item* to the Sound Deck

a) Prepare your `.mp3` sound (more in section How to prepare sound)
b) Add new *item* by copy the `button` fragment code

```
<button class="button" onclick="playSound('sound_deck/sound/repete.mp3')">Repete</button>
```
c) Replace the *value* in `playSound()` function in order to reffer to your desired `.mp3` file
d) Change the *value* in `<button> Your text to display </button>` in order to show your `.mp3` Title. This *valuer* is displayed in the Tile.
e) Save your changes, commit your own `branch` as a *pull request*


## Demo
You can access working Sound Deck [here](https://vpsolution.cz/sound_deck/sound_deck.html)


## How to prepare **sound**
Step-by-Step guide how to create your own `.mp3` sound

1) Find your video on [Youtube](https://www.youtube.com/) and copy video URL
2) Open [YoutubeToMp3 converter](https://ytmp3.nu/9A1f/) , paste the video URL and press **Covert** button
3) Save converted `.mp3` file in to `sound` folder in the project
4) If it is necesarry open the [MP3 online editor](https://mp3cut.net/) to adjust `.mp3` file

----


## References
- [YoutubeToMp3 converter](https://ytmp3.nu/9A1f/)
- [MP3 online editor](https://mp3cut.net/)

## Issues
Please feel free to report issuess in [GitHub](https://github.com/forgatn/SoundDeck/issues) or via email [forgatn@gmail.com](forgatn@gmail.com)
