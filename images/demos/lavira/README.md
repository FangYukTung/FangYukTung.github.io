# LaViRA — Real-Robot Demos

Drop your demo files **into this folder** and they will appear automatically on the
LaViRA publication page, under the **"Real-Robot Demos"** heading:

    https://fangyuktung.github.io/publication/2025-09-16-lavira

## How it works

The publication page (`_publications/2025-09-16-lavira.md`) loops over every file
in this folder and renders it. **No code changes needed** — just add files here.

- **Videos** (`.mp4`, `.webm`) → rendered as an inline `<video>` player (loop + muted).
- **Images / GIFs** (`.gif`, `.png`, `.jpg`, `.jpeg`) → rendered as an inline image.
- Files are shown in **alphabetical order** of filename — name them `01-...`, `02-...`
  to control the order.

## Tips

- Keep file sizes small (ideally a few MB each, < 20 MB) so the page loads fast and
  the git repo stays lean. For `.mp4`, H.264 + `faststart` plays everywhere.
- This README (`.md`) and any non-media files are ignored by the display loop.
