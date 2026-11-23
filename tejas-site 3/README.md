# Tejas Vanjari — personal website

**Live site: https://vanjaritejas.github.io**

I'm an AI master's student at Northeastern University in Boston. I build computer vision that detects, tracks and counts, and I test it where it breaks: overlapping fish, low sun and crowded frames. I'm open to Spring 2027 co-ops in applied AI and machine learning.

## What's on the site

- **Hero video** I filmed myself: two rowing eights racing toward the camera on the Charles River. Desktops get a 2160 × 1216 version (the full width my 4K camera recorded) and phones get the full vertical frame at 1080 × 1920.
- **Live edge detection under the cursor.** Moving the mouse over the video paints a Sobel edge map of the current frame, computed in your browser on a 640 × 360 copy of each frame.
- **Selected work:** counting river herring (Northeastern × MIT Sea Grant), lane and object detection, visual question answering, and my YouTube channel.
- **Numbers from my projects**, a contact form that opens your email app, light and dark mode, and reduced-motion support.

## Built with

Plain HTML, CSS and JavaScript in a single `index.html`, with [Lenis](https://github.com/darkroomengineering/lenis) for smooth scrolling and the Onest font. No build step, hosted on GitHub Pages.

## Files

| Path | Contents |
|---|---|
| `index.html` | The whole site |
| `video/` | Hero videos (wide 2160p, wide 1080p for slow connections, vertical 1080p for phones) and their first-frame posters |
| `images/` | Project images |
| `og-image.jpg` | Picture shown when the link is shared |
| `favicon.svg` | Tab icon |

## Run it locally

```
python3 -m http.server 8000
```

Then open http://localhost:8000. (The edge-detection effect needs the page to be served, not opened as a file.)

## Contact

[Vanjari.t@northeastern.edu](mailto:Vanjari.t@northeastern.edu) · [LinkedIn](https://www.linkedin.com/in/tejas-vanjari-p) · [YouTube](https://www.youtube.com/@32tejasvanjari87)

---

© 2026 Tejas Vanjari. All rights reserved. The photos, video and writing are my own.
