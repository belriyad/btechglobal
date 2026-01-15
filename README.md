# B Tech Global LLC Website

Professional consulting firm website for B Tech Global LLC, a technology and AI consulting company based in Doha, Qatar.

## About B Tech Global

B Tech Global LLC helps startups, founders, and organizations adopt AI, product strategy, and structured execution to move from idea to impact. The firm specializes in:

- AI enablement for non-technical founders
- Startup advisory
- Product management consulting
- Innovation programs for schools and institutions across Qatar and the GCC

## Website Structure

The website consists of the following pages:

- **Home** (`index.html`) - Clear value proposition and overview
- **About Us** (`about.html`) - Mission, vision, and values
- **Services** (`services.html`) - Detailed service offerings
- **Programs** (`programs.html`) - Structured learning and development programs
- **Why Us** (`why-us.html`) - Differentiators and approach
- **Contact** (`contact.html`) - Contact information and inquiry form

## Technology Stack

- **HTML5** - Semantic markup with SEO optimization
- **CSS3** - Modern, responsive design with custom properties
- **Vanilla JavaScript** - Interactive features without dependencies
- **Google Fonts** - Inter font family for clean typography

## Design Features

- Clean, professional consulting aesthetic
- Deep blue (#1a3a52) and dark green (#1b4332) primary colors
- Gold accents (#d4af37) for premium feel
- Mobile-first responsive design
- Accessible and SEO-optimized
- Fast loading with minimal dependencies

## Deployment

### Option 1: Static Hosting (Recommended)

Deploy to any static hosting service:

#### GitHub Pages
1. Go to repository Settings > Pages
2. Select branch: `main` or `copilot/create-consulting-firm-website`
3. Select folder: `/ (root)`
4. Click Save
5. Your site will be available at: `https://yourusername.github.io/btechglobal/`

#### Netlify
1. Sign up at [netlify.com](https://netlify.com)
2. Click "Add new site" > "Import an existing project"
3. Connect your GitHub repository
4. Set build settings:
   - Build command: (leave empty)
   - Publish directory: `/`
5. Click "Deploy site"

#### Vercel
1. Sign up at [vercel.com](https://vercel.com)
2. Click "New Project"
3. Import your GitHub repository
4. Framework Preset: Other
5. Click "Deploy"

#### Cloudflare Pages
1. Sign up at [pages.cloudflare.com](https://pages.cloudflare.com)
2. Click "Create a project"
3. Connect your GitHub repository
4. Build settings:
   - Build command: (leave empty)
   - Build output directory: `/`
5. Click "Save and Deploy"

### Option 2: Traditional Web Hosting

Upload all files to your web hosting provider via FTP/SFTP:

1. Connect to your hosting via FTP client (FileZilla, Cyberduck, etc.)
2. Upload all files to the `public_html` or `www` directory
3. Ensure `index.html` is in the root directory
4. Set appropriate file permissions (644 for files, 755 for directories)

### Option 3: Custom Domain

After deploying to any hosting service:

1. Purchase domain at your preferred registrar
2. Add DNS records:
   - A record pointing to your hosting IP, or
   - CNAME record pointing to your hosting service
3. Update the base URL in `sitemap.xml`
4. Update Open Graph URLs in HTML meta tags

## Customization

### Contact Form Backend

The contact form currently shows a demo success message. To make it functional:

1. **Option A - Use a form service:**
   - [Formspree](https://formspree.io/)
   - [Netlify Forms](https://www.netlify.com/products/forms/)
   - [Form.io](https://form.io/)

2. **Option B - Build custom backend:**
   - Create an API endpoint to receive form submissions
   - Update the AJAX call in `script.js` (line ~90)
   - Add email notification service

### Analytics

Add Google Analytics or other analytics:

1. Create an account at [analytics.google.com](https://analytics.google.com)
2. Get your tracking ID
3. Add the tracking script before `</head>` in all HTML files

### SEO Improvements

1. Update the domain name in `sitemap.xml` and all Open Graph tags
2. Submit sitemap to Google Search Console
3. Verify site in Bing Webmaster Tools
4. Add schema.org structured data for better rich snippets

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Minimal external dependencies (only Google Fonts)
- Optimized CSS with custom properties
- Vanilla JavaScript (no framework overhead)
- Semantic HTML for faster parsing
- Mobile-first responsive design

## Accessibility

- Semantic HTML5 elements
- ARIA labels where appropriate
- Keyboard navigation support
- Focus indicators for interactive elements
- Alt text ready for images
- Proper heading hierarchy

## SEO Features

- Meta descriptions on all pages
- Open Graph tags for social sharing
- Structured heading hierarchy
- Semantic HTML
- robots.txt for crawler instructions
- XML sitemap for search engines
- Mobile-friendly design
- Fast loading times
- Descriptive URLs and anchor text

## Contact Information

- **Email:** info@btechgloballlc.com
- **Phone/WhatsApp:** +974 520 46 176
- **Location:** Doha, Qatar

## License

© 2026 B Tech Global LLC. All rights reserved.

## Support

For issues or questions about the website, please contact the development team or open an issue in this repository.