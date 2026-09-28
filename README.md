# Modern Minimalist Student Portfolio

A modern, high-performance personal portfolio website built with **100% Pure HTML5 & CSS3** (Strictly Zero JavaScript).

---

## ✨ Key Features

- **Pure CSS Dark / Light Mode Switch:** Instant theme switching powered by `:root:has(#theme-toggle:checked)` and CSS Custom Properties.
- **Pure CSS Mobile Navigation Drawer:** Fully functional responsive drawer that transforms the hamburger icon without a single line of JS.
- **Interactive Project Cards:** Hover elevation, subtle gradient headers, tech stack tags, and direct GitHub/Demo action buttons.
- **Recruiter-Optimized Information Flow:**
  - Live pulsing availability badge (*"Actively Seeking 2026 Internships & New Grad Roles"*).
  - Education card with degree details, GPA/Honors, and categorized coursework chips.
  - 4-column Technical Competencies matrix (Languages, Frameworks, Tools, CS Fundamentals).
  - Vertical milestone timeline for internships, teaching assistantships, and hackathons.
  - Dual contact section (direct mailto/LinkedIn/GitHub cards + accessible pure HTML contact form).
- **100/100 Lighthouse Ready:** Zero runtime script overhead, semantic HTML5 tags, and accessible contrast ratios.

---

## 📁 Project Structure

```text
portfolio/
├── PRD.md                  # Complete product requirements specification
├── README.md               # Quick-start documentation
├── index.html              # Main semantic HTML document
├── css/
│   └── style.css           # Consolidated stylesheet (tokens, theme switcher, layout, components)
└── assets/
    └── resume.pdf          # Place your PDF resume here
```

---

## 🚀 How to Run Locally

You don't need Node.js, Python, or any bundler! Simply open [`index.html`](index.html) in your browser:

1. Double-click [`index.html`](index.html) in File Explorer, or
2. Right-click and choose **Open with > Google Chrome** (or your favorite browser).

Or serve it with any static server:
```bash
# Optional: using Python 3
python -m http.server 8000
```
Then navigate to `http://localhost:8000`.

---

## 🎨 Customization Checklist

1. **Personal Information:** Open [`index.html`](index.html) and search for `Alex Chen` to replace with your name, university, email, and social links.
2. **Resume:** Place your resume PDF inside `assets/resume.pdf` (or update the `href` in the hero button).
3. **Projects:** Update the 3 project cards with your own projects, GitHub URLs, and demo links.
4. **Contact Form:**
   - To receive real emails from the contact form without a backend, sign up for free at [Formspree](https://formspree.io) or [Web3Forms](https://web3forms.com).
   - Replace `action="https://formspree.io/f/sample"` in `index.html` with your Formspree endpoint URL.

---

## 🌐 Deploy to GitHub Pages (Free)

1. Initialize git and commit:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio release"
   ```
2. Push to a new GitHub repository named `<your-username>.github.io` or `portfolio`.
3. In GitHub, navigate to **Settings > Pages** and select `main` branch root (`/`).
4. Your site will be live instantly with a free SSL certificate!
