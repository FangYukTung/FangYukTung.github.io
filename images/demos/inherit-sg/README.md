# INHerit-SG — Real-Robot Demos

Drop your demo files **into this folder** and they will appear automatically on the
INHerit-SG publication page, under the **"Real-Robot Demos"** heading:

    https://fangyuktung.github.io/publication/2026-02-07-inherit-sg

## How it works

The publication page (`_publications/2026-02-07-inherit-sg.md`) loops over every file
in this folder and renders it. **No code changes needed** — just add files here.

- **Videos** (`.mp4`, `.webm`) → rendered as an inline `<video>` player (autoplay-friendly: loop + muted).
- **Images / GIFs** (`.gif`, `.png`, `.jpg`, `.jpeg`) → rendered as an inline image.
- Files are shown in **alphabetical order** of filename, so name them e.g. `01-...`, `02-...`
  to control the order.

## Tips

- Recommended: 1–2 short clips (a few seconds each) showing the robot in action.
- Keep file sizes reasonable (ideally < 10–20 MB each) so the page loads fast.
  For `.mp4`, H.264 + `faststart` plays everywhere. GIFs get large quickly — prefer `.mp4`.
- This README (`.md`) and any non-media files are ignored by the display loop.
