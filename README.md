# Modern React Portfolio

A feature-rich, responsive portfolio website built with React, featuring dynamic themes, animations, and interactive elements.

![Portfolio Preview](public/images/portfolio-preview.png)

## 🌟 Features

- **Dynamic Theme Switching**: Light/Dark mode with customizable accent colors
- **Interactive UI Elements**: 
  - Animated page transitions
  - Floating objects animation
  - Particle background effects
  - Scroll progress indicator
- **Responsive Design**: Fully responsive across all devices
- **Modern Technologies**:
  - React with Hooks
  - Framer Motion animations
  - React Router for navigation
  - Context API for state management
  - CSS Modules for styling
- **Performance Optimized**:
  - Lazy loading of images
  - Code splitting
  - Optimized build configuration

## 🚀 Live Demo

Visit the live portfolio: [Portfolio URL](https://your-portfolio-url.com)

## 💻 Tech Stack

- React 18
- Framer Motion
- React Router v6
- React Icons
- React tsParticles
- CSS3 with CSS Modules

## 🛠️ Installation & Setup

1. Clone the repository
```bash
git clone https://github.com/yourusername/portfolio.git
```

2. Navigate to project directory
```bash
cd portfolio
```

3. Install dependencies
```bash
npm install
```

4. Start the development server
```bash
npm start
```

5. Build for production
```bash
npm run build
```

## 📁 Project Structure

```
portfolio/
├── public/
│   └── images/
├── src/
│   ├── components/
│   │   ├── About.js
│   │   ├── Contact.js
│   │   ├── Footer.js
│   │   ├── Home.js
│   │   ├── Navigation.js
│   │   ├── ParticleBackground.js
│   │   ├── Projects.js
│   │   ├── ScrollProgress.js
│   │   └── ThemeSwitcher.js
│   ├── context/
│   │   └── ThemeContext.js
│   ├── styles/
│   │   └── App.css
│   ├── App.js
│   └── index.js
└── package.json
```

## 🎨 Customization

### Theme Colors
Edit the root variables in `src/App.css`:
```css
:root {
  --primary-color: #2A2A72;
  --secondary-color: #009FFD;
  --accent-color: #FFA400;
  // ...other color variables
}
```

### Content
Update personal information in respective components:
- `Home.js`: Hero section content
- `About.js`: Personal bio and skills
- `Projects.js`: Project showcases
- `Contact.js`: Contact information

## 📱 Responsive Design

The portfolio is responsive across various screen sizes:
- Mobile: < 768px
- Tablet: 768px - 1024px
- Desktop: > 1024px

## ⚡ Performance Optimizations

- Implemented lazy loading for images
- Used React.lazy() for component code splitting
- Optimized animations for better performance
- Minimized bundle size

## 🔧 Advanced Features

### Theme Switcher
```javascript
const ThemeSwitcher = () => {
  const { isDark, toggleTheme } = useContext(ThemeContext);
  // Implementation details in src/components/ThemeSwitcher.js
};
```

### Particle Background
```javascript
const ParticleBackground = () => {
  // Configuration in src/components/ParticleBackground.js
};
```

### Scroll Progress
```javascript
const ScrollProgress = () => {
  // Implementation in src/components/ScrollProgress.js
};
```

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Contact

Chileshe Besa
- Email: chilebesa@gmail.com
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/yourusername)
- GitHub: [Your GitHub](https://github.com/yourusername)

## 🙏 Acknowledgments

- [React](https://reactjs.org/)
- [Framer Motion](https://www.framer.com/motion/)
- [React Icons](https://react-icons.github.io/react-icons/)
- [React tsParticles](https://particles.js.org/)
#   r e a c t  
 