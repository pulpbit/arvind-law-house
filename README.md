# Arvind Law House - Advocate Website

A premium, high-end static website for **Adv. Arvind R. Singh**, a trusted advocate in Mumbai. Built using **HTML5, Tailwind CSS v4, and Vanilla JavaScript**.

## Features
- **Premium Design**: Deep Navy and Gold theme conveying authority and trust.
- **Tailwind CSS v4**: Modern, high-performance utility-first styling.
- **Responsive**: Fully optimized for Desktop, Tablet, and Mobile devices.
- **Scroll Animations**: Smooth reveal animations using Intersection Observer.
- **Static**: Perfect for hosting on Cloudflare Pages or GitHub Pages.

## Project Structure
```
arvind-law-house/
├── index.html          # Homepage
├── about.html          # About the Advocate
├── practice-areas.html # Detailed Services
├── contact.html        # Contact Info & Form
├── css/
│   └── style.css       # Compiled Tailwind CSS
├── js/
│   └── main.js         # Interactivity & Animations
├── assets/
│   ├── images/         # Photos & Hero Backgrounds
│   └── icons/          # Custom SVGs
├── src/
│   └── input.css       # Tailwind Source File
└── package.json        # Build Scripts
```

## Local Development
1. Clone the repository.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Run the CSS build (one-time):
   ```bash
   npm run build:css
   ```
4. Watch for CSS changes during development:
   ```bash
   npm run watch:css
   ```
5. Open `index.html` in your browser.

## Deployment to Cloudflare Pages
1. Push your code to a GitHub/GitLab repository.
2. Connect the repository to Cloudflare Pages.
3. Set the **Build Command**: `npm run build:css`
4. Set the **Output Directory**: `.` (root) or move everything to a `dist` if preferred.
5. Deploy!

## Credits
- **Advocate**: Adv. Arvind R. Singh
- **Design & Code**: Built with Antigravity (Google DeepMind)
