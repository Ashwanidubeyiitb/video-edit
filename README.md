# 🎓 Reel — College Memory Studio

A beautiful web app for applying cinematic filters and compressing videos, built for making college farewell videos.

## Features

### 🎬 Cinematic Filters
- 8 presets: Dreamy Glow, Shutter Blur, Film Grain, Golden Hour, Cinematic, Slow Dream, All Combined, Muted Lux
- Live preview with real-time CSS filters
- 10 adjustable sliders: Brightness, Contrast, Saturation, Warmth, Dreamy Blur, Vignette, Hue Shift, Film Grain, Fade, Speed
- Upload multiple videos and apply same settings to all
- Generates FFmpeg commands for actual processing

### 📦 Video Compression
- H.265 / H.264 codec selection
- Quality presets: Lossless → High → Balanced → Small
- Resolution options: Original, 1080p, 720p, 480p
- Batch compress multiple videos at once
- Generates Google Colab commands

### 📓 Colab Notebooks
- Download ready-to-run `.ipynb` notebooks
- Filters notebook with all 8 effects
- Compression notebook with H.265

## Deploy to GitHub Pages

1. Create a new GitHub repository
2. Upload `index.html` to the repo
3. Go to **Settings → Pages**
4. Set source to **main branch / root**
5. Your site is live at `https://yourusername.github.io/repo-name`

## Local Use

Just open `index.html` in any browser — no server needed.

## How it works

This is a pure HTML/CSS/JS single-file app. No dependencies, no build step.

- **Preview**: Uses CSS filters for real-time visual preview
- **Processing**: Generates FFmpeg commands → run in Google Colab or terminal
- **Compression**: Generates batch FFmpeg commands for H.265 encoding
