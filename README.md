# Hypertrace

[Open the live reader](https://hypertrace-r04.gener8or.chatgpt.site)

Hypertrace displays live Boosted remote inputs alongside an interactive enclosure. Rotate the housing, change its finish, or connect a compatible remote to watch the thumbwheel and trigger readings.

## Run locally

From this directory, run `python3 -m http.server 8000 --bind 127.0.0.1 --directory dist` and open [localhost:8000](http://localhost:8000). Use a Bluetooth-capable desktop browser such as Chrome or Edge for pairing. The housing viewer also works without a remote.

## Edit and host

The editable HTML, CSS, JavaScript, and embedded Three.js viewer are in `dist/index.html`. The enclosure model, motion limits, and fonts are bundled under `dist/`. Serve that directory as a static site over HTTPS for Bluetooth use. GitHub pushes do not automatically update the live ChatGPT Site.

Third-party font licenses are included in `dist/fonts/`. The embedded Three.js license is in the HTML source.
