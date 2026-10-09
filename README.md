# Task 3: CSS Units, Box Model, Fonts

TuteDude MERN Stack course, HTML and CSS assignment. Built with plain HTML and CSS only.

## Files
- `index.html` - page structure: image container, image, and "Click Me" button
- `style.css` - all styling
- `README.md` - this file

## How to run
1. Keep `index.html` and `style.css` in the same folder.
2. Double-click `index.html` to open it in a browser (or use VS Code Live Server).
3. An internet connection is needed because the image loads from a URL.

## Layout approach
- `body` uses `padding: 10vh 25vw` with `box-sizing: border-box`, so the padding is
  included in its `100vh` height and the page never scrolls.
- `.image-container` fills the body's content box (50vw x 80vh) and has a 1px black border.
- The image takes 80% of the container height and the button the remaining 20%.
- The button uses a `linear-gradient(to right, ...)` background-image from yellow-orange to green.

## Constraints followed
- No Flexbox
- No `position: relative` or `absolute`
- No `overflow: hidden`
- No CSS frameworks
- Viewport units (`vw`, `vh`) used for spacing and font size