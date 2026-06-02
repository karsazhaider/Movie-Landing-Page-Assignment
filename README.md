[README.md.md](https://github.com/user-attachments/files/28499901/README.md.md)
# QuickShow - Movie Streaming & Ticket Booking Platform

QuickShow is a modern, dark-themed, fully responsive frontend web interface designed for movie exploration and theater ticket booking. It features a polished user experience built with clean semantic structures and pure CSS interactive overlays.

---

## 🚀 Key Features & UI Systems

* **Thematic Dark UI System**: Built on a premium `#0b0f19` dark palette using clean, modern typography fallback chains (`Segoe UI`).
* **Overlay Navigation Bar**: Features an absolute-positioned top header utilizing a soft vertical linear-gradient backdrop, a flex-based layout configuration, custom logo handling, and hover-responsive active link colorization.
* **Cinematic Hero Module**: Showcases marquee content using background cover textures paired with a multi-stop color gradient to keep typography readable. Includes custom logo rendering rules and dedicated action buttons.
* **Pure CSS Audio/Video Triggers**: Interactive video play elements designed without image dependencies. Uses clever CSS pseudo-elements (`::after`) to generate zero-latency vector play triangles that shift scales and colors seamlessly on hover events.
* **Responsive Fluid Grid**: An adaptive structural grid utilizing CSS `grid-template-columns` with media query configurations (`repeat(auto-fit, minmax(220px, 1fr))`) to dynamically rearrange layout flows on tablet devices.
* **Trailers Integration Hub**: Houses an immersive widescreen preview area (max-width `960px`) accompanied by a flexible thumbnail row displaying semi-transparent active states (`opacity: 0.6`).
* **Enterprise Footer Infrastructure**: Designed with flexible multi-column wrapper distributions (`flex-wrap`) providing store badge hover acceleration transitions, legal directories, and unified copyright boundaries.

---

## 📂 Project Architecture

```text
├── index.html                  # Core markup file containing semantic elements
├── style.css                   # Master stylesheet (Reset, Components, Media Queries)
├── icon.png                    # Brand platform primary logo graphic
├── search.svg                  # Global navigation lookup asset
├── marvelLogo.svg              # Promotional vector element for hero section
├── google-play.png             # Application marketplace redirection link asset
├── app-store.png               # Application marketplace redirection link asset
└── [images]/                   # UI backing textures and dynamic preview thumbnails:
                                # - wp1814934.jpg (Hero/Showcase background)
                                # - wp9049770 1.png, wp4926059 1.png, etc.
