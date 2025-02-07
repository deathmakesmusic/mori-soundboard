# Mori Soundboard

## Use it

https://deathmakesmusic.github.io/mori-soundboard/

## Adding new sounds

Add an audio file to `sounds`.

A GitHub Actions workflow will automatically make an entry for it in `sounds.json` with the filename as `file`.
You can edit two optional fields per sound in `sounds.json`:

* `name`: override the name generated based on the filename
* `tags`: a list of additional searchable strings for the sound 
