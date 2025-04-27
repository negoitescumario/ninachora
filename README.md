# ninachora

`ninachora` is a simple graphical terminal client for drawing pixel-art written in Lua.
Inspired by [pxltrm](https://github.com/dylanaraps/pxltrm).

![example SVG](./example.svg)

<sup>SVG image created with ninachora</sup>

![screenshot](./screenshot.jpg)

The same image, opened in ninachora.

# Usage

## Starting

```
$ ninachora [name]
```

Where '[name]' is the name of the file you want to edit.

## Controls

Movement uses BNPF keys, as in Emacs.

* B - Go left
* N - Go down
* P - Go up
* F - Go right

The rest is also quite simple.

* I - Insert a pixel
* O - take Out a pixel
* C - Choose a color (1-8)
* S - Save
* E - Export
* Q - Quit (will ask if unsaved)

# Others

## Supported formats

As of right now, ninachora supports exporting to SVG and X PixMaps (.xpm).
Only ninachora files (.nc) can be opened for (re)editing.

## Name origin

From Swahili 'ninachora', which means 'to draw'.
