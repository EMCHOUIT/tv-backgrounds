# tv-backgrounds

Islamic and Arab-Islamic culture photos used as background images by my Android TV screensaver and home screen ([UrTV](https://github.com/tshi-dev/UrTV), patched to read its photos from here).

- `photos/index.json`: the list the TV downloads. One entry per photo: `f` file name, `c` credit shown on the screen, `d` how much of the photo is kept (the rest is dimmed so the clock and cards stay readable; 1 = not dimmed).
- `photos/*.jpg`: the photos, 1920 px wide.
- `CREDITS.md`: author, licence and original page of each photo.

## Licences
The photos come from [Wikimedia Commons](https://commons.wikimedia.org/) and keep their own licences (mostly CC BY-SA 3.0/4.0, a few CC BY, CC0 or public domain), listed in `CREDITS.md`. Reusing a photo needs the author's credit and, for CC BY-SA, the same licence for derived works.

## Add or remove a photo
Put a JPEG (letters, digits, `_` and `-` in the name) in `photos/`, add its line to `photos/index.json` and to `CREDITS.md`. The TV refreshes the list once a day.
