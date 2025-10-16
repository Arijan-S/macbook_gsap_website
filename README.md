# MacBook Pro GSAP Website

A modern, interactive website showcasing the MacBook Pro with stunning 3D models, smooth animations, and engaging user experience. Built with React, Three.js, and GSAP for premium visual effects.

## 🚀 Features

- **Interactive 3D Product Viewer** - Rotate and explore MacBook Pro models in 3D
- **Smooth GSAP Animations** - Professional-grade animations and transitions
- **Responsive Design** - Optimized for desktop and mobile devices
- **Multiple MacBook Models** - 14" and 16" MacBook Pro variants
- **Color Customization** - Switch between Space Gray and Dark colors
- **Performance Showcase** - Interactive performance metrics display
- **Feature Highlights** - AI-powered features with video demonstrations
- **Modern UI/UX** - Clean, Apple-inspired design language

## 🛠️ Tech Stack

- **Frontend**: React 19.1.1
- **3D Graphics**: Three.js, React Three Fiber, React Three Drei
- **Animations**: GSAP (GreenSock Animation Platform)
- **Styling**: Tailwind CSS 4.1.14
- **State Management**: Zustand
- **Build Tool**: Vite
- **3D Models**: GLB format MacBook models

## 📦 Installation

1. **Clone the repository**

   ```bash
   git clone <repository-url>
   cd macbook_gsap_website
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Start the development server**

   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173`

## 🏗️ Project Structure

```
src/
├── components/
│   ├── models/           # 3D MacBook model components
│   │   ├── Macbook.jsx
│   │   ├── Macbook-14.jsx
│   │   └── Macbook-16.jsx
│   ├── three/            # Three.js utilities
│   │   ├── ModelSwitcher.jsx
│   │   └── StudioLights.jsx
│   ├── Features.jsx      # AI features showcase
│   ├── Footer.jsx        # Footer component
│   ├── Hero.jsx          # Hero section
│   ├── Highlights.jsx    # Product highlights
│   ├── Navbar.jsx        # Navigation bar
│   ├── Performance.jsx   # Performance metrics
│   ├── ProductViewer.jsx # 3D product viewer
│   └── Showcase.jsx      # Product showcase
├── constants/
│   └── index.js          # App constants and data
├── store/
│   └── index.js          # Zustand state management
├── App.jsx               # Main app component
├── main.jsx             # App entry point
└── index.css            # Global styles
```

## 🎮 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🎨 Key Components

### ProductViewer

Interactive 3D MacBook viewer with:

- Orbit controls for model rotation
- Color switching (Space Gray/Dark)
- Size selection (14"/16")
- Responsive scaling

### Performance

Dynamic performance metrics with:

- Animated image positioning
- Scroll-triggered animations
- Interactive data visualization

### Features

AI-powered feature showcase featuring:

- Email AI summarization
- Image AI generation
- Text summarization
- AirDrop functionality
- Writing assistance tools

## 🎬 Animations

The project uses GSAP for smooth, professional animations:

- Scroll-triggered animations
- Text splitting effects
- Smooth transitions
- Performance-optimized animations

## 📱 Responsive Design

- Mobile-first approach
- Adaptive 3D model scaling
- Responsive typography
- Touch-friendly controls

## 🎯 3D Models

The project includes high-quality GLB models:

- `macbook.glb` - Base MacBook model
- `macbook-14.glb` - 14" MacBook Pro
- `macbook-16.glb` - 16" MacBook Pro
- Transformed variants for different viewing angles

## 🎥 Media Assets

- Hero video (`/videos/hero.mp4`)
- Feature demonstration videos
- Performance images
- Product photography
- Custom icons and graphics

## 🔧 Configuration

### Environment Variables

No environment variables required for basic functionality.

### Customization

- Modify `src/constants/index.js` to update content
- Adjust animations in individual components
- Customize colors in Tailwind config
- Replace 3D models in `/public/models/`

## 📄 License

This project is for educational and portfolio purposes.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Support

For questions or support, please open an issue in the repository.

---

Built with ❤️ using React, Three.js, and GSAP
