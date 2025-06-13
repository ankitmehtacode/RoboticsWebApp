# Sun Robotics & AI - Setup Instructions

## Quick Setup Guide

### 1. Create Project Directory
```bash
mkdir sun-robotics-ai
cd sun-robotics-ai
```

### 2. Initialize Project
```bash
npm init -y
```

### 3. Install Dependencies
```bash
# Core dependencies
npm install react@^18.3.1 react-dom@^18.3.1 framer-motion@^11.0.0 lucide-react@^0.344.0

# Development dependencies
npm install -D @vitejs/plugin-react@^4.3.1 vite@^5.4.2 typescript@^5.5.3 @types/react@^18.3.5 @types/react-dom@^18.3.0 tailwindcss@^3.4.1 autoprefixer@^10.4.18 postcss@^8.4.35 eslint@^9.9.1 @eslint/js@^9.9.1 typescript-eslint@^8.3.0 eslint-plugin-react-hooks@^5.1.0-rc.0 eslint-plugin-react-refresh@^0.4.11 globals@^15.9.0
```

### 4. Copy All Files
Copy all the files provided above into their respective locations according to the folder structure.

### 5. Run the Project
```bash
npm run dev
```

## Features Included

✅ **Modern React 18** with TypeScript
✅ **Framer Motion** for smooth animations
✅ **Tailwind CSS** for styling
✅ **Lucide React** for icons
✅ **3D Background Elements** in Hero section
✅ **Responsive Design** for all devices
✅ **Professional UI/UX** with glassmorphism effects
✅ **Smooth Scrolling** navigation
✅ **Interactive Components** with hover effects
✅ **Production Ready** code structure

## Project Structure
- **src/components/** - All React components
- **src/App.tsx** - Main application component
- **src/main.tsx** - React entry point
- **tailwind.config.js** - Tailwind configuration
- **vite.config.ts** - Vite build configuration
- **package.json** - Dependencies and scripts

## Available Scripts
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance Optimizations
- Lazy loading of images
- Optimized animations with Framer Motion
- Efficient re-renders with React hooks
- Tailwind CSS purging for smaller bundle size
