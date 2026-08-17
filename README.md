# Quantum-Cosmos-Portfolio
# ✦ Quantum Cosmos Portfolio

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/yourusername/quantum-portfolio)](https://github.com/yourusername/quantum-portfolio/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/yourusername/quantum-portfolio)](https://github.com/yourusername/quantum-portfolio/network)
[![GitHub issues](https://img.shields.io/github/issues/yourusername/quantum-portfolio)](https://github.com/yourusername/quantum-portfolio/issues)

A premium, audio-reactive portfolio website with smooth scrolling, 3D orbital animations, and immersive particle effects. Built with pure HTML, CSS, and JavaScript.

![Portfolio Preview](https://via.placeholder.com/1200x600/0c0f17/c9a96e?text=Quantum+Cosmos+Portfolio)

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎵 **Audio-Reactive** | Real-time music visualization |
| 🖱️ **Lenis Smooth Scroll** | Buttery smooth scrolling experience |
| 🌌 **Interactive Particles** | Dynamic star background |
| 🎨 **Custom Cursor** | Premium interactive cursor |
| 📊 **Orbital Skills** | Rotating skill solar system |
| 🏗️ **Filterable Projects** | Web, AI, and 3D categories |
| 📱 **Fully Responsive** | Mobile-friendly design |
| 🚀 **High Performance** | Optimized for speed (95+ Lighthouse) |

---

## 🚀 Quick Start

### Option 1: GitHub Pages (အလွယ်ဆုံး)

1. **Fork** ဒီ repository
2. **Settings** → **Pages** သွားပါ
3. **Source** မှာ `main` branch ရွေးပါ
4. **Save** နှိပ်ပါ
5. သင့် site အသင့်! 🎉

```
https://yourusername.github.io/quantum-portfolio
```

### Option 2: Local Development

```bash
# Clone repository
git clone https://github.com/yourusername/quantum-portfolio.git

# Enter directory
cd quantum-portfolio

# Start local server (choose one)
python -m http.server 8000
# or
npx serve
# or
php -S localhost:8000
```

### Option 3: GitLab Pages

1. Repository ကို GitLab မှာ import လုပ်ပါ
2. **Settings** → **Pages** သွားပါ
3. Source မှာ `main` branch root (`/`) ရွေးပါ
4. **Save** နှိပ်ပါ

```
https://yourusername.gitlab.io/quantum-portfolio
```

---

## 🎨 Customization Guide

### Color Scheme ပြောင်းရန်

`index.html` ထဲက `:root` ကို ပြင်ပါ:

```css
:root {
    --gold: #c9a96e;      /* Primary accent */
    --cyan: #64ffb8;      /* Secondary accent */
    --purple: #b790ff;    /* Tertiary accent */
    --bg: #05060a;        /* Background */
}
```

### Content ပြောင်းရန်

| Section | File | Location |
|---------|------|----------|
| Hero | `index.html` | Line ~200 |
| About | `index.html` | Line ~400 |
| Projects | `index.html` | Line ~500 |
| Skills | `index.html` | Line ~600 |
| Experience | `index.html` | Line ~700 |
| Blog | `index.html` | Line ~900 |
| Contact | `index.html` | Line ~1000 |

### Audio Files ပြောင်းရန်

`initializeAudioSystem()` function ထဲက:

```javascript
const sounds = [
    'https://your-audio-1.mp3',
    'https://your-audio-2.mp3',
    'https://your-audio-3.mp3'
];
```

### Social Links ပြောင်းရန်

Footer ထဲက:
```html
<a href="https://github.com/yourusername">
<a href="https://twitter.com/yourusername">
<a href="https://linkedin.com/in/yourusername">
```

---

## 📁 Project Structure

```
├── index.html          # Main portfolio file
├── README.md          # This documentation
├── LICENSE           # MIT License
├── .gitignore       # Git ignore rules
├── SECURITY.md      # Security policy
├── robots.txt       # SEO rules
├── CNAME           # Custom domain (optional)
├── _config.yml     # GitHub Pages config
├── .gitlab-ci.yml  # GitLab CI/CD config
├── vercel.json     # Vercel deployment config
├── deploy.sh       # Deployment script
└── package.json    # npm config
```

---

## 🛠️ Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom properties & animations
- **JavaScript** - ES6+, Canvas API, Web Audio API
- **Lenis** - Smooth scrolling library
- **AOS** - Scroll animation library
- **Font Awesome** - Icons
- **Space Grotesk** - Typography

---

## 📱 Browser Support

| Browser | Version |
|---------|---------|
| Chrome | 60+ ✅ |
| Firefox | 55+ ✅ |
| Safari | 12+ ✅ |
| Edge | 79+ ✅ |
| Opera | 47+ ✅ |

---

## 🚀 Deployment Platforms

### Vercel
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/yourusername/quantum-portfolio)

### Netlify
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/yourusername/quantum-portfolio)

---

## 🤝 Contributing

1. Fork it (https://github.com/yourusername/quantum-portfolio/fork)
2. Create feature branch (`git checkout -b feature/amazing`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push branch (`git push origin feature/amazing`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

**Your Name**

- GitHub: [@yourusername](https://github.com/yourusername)
- LinkedIn: [your-linkedin](https://linkedin.com/in/yourprofile)
- Twitter: [@yourtwitter](https://twitter.com/yourtwitter)
- Website: [quantum.dev](https://yourwebsite.com)

---

## 🙏 Acknowledgements

- [Lenis](https://github.com/darkroomengineering/lenis) - Smooth scrolling
- [AOS](https://michalsnik.github.io/aos/) - Scroll animations
- [Font Awesome](https://fontawesome.com/) - Icons
- [Space Grotesk](https://fonts.google.com/specimen/Space+Grotesk) - Typography

---

## 📊 Star History

[![Star History Chart](https://api.star-history.com/svg?repos=yourusername/quantum-portfolio&type=Date)](https://star-history.com/#yourusername/quantum-portfolio&Date)

---

<p align="center">
  Made with ❤️ by <a href="https://github.com/yourusername">Your Name</a>
</p>
```
