# Levi Bickel - Personal Promotion Website

A modern, minimal personal portfolio website showcasing professional skills, projects, and contact information.

## 🚀 Quick Start

Simply open `index.html` in any web browser to view the website locally.

## 📁 Project Structure

```
PersonalPromotionWebsite/
├── index.html          # Main HTML structure
├── styles.css          # All styling and responsive design
├── script.js           # Interactive features and animations
├── assets/             # Directory for images and resources
└── README.md           # This file
```

## ✨ Features

### Sections
- **Hero Section**: Eye-catching introduction with name, title, and call-to-action buttons
- **About Section**: Professional summary, education, and experience highlights
- **Skills Section**: Technical skills organized by category
- **Projects Section**: Portfolio of featured projects with descriptions and tech stacks
- **Contact Section**: Contact information and professional links

### Interactive Features
- Smooth scrolling navigation
- Mobile-responsive hamburger menu
- Active navigation link highlighting based on scroll position
- Fade-in animations on scroll
- Hover effects on cards and buttons
- Accessible keyboard navigation

### Technical Highlights
- **Mobile-First Design**: Fully responsive from mobile to desktop
- **Modern CSS**: CSS variables for easy theming, Flexbox/Grid layouts
- **Vanilla JavaScript**: No dependencies, lightweight and fast
- **Accessibility**: Semantic HTML5, ARIA labels, keyboard navigation
- **Performance**: Optimized for fast loading, respects reduced motion preferences

## 🎨 Customization

### Colors
Edit the CSS variables in `styles.css` to change the color scheme:

```css
:root {
    --primary-color: #2563eb;      /* Main brand color */
    --primary-dark: #1e40af;       /* Darker shade */
    --secondary-color: #64748b;    /* Secondary text */
    --accent-color: #0ea5e9;       /* Accent highlights */
    /* ... more variables */
}
```

### Content
Edit `index.html` to update:
- Personal information
- Skills and certifications
- Project descriptions
- Contact details

### Adding Images
1. Place images in the `assets/` directory
2. Update image paths in `index.html`
3. For the profile photo, replace the `.hero-badge` content with an `<img>` tag

Example:
```html
<div class="hero-badge">
    <img src="assets/profile.jpg" alt="Levi Bickel" style="border-radius: 1rem;">
</div>
```

## 📱 Responsive Design

The website is fully responsive and optimized for:
- Mobile phones (320px and up)
- Tablets (768px and up)
- Desktops (1024px and up)

## 🌐 Deployment Options

### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Push your code to the repository
3. Go to Settings → Pages
4. Select branch and `/root` directory
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free)
1. Create a free account at [Netlify](https://www.netlify.com)
2. Drag and drop your project folder
3. Site is instantly deployed with a custom URL
4. Optional: Connect to GitHub for automatic deployments

### Option 3: Vercel (Free)
1. Create a free account at [Vercel](https://vercel.com)
2. Import your project from GitHub or upload files
3. Automatic deployment and custom domain support

### Option 4: Traditional Web Hosting
1. Upload all files to your web hosting via FTP
2. Ensure `index.html` is in the root directory
3. Access via your domain name

## 🔧 Browser Support

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Opera (latest)

## 📄 License

This is a personal portfolio website. Feel free to use the code as inspiration for your own portfolio, but please don't use the personal content (name, projects, etc.).

## 📞 Contact

**Levi Bickel**
- Email: levibickel@gmail.com
- LinkedIn: [linkedin.com/in/levibickel](https://linkedin.com/in/levibickel)
- GitHub: [github.com/LeviBickel](https://github.com/LeviBickel)
- Location: South Bend, IN

---

**Built with HTML, CSS, and JavaScript** | No frameworks, no build tools, just clean code.
