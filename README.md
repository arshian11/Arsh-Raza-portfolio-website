# Portfolio Website

A modern, responsive portfolio website showcasing projects and skills.

## Features

- 🎨 Modern and elegant design
- 📱 Fully responsive layout
- ⚡ Fast loading and optimized
- 🎯 SEO-friendly structure
- 🌟 Smooth animations and interactions
- 📧 Contact form integration ready

## Technologies Used

- HTML5
- CSS3 (with modern features like Grid and Flexbox)
- Vanilla JavaScript
- Font Awesome icons
- Google Fonts

## Getting Started

### Prerequisites

- Node.js (for local development server)
- Git

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/portfolio-website.git
cd portfolio-website
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and visit `http://localhost:3000`

## Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your GitHub repository to Vercel
3. Deploy automatically with each push

### Netlify

1. Push your code to GitHub
2. Connect your GitHub repository to Netlify
3. Deploy automatically with each push

## Customization

### Adding Your Projects

Edit the projects section in `index.html`:

```html
<div class="project-card">
    <div class="project-image">
        <img src="your-project-image.jpg" alt="Project Name">
        <div class="project-overlay">
            <div class="project-links">
                <a href="https://github.com/yourusername/project" target="_blank" class="project-link">
                    <i class="fab fa-github"></i>
                </a>
                <a href="https://your-project-demo.com" target="_blank" class="project-link">
                    <i class="fas fa-external-link-alt"></i>
                </a>
            </div>
        </div>
    </div>
    <div class="project-content">
        <h3 class="project-title">Your Project Name</h3>
        <p class="project-description">
            Description of your project...
        </p>
        <div class="project-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
    </div>
</div>
```

### Updating Contact Information

Update the contact section in `index.html` with your actual information:

```html
<a href="mailto:your-email@example.com" class="contact-link">
    <i class="fas fa-envelope"></i>
    <span>your-email@example.com</span>
</a>
```

### Customizing Colors

Edit the CSS custom properties in `styles.css`:

```css
:root {
    --primary-color: #3182ce;
    --secondary-color: #667eea;
    --text-color: #2d3748;
    --bg-color: #ffffff;
}
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

Your Name - [your-email@example.com](mailto:your-email@example.com)

Project Link: [https://github.com/yourusername/portfolio-website](https://github.com/yourusername/portfolio-website)