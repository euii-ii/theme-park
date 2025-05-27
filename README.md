# 🎢 3D Theme Park

> An immersive 3D theme park experience built with modern web technologies

A fully interactive 3D theme park built with **Vite**, **Three.js**, **TypeScript**, and **Tailwind CSS**. Experience rides, explore attractions, and navigate through a beautifully crafted virtual environment.

## ✨ Features

- 🎯 **Interactive 3D Environment** - Fully navigable theme park with realistic physics
- ⚡ **Lightning Fast** - Optimized with Vite for instant hot reloading
- 🔒 **Type Safe** - Built with TypeScript for robust development
- 📱 **Responsive Design** - Seamless experience across all devices
- 🎨 **Custom Animations** - Smooth transitions and interactive elements
- 🏗️ **Modular Architecture** - Clean, scalable, and maintainable codebase
- 🎮 **Multiple Camera Controls** - First-person and orbital camera modes
- 🌅 **Dynamic Lighting** - Realistic day/night cycle with shadows

## 🛠️ Tech Stack

| Technology | Purpose | Version |
|------------|---------|---------|
| [Vite](https://vitejs.dev/) | Build tool & dev server | ^5.0.0 |
| [Three.js](https://threejs.org/) | 3D rendering engine | ^0.160.0 |
| [TypeScript](https://www.typescriptlang.org/) | Static type checking | ^5.0.0 |
| [Tailwind CSS](https://tailwindcss.com/) | Utility-first CSS | ^3.4.0 |

## 🚀 Quick Start

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/euii-ii/theme-park.git
   cd 3d-theme-park
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start development server**
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. **Open in browser**
   Navigate to `http://localhost:5173`

### Build & Deploy

```bash
# Build for production
npm run build

# Preview production build locally
npm run preview

# Deploy to your hosting service
npm run deploy
```

## 📁 Project Structure

```
3d-theme-park/
├── 📁 public/                 # Static assets & models
│   ├── models/               # 3D models (.gltf, .glb)
│   ├── textures/             # Material textures
│   └── sounds/               # Audio files
├── 📁 src/
│   ├── 📁 components/        # Reusable UI components
│   │   ├── UI/              # Interface elements
│   │   └── Controls/        # Input handlers
│   ├── 📁 scenes/           # Three.js scene management
│   │   ├── ThemePark.ts     # Main park scene
│   │   ├── Attractions.ts   # Ride implementations
│   │   └── Environment.ts   # Lighting & atmosphere
│   ├── 📁 utils/            # Helper functions
│   │   ├── loaders.ts       # Asset loading utilities
│   │   └── physics.ts       # Physics calculations
│   ├── 📁 types/            # TypeScript definitions
│   ├── 📁 styles/           # Global styles
│   └── main.ts              # Application entry point
├── 📄 index.html             # Main HTML template
├── ⚙️ vite.config.ts         # Vite configuration
├── ⚙️ tsconfig.json          # TypeScript config
├── ⚙️ tailwind.config.js     # Tailwind CSS config
└── 📄 package.json           # Project dependencies
```

## 🎮 Controls & Navigation

- **W, A, S, D** - Move around the park
- **Mouse** - Look around / Rotate camera
- **Space** - Jump / Ascend
- **Shift** - Run / Fast movement
- **Tab** - Switch camera modes
- **Click** - Interact with attractions

## 🎨 Customization

### Adding New Attractions

1. Create a new attraction class in `src/scenes/attractions/`
2. Import and register in `src/scenes/ThemePark.ts`
3. Add corresponding UI elements in `src/components/`

### Modifying Visuals

- **Lighting**: Edit `src/scenes/Environment.ts`
- **Materials**: Update texture paths in `public/textures/`
- **Models**: Replace 3D assets in `public/models/`

## 🔧 Development Scripts

```bash
npm run dev          # Start development server
npm run build        # Build for production
npm run preview      # Preview production build
npm run lint         # Run ESLint
npm run type-check   # Run TypeScript compiler
npm run clean        # Clean build artifacts
```

## 🌐 Browser Support

- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

*WebGL 2.0 support required*

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-ride`)
3. Commit your changes (`git commit -m 'Add amazing new ride'`)
4. Push to the branch (`git push origin feature/amazing-ride`)
5. Open a Pull Request

## 📝 License

This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.

## 🙏 Acknowledgments

- Three.js community for excellent documentation
- Poly Haven for high-quality textures
- Sketchfab for 3D model inspiration

## 🔗 Links

- [Live Demo](https://your-live-demo-link.com) 🌐
- [Documentation](https://github.com/euii-ii/theme-park/wiki) 📚
- [Issues](https://github.com/euii-ii/theme-park/issues) 🐛
- [Discussions](https://github.com/euii-ii/theme-park/discussions) 💬

---

<div align="center">
  <p>Made with ❤️ by <a href="https://github.com/euii-ii">@euii-ii</a></p>
  <p>⭐ Star this repo if you found it helpful!</p>
</div>
