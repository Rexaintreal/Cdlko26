<div align="center">

# Lubunut
### A custom Linux distro built for playing (and hacking on) Mario2, made at CodeDay Lucknow 2026

</div>

---

## What is this?

This started as Mario2, a small Mario style platformer built for ArcadeAI YSWS. For CodeDay Lucknow 2026 we took it further: we built our own custom Linux distro to run it on, themed it with custom icons, and got it working with a hardware gamepad.

This repo has two halves:
- **`Game/`**, the Mario2 platformer itself
- **`lubunut/`**, our custom Linux distro (built as a VirtualBox VM) plus custom desktop assets

---

## Team

Built at CodeDay Lucknow 2026 by:
- **Aniruddh**
- **Atharv Shukla**, [@Atharv-Shukla-987](https://github.com/Atharv-Shukla-987)
- **Yuvraj**
- **Saurabh Tiwari**, [@rexaintreal](https://github.com/rexaintreal)

Custom icons and extra assets made with help from the CodeDay crew, thank you!

---

## What we built at CodeDay

- **Custom Linux distro (lubunut)**, packaged as a VirtualBox VM (`lubunut.vbox` / `.vdi`), set up so Mario2 boots and runs on it directly.
- **Custom desktop icons**, replaced the default Firefox, Recycle Bin, Terminal, and VLC icons with our own designs.
- **Hardware gamepad support**, got a physical gamepad working with the game so you can play with a controller instead of the keyboard.
- **Continued work on the game itself**, carried over all the earlier additions like assets, sound, powerups, and the boss fight.

---

## Mario2, the game

No frameworks or libraries used. Just HTML, CSS, and vanilla JavaScript, with everything rendered using the Canvas 2D API.

### Features
- Real sprite assets for the player, enemies, and tiles
- Sound effects and background music
- A longer level with more platforms, pipes, and pits
- A powerup that gives Mario temporary invincibility
- A sword used to fight the final boss
- Particle effects for jumping, coin pickup, and attacking
- A boss fight against an ender dragon
- Improved start, game over, and win screens plus an in-game HUD
- Gamepad support, new for CodeDay

---

## Folder structure

```
assets/               custom distro icons (firefox, recycle bin, terminal, vlc)
Game/                 the Mario2 platformer
  assets/             player, dragon, tiles, coin, powerup images, etc.
  music/              sound effects and background music
  screenshots/        dev log screenshots
  game.js
  index.html
  style.css
lubunut/              our custom Linux distro
  Logs/
  lubunut.vbox
  lubunut.vbox-prev
  lubunut.vdi
README.md
```
