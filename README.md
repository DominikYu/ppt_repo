# MCT Pitch Deck

An interactive 15-slide HTML pitch deck for **Vidhance MCT (Multi-Camera Toolbox)** — a multi-camera calibration and video processing solution.

## What's Inside

| File | Description |
|---|---|
| `index.html` | 15-slide interactive pitch deck (GSAP-animated) |
| `mct2.0.mp4` | MCT 2.0 hero demo (9.0 MB) |
| `comparison.mp4` | Before/after stabilization comparison (5.1 MB) |
| `far.mp4` | Far-field capture demo (3.8 MB) |
| `near.mp4` | Near-field capture demo (2.4 MB) |
| `outdoor_c.mp4` | Outdoor capture demo (5.3 MB) |
| `indoor_c_.mp4` | Indoor capture demo (2.3 MB) |
| `vidhance-mct-outdoor.mp4` | Outdoor Vidhance MCT sample (4.3 MB) |
| `vidhance-mct-indoor.mp4` | Indoor Vidhance MCT sample (1.8 MB) |

All videos compressed with `ffmpeg -c:v libx264 -crf 28 -preset slow -movflags +faststart`.

## Usage

Serve via any static file server or GitHub Pages:

```bash
python3 -m http.server 8000
# or
npx serve .
```

Then open `http://localhost:8000`.

## Tech Stack

- Vanilla HTML/CSS/JS
- GSAP 3.12.5 for slide transitions
- Fonts: Space Grotesk (headings), DM Sans (body)

## Details

- 15 slides covering problem, solution, product demo, technical architecture, team, and ask
- Responsive 16:9 layout, keyboard navigation (←/→), dot indicators
- Deployed to GitHub Pages for easy viewing
