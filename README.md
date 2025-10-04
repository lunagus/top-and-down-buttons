# Top and Down Buttons

A modern, optimized userscript that adds smooth scroll-to-top and scroll-to-bottom buttons to every webpage.

## Installation

1. Install a userscript manager:
   - [Tampermonkey](https://www.tampermonkey.net/) (Chrome, Firefox, Safari, Edge)
   - [Violentmonkey](https://violentmonkey.github.io/) (Chrome, Firefox, Edge)
   - [Greasemonkey](https://www.greasespot.net/) (Firefox)

2. [Click here to install the userscript](https://github.com/lunagus/top-and-down-buttons/raw/refs/heads/main/top-and-down-buttons.user.js) or manually copy the code 

## Usage

### Scroll Buttons

Two buttons will appear on the right side of your screen when viewing scrollable pages:

- **Up Button** (bottom-right) - Scrolls to the top of the page
- **Down Button** (top-right) - Scrolls to the bottom of the page

### Interactions

- **Click** - Smoothly scrolls to top/bottom with easing animation
- **Hover** - Continuously scrolls while your mouse is over the button
- **Auto-hide** - Buttons disappear when you're already at the top/bottom

## Configuration

You can easily customize the script by modifying the `CONFIG` object:

```javascript
const CONFIG = {
    speedClick: 500,        // Smooth scroll duration on click (ms)
    speedHover: 100,        // Continuous scroll speed on hover (ms)
    zIndex: 1001,           // Z-index for buttons
    scrollStep: 1,          // Pixels to scroll per interval on hover
    hideThreshold: 0        // Scroll position to show/hide buttons
};
```

### Customization Examples

**Faster scrolling on click:**
```javascript
speedClick: 300  // Change from 500 to 300
```

**Slower continuous scrolling:**
```javascript
speedHover: 150  // Change from 100 to 150
```

**Larger scroll steps:**
```javascript
scrollStep: 3    // Change from 1 to 3
```

## Icons

Icons are from [SVGRepo](https://www.svgrepo.com/) (CC0 License):
- [Arrow Up Square](https://www.svgrepo.com/show/437449/arrow-up-square.svg)
- [Arrow Down Square](https://www.svgrepo.com/show/437402/arrow-down-square.svg)

## Support

If you encounter any issues or have suggestions, please [open an issue](https://github.com/lunagus/top-and-down-buttons/issues) on GitHub.

---
