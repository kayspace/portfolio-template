# Open Source Portfolio Template

A clean, minimal, easy and ready-to-go portfolio template built with pure HTML, CSS, JavaScript, and GSAP animations. Designed to be easily customizable and deployment-ready.

## Live Preview

[View Live Demo](https://opensource-portfolio-template.vercel.app)

## Features

- **Pure HTML/CSS/JS** - No frameworks, just vanilla web technologies
- **GSAP Animations** - Smooth, performant animations
- **CSS Variables** - Easy color and design customization
- **Responsive Design** - Works perfectly on all devices
- **Fast Loading** - Optimized for performance
- **Clean Typography** - Monospace fonts for a developer aesthetic
- **Text-Based Design** - No images required, fully text-based
- **Easy Customization** - Simple placeholder system

## Quick Start

1. **Clone or Download**
   ```bash
   git clone https://github.com/kayspace/portfolio-template.git
   cd portfolio-template
   ```

2. **Open in Browser**
   - Open `index.html` in your browser
   - Or use a local server (recommended)

3. **Customize Your Content**
   - Edit `index.html` to replace placeholder text
   - Modify colors in `styles.css` (CSS variables section)
   - Adjust animations in `script.js` if needed

## Customization Guide

### Replacing Placeholder Content

1. **Personal Information**
   - Replace `[Your Name]` with your actual name
   - Update `[Your Title/Role]` with your professional title
   - Change `[Your Description]` to your personal description

2. **Sections to Customize**
   - **Home**: Update tagline and description
   - **Work**: Replace with your actual projects
   - **Skills**: Add your real skills and technologies
   - **About**: Write your genuine story
   - **Contact**: Add your real contact information

### Color Customization

All colors are defined as CSS variables in `styles.css`:

```css
:root {
  --background: hsl(0, 0%, 100%);
  --secondary: hsl(0, 0%, 96%);
  --border: hsl(0, 0%, 80%);
  --text-primary: hsl(0, 0%, 10%);
  --text-secondary: hsl(0, 0%, 20%);
  /* ... more variables */
}
```

### Typography

The template uses monospace fonts. To change:

  - Go to google fonts, get ur desired fonts, and add thier respective tags in the `index.html` and change the font through css

```css
:root {
  --font-mono: 'Your Preferred Font', monospace;
}
```

### Layout Modifications

- Section spacing: Adjust `--section-padding` variable
- Container width: Modify `--container-max-width`
- Animation timing: Edit GSAP timeline values in `script.js`

## Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to [Vercel](https://vercel.com)
3. Deploy with default settings

### Netlify

1. Drag and drop the folder to [Netlify](https://netlify.com)
2. Or connect your GitHub repository

### GitHub Pages

1. Push to GitHub
2. Go to repository Settings > Pages
3. Set source to your main branch folder

## Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with custom properties
- **JavaScript** - Vanilla JS for interactions
- **GSAP** - Animation library
- **CSS Variables** - For easy theming

## Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

- Open an [issue](https://github.com/kayspace/portfolio-template/issues) for bugs
- Start a [discussion](https://github.com/kayspace/portfolio-template/discussions) for questions

## Author

**kayspace** - [GitHub Profile](https://github.com/kayspace)  

>*You’re free to fork, tweak, or use it as your base.
If you really like the theme and if it was really useful to you, you can [spare me a star ✪](https://github.com/kayspace/portfolio-template) hehe!*