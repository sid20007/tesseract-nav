# 🔮 Tesseract Navigation

> An interactive 4D hypercube visualization that lets you explore the fourth dimension in real-time

![Tesseract](https://img.shields.io/badge/Dimensions-4D-00ffff?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow?style=for-the-badge)

## ✨ What is This?

**Tesseract Navigation** is a mind-bending visualization of a tesseract - a 4-dimensional hypercube. Just as a cube is made of 6 squares, a tesseract is made of 8 cubes. What you see here is a **3D projection** of a 4D object, similar to how a cube casts a 2D shadow.

Think of it this way:
- A **square** is 2D (4 vertices, 4 edges)
- A **cube** is 3D (8 vertices, 12 edges)  
- A **tesseract** is 4D (16 vertices, 32 edges)

This visualization allows you to rotate the tesseract through **6 different planes of rotation** - far more than the 3 we're used to in 3D space!

## 🎮 Features

- **Interactive 4D Rotation**: Drag to rotate across multiple dimensions
- **6 Rotation Planes**: XY, YZ, ZW, XW, YW, XZ
- **Real-time Projection**: 4D → 3D → 2D mathematical transformations
- **Particle System**: Glowing particle trails (200 max particles)
- **Neon Aesthetics**: Depth-based color gradients and glow effects
- **Manual & Auto Modes**: Control rotation manually or watch it spin automatically
- **Precision Controls**: Fine-tune rotations with sliders

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/tesseract-nav.git
   cd tesseract-nav
   ```

2. **Open in browser**
   - Simply open `index.html` in your browser, **OR**
   - Use a local server:
     ```bash
     python -m http.server 8000
     # Then visit http://localhost:8000
     ```

3. **Start exploring!**
   - Drag to rotate
   - Click for particle bursts
   - Use sliders for precise control
   - Enable auto-rotate for mesmerizing animations

## 🎯 How to Use

### Controls
- **Mouse Drag**: Manually rotate the tesseract through 3D space
- **Click**: Create colorful particle bursts
- **XY Slider**: Rotate in the XY plane
- **ZW Slider**: Rotate in the ZW plane (4D rotation!)
- **XW Slider**: Rotate in the XW plane (4D rotation!)
- **Auto Rotate**: Toggle automatic rotation
- **Reset View**: Return to default perspective

### Understanding the Visualization
- **Edges**: 32 glowing lines connecting the 16 vertices
- **Vertices**: 16 pulsating points in 4D space
- **Colors**: Depth-based gradients (cyan to blue)
- **Brightness**: Indicates proximity in 4D space
- **Particles**: Trail effects showing motion

## 🧠 The Math Behind It

The visualization performs mathematical projections:

1. **4D Rotation**: Applies rotation matrices across 6 planes
2. **4D → 3D Projection**: Perspective projection based on W-axis distance
3. **3D → 2D Projection**: Standard perspective projection to your screen

Each vertex starts as a 4D coordinate `(x, y, z, w)` and gets transformed through multiple rotation matrices before being projected to your 2D screen.

## 🌟 Why This Matters

- **Physics**: Tesseracts appear in **string theory** and theoretical physics
- **Mathematics**: Understanding higher dimensions helps with complex problem-solving
- **Art**: Creating impossible geometries that challenge perception
- **Mind-Bending**: It's just really cool to see the impossible made visible!

## 🛠️ Technology Stack

- **Pure JavaScript** - No frameworks, just math
- **HTML5 Canvas** - For rendering
- **Vanilla CSS** - Clean, modern UI
- **No Dependencies** - Runs anywhere

## 📸 Screenshots

> *Coming soon - Add your own screenshots!*

## 🎨 Customization

You can easily customize:
- **Colors**: Modify the HSL values in the drawing code
- **Particle Count**: Change `maxParticles` variable
- **Rotation Speed**: Adjust the increment values in auto-rotate
- **Edge Thickness**: Modify `ctx.lineWidth`
- **Glow Effects**: Adjust `ctx.shadowBlur` values

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Add new rotation modes
- Improve the particle system
- Add sound/music integration
- Create preset animation sequences
- Enhance mobile touch controls

## 📝 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 💡 Inspiration

Inspired by:
- Theoretical physics and string theory
- Carl Sagan's explanation of dimensions in "Cosmos"
- The tesseract scene in the movie "Interstellar"
- Mathematical art and impossible geometries

## 🔗 Links

- [Live Demo](#) *(Add your demo link here)*
- [More 4D Math](https://en.wikipedia.org/wiki/Tesseract)
- [Understanding Higher Dimensions](https://en.wikipedia.org/wiki/Four-dimensional_space)

---

**Made with 🌌 and JavaScript**

*If you find this project interesting, give it a ⭐ on GitHub!*
