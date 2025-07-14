# AJIB - Data Analyst Portfolio Website

A professional, modern single-page portfolio website for data analysts, built with HTML, CSS, and JavaScript. Fully responsive and optimized for GitHub Pages deployment.

## Features

- **Responsive Design**: Mobile-friendly layout that works on all devices
- **Modern Styling**: Clean, professional design with navy/teal color scheme
- **Interactive Navigation**: Smooth scrolling navigation with active section highlighting
- **Project Showcase**: Cards displaying data analysis projects with tools and links
- **Skills Section**: Organized display of technical skills and tools
- **Contact Form**: Functional contact form with validation and notifications
- **SEO Optimized**: Meta tags and semantic HTML for better search engine visibility
- **Accessible**: ARIA labels and semantic markup for screen readers

## Files Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── style.css           # CSS styling
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Customization

### Personal Information
Edit the following sections in `index.html`:

1. **Header**: Update name and title
2. **About Me**: Replace bio text and profile photo URL
3. **Projects**: Update project titles, descriptions, tools, and GitHub links
4. **Contact**: Change email address and form action
5. **Footer**: Update LinkedIn and GitHub profile links

### Styling
Modify `style.css` to change:
- Color scheme (search for `#2c3e50` and `#18bc9c`)
- Typography (font families and sizes)
- Layout and spacing

### Profile Photo
Replace the placeholder image URL in the About section:
```html
<img src="https://via.placeholder.com/300x300/2c3e50/ffffff?text=AJIB" alt="AJIB - Data Analyst professional photo" class="profile-photo">
```

## GitHub Pages Deployment

### Method 1: Direct Upload
1. Create a new repository on GitHub
2. Upload `index.html`, `style.css`, and `script.js` to the repository
3. Go to repository Settings → Pages
4. Select "Deploy from a branch" → "main" branch → "/ (root)"
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Method 2: Git Commands
```bash
# Clone or create your repository
git clone https://github.com/yourusername/your-portfolio-repo.git
cd your-portfolio-repo

# Copy the website files
cp index.html style.css script.js your-portfolio-repo/

# Commit and push
git add .
git commit -m "Add portfolio website"
git push origin main

# Enable GitHub Pages in repository settings
```

## Local Development

To test the website locally:

```bash
# Navigate to the project directory
cd portfolio-website

# Start a local server (Python 3)
python3 -m http.server 8000

# Or with Python 2
python -m SimpleHTTPServer 8000

# Or with Node.js
npx http-server

# Open http://localhost:8000 in your browser
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Features

- Optimized CSS with efficient selectors
- Minimal JavaScript for fast loading
- Responsive images and layouts
- Smooth animations with reduced motion support

## Accessibility Features

- Semantic HTML5 elements
- ARIA labels and roles
- Keyboard navigation support
- Screen reader friendly
- High contrast colors
- Focus indicators

## Contact Form

The contact form includes:
- Client-side validation
- Success/error notifications
- Form reset after submission
- Email format validation

**Note**: The form currently shows a success message but doesn't actually send emails. To make it functional, you'll need to:
1. Use a form service like Formspree, Netlify Forms, or EmailJS
2. Set up server-side processing
3. Update the form action attribute

## Google Analytics

To add Google Analytics:
1. Uncomment the GA code in the `<head>` section of `index.html`
2. Replace `GA_MEASUREMENT_ID` with your actual tracking ID

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

For questions or support, please open an issue in the GitHub repository.

---

**Ready to deploy!** Simply upload the files to your GitHub repository and enable GitHub Pages.
