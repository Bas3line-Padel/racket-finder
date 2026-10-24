# Bas3line Racket Finder

A phone-friendly app for Bas3line ambassadors and coaches. Three questions recommend a racket, with specs to show the player.

## What's in this folder

- `index.html`: the whole app (questions, decision matrix and racket details)
- `images/`: logo, home-screen icons and racket photos
- `fonts/`: Obviously web fonts
- `manifest.webmanifest`: lets the app be added to a phone's home screen

## Making changes

Open `index.html` in GitHub (click the file, then the pencil icon).

- **Prices, specs or descriptions:** edit the `RACKETS` section near the top of the script.
- **Recommendations:** edit the `MATRIX` section. `A` is the no-injury path (level|style) and `B` is the some-pain path (level|injury type).
- **New racket photo:** upload a portrait image to `images/rackets/` using the racket's id as the name (for example `vega.webp`).

Commit the change, and the live app updates within a minute or two.
