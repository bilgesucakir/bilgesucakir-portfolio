# bilgesucakir-portfolio

Personal portfolio for Bilgesu Çakır, built as an interactive click-wheel iPod. Browse the
menu with the wheel (or the arrow keys).

## Stack

Single static `index.html` — no build step, no dependencies to install. Vanilla HTML, CSS
and JavaScript, all inline.

## Layout

```
index.html          the whole site
images/             used images in the site
files/              used files in the site
```

## Running locally

Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server
```

## Deploying

It's a static site — publish the repo root as-is. On a host that asks for a
**publish directory**, use `.`; leave the build command empty.
