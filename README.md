# Misty's Website

A tiny 3-page website. Page 1 looks like an old army video game character
select screen. Picking the wrong character sends you to a "GAME OVER"
page. Picking the right one takes you to a pink GeoCities-style fan page
for a cat named Misty. No JavaScript, just HTML and CSS.

## Files

```
index.html          <- page 1, character select
gameover.html        <- shown if you pick SOLDIER or GENERAL
misty.html            <- Misty's homepage
style-military.css    <- styles for page 1 and gameover.html
style-misty.css        <- styles for misty.html
images/                <- all photos and the game-over video
images/gifs/            <- the spinning/blinking GeoCities gifs on the sides of misty.html
```

## How it works

- Open `index.html` in any web browser to start.
- Hover over a character to see it light up.
- Click "SOLDIER" or "GENERAL" and you get sent to `gameover.html`.
- Click "KJ" and it jumps straight to `misty.html`.

## Adding your own photos

Drop your images into the `images` folder using these exact names:

- `soldier.png`, `general.png`, `kj.png` — the three character portraits (background removed, so use a transparent PNG)
- `bg-military.jpg` — background photo on the character select page
- `cat1.jpg`, `cat2.jpg`, `cat3.jpg`, `cat4.jpg` — photos of Misty
- `cat-with-me.jpg` — the featured photo shown in the middle of the grid
- `gameover.mp4` — video shown on the game-over page

Then just refresh the page in your browser, no other steps needed.

## Putting it online

This is a static site, so you can upload the whole folder as-is to any
free host (GitHub Pages, Netlify, Vercel, etc.) and it will just work.
