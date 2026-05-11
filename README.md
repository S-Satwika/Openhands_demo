# 🎨 Modern Portfolio Website

A responsive personal portfolio website with dark mode, glassmorphism UI, and smooth animations.

![Portfolio Preview](https://via.placeholder.com/1200x600/0a0a0f/6366f1?text=Portfolio+Preview)

## ✨ Features

- **Dark Mode** - Elegant dark theme by default
- **Glassmorphism** - Frosted glass UI elements
- **Animated Background** - Floating gradient orbs
- **Typing Animation** - Rotating text in hero section
- **Scroll Reveal** - Elements animate on scroll
- **Responsive** - Works on mobile, tablet, and desktop
- **Smooth Scrolling** - Navigation clicks smoothly scroll to sections
- **Contact Form** - Ready for form backend integration

## 📁 Project Structure

```
portfolio/
├── index.html    # Main HTML file
├── style.css    # Styles (dark theme, animations, responsive)
├── script.js   # Interactivity (typing, scroll, navigation)
└── README.md   # This file
```

## 🚀 Quick Start

### Option 1: Open Directly

```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

### Option 2: Local Server (Recommended)

```bash
# Python
python3 -m http.server 8000

# Then open http://localhost:8000
```

```bash
# Node.js (if installed)
npx serve .

# Then open http://localhost:3000
```

### Option 3: VS Code

1. Install "Live Server" extension
2. Right-click index.html → "Open with Live Server"

## 🎯 Sections

| Section | Description |
|---------|------------|
| Home | Hero with typing animation, code block |
| About | Bio, stats (5+ years, 50+ projects) |
| Skills | 18 technologies in 3 categories |
| Projects | 6 project cards with links |
| Experience | 4-item professional timeline |
| Contact | Form with social links |

## 🎨 Customization

### Change Name
Edit `index.html` - replace "Alex Morgan" with your name

### Change Colors
Edit `style.css` - modify CSS variables:
```css
:root {
    --accent-primary: #6366f1;  /* Change accent color */
    --bg-primary: #0a0a0f;    /* Change background */
}
```

### Add Projects
Copy/paste `project-card` sections in index.html

### Connect Form
Integrate with [Formspree](https://formspree.io) or [EmailJS](https://www.emailjs.com)

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)

## 📝 License

MIT License - Feel free to use for your own portfolio!

## 🤝 Credits

- [Google Fonts](https://fonts.google.com) - Outfit & Space Mono
- [Font Awesome](https://fontawesome.com) - Icons