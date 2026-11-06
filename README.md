# Rajawat Family Wedding Invitation & Interactive Web Experience

A high-fidelity, interactive wedding invitation web experience featuring playful animations, GSAP scroll-triggered choreography, 3D object frame sequences, and 100% visual and animation parity across desktop, tablet, and mobile devices.

---

## 🌟 Highlights

- **Loading Screen & Preloader:**
  Custom rounded handwritten typography displaying:
  > *"THE RAJAWAT FAMILY HAS A WEDDING TO HOST"*
  with smooth percentage progression and seamless header transition.

- **Minimal Header Section:**
  Clean, balanced header featuring the signature sentence that gracefully transitions out upon scrolling.

- **Hero Section:**
  Animated entrance text:
  > *"And you, dear guest, have a very important date with us"*
  with 15 floating 3D peanuts and autonomous physics.

- **100% Mobile & Desktop Visual Parity:**
  - Full Webflow IX3 animations enabled across all screen widths (`<=991px`, `<=767px`, `<=479px`).
  - 120-frame 3D rotating Lemon Pepper package sequence (`#hero-canvas`) unified across all devices.
  - Interactive multi-flavor sticky scroll slider (`KIMCHI`, `CHICKEN`, `BUFFALO`, `PEPPER`).
  - 6-tab horizontal expanding/collapsing accordion with floating 3D icons.
  - 3D card flip testimonial sequence (`rotateY(180deg)`) and 4-card Scandal Pages grid.
  - Complete 3-column footer navigation and character badge.

- **Continuous Vertical PDF Invitation Card:**
  Includes [`invitation.html`](./invitation.html) — an elegant, long-format vertical printable wedding invitation card with pure white background, regal typography, gold/earthy accents, and multi-section itinerary.

---

## 🚀 Local Development

To run the project locally:

```bash
# Start a local HTTP server
python3 -m http.server 8080

# Open in browser:
# Interactive Website:
http://localhost:8080/henrietta.wearetattoodigital.com/index.html

# Vertical PDF Invitation Card:
http://localhost:8080/invitation.html
```

---

## 📁 Repository Structure

```text
├── invitation.html                     # Long vertical PDF-style invitation card
├── henrietta.wearetattoodigital.com/   # Main website root
│   └── index.html                      # Interactive wedding experience
├── cdn.prod.website-files.com/         # Localized Webflow CSS, JS & media assets
├── cdn.jsdelivr.net/                   # Lenis smooth scrolling library
├── fonts.googleapis.com/               # Web font definitions
└── fonts.gstatic.com/                  # Static font binaries
```

---

## 📜 License

Created for the Rajawat Family Wedding. All rights reserved.
