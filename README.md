# GTA VI Landing Page

A modern, interactive landing page for Grand Theft Auto VI built with React, featuring smooth animations and responsive design.

## 🎮 Features

- **Interactive Hero Section** - Dynamic background with video elements
- **Character Showcases** - Dedicated sections for Jason and Lucia characters
- **Video Integration** - Multiple video sections with smooth transitions
- **Responsive Design** - Optimized for all device sizes
- **Smooth Animations** - GSAP-powered scroll-triggered animations
- **Modern UI** - Custom fonts and gradient backgrounds

## 🛠️ Tech Stack

- **React 19** - Modern React with latest features
- **Vite** - Fast build tool and development server
- **GSAP** - Professional-grade animations
- **Tailwind CSS** - Utility-first CSS framework
- **React Responsive** - Responsive design utilities

## 📁 Project Structure

```
gta_landing/
├── public/
│   ├── fonts/           # Custom fonts (Long, Round, Round Bold)
│   ├── images/          # All project images and assets
│   └── videos/          # Video files for different sections
├── src/
│   ├── sections/        # React components for each page section
│   │   ├── Hero.jsx
│   │   ├── NavBar.jsx
│   │   ├── FirstVideo.jsx
│   │   ├── Jason.jsx
│   │   ├── SecondVideo.jsx
│   │   ├── Lucia.jsx
│   │   ├── PostCard.jsx
│   │   ├── Final.jsx
│   │   └── Outro.jsx
│   ├── App.jsx          # Main application component
│   ├── main.jsx         # Application entry point
│   └── index.css        # Global styles and CSS variables
├── constants/           # Application constants
└── config files        # Vite, Tailwind, ESLint configuration
```

## 🚀 Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd gta_landing
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173`

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 🎨 Design Features

### Custom Fonts
- **Long** - Decorative font for special elements
- **Round** - Primary font family
- **Round Bold** - Bold variant for emphasis

### Color Scheme
- Custom CSS variables for consistent theming
- Gradient backgrounds with dark theme
- Yellow and pink accent colors

### Animations
- GSAP ScrollTrigger for scroll-based animations
- Smooth transitions between sections
- Interactive elements with hover effects

## 📱 Responsive Design

The landing page is fully responsive with breakpoints:
- **xs**: 20rem (320px)
- **sm**: 40rem (640px)
- **3xl**: 120rem (1920px)

## 🎬 Video Integration

Multiple video sections featuring:
- Hero background videos
- Character introduction videos
- Postcard-style video presentations

## 🔧 Customization

### Adding New Sections
1. Create a new component in `src/sections/`
2. Import and add to `App.jsx`
3. Style with Tailwind CSS classes

### Modifying Animations
- GSAP animations are configured in individual components
- ScrollTrigger is registered globally in `App.jsx`

### Updating Assets
- Images: Replace files in `public/images/`
- Videos: Replace files in `public/videos/`
- Fonts: Update `@font-face` declarations in `index.css`

## 📄 License

This project is for educational/demonstration purposes. All GTA-related assets and trademarks belong to Rockstar Games.

## 👨‍💻 Author

Created by Oxana - A modern web developer passionate about interactive experiences.

---

*Built with ❤️ using React, GSAP, and modern web technologies*