# 😮 Normilio
The pragmatic normalize. It only does what you really need.

## What it does?

1. Removes margin from `body`
2. Sets `box-sizing` to `border-box` for all elements including pseudos
3. Sets `line-height` to `1.5` for all elements so you don't have to worry about inline blocks' vertical alignment and other quirks
4. Sets `backface-visibility` to `hidden` to prevent typefaces from turning blurry with `transform` properties in old browsers
5. Ensures that `[hidden]` elements will be hidden
6. Enables some ligatures but not all of them
7. Optimizes typeface smoothing and legibility
8. Sets the system typeface as the default
9. Turns images to blocks
10. Prevents images from being resized more than their actual size
11. Makes HTML fully responsive by default: images, canvases, tables and other quirky tags
12. Sets `cursor` to `pointer` for all interactive elements

## Usage
```HTML
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/uyouthe/normilio/normilio.min.css">
```
