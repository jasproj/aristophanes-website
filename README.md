# Aristo Phanes International Website

A professional, multi-page website for Aristo Phanes International - a global business consulting firm.

## Features

- **Multi-page structure**: Home, About, Services, Industries, Contact
- **Responsive design**: Works seamlessly on desktop, tablet, and mobile devices
- **Sophisticated black and gold color scheme**: Elegant and professional aesthetic
- **Contact form**: Integrated email functionality for client inquiries
- **Global presence showcase**: Highlighting operations in 7 key markets
- **Multi-industry expertise**: Covering 7 major industry sectors
- **Smooth animations**: Professional transitions and interactive elements

## Pages

1. **Home (index.html)**: Hero section, company overview, services preview, industries preview
2. **About (about.html)**: Company history, mission, values, global presence
3. **Services (services.html)**: Comprehensive consulting services breakdown
4. **Industries (industries.html)**: Detailed industry sector information
5. **Contact (contact.html)**: Contact information and inquiry form

## Technologies Used

- HTML5
- CSS3 with custom properties (CSS variables)
- Vanilla JavaScript (no frameworks required)
- Google Fonts (Cinzel, Crimson Pro, Montserrat)
- Responsive design with CSS Grid and Flexbox

## Deployment to GitHub Pages

### Option 1: Using an existing repository

1. Upload all files to your GitHub repository
2. Go to repository Settings
3. Navigate to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Select your branch (usually "main" or "master")
6. Select the folder: "/" (root)
7. Click "Save"
8. Your site will be published at: `https://yourusername.github.io/repository-name`

### Option 2: Using a custom domain (aristophanesintinc.com)

1. Follow steps 1-7 from Option 1
2. In your domain registrar (where you bought aristophanesintinc.com):
   - Add a CNAME record pointing to: `yourusername.github.io`
   - Or add A records pointing to GitHub's IP addresses:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
3. Back in GitHub Pages settings, enter "aristophanesintinc.com" in the Custom domain field
4. Check "Enforce HTTPS" for security
5. Wait for DNS propagation (can take up to 24 hours)

## File Structure

```
aristo-phanes-site/
├── index.html          # Home page
├── about.html          # About Us page
├── services.html       # Services page
├── industries.html     # Industries page
├── contact.html        # Contact page
├── styles.css          # Main stylesheet
├── script.js           # JavaScript functionality
├── logo.jpeg           # Company logo
└── README.md           # This file
```

## Customization

### Colors
All colors are defined as CSS variables in `styles.css`:
- `--gold`: Main gold color (#C9A961)
- `--black`: Background color (#0A0A0A)
- Modify these in the `:root` selector to change the entire color scheme

### Content
- All text content is in the HTML files and can be easily edited
- Contact information is in the footer of each page
- Update phone/email/address as needed

### Images
- Replace `logo.jpeg` with your logo file
- Additional images can be added to enhance content sections

## Contact Form

The contact form uses a mailto: link that opens the user's email client with pre-filled information. For a production environment, you may want to integrate with:
- Formspree
- Netlify Forms
- EmailJS
- Your own backend service

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Lightweight: No heavy frameworks or libraries
- Fast loading: Minimal dependencies
- Optimized CSS: Uses modern CSS features for efficiency
- Smooth animations: CSS-based animations for performance

## License

Copyright © 2024 Aristo Phanes International. All rights reserved.

## Support

For questions or assistance with the website, contact:
- Email: info@cladutacorp.com
- Phone: +1 (305) 747-3779
