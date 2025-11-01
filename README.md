# 🔲 Modal Window Component

A lightweight, reusable modal window system built with  HTML, CSS, and JavaScript. Smooth animations, multiple modal support, and accessibility baked in—no libraries required.

## Live Demo

Check it out here: [Live Demo](https://zayynabz.github.io/modal/)

## 📁 Project Structure

```
modal/
├── index.html              # Demo page with multiple modal examples
├── style.css               # Modal-specific styles and animations
├── script.js               # Modal functionality and event handling
└── README.md               # This documentation
```

## 🚀 Quick Start

Open `index.html` in your browser — no install, no build, no hassle.

**From PowerShell on Windows:**
```powershell
Start-Process 'C:\path\to\modal\index.html'
```

**From terminal (Mac/Linux):**
```bash
open modal/index.html
```

Everything runs entirely client-side — no dependencies.

## ✨ Features

### 🎭 Multiple Modal Support
- Independent modals with unique content
- Clean separation between modal instances
- Flexible targeting system

### 🎬 Smooth Animations
- Elegant slide-down & fade transitions
- CSS-powered performance
- Fully customizable timing & easing

### 🖱️ Flexible Interaction
- **Close button** (×) in header
- **Click outside model** to dismiss
- **Overlay background** dimmed for focus

### ♿ Accessibility-First
- Focus management
- Semantic HTML structure
- Keyboard-friendly controls

### 🎨 Fully Customizable
- Responsive layout
- Clean, modern styling
- Easy to theme or tweak



## 🌐 Browser Compatibility

- **Chrome** 15+
- **Firefox** 3.5+
- **Safari** 6.1+
- **Edge** 12+
- **IE** 11 (with polyfills)

## 📱 Responsive Behavior

- **Desktop**: Centered, fixed width
- **Tablet**: Adaptive padding & margins
- **Mobile**: Full-width modals with safe-area aware

## 🐛 Troubleshooting

**❌ Modal doesn't open?**
- Check console for JavaScript errors
- Verify `data-target` matches modal ID
- Ensure CSS and JS files are properly linked

**❌ Animation not working?**
- Confirm CSS transitions are supported
- Check for conflicting CSS rules

**❌ Overlay not appearing?**
- Verify `#overlay` element exists
- Check z-index values

## 🚀 Performance Notes

- **Lightweight**: ~2KB minified CSS + JS
- **Efficient**: Event delegation reduces memory usage
- **Fast**: CSS transforms for smooth animations

## 🤝 Contributing

Love improvements? Pull requests welcome! Suggestions:
- Accessibility enhancements
- Extra animation options
- Mobile gesture support
- Theme customization


## 📄 License

This project is licensed under the MIT License.

---

**Next Up**: Draggable Todo App coming soon! 🚀

❤️ **Made with love: Zaynab**