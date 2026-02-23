# [Nonograms](https://vlmna13.github.io/nonograms)

A fully playable nonogram (picross) puzzle game in the browser — built with vanilla JavaScript and ES Modules.

## Gameplay

Fill in a grid by following the numeric clues along rows and columns. Left-click to fill a cell, right-click to mark it with a cross. Solve the puzzle before time runs out.

## Features

- **Dynamic grid rendering** — rows and columns generated from a matrix definition; clues calculated and rendered automatically
- **Left-click / right-click controls** — fill or cross-mark individual cells
- **Multiple difficulty levels** — Easy, Medium, Hard; each with several puzzle variants
- **Timer** — tracks minutes and seconds during active gameplay
- **Top-5 leaderboard** — stores best results (level, variant, time) across sessions using `localStorage`
- **Mute toggle** — switch sound effects on/off
- **Sound effects** — distinct audio for fill, cross, leaves, and win (MP3 via Web Audio)
- **Save & restore** — game state persisted in `localStorage`, restored on next visit
- **Win modal** — congratulates the player and shows the scoreboard on puzzle completion

## Tech Stack

| | |
|---|---|
| Markup | HTML5 |
| Styles | CSS3 |
| Logic | Vanilla JavaScript, ES Modules |
| Audio | MP3 files played via `HTMLAudioElement` |
| Storage | `localStorage` |


## Gameplay

Fill in a grid by following the numeric clues along rows and columns. Left-click to fill a cell, right-click to mark it with a cross.

## Features

- **Dynamic grid rendering** — rows and columns generated from a matrix definition; clues calculated and rendered automatically
- **Left-click / right-click controls** — fill or cross-mark individual cells
- **Multiple difficulty levels** — Easy, Medium, Hard; each with several puzzle variants
- **Timer** — tracks minutes and seconds during active gameplay
- **Top-5 leaderboard** — stores best results (level, variant, time) across sessions using `localStorage`
- **Mute toggle** — switch sound effects on/off
- **Sound effects** — distinct audio for fill, cross, leaves, and win (MP3 via Web Audio)
- **Save & restore** — game state persisted in `localStorage`, restored on next visit
- **Win modal** — congratulates the player and shows the scoreboard on puzzle completion

## Tech Stack

| | |
|---|---|
| Markup | HTML5 |
| Styles | CSS3 |
| Logic | Vanilla JavaScript, ES Modules |
| Audio | MP3 files played via `HTMLAudioElement` |
| Storage | `localStorage` |
