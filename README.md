# Matrix Digital Rain

A mesmerizing recreation of the iconic "digital rain" effect from The Matrix movie, built with vanilla HTML5 Canvas and JavaScript.

## ✨ Features

- **Authentic Matrix Effect**: Falling green characters that recreate the movie's iconic digital rain
- **Mixed Character Set**: Combines Japanese Katakana characters with ASCII letters and numbers
- **Smooth Animation**: 30fps animation with trailing effects for realistic appearance
- **Responsive Design**: Automatically adapts to any screen size
- **Lightweight**: Pure vanilla JavaScript with no dependencies
- **Performance Optimized**: Efficient canvas rendering for smooth performance

## 📁 Project Structure

```
matrix-digital-rain/
├── matrix.html          # Main HTML file with embedded CSS and JavaScript
├── README.md           # Project documentation
├── LICENSE             # MIT License
└── preview.gif         # Demo preview image
```

## 🎮 Usage

### Option 1: Direct Download
1. Download the `matrix.html` file
2. Open it in any modern web browser
3. Enjoy the Matrix effect!

### Option 2: Clone Repository
```bash
git clone https://github.com/yourusername/matrix-digital-rain.git
cd matrix-digital-rain
open matrix.html
```

### Option 3: Serve Locally
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (with http-server)
npx http-server

# Then open http://localhost:8000/matrix.html
```

## ⚙️ Customization

You can easily customize the effect by modifying these variables in the JavaScript section:

```javascript
// Font size (affects column width and character size)
const fontSize = 18;

// Character sets used in the animation
const katakana = "アイウエオカキクケコサシスセソタチツテトナニヌネノハヒフヘホマミムメモヤユヨラリルレロワヲン";
const ascii = "ABCDEFGHIJKLMNOPQRSTUVWXYZ0123456789";

// Animation speed (lower = faster, higher = slower)
setInterval(draw, 33); // Currently ~30fps

// Trail effect intensity
ctx.fillStyle = "rgba(0, 0, 0, 0.05)"; // Lower opacity = longer trails
```

### Color Variations
Change the text color by modifying:
```javascript
ctx.fillStyle = "#0F0"; // Green (default)
// Try: "#F00" (red), "#00F" (blue), "#FFF" (white)
```
## 📱 Browser Support

- ✅ Chrome 
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

Contributions are welcome! Here are some ideas:

- Add sound effects
- Implement different character falling speeds
- Add color transitions
- Create mobile touch interactions
- Add fullscreen API support

### Development Setup
1. Fork this repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🎬 Inspiration

Inspired by the iconic digital rain effect from The Matrix (1999) directed by the Wachowskis. This project is a tribute to one of cinema's most recognizable visual effects.

## ⭐ Show Your Support

If you enjoyed this project, please give it a star! It helps others discover the project.



---

**"Wake up, Neo... The Matrix has you."** 🕶️