# Responsive Portfolio Website Template (HTML, CSS, JS)

A clean, modern, and fully responsive portfolio website template built with HTML, CSS, and JavaScript. Perfect for developers, designers, students, and freelancers who want a professional online presence.

**No frameworks. No dependencies. Just clean code.**
 
>**Note:** This is a free preview version. The full package includes additional features, priority support, and lifetime updates. [Get it here](https://gumroad.com/yourlink).

---
## Features

- Fully responsive (desktop, tablet, mobile)
- Dark mode toggle with persistent storage
- Typing animation in hero section
- Animated statistics counters
- Filterable project gallery
- Client testimonials section
- Working contact form (EmailJS integration)
- Smooth scroll animations
- Mobile-friendly navigation
- Scroll-to-top button
- Clean, well-commented code
- Easy to customize
- No frameworks required

## What's Included

- `index.html` — main page
- `/css` — CSS styles with variables
- `/js` — JavaScript files
- `/assets` — images and icons
- Documentation (this README.md)

## Who This Is For

- Beginners learning web development
- Freelancers building their portfolio
- Students showcasing projects
- Designers displaying their work
- Developers wanting a professional site quickly
- Anyone needing a modern online presence

## How to Use

1. Download or clone the repository
2. Open `index.html` in your browser to see the template
3. Edit content in HTML (look for `<!-- EDIT: -->` comments)
4. Customize colors in `css/styles.css` using CSS variables
5. Replace images in `/assets/images/` with your own
6. Deploy to GitHub Pages, Netlify, Vercel, or any hosting

## Customization Guide

### Changing Colors

Edit CSS variables in `css/styles.css`:
```css
:root {
  --accent-primary: #3b82f6;
  --bg-primary: #ffffff;
  --text-primary: #1e293b;
}
```

### Typing Animation

Update phrases in `js/script.js`:
```javascript
const phrases = [
  "Front-End Developer",
  "UI/UX Designer",
  "Your Title Here"
];
```

### Adding Projects

Duplicate a project card in `index.html`:
```html
<article class="project-card" data-category="web">
  <!-- Your project details -->
</article>
```

Available categories: `web`, `app`, `ui`

### Contact Form Setup (Optional)

The template uses EmailJS for a working contact form (no backend needed):

1. Create a free account at [emailjs.com](https://www.emailjs.com/)
2. Add an email service and create a template
3. Update your credentials in `js/script.js`:
```javascript
const EMAILJS_CONFIG = {
  serviceID: "your_service_id",
  templateID: "your_template_id",
  publicKey: "your_public_key"
};
```

4. Uncomment the initialization line in the script

## File Structure
```
portfolio-template/
├── index.html              # Main HTML file
├── css/
│   └── styles.css          # All styles with CSS variables
├── js/
│   └── script.js           # All JavaScript functionality
├── assets/
│   └── images/             # Image assets
└── README.md               # Documentation
```

## Sections Included

- Hero section with typing animation
- Animated statistics counters (projects, clients, experience)
- About section with skills showcase
- Filterable projects gallery
- Client testimonials with ratings
- Contact form with social media links
- Professional footer

## Deployment

Deploy to any static hosting platform:

- **GitHub Pages** — Enable in repository settings
- **Netlify** — Drag and drop your folder or connect GitHub
- **Vercel** — Import from GitHub repository
- **Traditional hosting** — Upload via FTP/cPanel

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Tips

- Optimize images before uploading (use TinyPNG or similar)
- Change colors, fonts, and sections in the CSS for a unique look
- Add your own projects and images to the portfolio section
- Keep the folder structure intact for smooth customization
- Update meta tags in HTML for better SEO
- Test on multiple devices before deploying

## Troubleshooting

**Contact form not working?**
- Check that EmailJS credentials are correct in `script.js`
- Verify your email service is connected in EmailJS dashboard
- Check browser console for errors (press F12)

**Animations not playing?**
- Clear your browser cache
- Ensure JavaScript is enabled
- Check console for JavaScript errors

**Mobile menu not opening?**
- Verify `script.js` is loading correctly
- Check for conflicting JavaScript code

## License

MIT License — Free to use for personal and commercial projects.

## Support

If you have questions or need help customizing:

- Open an issue on GitHub
- Check existing issues for solutions
- Review the code comments for guidance
- Contact via PixelyCode support channels

## Contributing

Contributions are welcome! Feel free to:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

---

Made by PixelyCode

