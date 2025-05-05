# 🌐 Personal Portfolio Website

Welcome to my personal portfolio website — a modern, responsive, and interactive site built to showcase my skills, projects, and experience as a web developer. This project demonstrates my proficiency in frontend development, UI/UX design, and deployment best practices.

---

## 🚀 Live Demo

## 🔗 [View the live site here](https://alwyn-411.github.io/Portfolio/)

## 🛠️ Technologies Used

| Category       | Tech Stack                        |
| -------------- | --------------------------------- |
| **Frontend**   | Astro, HTML, CSS, JavaScript      |
| **Build Tool** | Vite                              |
| **Deployment** | GitHub Pages (via GitHub Actions) |

---

## 🔑 Key Features

- ✅ Responsive design (mobile-first)
- 🌙 Dark/light mode toggle
- 🎯 Project filtering system
- 🎞️ Smooth animations and transitions
- 🧠 SEO optimization
- ⚡ Performance-focused build with Astro
- 📩 Contact form with email integration (via Formsubmit / Formspree)
- 🌍 Deployed using GitHub Actions to a `prod` branch

---

## 📬 Contact Form

The contact form uses a 3rd-party service (like [Formsubmit](https://formsubmit.co) or [Formspree](https://formspree.io)) to handle form submissions and deliver them to your email — no backend needed.

---

## 🧑‍💻 Sections Overview

- **Hero** — Eye-catching intro with name and call-to-action
- **About Me** — Summary of my background and skills
- **Projects** — Interactive portfolio cards with GitHub and live links
- **Skills** — Technology stack and tools visualized
- **Experience** — Work history and education timeline
- **Contact** — Reach-out form with real-time validation
- **Footer** — Social icons and copyright

---

## ⚙️ Getting Started

### 🧪 Local Development

```bash
# Install dependencies
npm install

# Run in development mode
npm run dev
```

### 🏗️ Build for Production

```bash
npm run build
```

### 🔍 Preview the Production Build

```bash
npm run preview
```

---

## 🚀 Deployment (GitHub Pages via GitHub Actions)

This project is automatically deployed to the `prod` branch using a GitHub Actions workflow.

1. Builds are triggered on pushes to `main`
2. Output in `dist/` is pushed to the `prod` branch
3. GitHub Pages serves the site from the `prod` branch root

Make sure your `astro.config.mjs` has the correct base:

```js
base: '/Portfolio/';
```

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 🙋‍♀️ Want to Collaborate?

Feel free to fork, submit issues, or contribute ideas! Connect with me on [LinkedIn](https://linkedin.com/in/yourprofile) or drop me an email via the contact form.
