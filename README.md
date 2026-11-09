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

- Built-in songs: three tracks that ship inside the file.
- Upload from your device: mp3, wav, ogg and other audio or video files.
- Link: paste a YouTube link or a direct link to an audio file.
- Random song: picks one of 50 popular YouTube music videos.

### YouTube songs

The game cannot hear YouTube audio, so it builds the notes from a beat grid instead of the music. It needs the tempo and where the first beat lands. You can tap along to set them, or let Random song find them for you.

### Random song

Press Random song and the game picks a video, checks that it can be played, sets the tempo and returns you to the start menu with the song ready.

For accurate timing, press Match video colours first and tick Share tab audio. The game then plays about 10 seconds of the song, listens to it and measures the tempo and beat position. Without shared audio it falls back to a stored tempo and assumes the beat starts at the beginning of the video, which can be off.

This part needs desktop Chrome or Edge.

## Colours

- Colours come from the song cover art by default.
- Two sliders on the main menu set the primary and secondary colours by hand.
- Match video colours samples the playing video and recolours the game. Share this tab when the browser asks. It samples once at the start of each song.
- Pick colour (on the pause screen) lets you click any spot on screen to use its colour. Desktop Chrome and Edge only.

## Options

- Volume slider for the song and all sound effects.
- Sync offset (in milliseconds) to fix timing if the notes feel early or late.
- Hit sounds: Chime, Pluck, Bell, Drum, Click or Off.
- Key rebinding for every mode.

## Browser support

| Feature | Chrome and Edge (desktop) | Other browsers |
| --- | --- | --- |
| Game and built-in songs | Yes | Yes |
| Upload and links | Yes | Yes |
| YouTube songs | Yes | Yes |
| Match video colours and beat listening | Yes | No |
| Pick colour | Yes | No |

## Known limits

- YouTube timing depends on the tempo and beat position being right. Tap along or use the audio sharing option if a song feels off.
- Random song uses a fixed list of 50 videos. A video that has been removed or blocked is skipped automatically.
- The tempo values stored for the list were not all checked against a source. Beat listening replaces them when audio is shared.

## Files

- `Switchback.html`: the whole game.
- `README.md`: this file.
