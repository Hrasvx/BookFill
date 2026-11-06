<h1 align="center">
BookFill Minecraft Exploit
</h1>
  <p align="center">
  <img src="preview.png" width="300">
</p>

**Client-side** Fabric mod

Check out the [BookFill Minecraft Exploit Website](https://bookfill.hrasvx.dev/) for a tutorial. 
[![minecraft version: 1.21.8](https://img.shields.io/badge/minecraft_version-1.21.8-92B780.svg?style=flat-square)](https://github.com/prettier/prettier)
 
## What it does

- `/bookfill <filename>` — reads `config/bookfill/<filename>.txt` and types
  it into the Book and Quill you're holding,
  splitting it into pages automatically. Book stays editable (not signed).

- `/bookfill maxpages <n>` — change it (1–5000). Persists across restarts
  in `config/bookfill/bookfill.properties`. **singleplayer.**

## Raised per-page character limit

A `BookEditScreen` mixin raises the vanilla 1023-character-per-page cap in
the book editor to 32,000, so typing or pasting past the old limit works
in the GUI itself.

## Usage

Put your `.txt` file(s) in `.minecraft/config/bookfill/`, e.g.
   `.minecraft/config/bookfill/example.txt`.
In-game: hold an empty Book and Quill, run `/bookfill example`.

This exploit mostly uses ai generated code!!
