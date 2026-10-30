# thesis-video

Supplementary videos for the PhD thesis of Edoardo Forti, served with GitHub Pages at
<https://edforti.github.io/thesis-video/>.

- `videos/` — MP4 files (remuxed with `+faststart` for web streaming) and poster frames
- `<slug>/index.html` — one page per video (the target of each QR code in the thesis)
- `latex/thesis_videos.tex` — LaTeX macro `\thesisvideo{<slug>}{<caption>}` for Overleaf
- `build.py` — regenerates pages and LaTeX snippet; edit titles/descriptions there
