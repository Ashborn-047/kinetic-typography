# Kinetic Typography

**Interactive typography experiments exploring the intersection of motion and letterforms.**

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Live Demo

[View Live Demo](https://ashborn-047.github.io/kinetic-typography/)

## 📖 About

A visual exploration of kinetic typography, showcasing how letterforms can transcend static design and become living, breathing elements. This project features 9 unique typographic experiments, each demonstrating different motion and interaction paradigms.

## 🎨 Experiments

| # | Name | Description |
|---|------|-------------|
| 01 | **ELASTIC** | Letters react to cursor proximity with rubber-like physics |
| 02 | **LAYERS** | Chromatic aberration split on mouse movement |
| 03 | **ECLIPSE** | 3D rotation casting directional shadows |
| 04 | **GLITCH** | Digital signal decay and RGB displacement |
| 05 | **VAPOR** | Ghosting trail effect with blur filters |
| 06 | **PIXELS** | Character scrambling into raw data blocks |
| 07 | **AURA** | Neon luminescence and atmospheric glow |
| 08 | **VERTEX** | Real-time WebGL 3D geometry rendering |
| 09 | **FLUID** | Turbulent wave distortion like liquid ink |

## 🛠️ Tech Stack

- **HTML5** - Semantic structure
- **CSS3** - Custom properties, animations, Tailwind CSS
- **JavaScript** - Vanilla ES6+ modules
- **GSAP** - ScrollTrigger, CustomEase animations
- **Three.js** - WebGL 3D rendering
- **SVG Filters** - Displacement maps, turbulence effects

## 📁 Project Structure

```
kinetic-typography/
├── index.html              # Main page
├── css/
│   ├── variables.css       # CSS custom properties
│   ├── base.css            # Base styles
│   ├── components.css      # Component styles
│   └── animations.css      # Animation keyframes
├── js/
│   ├── utils.js            # Utility functions
│   ├── cursor.js           # Custom cursor
│   ├── hero.js             # Hero section effects
│   ├── archive.js          # Archive grid interactions
│   ├── typewriter.js       # Typewriter effect
│   ├── three-scene.js      # 3D WebGL scene
│   └── scroll-animations.js # Scroll-based animations
└── experiments/
    ├── elastic.html        # Standalone experiment pages
    ├── layers.html
    ├── eclipse.html
    ├── glitch.html
    ├── vapor.html
    ├── pixels.html
    ├── aura.html
    ├── vertex.html
    └── fluid.html
```

## 🚀 Getting Started

### Local Development

```bash
# Clone the repository
git clone https://github.com/Ashborn-047/kinetic-typography.git

# Navigate to project
cd kinetic-typography

# Start a local server (Python)
python -m http.server 3000

# Or use Node.js serve
npx serve -l 3000
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Typography inspiration from Swiss design principles
- Animation techniques from creative coding community
- Three.js examples and documentation

---

**Type is no longer just ink on paper. It is a living signal.**
