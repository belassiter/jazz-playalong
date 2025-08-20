# Shed It!

**Shed It!** is a web-based jazz play-along tool designed for musicians to practice improvisation and learn chord progressions. It was created by Brian Einstein Lassiter.

This tool runs entirely in your web browser. Just open the `shedit.html` file to get started.

## Features

*   **Multiple Progressions**: Practice over a variety of standard and generated chord progressions, including:
    *   12-Bar Blues & Bird Blues
    *   Rhythm Changes
    *   Major and Minor `ii-V-I`s
    *   Modal tunes
    *   Standard tunes like "Take the A-Train"
    *   Cycle exercises like Descending `ii-V-I`s and Descending 7ths
    *   Randomly generated progressions (Diatonic and Advanced)
*   **Full Key Control**: Play any progression in all 12 concert keys.
*   **Instrument Transposition**: The chord display can be transposed for B♭, E♭, F, and G instruments.
*   **Tempo & Volume Control**: Easily adjust the tempo (from 40 to 400 BPM) and master volume.
*   **Virtual Backing Band**:
    *   **Piano**: Plays chord voicings with varied rhythms.
    *   **Bass**: Generates a walking bassline that outlines the harmony.
    *   **Drums**: Provides a steady swing beat with kick, snare, ride, and hi-hat.
*   **Track Muting**: Isolate instruments by muting the piano, bass, or drums tracks individually.
*   **Real-time Chord Highlighting**: The user interface displays the full progression and highlights the current chord as it plays, making it easy to follow along.

## How to Use

1.  **Open the File**: Open the `shedit.html` file in a modern web browser (like Chrome, Firefox, or Safari).
2.  **Load Samples**: The "Play" button will be disabled and read "Loading Samples..." until the audio files are ready. This should only take a moment.
3.  **Select a Progression**: Use the "Progression" dropdown to choose the chord changes you want to practice.
4.  **Set the Key & Transposition**:
    *   Choose the **Concert Key** for the tune.
    *   If you play a transposing instrument, select it from the **Transposition** dropdown to see the chords written correctly for you.
5.  **Adjust Settings**:
    *   Use the **Tempo** slider to set your desired speed.
    *   Use the **Volume** slider to control the overall output level.
6.  **Play and Stop**:
    *   Click the **Play** button to start the backing track.
    *   The button will turn into a **Stop** button while playing.
7.  **Mute Tracks**: Click the "Piano", "Bass", or "Drums" buttons to mute or unmute them. The button turns red when a track is muted.

## Technical Details

*   **Frontend**: The application is a single HTML file built with vanilla JavaScript.
*   **Styling**: The user interface is styled using **Tailwind CSS**.
*   **Web Audio**: Audio scheduling, synthesis, and sample playback are handled by **Tone.js**.
*   **Audio Samples**:
    *   Piano samples are from the Salamander Grand Piano set provided by the Tone.js examples.
    *   Bass and Cymbal samples are hosted at `belassiter.com`.

## License

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

![CC BY-NC-SA License](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-nc-sa.svg)
