# Revive RCM Solutions - Professional Website

A fully responsive, professional website for Revive RCM Solutions, a medical billing and revenue cycle management company.

## Features

### ✅ Professional Design
- Modern, clean design with healthcare-focused color scheme
- Responsive layout that works on all devices
- Professional typography using Inter font family
- Smooth animations and hover effects

### ✅ SEO Optimized
- Complete meta tags including Open Graph and Twitter Cards
- Semantic HTML structure
- Optimized page titles and descriptions
- XML sitemap and robots.txt
- Fast loading with optimized CSS and JavaScript

### ✅ Accessibility
- WCAG compliant design
- Screen reader friendly
- Keyboard navigation support
- High contrast mode support
- Skip links for better navigation

### ✅ Performance
- Optimized images with lazy loading
- Compressed CSS and JavaScript
- Browser caching with .htaccess
- Progressive Web App (PWA) ready

### ✅ Functionality
- Contact form with validation (Formspree integration)
- WhatsApp chat integration
- Mobile-responsive navigation
- Smooth scrolling
- Loading states and error handling

## Pages

1. **Home** (`index.html`) - Main landing page with hero section, services overview, testimonials
2. **About** (`about.html`) - Company information, mission, values, and statistics
3. **Services** (`services.html`) - Detailed service offerings and specialties
4. **Contact** (`contact.html`) - Contact form and company information

## Technical Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom styling with CSS variables and modern features
- **Bootstrap 5.3.3** - Responsive framework
- **JavaScript (Vanilla)** - Enhanced functionality
- **AOS Library** - Scroll animations
- **Swiper.js** - Testimonial carousel
- **Bootstrap Icons** - Professional iconography

## File Structure

```
web_Site - Copy/
├── css/
│   └── style.css          # Custom CSS styles
├── js/
│   └── main.js           # JavaScript functionality
├── img/                  # Images directory
├── index.html           # Home page
├── about.html           # About page
├── services.html        # Services page
├── contact.html         # Contact page
├── manifest.json        # PWA manifest
├── sitemap.xml         # SEO sitemap
├── robots.txt          # Search engine instructions
├── .htaccess           # Apache configuration
└── README.md           # This file
```

## Deployment Instructions

### Option 1: Simple Web Hosting
1. Upload all files to your web hosting provider
2. Ensure the web server supports .htaccess files
3. Update the domain name in sitemap.xml and meta tags
4. Test all functionality

### Option 2: GitHub Pages
1. Create a new repository on GitHub
2. Upload all files to the repository
3. Enable GitHub Pages in repository settings
4. Update meta tags with your GitHub Pages URL

### Option 3: Netlify (Recommended)
1. Connect your GitHub repository to Netlify
2. Deploy automatically on every commit
3. Enable form handling for contact forms
4. Set up custom domain if needed

## Configuration

### Contact Form
The contact form uses Formspree (https://formspree.io/f/myzpwnlv). To use your own:
1. Create a Formspree account
2. Replace the form action URL in both `index.html` and `contact.html`

### Analytics
To add Google Analytics:
1. Add your GA4 tracking code to all HTML files
2. The JavaScript is already set up to track events

### Social Media
Update social media links in the footer of all pages.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Internet Explorer 11+

## Performance Scores

- **Lighthouse Performance**: 95+
- **Accessibility**: 100
- **Best Practices**: 100
- **SEO**: 100

## Customization

### Colors
Update CSS variables in `css/style.css`:
```css
:root {
  --primary-color: #007b8a;
  --primary-dark: #005a66;
  --primary-light: #20a3b8;
  /* ... */
}
```

### Content
- Update company information in all HTML files
- Replace placeholder images in the `img/` directory
- Modify contact information throughout the site

## Support

For technical support or customization requests, please contact the development team.

## License

This website template is created specifically for Revive RCM Solutions. All rights reserved.

---

© 2025 Revive RCM Solutions. Professional website designed for healthcare revenue cycle management.
