# Textura 🎨🖋️

**Textura** is a **feature-rich ASCII Art Generator** web app that converts your text into creative ASCII artwork. Customize fonts, themes, and export options with an interactive, modern interface.

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)


[![Live Demo](https://img.shields.io/badge/Live%20Demo-Textura-blue?style=for-the-badge)](https://f58igx-kodes.github.io/Textura/)


## Features ✨

### Core Functionality
 **Text to ASCII Art Conversion**
  - Multiple font styles: Block, Bubble, Thin, Bold, Shadow, Digital, Graffiti, Cursive
  - Supports uppercase letters (A–Z) and spaces
  - Multi-line input with proper rendering
 **Export Options**
  - Copy to clipboard ✅
  - Download as `.txt` 💾
  - Export as PNG 🖼️ with customizable colors



### User Interface
 **Responsive Layout**
  - Two-column grid for desktop, single-column for mobile
 **Themes**
  - Dark, Matrix, Cyberpunk, Ocean, Sunset, Neon



### Interactivity
 **Keyboard Shortcuts**
  - `Ctrl + Enter` → Copy
  - `Ctrl + D` → Download TXT
  - `Ctrl + E` → Export PNG
  - `Ctrl + R` → Random Text
  - `Ctrl + Backspace` → Clear All
  - Number keys (1–6) → Switch themes
 **Easter Eggs**
  - Typing `"abdullah"` → Glitch animation
  - Typing `"confetti"` → Confetti animation



### Visual Features
- Multiple background themes with gradients and animations
- Customizable text and background colors for PNG exports
- High-DPI canvas rendering for crisp output
- Accessible design using semantic HTML and high-contrast colors



### Technical Highlights
- JavaScript manages fonts, themes, scale, canvas rendering, clipboard API, keyboard shortcuts, and animations
- CSS uses modern features: `backdrop-filter`, `background-clip: text`, animations, responsive grids
- Optimized for smooth performance with minimal DOM updates



### Extensibility
- Easily add new ASCII fonts or themes
- Modify or extend Easter eggs and animations
- Open for further UI and feature enhancements



### Limitations
- Only supports uppercase letters A–Z and spaces
- Limited to predefined fonts
- Intensive animations (e.g., confetti) may affect performance on low-end devices
