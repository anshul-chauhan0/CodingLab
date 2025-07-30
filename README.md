# Professional Portfolio Website

A modern, responsive, and visually stunning portfolio website built with HTML5, CSS3, and JavaScript. Features clean UI/UX design, smooth animations, and mobile-first responsive layout.

## 🌟 Features

### Design & User Experience
- **Modern UI/UX**: Clean, professional design with attractive gradients and typography
- **Responsive Design**: Mobile-first approach that works perfectly on all devices
- **Smooth Animations**: CSS and JavaScript animations for enhanced user experience
- **Interactive Elements**: Hover effects, scroll animations, and dynamic content

### Sections
- **Hero Section**: Eye-catching introduction with profile image and social links
- **About**: Personal information with animated statistics counters
- **Skills**: Organized skill categories with technology icons
- **Projects**: Portfolio showcase with project cards and overlay effects
- **Experience**: Professional timeline with work history
- **Contact**: Contact form with validation and contact information

### Technical Features
- **Smooth Scrolling**: Navigation with smooth scroll behavior
- **Mobile Navigation**: Hamburger menu for mobile devices
- **Form Validation**: Client-side form validation with user feedback
- **Performance Optimized**: Throttled scroll events and optimized animations
- **Accessibility**: Proper focus states and semantic HTML
- **SEO Ready**: Semantic markup and meta tags

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- Basic text editor (VS Code, Sublime Text, etc.)
- Optional: Local web server for development

### Installation

1. **Clone or Download** the project files
2. **Open** `index.html` in your web browser
3. **Or serve locally** using a web server:
   ```bash
   # Using Python
   python3 -m http.server 8000
   
   # Using Node.js (if you have live-server installed)
   npx live-server
   
   # Using PHP
   php -S localhost:8000
   ```

## 🎨 Customization

### Personal Information
Edit the following in `index.html`:
- Name and title in the hero section
- About section content
- Skills and technologies
- Project information
- Experience timeline
- Contact details

### Styling
Modify `style.css` to customize:
- **Colors**: Update CSS variables in `:root`
- **Fonts**: Change font imports and font-family values
- **Layout**: Adjust grid layouts and spacing
- **Animations**: Modify transition and animation properties

### Images
Replace images in the `img/` folder:
- `img1.jpg`: Hero and project images
- `favicon.png`: Browser favicon

### CSS Variables
The website uses CSS custom properties for easy theming:

```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #f093fb;
    --text-primary: #2d3748;
    --text-secondary: #4a5568;
    --text-light: #718096;
    /* ... more variables */
}
```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🔧 JavaScript Features

### Core Functionality
- Mobile navigation toggle
- Smooth scrolling navigation
- Active section highlighting
- Scroll-based navbar styling
- Intersection Observer animations

### Interactive Elements
- Typing effect for hero title
- Counter animations for statistics
- Project card hover effects
- Contact form validation
- Scroll-to-top button
- Custom notification system

### Performance Features
- Throttled scroll events
- Lazy loading ready
- Optimized animations
- Efficient DOM queries

## 🎯 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📋 File Structure

```
portfolio/
├── index.html          # Main HTML file
├── style.css           # CSS styles
├── script.js           # JavaScript functionality
├── README.md           # Documentation
└── img/
    ├── favicon.png     # Browser favicon
    └── img1.jpg        # Hero/project image
```

## 🚀 Deployment

### GitHub Pages
1. Push to GitHub repository
2. Go to Settings > Pages
3. Select source branch
4. Access via `https://username.github.io/repository-name`

### Netlify
1. Drag and drop folder to Netlify
2. Or connect GitHub repository
3. Auto-deploy on changes

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel`
3. Follow deployment prompts

## 🎨 Color Scheme

The website uses a modern gradient-based color scheme:

- **Primary**: Blue to Purple gradient (#667eea → #764ba2)
- **Accent**: Pink to Blue gradient (#f093fb → #667eea)
- **Text**: Dark grays for excellent readability
- **Background**: Clean whites and light grays

## 📝 Customization Guide

### Changing Colors
1. Open `style.css`
2. Modify the CSS variables in `:root`
3. The entire site will update automatically

### Adding New Sections
1. Add HTML structure in `index.html`
2. Add corresponding styles in `style.css`
3. Update navigation links
4. Add JavaScript functionality if needed

### Project Cards
To add new projects:
1. Copy existing `.project-card` structure
2. Update image, title, description, and tech tags
3. Add project links (live demo, GitHub)

## 🔍 SEO Optimization

- Semantic HTML5 structure
- Meta tags for description and keywords
- Alt attributes for images
- Proper heading hierarchy
- Clean URL structure

## 📞 Support

For questions or customization help:
- Check the code comments for guidance
- Modify the contact section with your information
- Test thoroughly after making changes

## 🎉 Features Showcase

### Animations
- Fade-in animations on scroll
- Smooth hover transitions
- Typing effect for hero title
- Counter animations for statistics
- Parallax effects

### Interactive Elements
- Mobile-friendly navigation
- Form validation with feedback
- Smooth scrolling between sections
- Dynamic navbar styling
- Project overlay effects

### Performance
- Optimized CSS with variables
- Efficient JavaScript
- Responsive images
- Minimal dependencies
- Fast loading times

---

**Built with ❤️ using modern web technologies**

*This portfolio template is designed to be easily customizable while maintaining professional quality and performance.*