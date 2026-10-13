# Color Beats

Draw a picture or upload one, and Color Beats turns its colors into a song.

## How it works
1. Every pixel's hex code is matched to the closest of 12 named colors.
2. Each color is an instrument (Red = Kick Drum, Blue = Piano, Skin Tone #FFDBAC = Hand Clap, and so on).
3. The picture is read left to right as 4 bars of music. Higher colors play higher notes.
4. Music rules (one key, a pentatonic melody, a chord progression, and groove-snapped drums) keep it sounding good.

## Song settings
- **Genre:** Pop, Rock, Hip-Hop, EDM, Jazz, or Hot Garbage (no rules, every color plays exactly where it is).
- **Song size:** 2, 4, 8, or 16 bars. Bigger songs read the picture in more, thinner slices.

Everything lives in a single `index.html` file with no build step. Open it in a browser, or turn on GitHub Pages for this repo.
