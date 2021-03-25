# Conways Game of Life (in TIC-80)

Just a quick and messy implementation of conway's game of life. Initial pattern is random.

<img src="cover.gif" style="width:100%;image-rendering: pixelated;">

Might be interesting to re-make it and keep some interactive stuff.

## Notes
- a one-dimensional array to store the grid was much faster, but introduced wrapping around on the sides. Proper game of life implementations use an infinite plane instead.
- First version ran at only 3 frames as second but after optimisation and removing interactive features this now runs at 35-ish.