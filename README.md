# bilgesucakir-portfolio

Personal portfolio for Bilgesu Çakır, built as an interactive click-wheel iPod. Browse the
menu with the wheel (or the arrow keys); "Experience" and "Volunteer" drill into sub-menus.

## Stack

Single static `index.html` — no build step, no dependencies to install. Vanilla HTML, CSS
and JavaScript, all inline. Two web fonts load from Google Fonts and tech-stack logos load
from the [devicon](https://github.com/devicons/devicon) CDN; everything else is local.

## Layout

```
index.html          the whole site
images/             used images in the site
files/              mqtt-report.pdf (graduation project report)
```

## Running locally

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server
```

## Deploying

It's a static site — publish the repo root as-is. On a host that asks for a
**publish directory**, use `.`; leave the build command empty.

## Features

- Light / dark theme toggle (top right) — the iPod flips between the silver and black
  classic finishes for contrast
- Keyboard navigation (↑ ↓ to move, Enter to select)
- Responsive down to mobile, where the layout stacks
- `prefers-reduced-motion` respected
