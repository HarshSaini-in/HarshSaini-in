# 🚀 Harsh Saini — Personal Portfolio

<div align="center">

![Portfolio Banner](https://img.shields.io/badge/Portfolio-Harsh%20Saini-00f5d4?style=for-the-badge&logo=react&logoColor=white)
![Status](https://img.shields.io/badge/Status-Live-brightgreen?style=for-the-badge)
![Made With](https://img.shields.io/badge/Made%20With-React%20%2B%20Tailwind-b14aed?style=for-the-badge&logo=react)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

**A modern, futuristic personal portfolio website built for a B.Tech CSE (AI & ML) student at NIELIT Ropar.**

[🌐 Live Demo](#) · [🐛 Report Bug](https://github.com/harshsaini/portfolio/issues) · [✨ Request Feature](https://github.com/harshsaini/portfolio/issues)

</div>

---

## 📸 Preview

> *(Add a screenshot here after deployment)*
> `screenshots/preview-dark.png` | `screenshots/preview-light.png`

---

## ✨ Features

- 🌙 **Dark / Light Mode Toggle** — Smooth theme switching with persistent feel
- 🔤 **Typing Animation** — Dynamic hero text cycling through roles
- 🕸️ **Animated Particle Network** — Interactive canvas background
- 📊 **Animated Skill Bars** — Scroll-triggered fill animations
- 🃏 **Project Cards** — Hover glow effects with tech stack tags
- 🐙 **Live GitHub Integration** — Fetches repos & stats via GitHub REST API
- 📱 **Fully Responsive** — Mobile, tablet, and desktop layouts
- 🎓 **Education Timeline** — Visual academic journey
- 🏅 **Certifications Section** — Cisco Python Essentials 1 & 2
- ⚡ **Loading Screen** — Branded entry animation
- 🧭 **Sticky Navbar** — Blur-on-scroll with smooth scroll navigation
- 🔢 **Scroll-triggered Animations** — `IntersectionObserver`-powered reveals

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Framework** | React 18 (JSX) |
| **Styling** | Tailwind CSS + Inline CSS Variables |
| **Fonts** | Syne · Space Mono · Figtree (Google Fonts) |
| **Animations** | CSS Keyframes + IntersectionObserver |
| **Data** | GitHub REST API v3 |
| **Canvas** | HTML5 Canvas (Particle Network) |
| **Icons** | Inline SVG |

---

## 📁 Project Structure

```
portfolio/
├── public/
│   └── index.html
├── src/
│   ├── App.jsx              # Main portfolio component
│   ├── index.js             # React entry point
│   └── index.css            # Global resets (if any)
├── screenshots/
│   ├── preview-dark.png
│   └── preview-light.png
├── .gitignore
├── package.json
└── README.md                # ← You are here
```

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or higher)
- npm or yarn

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/harshsaini/portfolio.git

# 2. Navigate into the project directory
cd portfolio

# 3. Install dependencies
npm install

# 4. Start the development server
npm start
```

The app will open at `http://localhost:3000` 🎉

### Build for Production

```bash
npm run build
```

This creates an optimized production build in the `build/` folder.

---

## ⚙️ Configuration

To personalize this portfolio for yourself, edit the config section at the top of `src/App.jsx`:

```js
// ─── CONFIG ─────────────────────────────────────
const GITHUB_USERNAME = "harshsaini";   // ← Your GitHub username

const TYPING_STRINGS = [
  "Building Smart IoT Systems",          // ← Your roles / taglines
  "Exploring AI & Machine Learning",
  ...
];

const SKILLS = [ ... ];    // ← Update skill names & percentages
const PROJECTS = [ ... ];  // ← Add your own projects
const CERTS = [ ... ];     // ← Your certifications
```

> **Note:** GitHub API has a rate limit of 60 requests/hour for unauthenticated requests. For production, consider adding a GitHub token via environment variables.

---

## 🌐 Deployment

### Deploy on Vercel (Recommended)

```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel
```

### Deploy on GitHub Pages

```bash
# Install gh-pages
npm install --save-dev gh-pages

# Add to package.json scripts:
# "predeploy": "npm run build",
# "deploy": "gh-pages -d build"

npm run deploy
```

### Deploy on Netlify

Just drag and drop your `build/` folder at [netlify.com/drop](https://netlify.com/drop) ✅

---

## 📦 Sections Overview

| Section | Description |
|---------|-------------|
| **Hero** | Name, typing animation, CTA buttons, particle canvas |
| **About** | Bio, info cards, NIELIT Ropar details |
| **Skills** | Animated progress bars — Python, C++, Arduino, ESP32 |
| **Projects** | AI Smart Waste Monitoring System (expandable) |
| **GitHub** | Live repo cards, follower stats via GitHub API |
| **Certifications** | Cisco Python Essentials 1 & 2 |
| **Education** | B.Tech, 12th, 10th timeline |
| **Strengths** | Problem Solver, Fast Learner, Builder, Goal-Oriented |
| **Goal** | "To beat my past self." |
| **Contact** | Email, GitHub, LinkedIn cards |

---

## 🎨 Design Decisions

- **Color Palette:** Deep navy `#040d1a` background · Electric cyan `#00f5d4` primary · Violet `#b14aed` accent
- **Typography:** `Syne` for bold headings, `Space Mono` for code-like labels, `Figtree` for readable body text
- **Theme:** Cyberpunk-meets-clean-tech — futuristic yet professional
- **Motion Philosophy:** Scroll-triggered, purposeful animations — nothing gratuitous

---

## 🤝 Contributing

This is a personal portfolio, but suggestions are always welcome!

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-idea`
3. Commit your changes: `git commit -m 'Add: your feature'`
4. Push to the branch: `git push origin feature/your-idea`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

Feel free to use this as a template for your own portfolio. A credit/star would be appreciated! ⭐

---

## 👤 Author

**Harsh Saini**
- 🎓 B.Tech CSE (AI & ML) — NIELIT Ropar
- 💼 GitHub: [HarshSaini-in]
- 🔗 LinkedIn: [Harsh Saini]
- 📧 Email: harsh.saini13881@gmail.com

---

<div align="center">

Made with ❤️ and a lot of ☕ by **Harsh Saini**

⭐ **Star this repo if you found it helpful!**

</div>
