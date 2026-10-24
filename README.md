# Bas3line Racket Finder

A phone-friendly app for Bas3line ambassadors and coaches. Three questions recommend a racket, with specs to show the player.

## What's in this folder

All files sit at the top level of the repository.

- `index.html`: the whole app (questions, decision matrix and racket details)
- `.webp`, `.svg` and `.png` files: racket photos, front page artwork, logo and home-screen icons
- `.woff` and `.woff2` files: Obviously web fonts
- `manifest.webmanifest`: lets the app be added to a phone's home screen

## Making changes

Open `index.html` in GitHub (click the file, then the pencil icon).

- **Prices, specs or descriptions:** edit the `RACKETS` section near the top of the script.
- **Recommendations:** edit the `MATRIX` section. `A` is the no-injury path (level|style) and `B` is the some-pain path (level|injury type).
- **New racket photo:** upload a portrait image using the racket's id as the name, replacing the old one (for example `vega.webp`).

Commit the change, and the live app updates within a minute or two.
