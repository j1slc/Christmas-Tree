<p align="center">
  <img src="christmas-tree-logo.svg" alt="Christmas Tree logo" width="160">
</p>

<h1 align="center">Christmas Tree</h1>

<p align="center">
  A 3D Christmas tree built out of text characters, drawn live on a canvas, with music.
</p>

<p align="center">
  <a href="https://j1slc.github.io/Christmas-Tree/"><strong>Live demo</strong></a>
</p>

---

## About

A rotating Christmas tree made entirely of ASCII characters (`%`, `@`, `#`, `o`, `+`, `-` ...). The scene is a 3D point cloud that is projected onto a character grid every frame and drawn on an HTML `<canvas>`.

The animation builds the tree from scratch: a snowy ground ring appears first, then the trunk, the needles layer by layer, the garland, the gifts, the lights, and finally the star on top. After about 20 seconds it loops.

Everything lives in a single HTML file. There are no dependencies, no build step and no external requests. The audio is embedded in the file.

## Usage

1. Open the page and press the **play** button in the middle of the screen.
2. Use the speaker button in the top-left corner to mute or unmute the sound.

Browsers block autoplay, so the music only starts after the first click.

## Browser support

Works in current versions of Chrome, Edge, Brave, Firefox and Safari. Mobile browsers are supported too.

## Credits

Original animation by **Jio**. This version adds the full-screen background, the extended ground, the repositioned counters, the mute button, the animated tab title and the logo.
