# 🌐 Shreepoorna Purohit — Personal Portfolio

A modern, responsive developer portfolio built with vanilla HTML, CSS, and JavaScript. Features animated particle backgrounds, glassmorphism design, dark/light mode, scroll-driven animations, and a typing effect hero section.

**Live:** [shreepoorna1903.github.io](https://shreepoorna1903.github.io)

![Dark Mode](https://img.shields.io/badge/theme-dark%20%2F%20light-8b5cf6)
![GitHub Pages](https://img.shields.io/badge/deployed-GitHub%20Pages-06b6d4)

---

## ✨ Features

- **Interactive Particle Canvas** — Mouse-reactive particle network rendered on an HTML5 canvas with dynamic connection lines
- **Dark / Light Mode** — Toggle with system preference detection and `localStorage` persistence
- **Typing Animation** — Rotating hero text cycling through focus areas (AI/ML, NLP, Cloud Systems, Deep Learning)
- **Scroll Animations** — Intersection Observer-powered reveal effects with staggered delays
- **3D Tilt Cards** — Perspective-based mouse-tracking tilt on project cards
- **Active Nav Indicator** — Sliding highlight that tracks the current viewport section
- **Scroll Progress Bar** — Fixed gradient bar indicating page scroll position
- **Fully Responsive** — Adapts across desktop, tablet, and mobile breakpoints

## 🛠 Tech Stack

| Layer     | Technology                          |
|-----------|-------------------------------------|
| Markup    | Semantic HTML5                      |
| Styling   | CSS3 (custom properties, gradients, glassmorphism, grid/flexbox) |
| Scripts   | Vanilla JavaScript (no frameworks)  |
| Hosting   | GitHub Pages                        |

## 📂 Project Structure

```
Shreepoorna1903.github.io/
├── index.html          # Single-page application (markup + styles + scripts)
├── resume/
│   └── Shreepoorna_Resume_AiML.pdf
└── README.md
```

## 🚀 Getting Started

### View Live

Visit [shreepoorna1903.github.io](https://shreepoorna1903.github.io).

### Run Locally

```bash
git clone https://github.com/Shreepoorna1903/Shreepoorna1903.github.io.git
cd Shreepoorna1903.github.io
# Open index.html in any browser, or use a local server:
python3 -m http.server 8000
```

Then navigate to `http://localhost:8000`.

## 🎨 Customization

The site uses CSS custom properties for easy theming. Edit the `:root` and `[data-theme="light"]` blocks in `index.html` to adjust colors:

```css
:root {
  --accent: #8b5cf6;   /* Primary accent (violet) */
  --accent2: #06b6d4;  /* Secondary accent (cyan) */
  --accent3: #22c55e;  /* Tertiary accent (green) */
  --bg: #09090b;       /* Background */
}
```

Particle count, connection distance, and mouse interaction radius can be tuned in the JavaScript section at the bottom of `index.html`.

## 📄 Sections

| Section    | Description                                             |
|------------|---------------------------------------------------------|
| Hero       | Introduction, stats, quick profile sidebar              |
| Education  | Northeastern University (M.S. CS) and PES University (B.Tech ECE) |
| Experience | IBM Cloud SDE-2, IBM Intern, PthinkS Intern            |
| Projects   | FinBERT stock sentiment, BERT NER probing, melanoma CNN |
| Skills     | Languages, ML frameworks, cloud/DevOps tooling          |
| Contact    | Email, phone, LinkedIn, GitHub                          |

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

## 📬 Contact

- **Email:** purohit.shr@northeastern.edu
- **LinkedIn:** [shreepoorna-dp-870737192](https://www.linkedin.com/in/shreepoorna-dp-870737192)
- **GitHub:** [Shreepoorna1903](https://github.com/Shreepoorna1903)
