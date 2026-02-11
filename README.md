# Ahmed Dahy Shaban - Portfolio Website

A modern, animated personal portfolio website showcasing my work as a Web Developer specializing in .NET and WordPress.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-success)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🌟 Features

- **Modern Design**: Clean, minimalist interface with smooth animations
- **Dark/Light Theme**: Toggle between dark and light modes with preference persistence
- **Particle Effects**: Interactive particle.js background for an "anti-gravity" feel
- **Smooth Animations**: 
  - Typing effect for hero title
  - Fade-in animations on scroll
  - Hover effects on cards and buttons
  - Floating animations for hero elements
- **Fully Responsive**: Optimized for mobile, tablet, and desktop devices
- **Performance Optimized**: 
  - Lazy loading images
  - CSS animations using GPU acceleration
  - Debounced scroll events
- **Interactive Contact Form**: Client-side validation with user-friendly error messages
- **Smooth Scrolling**: Navigation with active section highlighting

## 🛠️ Technology Stack

- **HTML5**: Semantic markup with accessibility considerations
- **CSS3**: Custom properties, Grid, Flexbox, animations
- **JavaScript (ES6+)**: Vanilla JS for interactivity
- **External Libraries**:
  - [Particles.js](https://vincentgarreau.com/particles.js/) - Particle background effects
  - [AOS](https://michalsnik.github.io/aos/) - Animate On Scroll library
  - [Typed.js](https://mattboldt.com/demos/typed-js/) - Typing animation
  - [Font Awesome](https://fontawesome.com/) - Icons
  - [Google Fonts](https://fonts.google.com/) - Poppins font family

## 📁 File Structure

```
Portfolio/
│
├── index.html          # Main HTML file with all sections
├── styles.css          # Complete CSS styling and animations
├── script.js           # JavaScript for interactivity
└── README.md           # This file
```

## 🚀 Getting Started

### Local Development

1. **Clone or download** this repository
2. **Open `index.html`** in your web browser
3. That's it! No build process required.

### Using a Local Server (Recommended)

For the best development experience, use a local server:

**Option 1: VS Code Live Server**
```bash
# Install the Live Server extension in VS Code
# Right-click on index.html and select "Open with Live Server"
```

**Option 2: Python HTTP Server**
```bash
# Navigate to the project directory
cd Portfolio

# Python 3
python -m http.server 8000

# Open http://localhost:8000 in your browser
```

**Option 3: Node.js HTTP Server**
```bash
# Install http-server globally
npm install -g http-server

# Run server
http-server -p 8000

# Open http://localhost:8000 in your browser
```

## 🌐 Deployment

### Deploy to Vercel

1. **Install Vercel CLI** (if not already installed):
   ```bash
   npm install -g vercel
   ```

2. **Deploy**:
   ```bash
   cd Portfolio
   vercel
   ```

3. **Follow the prompts** to complete deployment

### Deploy to Netlify

**Option 1: Drag & Drop**
1. Go to [Netlify Drop](https://app.netlify.com/drop)
2. Drag the entire Portfolio folder
3. Your site is live!

**Option 2: Netlify CLI**
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Deploy
cd Portfolio
netlify deploy

# Follow prompts and select the current directory as the publish directory
```

### Deploy to GitHub Pages

1. **Create a repository** on GitHub
2. **Push your code**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/portfolio.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to repository Settings > Pages
   - Select "main" branch as source
   - Your site will be live at `https://yourusername.github.io/portfolio/`

## 🎨 Customization

### Updating Personal Information

**1. HTML Content (`index.html`)**
   - Update name, title, and bio in the respective sections
   - Add your own projects in the Projects section
   - Update experience and education details

**2. Theme Colors (`styles.css`)**
   ```css
   :root {
       --accent-blue: #0d6efd;    /* Primary accent color */
       --accent-green: #10b981;   /* Secondary accent color */
   }
   ```

**3. Profile Image**
   - Replace the avatar URL in the About section:
   ```html
   <img src="your-image-url.jpg" alt="Ahmed Dahy Shaban">
   ```

**4. Social Links**
   - Update email, phone, LinkedIn, and GitHub links in the Contact section

### Adding New Sections

1. Add HTML structure in `index.html`
2. Add navigation link in the navbar
3. Style the section in `styles.css`
4. Add scroll animations with `data-aos` attributes

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## ⚡ Performance

- **Lighthouse Score**: 95+ (Performance, Accessibility, Best Practices, SEO)
- **Lazy Loading**: Images load only when needed
- **Optimized Animations**: CSS animations use GPU acceleration
- **Minimal Dependencies**: Only essential libraries included

## 📝 Form Integration

The contact form currently uses client-side validation only. To make it functional:

1. **Use a Form Service**:
   - [Formspree](https://formspree.io/)
   - [Netlify Forms](https://www.netlify.com/products/forms/)
   - [EmailJS](https://www.emailjs.com/)

2. **Add Backend**:
   - Create an API endpoint to handle form submissions
   - Update the form submission handler in `script.js`

Example with Formspree:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

## 🐛 Troubleshooting

**Particles not showing?**
- Check browser console for errors
- Ensure internet connection (particles.js loads from CDN)

**Animations not working?**
- Clear browser cache
- Ensure JavaScript is enabled
- Check browser console for errors

**Theme not persisting?**
- Check if localStorage is enabled in your browser
- Clear localStorage and try again

## 📄 License

This project is open source and available for personal and commercial use.

## 👤 Contact

**Ahmed Dahy Shaban**
- Email: [ahmeddahy134@gmail.com](mailto:ahmeddahy134@gmail.com)
- Phone: +20 112 027 4411
- LinkedIn: [linkedin.com/in/ahmeddahy1](https://linkedin.com/in/ahmeddahy1)
- GitHub: [github.com/ahmeddahy134](https://github.com/ahmeddahy134)

---

**Built with ❤️ by Ahmed Dahy Shaban**

*Building secure, scalable web solutions with passion and precision.*
