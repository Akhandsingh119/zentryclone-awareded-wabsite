# 🚀 ZENTRY CLONE WABSITE

A modern, award-winning Zentry clone website built with React, featuring stunning animations, video backgrounds, and a responsive design. This project showcases advanced web development techniques including GSAP animations, video integration, and modern UI/UX practices.

## ✨ Features

- **Hero Section**: Dynamic video backgrounds with smooth transitions
- **About Section**: Engaging content presentation with animations
- **Features Showcase**: Interactive feature highlights
- **Story Section**: Narrative-driven content with visual elements
- **Contact Form**: User-friendly contact interface
- **Responsive Design**: Mobile-first approach with Tailwind CSS
- **Smooth Animations**: GSAP-powered scroll-triggered animations
- **Video Integration**: Multiple video backgrounds and previews
- **Modern UI**: Clean, minimalist design with custom fonts

## 🚀 Technologies Used

### Frontend Framework
- **React 18.3.1** - Modern React with hooks and functional components
- **Vite 5.4.10** - Fast build tool and development server

### Animation & Effects
- **GSAP 3.12.5** - Professional-grade animations
- **@gsap/react 2.1.1** - React integration for GSAP
- **ScrollTrigger** - Scroll-based animation triggers

### Styling & UI
- **Tailwind CSS 3.4.14** - Utility-first CSS framework
- **PostCSS 8.4.49** - CSS processing
- **Autoprefixer 10.4.20** - CSS vendor prefixing

### Development Tools
- **ESLint 9.14.0** - Code linting and quality
- **Prettier 3.3.3** - Code formatting
- **TypeScript types** - Type safety for React components

### Utilities
- **clsx 2.1.1** - Conditional CSS class names
- **react-icons 5.3.0** - Icon library
- **react-use 17.5.1** - Useful React hooks

## 📁 Project Structure

```
zentryclone-awareded-wabsite/
├── public/                          # Static assets
│   ├── audio/                       # Audio files
│   │   └── loop.mp3                # Background audio
│   ├── fonts/                       # Custom fonts
│   │   ├── circularweb-book.woff2
│   │   ├── general.woff2
│   │   ├── robert-medium.woff2
│   │   ├── robert-regular.woff2
│   │   └── zentry-regular.woff2
│   ├── img/                         # Image assets
│   │   ├── about.webp              # About section images
│   │   ├── contact-1.webp          # Contact images
│   │   ├── contact-2.webp
│   │   ├── entrance.webp           # Entrance image
│   │   ├── gallery-*.webp          # Gallery images
│   │   ├── jsm-logo.png            # Logo
│   │   ├── logo.png
│   │   ├── play.svg                # Play button icon
│   │   ├── stones.webp             # Decorative images
│   │   └── swordman*.webp          # Hero images
│   └── videos/                      # Video assets
│       ├── feature-*.mp4           # Feature videos
│       ├── hero-*.mp4              # Hero background videos
│       └── vite.svg                # Vite logo
├── src/                             # Source code
│   ├── components/                  # React components
│   │   ├── About.jsx               # About section component
│   │   ├── AnimatedTitle.jsx       # Animated title component
│   │   ├── Button.jsx              # Reusable button component
│   │   ├── Contact.jsx             # Contact form component
│   │   ├── Features.jsx            # Features showcase component
│   │   ├── Footer.jsx              # Footer component
│   │   ├── Hero.jsx                # Hero section component
│   │   ├── Navbar.jsx              # Navigation component
│   │   ├── Story.jsx               # Story section component
│   │   └── VideoPreview.jsx        # Video preview component
│   ├── App.jsx                     # Main application component
│   ├── main.jsx                    # Application entry point
│   └── index.css                   # Global styles
├── package.json                     # Dependencies and scripts
├── tailwind.config.js              # Tailwind CSS configuration
├── vite.config.js                  # Vite build configuration
├── postcss.config.js               # PostCSS configuration
└── eslint.config.js                # ESLint configuration
```

## 🛠️ Installation & Setup

### Prerequisites
- Node.js (version 16 or higher)
- npm or yarn package manager

### Getting Started

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd zentryclone-awareded-wabsite
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

4. **Open your browser**
   Navigate to `http://localhost:5173` (or the port shown in your terminal)

## 📜 Available Scripts

- **`npm run dev`** - Start development server with hot reload
- **`npm run build`** - Build production version
- **`npm run preview`** - Preview production build locally
- **`npm run lint`** - Run ESLint for code quality checks

## 🎨 Key Components

### Hero Section (`Hero.jsx`)
- Dynamic video backgrounds with smooth transitions
- GSAP-powered animations and scroll triggers
- Interactive video controls and loading states
- Custom clip-path animations

### Navigation (`Navbar.jsx`)
- Responsive navigation menu
- Smooth scroll behavior
- Mobile-friendly design

### Features (`Features.jsx`)
- Interactive feature showcase
- Video previews and descriptions
- Responsive grid layout

### About & Story Sections
- Engaging content presentation
- Scroll-triggered animations
- Rich media integration

## 🎭 Animation System

The website uses GSAP (GreenSock Animation Platform) for:
- **Scroll-triggered animations** - Elements animate as they come into view
- **Video transitions** - Smooth video background changes
- **Clip-path animations** - Dynamic shape morphing
- **Timeline-based sequences** - Coordinated animation sequences

## 🎥 Video Integration

- **Hero Videos**: Multiple background videos with smooth transitions
- **Feature Videos**: Showcase videos for different features
- **Video Previews**: Interactive video preview components
- **Loading States**: Smooth loading animations for video content

## 🎨 Design System

- **Typography**: Custom font families (Circular, Robert, Zentry)
- **Color Palette**: Carefully selected color scheme
- **Spacing**: Consistent spacing using Tailwind's design tokens
- **Responsive**: Mobile-first responsive design approach

## 🚀 Performance Features

- **Lazy Loading**: Videos and images load on demand
- **Optimized Assets**: WebP images and compressed videos
- **Efficient Animations**: GSAP's optimized animation engine
- **Modern Build**: Vite's fast build and development experience

## 🔧 Customization

### Adding New Sections
1. Create a new component in `src/components/`
2. Import and add it to `App.jsx`
3. Style with Tailwind CSS classes

### Modifying Animations
1. Edit GSAP animations in component files
2. Adjust ScrollTrigger parameters
3. Modify timing and easing functions

### Updating Content
1. Replace media files in `public/` directories
2. Update component content and props
3. Modify styling in component files

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run linting: `npm run lint`
5. Submit a pull request

## 📄 License

This project is private and proprietary.

## 🙏 Acknowledgments

- **GSAP** for powerful animation capabilities
- **Tailwind CSS** for utility-first styling
- **Vite** for fast development experience
- **React** for component-based architecture

---

**Built with ❤️ using modern web technologies**
