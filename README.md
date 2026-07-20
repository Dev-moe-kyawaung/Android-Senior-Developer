m# 🚀 Moe Kyaw Aung - Senior Android Developer Portfolio

[![License: MIT](https://img.shields.io/badge/License-MIT-cyan.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![GitHub Pages](https://img.shields.io/badge/Deployed%20on-GitHub%20Pages-00f0ff)](https://dev-moe-kyawaung.github.io/)

> ⭐ **Professional portfolio showcasing 12+ years of Android development expertise**

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Demo](#demo)
- [Screenshots](#screenshots)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Deployment](#deployment)
- [Customization](#customization)
- [Browser Support](#browser-support)
- [Performance](#performance)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🌟 Overview

A modern, cyberpunk-themed portfolio website showcasing my journey as a Senior Android Developer with 12+ years of experience. Built with vanilla HTML, CSS, and JavaScript, featuring particle animations, smooth scrolling, and comprehensive sections highlighting skills, projects, and achievements.

**Live Demo:** [https://dev-moe-kyawaung.github.io/](https://dev-moe-kyawaung.github.io/)

## ✨ Features

### 🎨 Design & UI/UX
- ✅ Cyberpunk/Terminal aesthetic with neon color scheme
- ✅ Dark mode by default with light mode toggle
- ✅ Custom animated cursor
- ✅ Particle.js interactive background
- ✅ Smooth scroll animations and transitions
- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Glassmorphism effects and glowing borders

### 📱 Sections (20+)
1. **Hero Section** - Animated introduction with stats
2. **About Section** - Professional summary with timeline
3. **Skills Section** - Tech stack with progress rings
4. **Apps Collection** - 16 featured Android applications
5. **GitHub Accounts** - 43+ GitHub profile links
6. **Lovable PWA** - 38+ Progressive Web Apps
7. **Email Collection** - 20+ professional email addresses
8. **Burmese Language Support** - Myanmar localization
9. **Certificates** - 82+ verified certificates (9 categories)
10. **FAQ Section** - Common questions accordion
11. **Contact Section** - Form with validation
12. **Footer** - Newsletter, links, social media

### 🚀 Interactive Features
- ✅ Certificate search and filtering system
- ✅ Animated statistics counters
- ✅ FAQ accordion with smooth transitions
- ✅ Email copy-to-clipboard functionality
- ✅ Mobile hamburger menu
- ✅ Back-to-top button
- ✅ Active navigation highlighting
- ✅ Contact form with validation
- ✅ Newsletter subscription
- ✅ Social media integration (16+ platforms)

### 🔧 Technical Features
- ✅ Single-file HTML architecture
- ✅ No build tools required
- ✅ Vanilla JavaScript (no frameworks)
- ✅ CSS custom properties (variables)
- ✅ Semantic HTML5 elements
- ✅ SEO optimized with meta tags
- ✅ WCAG accessibility compliant
- ✅ Fast loading (< 3s on 3G)
- ✅ Optimized for GitHub Pages

## 🎬 Demo

**Live Site:** [https://dev-moe-kyawaung.github.io/](https://dev-moe-kyawaung.github.io/)

### Quick Preview
```bash
# Clone and open
git clone https://github.com/Dev-moe-kyawaung/portfolio.git
cd portfolio
open index.html  # or double-click index.html
```

## 📸 Screenshots

### Desktop View
![Hero Section](https://via.placeholder.com/1200x600/0a0a0a/00f0ff?text=Hero+Section)
![Apps Section](https://via.placeholder.com/1200x600/0a0a0a/ff00ff?text=Apps+Collection)

### Mobile View
![Mobile Menu](https://via.placeholder.com/400x800/0a0a0a/00ff9f?text=Mobile+Menu)

## 🛠️ Technologies

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Custom properties, Grid, Flexbox, Animations
- **JavaScript (ES6+)** - Vanilla JS, Intersection Observer API

### Libraries
- **[Particles.js](https://vincentgarreau.com/particles.js/)** v2.0.0 - Interactive background
- **[Font Awesome](https://fontawesome.com/)** v6.5.1 - Icons
- **[Google Fonts](https://fonts.google.com/)** - JetBrains Mono, Space Grotesk

### Hosting
- **GitHub Pages** - Free static hosting
- **Cloudinary** - Image CDN

## 📦 Installation

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code, Sublime Text, etc.) for customization
- Git (for version control)

### Steps

1. **Clone the repository**
```bash
git clone https://github.com/Dev-moe-kyawaung/portfolio.git
cd portfolio
```

2. **Open in browser**
```bash
# Option 1: Direct open
open index.html

# Option 2: Local server (recommended)
python -m http.server 8000
# Then visit http://localhost:8000

# Option 3: VS Code Live Server
# Install Live Server extension and click "Go Live"
```

3. **Customize content** (optional)
- Edit `index.html` to update personal information
- Modify CSS variables in `:root` for color scheme
- Replace images with your own

## 💻 Usage

### Basic Setup
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Your Portfolio</title>
  <!-- Copy styles from index.html -->
</head>
<body>
  <!-- Copy structure from index.html -->
  <script>
    // Copy JavaScript from index.html
  </script>
</body>
</html>
```

### Customizing Colors
```css
:root {
  /* Change these variables */
  --bg-primary: #0a0a0a;
  --accent-cyan: #00f0ff;
  --accent-magenta: #ff00ff;
  /* ... */
}
```

### Adding New Sections
```html
<section class="section" id="new-section">
  <div class="container">
    <div class="section-header">
      <span class="section-label fade-up">Label</span>
      <h2 class="section-title fade-up">Title</h2>
    </div>
    <!-- Your content -->
  </div>
</section>
```

## 📁 Project Structure

```
portfolio/
├── index.html              # Main HTML file (complete portfolio)
├── README.md              # This file
├── LICENSE                # MIT License
├── .gitignore            # Git ignore rules
├── CONTRIBUTING.md       # Contribution guidelines
├── CHANGELOG.md          # Version history
├── docs/                 # Documentation
│   ├── CUSTOMIZATION.md  # Customization guide
│   └── DEPLOYMENT.md     # Deployment instructions
├── assets/               # Optional: local assets
│   ├── images/          # Profile images
│   ├── icons/           # Favicons
│   └── docs/            # Resume, certificates
└── .github/
    └── workflows/
        └── pages.yml     # GitHub Pages deployment
```

## 🚀 Deployment

### GitHub Pages (Recommended)

1. **Create GitHub repository**
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
git push -u origin main
```

2. **Enable GitHub Pages**
- Go to repository Settings
- Navigate to "Pages" section
- Source: Deploy from branch
- Branch: `main` / `root`
- Click Save

3. **Access your site**
```
https://YOUR_USERNAME.github.io/YOUR_REPO/
```

### Custom Domain (Optional)
```bash
# Add CNAME file
echo "yourdomain.com" > CNAME
git add CNAME
git commit -m "Add custom domain"
git push
```

Then configure DNS:
```
Type    Name    Value
A       @       185.199.108.153
A       @       185.199.109.153
A       @       185.199.110.153
A       @       185.199.111.153
CNAME   www     YOUR_USERNAME.github.io
```

### Alternative Hosting

**Netlify**
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Deploy
netlify deploy --prod
```

**Vercel**
```bash
# Install Vercel CLI
npm install -g vercel

# Deploy
vercel --prod
```

## 🎨 Customization

### Personal Information
Edit these sections in `index.html`:

```html
<!-- Line 200-250: Hero Section -->
<h1 class="hero-title">YOUR NAME</h1>
<h2 class="hero-subtitle">Your Title</h2>

<!-- Line 400-500: About Section -->
<p>Your bio...</p>

<!-- Line 600-1000: Apps Collection -->
<!-- Update project links and descriptions -->
```

### Color Scheme
```css
/* Change theme colors */
:root {
  --accent-cyan: #YOUR_COLOR;
  --accent-magenta: #YOUR_COLOR;
  /* Update all color variables */
}
```

### Images
Replace Cloudinary URLs with your own:
```html
<img src="YOUR_IMAGE_URL" alt="Description">
```

### Social Links
Update URLs in Hero and Footer sections:
```html
<a href="YOUR_GITHUB_URL" target="_blank">
  <i class="fab fa-github"></i>
</a>
```

## 🌐 Browser Support

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 90+ | ✅ Fully Supported |
| Firefox | 88+ | ✅ Fully Supported |
| Safari | 14+ | ✅ Fully Supported |
| Edge | 90+ | ✅ Fully Supported |
| Opera | 76+ | ✅ Fully Supported |
| Mobile Safari | iOS 14+ | ✅ Fully Supported |
| Chrome Mobile | Android 90+ | ✅ Fully Supported |

## ⚡ Performance

### Metrics
- **Lighthouse Score:** 95+
- **First Contentful Paint:** < 1.5s
- **Time to Interactive:** < 3.0s
- **Total Bundle Size:** < 100KB (excluding images)
- **Page Load Time:** < 2s (on 3G)

### Optimization Tips
```html
<!-- Lazy loading images -->
<img src="image.jpg" loading="lazy" alt="Description">

<!-- Preconnect to external resources -->
<link rel="preconnect" href="https://fonts.googleapis.com">

<!-- Defer non-critical JavaScript -->
<script src="script.js" defer></script>
```

## 🤝 Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

### Development Setup
```bash
# Fork the repository
git clone https://github.com/YOUR_USERNAME/portfolio.git

# Create feature branch
git checkout -b feature/amazing-feature

# Make changes and commit
git commit -m "Add amazing feature"

# Push to branch
git push origin feature/amazing-feature

# Open Pull Request
```

### Code Style
- Use semantic HTML5 elements
- Follow BEM naming convention for CSS
- Use ES6+ JavaScript features
- Add comments for complex logic
- Test on multiple browsers

## 📄 License

This project is licensed under the **MIT License** - see [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Moe Kyaw Aung

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction...
```

## 📞 Contact

**Moe Kyaw Aung**  
Senior Android Developer

- 📧 Email: [moekyawaung@programmer.net](mailto:moekyawaung@programmer.net)
- 💼 LinkedIn: [linkedin.com/in/moe-kyaw-aung](https://www.linkedin.com/in/moe-kyaw-aung-2653093a1)
- 🐙 GitHub: [github.com/Dev-moe-kyawaung](https://github.com/Dev-moe-kyawaung)
- 🌐 Website: [moekyawaung.dev](#)
- 📱 Phone: +95 9 889 000 889
- 📍 Location: Tachileik, Myanmar 🇲🇲 | Bangkok, Thailand 🇹🇭

---

## 🙏 Acknowledgments

- [Particles.js](https://vincentgarreau.com/particles.js/) - Vincent Garreau
- [Font Awesome](https://fontawesome.com/) - Icon library
- [Google Fonts](https://fonts.google.com/) - Typography
- [Cloudinary](https://cloudinary.com/) - Image hosting
- [GitHub Pages](https://pages.github.com/) - Free hosting

---

## 📈 Project Stats

![GitHub Stars](https://img.shields.io/github/stars/Dev-moe-kyawaung/portfolio?style=social)
![GitHub Forks](https://img.shields.io/github/forks/Dev-moe-kyawaung/portfolio?style=social)
![GitHub Watchers](https://img.shields.io/github/watchers/Dev-moe-kyawaung/portfolio?style=social)

**Made with ❤️ and ☕ by Moe Kyaw Aung**

---
