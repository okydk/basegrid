# Basegrid 🛠 [![NPM version](https://badge.fury.io/js/basegrid.svg)](http://badge.fury.io/js/basegrid) [![GitHub version](https://badge.fury.io/gh/basegrid.svg)](http://badge.fury.io/gh/basegrid)
Dynamic CSS-grid built for the future but usefull in the present (working in all major browsers).

## Features
- Lightweight (< 0.5KB)
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

## Get started
Include css ```https://unpkg.com/basegrid```

Create grid and set attributes (either via css files og directly)
```html
// Include css
<link rel="stylesheet" href="https://unpkg.com/basegrid">
// Create one or more grids
<div class="basegrid">
	<div style="--w:6">6 columns wide</div>
	<div style="--w:6">6 columns wide</div>
	<div style="--w:4">4 columns wide</div>
	<div style="--w:4">4 columns wide</div>
	<div style="--w:4">4 columns wide</div>
</div>
```

## Building
Install ```parcel``` and run ```yarn build```
