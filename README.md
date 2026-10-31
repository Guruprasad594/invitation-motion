# Anushree & Balakrishna wedding invitation

This is a static website. It has no build step or package installation.

## Celebration details

- Mehendi: Friday, 13 November 2026
- Wedding: Sunday, 15 November 2026 at 11:51
- Wedding venue: R. N. Shetty Hall, Kundapura

## Deploy to Netlify

1. In Netlify, create a new site using this project folder (or connect its Git repository).
2. Set the publish directory to `.`. Leave the build command empty.
3. Deploy.

The root `netlify.toml` already sets the publish directory. The main page is `index.html`.

The temple film and wedding background music are bundled locally as `assets/temple-film.mp4` and `assets/wedding-bgm.mp3`. The page requests music autoplay on load; guests can also start or pause it with the on-page music button. The fonts load from Google Fonts and fall back to system fonts if that service is unavailable.
