# WRAB Elteknik Website

A modern, responsive website for WRAB Elteknik - an electrical installation company based in Växjö, Småland, Sweden.

## Features

- **Responsive Design**: Works perfectly on mobile, tablet, and desktop
- **Modern UI**: Clean, professional design with WRAB Elteknik branding
- **Contact Form**: Netlify Forms integration with file upload support
- **Image Gallery**: Filterable reference images with lightbox functionality
- **SEO Optimized**: Proper meta tags, titles, and alt attributes
- **Fast Loading**: Optimized images and efficient CSS/JavaScript

## Pages

1. **Hem (Home)** - Hero section with floating icons and company overview
2. **Om Oss (About)** - Company information and background
3. **Tjänster (Services)** - Detailed list of electrical services offered
4. **Referensbilder (References)** - Project gallery with filtering
5. **Kontakt (Contact)** - Contact form and company details

## Technology Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **JavaScript**: Vanilla JS for interactivity
- **Netlify**: Hosting and form handling
- **Google Fonts**: Inter font family

## Deployment

### Netlify Deployment

1. **Connect Repository**: Link your GitHub/GitLab repository to Netlify
2. **Build Settings**: 
   - Build command: `echo 'No build step required'`
   - Publish directory: `.` (root)
3. **Environment Variables**: None required
4. **Form Handling**: Netlify Forms will automatically handle the contact form

### Manual Deployment

1. Upload all files to your web server
2. Ensure the `netlify.toml` file is in the root directory
3. Configure your server to serve static files

## Customization

### Colors
The website uses CSS custom properties for easy color customization:
- Primary Orange: `#fe7b00`
- Primary Blue: `#059ad2`

### Content
- Update company information in each HTML file
- Replace placeholder images with actual project photos
- Modify service descriptions as needed

### Contact Information
Update contact details in:
- All HTML files (footer sections)
- Contact page sidebar
- Quick contact section

## Form Configuration

The contact form is configured for Netlify Forms with:
- Name (required)
- Email (required)
- Phone (optional)
- Service type (dropdown)
- Message (required)
- File upload (optional)
- reCAPTCHA protection

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- Optimized images with proper sizing
- Efficient CSS with minimal redundancy
- Vanilla JavaScript for fast loading
- Netlify CDN for global delivery

## License

© 2024 WRAB Elteknik. All rights reserved.

## Contact

For technical support or questions about this website:
- Email: info@wrab-el.se
- Phone: 0733768058
