# Puasa Landing

This repository is a static landing page for the Puasa macOS menu bar app.

## How It Works

- `index.html` contains the landing page markup, metadata, and styling.
- `AppIcon.svg` is the favicon/app icon asset.
- `og-image.svg` is the current Open Graph image source.
- The page presents Puasa as a Ramadan fasting tracker for macOS with sahur, berbuka, imsak, and countdown information.

## Run

Open `index.html` in a browser, or serve the folder with any static web server.

```sh
python3 -m http.server
```

## Test

No automated test command was found.

## Notes

- The Git status currently shows a deleted `og-image.png`; verify whether that file was intentionally replaced by `og-image.svg`.
- `.DS_Store` is a local macOS artifact and should not be committed.
