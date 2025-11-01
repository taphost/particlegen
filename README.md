# ✨ Particles Generator

Interactive web-based particle system with real-time customization and export capabilities.

## 🔧 Technical Specifications

- **Zero Dependencies**: Pure vanilla JavaScript
- **Modern ES6+**: Classes, arrow functions, template literals, destructuring
- **Single File**: Complete app in one HTML file
- **Canvas API**: Hardware-accelerated 2D rendering
- **Performance Optimized**: Efficient algorithms for 800+ particles at 60fps

## 🎨 Features

### Particle Controls
- **Count**: 50-2000 particles
- **Size**: Min/max range (1-20px)
- **Shape**: Circle, Square, Rectangle, Triangle, Star, Snowflake
- **Angle**: 0-360° initial rotation

### Physics
- **Speed**: Global speed multiplier
- **Gravity**: Vertical acceleration (-1 to 10)
- **Wind**: Horizontal force (-2 to 2)
- **Spawn Speed**: Initial velocity
- **Turbulence**: Random motion intensity

### Behavior
- **Fade Modes**: None, Always (pulse), Exit (fade at edges)
- **Fade Speed**: Opacity transition rate
- **Rotation**: Continuous shape spinning

### Mouse Interaction
- **Mouse Tracking**: Attract particles to cursor
- **Mouse Influence**: Attraction strength (0-50)

### 🎭 Presets
- Confetti
- Snow
- Rain
- Stars
- Fireflies

## 🚀 Usage

1. Open the HTML file in your browser
2. Adjust controls in sidebar
3. Play/Pause animation
4. Export as PNG or standalone HTML

## ⚡ Performance

Optimized for 800+ particles:
- Cached shape references
- Canvas dimension parameters
- Minimal redundant draws
- Single-path snowflake rendering

## 💾 Export

- **Save PNG**: Current frame screenshot
- **Save HTML**: Standalone file with embedded animation
- **Show Code**: View/copy generated code

## 📄 License

MIT License - Copyright (c) 2025 - Free to use, modify, and distribute.
