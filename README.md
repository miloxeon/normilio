# 😮 Normilio
The modern, pragmatic normalize. It focuses on new browser features and improving the UX rather than making outdated browsers render things more predictably.

**Do choose this** if you want your UX improved and really only support modern browsers. Everything past 2016 will 100% work fine.

If you support IE6, Android 4.0.4, Opera Mini and other things like this, it's a good idea to pick [Normalize.css](https://github.com/necolas/normalize.css) instead.

## What does it do?

1. Removes the default margin from `body`
2. Sets `box-sizing` to `border-box` for all elements including pseudos
3. Sets `backface-visibility` to `hidden` to prevent typefaces from turning blurry with `transform` properties
4. Ensures that `[hidden]` elements will be hidden
5. Enables some ligatures but not all of them
6. Optimizes typeface smoothing and legibility
7. Sets the system UI typeface as [the default](https://systemfontstack.com)
8. Turns images into blocks
9. Prevents images from being resized further than their actual size
10. Makes HTML fully responsive by default: images, canvases, tables and several other tags
11. Sets a monospace font and tabs of width 4 for `code` and `pre`
12. Only let users resize `textarea`s vertically
13. Makes `input`s inherit their parent typeface
14. Uses appropriate cursors based on aria attributes.
