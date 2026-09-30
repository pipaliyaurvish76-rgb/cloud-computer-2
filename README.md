# Cloud Computing Website

## Description
A complete, modern, responsive, and professional educational and informational static website about Cloud Computing. Built with HTML5, CSS3, and Vanilla JavaScript. Features a premium SaaS-style interface with a dark/light mode toggle, smooth scrolling, and custom SVG animations.

## Features
- **Premium Modern Design**: SaaS-style interface with glassmorphism elements, custom gradients, and a sleek layout.
- **Dark/Light Mode**: User-selectable theme with `localStorage` persistence.
- **Fully Responsive**: Mobile-first design that looks great on all device sizes.
- **Smooth Animations**: Reveal animations on scroll, hover effects, and animated statistics.
- **Custom Illustrations**: Built entirely with CSS and inline SVGs—no external image assets required for core design.
- **Interactive Elements**: FAQ accordion, responsive navigation, service cards, and a mock contact form.
- **SEO & Accessibility**: Semantic HTML, ARIA attributes, optimal contrast, and basic SEO meta tags included.
- **GitHub Pages Ready**: Uses relative paths, completely static, requiring no backend.

## Technology Stack
- **HTML5**: Semantic structure.
- **CSS3**: Variables, Flexbox, CSS Grid, media queries, keyframe animations, glassmorphism.
- **Vanilla JavaScript**: DOM manipulation, event listeners, form validation, localStorage theme saving, intersection observers.

## Project Structure
```text
cloud-computing/
│
├── index.html          # Main homepage containing all sections
├── 404.html            # Custom error page
├── README.md           # Project documentation
├── robots.txt          # SEO configuration
├── sitemap.xml         # Basic sitemap
├── favicon.svg         # Scalable vector favicon
│
└── assets/
    ├── css/
    │   └── style.css   # Main stylesheet
    │
    ├── js/
    │   └── script.js   # Main JavaScript file
    │
    ├── images/         # Directory for additional images (if needed)
    │
    └── icons/          # Directory for custom icons
```

## How to Run Locally
1. Clone this repository or download the ZIP file.
2. Extract the contents (if downloaded as ZIP).
3. Open `index.html` directly in any modern web browser.
4. (Optional) For a better experience, serve it using a local development server like VS Code Live Server or Python's `http.server`:
   ```bash
   python -m http.server 8000
   ```
   Then navigate to `http://localhost:8000` in your browser.

## How to Publish on GitHub Pages

Follow these steps to host the website for free on GitHub Pages:

### Git Commands
```bash
git init
git add .
git commit -m "Initial Cloud Computing Website"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```

### GitHub Pages Instructions
1. Go to your repository on GitHub.
2. Click on **Settings** (the gear icon).
3. In the left sidebar, click on **Pages**.
4. Under "Build and deployment", select **Deploy from a branch** as the source.
5. Under "Branch", select the **main** branch and the **/(root)** folder.
6. Click **Save**.
7. Wait a few minutes. GitHub will display a message with the URL to your live site (e.g., `https://username.github.io/cloud-computing/`).

## Author
Created for educational and demonstration purposes.
