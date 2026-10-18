# FretGrind

A guitar learning game that listens through your microphone. Learning is a grind; this makes it a fun one.

- **Tuner**: tune each open string, with a reference pitch for every string.
- **Fretboard games**: 60-second rounds to learn where notes are on the neck.
- **Song lessons**: classic tunes, blues and flamenco, with a metronome, a tempo that speeds up as you improve, and a review after each pass that plays back your take and points out trouble spots.
- **Chords**: 12 beginner chords and 8 progressions, recognised from your strumming.

Everything runs in the browser. Mic audio is analysed on your device and never uploaded.

## Run it locally

Browsers only allow the microphone on `https://` or `localhost`, so serve the folder instead of double-clicking the file:

```bash
python -m http.server 8765
```

Then open http://localhost:8765.

## Ads

The banner at the bottom stays hidden until you fill in `ADS = { client, slot }` in `index.html` with your Google AdSense IDs.
