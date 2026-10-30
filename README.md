# Yashas & Nithina wedding invitation

This is a static website. It has no build step or package installation.

## Deploy to Netlify

1. In Netlify, create a new site using this project folder (or connect its Git repository).
2. Set the publish directory to `.`. Leave the build command empty.
3. Deploy.

The root `netlify.toml` already sets the publish directory. The main page is `index.html`.

The temple film is bundled locally as `assets/temple-film.mp4`, with `assets/temple-poster.jpg` as its poster. The fonts load from Google Fonts and fall back to system fonts if that service is unavailable.
