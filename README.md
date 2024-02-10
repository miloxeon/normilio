# 😮 Normilio
The modern, pragmatic normalize. It focuses on new browser features and improving the UX rather than making outdated browsers render things more predictable.

**Do choose this** if you want your UX improved and really only support more or less modern browsers.

If you support IE6, Android 4.0.4, Opera Mini and other things like this, it's a good idea to pick [Normalize.css](https://github.com/necolas/normalize.css) instead.

## What it does?

1. Removes the default margin from `body`
2. Sets `box-sizing` to `border-box` for all elements including pseudos
3. Sets `backface-visibility` to `hidden` to prevent typefaces from turning blurry with `transform` properties in old browsers
4. Ensures that `[hidden]` elements will be hidden
5. Enables some ligatures but not all of them
6. Optimizes typeface smoothing and legibility
7. Sets the system UI typeface as the default
8. Turns images into blocks so text wraps above and below them
9. Prevents images from being resized more than their actual size
10. Makes HTML fully responsive by default: images, canvases, tables and other less usual tags
11. Sets a monospace font and tabs of width 4 for `code` and `pre`
12. Only let users resize `textarea`s vertically
13. Makes the typeface in `input`s the same as the typeface on your website itself
14. Uses appropriate cursor based on aria-attributes
