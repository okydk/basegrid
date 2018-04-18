# Basegrid 🛠 [![NPM version](https://badge.fury.io/js/basegrid.svg)](https://www.npmjs.com/package/basegrid) [![](https://data.jsdelivr.com/v1/package/npm/basegrid/badge?style=rounded)](https://www.jsdelivr.com/package/npm/basegrid)

The smallest and most flexible grid-system possible.

Built for the future but usefull in the present (working in all major browsers).

## Features
- Lightweight (0.6KB)
- No dependencies
- Flexible AF
- Dynamic grid attributes
	- gw: Grid width
	- gc: Grid columns
	- gg: Grid gap
- Dynamic section attributes
	- w: Width
	- h: Height
	- x: Column position
	- y: Row position

## Examples
Include css either via CDN or install via NPM.
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/basegrid">
```

Grid samples
```html
// Simple grid
<div class="basegrid"></div>

// Fixed grid (equal width and height)
<div class="basegrid fixed"></div>

// Responsive grid
<div class="basegrid res"></div>
```

Section samples (using fixed grid)
```html
<!-- Fixed grid with  -->
<div class="basegrid">
	<div style="--w:5;">5 columns wide</div>
	<div style="--w:5;--h:5;">And 5 high</div>
	<div style="--w:5;--h:5;--x:3;--y:3;">With fixed position</div>
</div>
```