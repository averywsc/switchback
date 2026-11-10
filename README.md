# Switchback

A rhythm game that runs in one HTML file. The game mode changes as the song plays, so you switch between different ways of playing in the same track.

No install, no build, no libraries. Open `Switchback.html` in a browser.

## Run it

1. Download `Switchback.html`.
2. Open it in Chrome or Edge on a computer for all features. Other browsers work for most things.
3. Choose a song, set how long to play, and press Start.

YouTube songs need the game to be opened from a website (for example GitHub Pages), not as a local file. YouTube blocks its player on local files.

## Game modes

There are seven modes: Highway, Circles, Cube run, Catch, Crossfire, Grid and Pulse. The mode switches on the beat, in that order. A 3, 2, 1 count tells you when a change is coming. Under Controls and options you can turn modes on or off (one mode plays all the way through) and set how long each lasts.

- Highway: hit four lanes with D, F, J and K.
- Circles: hit circles with Z and X, or with the mouse.
- Cube run: jump with Space or Up, duck with S or Down.
- Catch: move left and right with the arrow keys or the mouse to catch falling items.
- Crossfire: hit up, right, down and left with the arrow keys. A second set on W, D, S and A is also available.
- Grid: a 3 by 3 grid hit with Q, W, E, A, S, D, Z, X and C.
- Pulse: tap Space or Enter on the beat.

All keys can be changed under Controls and options. Touch controls work on phones and tablets. Esc or P pauses.

## Difficulty

Baby, Easy, Medium, Hard, Expert and Impossible. Harder levels have more notes, faster movement and tighter timing. Baby has very few notes, wide timing and gentle health loss.

## Songs

- By genre: Hip hop, R&B, Anime, 90s pop, 2000s, 80s, Pop, Rock, EDM, K-pop, Latin, Country and Indie, with up to 16 songs each. The game checks every song in the background and hides any that are removed, blocked or the wrong video, so only songs that play are listed.
- Random song: picks a checked song from all genres.
- Upload from your device: mp3, wav, ogg and other audio or video files.
- Link: paste a YouTube link or a direct link to an audio file.

The song you load shows in a Now loaded card on the main menu with its title, tempo and length. The last song you played has its own Play again button at the bottom of the menu.

Play length is set to the whole song by default. Notes start after the first 3 seconds of the song.

### YouTube songs

The game cannot hear YouTube audio, so it builds the notes from a beat grid instead of the music. It needs the tempo and where the first beat lands. You can tap along to set them, or use Random song, which fills in a stored tempo.

### Random song and genres

Press Random song, or pick a song from a genre. The game loads the video quietly, sets the tempo and returns you to the start menu with the song ready. Press Start to play. Nothing plays until you press Start.

The tempo comes from a stored list and the game assumes the beat starts at the beginning of the video. If a song feels off, paste its link yourself and tap the beat.

## Colours

- For a YouTube song the game picks the main colours of the video (not just one tint) and spreads them across every mode. The colours keep shifting while a mode plays, following the video and changing every few beats.
- For other songs the colours come from the cover art.
- Two sliders on the main menu set the primary and secondary colours by hand. Setting them stops the automatic colours.
- Pick colour (on the pause screen) lets you click any spot on screen to use its colour. Desktop Chrome and Edge only.

## Results

At the end of a song you get your score, rank and accuracy, plus a Better than percentage of players with a graph of where you sit. The crowd is simulated and scaled to the difficulty you played, so it is for fun and not real player data.

## Options

- Volume slider for the song and all sound effects.
- Sync offset (in milliseconds) to fix timing if the notes feel early or late.
- Hit sounds: 19 voices (Chime, Pluck, Bell, Drum, Click, Marimba, Piano, Harp, Glass, Synth, Laser, Coin, Pop, Wood block, Kick, Snare, Clap, Hi-hat and Bubble) or Off.
- Echo on the hit sound: Off (default), Short, With the beat or Long.
- Click volume, and a master volume for everything.
- Key rebinding for every mode.

## Browser support

| Feature | Chrome and Edge (desktop) | Other browsers |
| --- | --- | --- |
| Game | Yes | Yes |
| Upload and links | Yes | Yes |
| YouTube songs | Yes | Yes |
| Pick colour | Yes | No |

## Known limits

- YouTube timing depends on the tempo and beat position being right. Tap along if a song feels off.
- The song lists are fixed. A video that has been removed or blocked is hidden automatically once the game has checked it.
- The stored tempo values were not all checked against a source.
- Video colours come from YouTube preview images, so they follow the video in a few steps rather than frame by frame.

## Files

- `Switchback.html`: the whole game.
- `README.md`: this file.
