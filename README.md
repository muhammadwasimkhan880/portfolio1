# Muhammad Wasim Khan - Modern Portfolio

An ultra-modern, high-performance personal portfolio website engineered for **Muhammad Wasim Khan**, Frontend Developer & UI Specialist.

Built with semantic HTML5, modern CSS3 (Custom Properties & Glassmorphism), and zero-dependency Vanilla JavaScript for instantaneous performance, fluid responsiveness, and high Core Web Vitals.

---

## 🚀 Features

- **Modern Dark & Light Themes**: Sleek dark mode with neon cyan and purple accents by default, with an instant one-click light theme switch persisted to `localStorage`.
- **Dynamic Typewriter Hero**: Smooth headline typewriter cycling through roles and specialties.
- **Interactive 3D Avatar Tilt**: Physics-based 3D tilt interaction reacting to mouse movements.
- **Filterable Skills & Tech Stack**: Interactive category filtering across Frontend Core, Frameworks, Styling & Motion, and Tools, complete with animated proficiency bars.
- **Featured Projects Showcase**:
  - Filter by category (`All`, `React Apps`, `UI & Dashboards`, `Landing Pages`).
  - Interactive project detail modal with case studies, architecture notes, live demo links, and GitHub links.
  - Crisp, scalable SVG mockup previews.
- **Career Journey Timeline**: Milestone progression showing roles, achievements, and education.
- **Interactive Contact Section**:
  - Functional contact form with client-side validation and toast celebration.
  - One-click "Copy Email to Clipboard" button.
  - Direct social & networking channels.
- **Delightful Micro-interactions**:
  - Scroll progress bar at top of viewport.
  - Active navigation spy highlighting current section.
  - Ambient mouse spotlight glow tracking.
  - Smooth mobile navigation drawer.

---

## 📁 File Structure

```
c:\protfolio\
├── index.html                  # Main semantic HTML5 markup
├── css/
│   └── style.css               # Design tokens, themes, typography & responsive layouts
├── js/
│   └── main.js                 # Zero-dependency interactive scripts & modal manager
├── assets/
│   └── images/
│       ├── avatar.jpg          # Generated 3D developer avatar portrait
│       ├── project-novacraft.svg
│       ├── project-aurastore.svg
│       ├── project-devpulse.svg
│       ├── project-zenith.svg
│       ├── project-cryptosphere.svg
│       └── project-motionflow.svg
└── README.md                   # Documentation & customization guide
```

---

## 💻 How to View & Preview

### Option 1: Direct File Open (Zero Setup)
Simply double-click `index.html` to open it immediately in Google Chrome, Microsoft Edge, Brave, Firefox, or Safari.

### Option 2: Local Python Server
Run the built-in Python web server in your terminal:

```bash
python -m http.server 8000
```

Then visit:
```
http://localhost:8000
```

---

## 🛠️ How to Customize

1. **Personal Information**:
   - Open `index.html` and search for `wasimkhan.dev@example.com` or social URLs to replace them with your live links.
2. **Projects**:
   - Update `projectsData` in `js/main.js` to modify descriptions, tech tags, or repository URLs.
3. **Avatar**:
   - Replace `assets/images/avatar.jpg` with your own photo at any time.

---

## 🌐 Free 1-Click Deployment

- **GitHub Pages**: Push this folder to a GitHub repository, head to **Settings > Pages**, choose the `main` branch, and save.
- **Netlify / Vercel**: Drag and drop the `protfolio` folder into Netlify Drop or import the repository in Vercel.
