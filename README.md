# Bhuntu

A self-contained mobile browser game with five challenges, ten personal photos, your dramatic tmro Buda, and an original synthesized soundtrack.

## Play

Open `index.html` in a modern browser, or upload it as the homepage of your website and open the resulting link on a phone. The game itself, photos, graphics, and music need no external files or network connection after the page is loaded. The optional artist song buttons open external websites.

Tap **Get my surprise** to begin. Watch the rules for each challenge, use **A tiny hint** when needed, and choose **A little more time** for gentler timings. Completed chapters save in the same browser when browser storage is available. The music starts after a tap; the header sound button turns it on or off.

## Publish this folder

The homepage is `index.html`. Include the supplied `.nojekyll` file when publishing this folder with GitHub Pages. No build step, package installation, or assets folder is required.

## Rebuild from the editable source

The modular version remains in `outputs/dashain-love-quest`. From the workspace, run:

```sh
node work/build-standalone.mjs
```

The builder embeds the latest source and validates the generated JavaScript before writing this folder.
