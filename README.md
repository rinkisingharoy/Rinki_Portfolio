# Animated Portfolio

A modern, responsive, and animated portfolio website built with HTML, CSS, and JavaScript. This portfolio features smooth animations, interactive elements, and a professional design that showcases your skills and projects effectively.

## 🚀 Features

### ✨ Animations & Effects
- **Smooth scroll animations** with Intersection Observer API
- **Typing effect** for hero section titles
- **Floating cards** with parallax effects
- **Skill bar animations** that fill up when scrolled into view
- **Counter animations** for statistics
- **Hover effects** on project cards and buttons
- **Particle background** for visual appeal
- **Loading animation** on page load

### 📱 Responsive Design
- Fully responsive layout that works on all devices
- Mobile-friendly navigation with hamburger menu
- Adaptive grid layouts for different screen sizes
- Touch-friendly interactive elements

### 🎨 Modern Design
- Clean and professional design with gradient backgrounds
- Glassmorphism effects with backdrop blur
- Modern typography using Google Fonts (Poppins)
- Consistent color scheme with purple-blue gradients
- Smooth transitions and micro-interactions

### 🔧 Interactive Features
- **Navigation**: Smooth scrolling to sections
- **Contact Form**: Functional form with validation
- **Project Cards**: Hover effects and links
- **Skill Bars**: Animated progress indicators
- **Statistics**: Animated counters
- **Scroll to Top**: Button appears when scrolling down

## 📁 File Structure

```
animated-portfolio/
├── index.html          # Main HTML structure
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Icons for visual elements
- **Google Fonts**: Typography (Poppins)

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation
1. Download or clone the project files
2. Open `index.html` in your web browser
3. The portfolio will load with all animations and functionality

### Customization

#### Personal Information
Edit the following sections in `index.html`:

```html
<!-- Hero Section -->
<span class="title-line highlight">Your Name</span>
<span class="title-line">Your Title</span>

<!-- About Section -->
<p class="about-description">Your personal description...</p>

<!-- Contact Information -->
<p>your.email@example.com</p>
<p>+1 (555) 123-4567</p>
<p>Your Location</p>
```

#### Skills
Update the skills section with your own:

```html
<div class="skill-item" data-skill="Your Skill" data-percentage="85">
    <div class="skill-info">
        <span class="skill-name">Your Skill</span>
        <span class="skill-percentage">85%</span>
    </div>
    <div class="skill-bar">
        <div class="skill-progress"></div>
    </div>
</div>
```

#### Projects
Replace the project cards with your own:

```html
<div class="project-card">
    <div class="project-image">
        <div class="image-placeholder">
            <i class="fas fa-laptop-code"></i>
        </div>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link">Live Demo</a>
            <a href="#" class="project-link">GitHub</a>
        </div>
    </div>
</div>
```

#### Statistics
Update the statistics in the About section:

```html
<div class="stat-item">
    <span class="stat-number" data-target="50">0</span>
    <span class="stat-label">Your Stat</span>
</div>
```

#### Colors
Customize the color scheme in `styles.css`:

```css
/* Primary gradient colors */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Accent color */
color: #ffd700;
```

## 🎯 Key Features Explained

### 1. Smooth Animations
The portfolio uses CSS animations and JavaScript to create smooth, engaging animations that trigger when elements come into view.

### 2. Intersection Observer
JavaScript uses the Intersection Observer API to detect when elements enter the viewport and trigger animations accordingly.

### 3. Responsive Design
The layout uses CSS Grid and Flexbox to create a responsive design that adapts to different screen sizes.

### 4. Interactive Elements
- Navigation with smooth scrolling
- Contact form with validation
- Hover effects on cards and buttons
- Animated skill bars
- Counter animations

### 5. Performance Optimized
- Efficient animations using CSS transforms
- Lazy loading of animations
- Optimized JavaScript with event delegation
- Minimal dependencies

## 🎨 Customization Tips

### Adding New Sections
1. Add the HTML structure in `index.html`
2. Add corresponding styles in `styles.css`
3. Add any JavaScript functionality in `script.js`

### Changing Animations
Modify the CSS animations in `styles.css`:

```css
@keyframes fadeInUp {
    to {
        opacity: 1;
        transform: translateY(0);
    }
}
```

### Adding New Features
The modular JavaScript structure makes it easy to add new features:

```javascript
function initNewFeature() {
    // Your new functionality here
}

// Add to the DOMContentLoaded event listener
document.addEventListener('DOMContentLoaded', function() {
    // ... existing initializations
    initNewFeature();
});
```

## 🌟 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📱 Mobile Support

The portfolio is fully responsive and works great on:
- Smartphones (iOS/Android)
- Tablets
- Desktop computers

## 🔧 Troubleshooting

### Animations Not Working
- Ensure JavaScript is enabled in your browser
- Check the browser console for any errors
- Verify that all files are in the same directory

### Styling Issues
- Clear browser cache
- Check that `styles.css` is properly linked
- Verify CSS syntax in browser developer tools

### Performance Issues
- Disable particle effects if needed (comment out `addParticleBackground()` in `script.js`)
- Reduce animation complexity for older devices

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to contribute to this project by:
- Reporting bugs
- Suggesting new features
- Submitting pull requests
- Improving documentation

## 📞 Support

If you have any questions or need help customizing the portfolio, feel free to reach out!

---

**Enjoy your new animated portfolio! 🎉** 