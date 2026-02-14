# Vedika S Kumbhar - Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript showcasing projects, skills, and achievements.

## 🚀 Features

### ✨ Modern Design
- Clean, professional interface with gradient accents
- Smooth animations and transitions
- Responsive design for all devices
- Dark/Light theme toggle
- Floating elements and parallax effects

### 📱 Responsive & Interactive
- Mobile-first responsive design
- Interactive navigation with smooth scrolling
- Animated project cards with hover effects
- Contact form with validation
- Social media integration

### 🎨 Visual Effects
- Typing animation for hero title
- Scroll-triggered animations
- Parallax scrolling effects
- Floating skill cards
- Gradient backgrounds and glassmorphism

### ⚡ Performance
- Optimized loading with lazy animations
- Debounced scroll events
- Efficient DOM manipulation
- Semantic HTML5 structure

## 📁 Project Structure

```
PF/
├── index.html          # Main HTML file
├── styles.css          # Complete styling with animations
├── script.js           # Interactive JavaScript features
└── README.md           # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with animations, gradients, and transitions
- **JavaScript (ES6+)**: Interactive features and animations
- **Font Awesome**: Icons for social links and UI elements
- **Google Fonts**: Inter font for typography

## 🌟 Key Features

### Navigation
- Fixed header with scroll effects
- Mobile hamburger menu
- Active link highlighting
- Smooth scroll to sections

### Hero Section
- Animated typing effect
- Floating skill cards
- Call-to-action buttons
- Social media links

### About Section
- Professional introduction
- Interactive skills grid
- Animated skill items

### Projects Showcase
- Card-based layout
- Technology tags
- GitHub integration
- Hover animations

### Achievements
- Certification cards
- External links to certificates
- Icon-based visual hierarchy

### Contact Section
- Functional contact form
- Contact information display
- Social media links
- Form validation

## 🎨 Customization

### Changing Colors
Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #667eea;    /* Primary brand color */
    --secondary-color: #764ba2;  /* Secondary accent color */
    --accent-color: #f093fb;     /* Additional accent */
}
```

### Adding Projects
Add new project cards in the `projects` section of `index.html`:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-your-icon"></i>
    </div>
    <div class="project-content">
        <h3>Your Project Title</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology</span>
        </div>
        <div class="project-links">
            <a href="your-github-link" class="project-link">
                <i class="fab fa-github"></i> GitHub
            </a>
        </div>
    </div>
</div>
```

### Updating Skills
Modify the skills grid in the `about` section:

```html
<div class="skill-item">
    <i class="fas fa-your-icon"></i>
    <span>Your Skill</span>
</div>
```

## 🚀 Deployment

### GitHub Pages
1. Push the files to your GitHub repository
2. Go to repository Settings → Pages
3. Select source as "Deploy from a branch"
4. Choose main branch and save
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Netlify
1. Create a Netlify account
2. Drag and drop the project folder
3. Your site will be deployed instantly

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run: `vercel` in the project directory
3. Follow the prompts to deploy

## 📱 Mobile Optimization

The website is fully responsive and optimized for:
- Mobile phones (320px+)
- Tablets (768px+)
- Desktops (1024px+)
- Large screens (1200px+)

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## ⚡ Performance Features

- Lazy loading animations
- Optimized images and assets
- Minimal external dependencies
- Efficient CSS animations
- Debounced scroll events

## 🔧 Configuration

### Contact Form
The contact form currently shows a success message. To make it functional:
1. Add a backend service (Formspree, Netlify Forms, etc.)
2. Update the form action in `index.html`
3. Configure the service to receive submissions

### Analytics
Add Google Analytics or other tracking by including the script in the `<head>` section of `index.html`.

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📞 Support

For any questions or support, please reach out:
- Email: vedikakumbhar1007@gmail.com
- GitHub: @Vedika-creates

---

**Built with ❤️ using HTML, CSS, and JavaScript**
