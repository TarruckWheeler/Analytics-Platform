# NEXUS Analytics Platform — Professional Edition (HTML Single‑File)

A self‑contained analytics dashboard that showcases network graphs (D3),  
interactive maps (Leaflet), timelines (Chart.js) and a lightweight AI assistant (TensorFlow JS fallback).  
Everything is packed into **one HTML file**—no build tools or server‑side code are required.

![screenshot](https://user-images.githubusercontent.com/placeholder/nexus-screenshot.png)

---

## ✨ Features
| Category                | Highlights                                                                   |
|-------------------------|-------------------------------------------------------------------------------|
| **Visualisation**       | D3 force‑directed network graph, Leaflet map, Chart.js timeline               |
| **AI Layer**            | Toy TensorFlow‑JS model + conversational helper                              |
| **Responsive UI**       | CSS Grid layout adapts at 1200 px and 768 px break‑points                     |
| **Security First**      | Strict CSP header, X‑Frame‑Options, Referrer‑Policy, X‑Content‑Type‑Options   |
| **No Build Step**       | One static file — perfect for GitHub Pages or any static host                 |

---

## 🚀 Quick Start
```bash
# 1 — clone
git clone https://github.com/<your‑handle>/nexus-analytics-professional.git
cd nexus-analytics-professional

# 2 — run (any static server or just open the file)
python -m http.server 8080  # then visit http://localhost:8080/index.html
# OR
open index.html             # double‑click on most OSs
