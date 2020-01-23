# GOLANG CHIP-8 Emulator

CHIP-8 Emulator writen in GO.

## Base Documentation
[Cowgod's Chip-8 Technical Reference](http://devernay.free.fr/hacks/chip8/C8TECH10.HTM#0.0)

[How to write an emulator (CHIP-8 interpreter) — Multigesture.net](http://www.multigesture.net/articles/how-to-write-an-emulator-chip-8-interpreter/)

[Wikipedia - CHIP-8](https://en.wikipedia.org/wiki/CHIP-8)

## Features
* Pause (Key: P)
* CPU Debug Cycle Firward (Key: [ while paused)

## Requirements
* GO
* go get github.com/faiface/pixel/pixelgl
* go get github.com/faiface/beep
* go get github.com/faiface/beep/mp3
* go get github.com/faiface/beep/speaker

## Usage

	$ go run chip8

## TODO LIST
1. TEST CLOCK PROGRAM
2. WRITE A DESCENT README.md FILE
3. SHOW SLOWNESS WHEN KEYPRESS
4. REVIEW FPS
5. REWRITE GRAPHICS TO JUST DRAW THE DIFFERENCES
6. ADD PAUSE FUNCION
7. TEST IN LINUX AND WINDOWS (JUST TESTED ON MAC)
