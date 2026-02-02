# Tanusri Jammalamadaka - Portfolio Website

A modern, executive-level portfolio website showcasing MarTech & AI strategy leadership.

## Features

- **Dark/Light Mode**: Automatically detects system preference with manual toggle
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern Aesthetics**: Elegant navy/gold color scheme with sophisticated typography
- **Smooth Animations**: Scroll-triggered animations and hover effects
- **Accessible**: Semantic HTML with proper ARIA labels
- **Fast Loading**: Single HTML file with CDN-hosted dependencies
- **SEO Ready**: Meta tags and Open Graph support

## Theme Behavior

The website automatically:
1. Detects your system's dark/light mode preference on first visit
2. Remembers your manual selection in localStorage
3. Responds to system theme changes if no manual preference is set
4. Provides smooth transitions when switching themes

## Deploy to Netlify

### Option 1: Drag & Drop (Easiest)

1. Go to [app.netlify.com](https://app.netlify.com)
2. Log in or create an account
3. Drag the entire `tanusri-portfolio` folder onto the deploy dropzone
4. Your site will be live in seconds!

### Option 2: Git-based Deployment

1. Push this folder to a GitHub/GitLab/Bitbucket repository
2. Go to [app.netlify.com](https://app.netlify.com)
3. Click "Add new site" → "Import an existing project"
4. Connect your repository
5. Leave build settings as default (no build command needed)
6. Click "Deploy"

### Option 3: Netlify CLI

```bash
# Install Netlify CLI
npm install -g netlify-cli

# Login to Netlify
netlify login

# Deploy (from this folder)
netlify deploy --prod
```

## Customization

### Update Contact Information

In `index.html`, search for and update:
- Email: `jtanusri@gmail.com`
- Phone: `408-338-5374`
- LinkedIn: `linkedin.com/in/tanusrij`

### Update Colors

The color scheme is defined in the Tailwind config:
- `primary`: #0f172a (deep navy)
- `accent`: #d4af37 (gold)
- `secondary`: #334155 (slate)
- `cream`: #faf9f6 (background)

### Add a Custom Domain

1. In Netlify dashboard, go to Site settings → Domain management
2. Click "Add custom domain"
3. Follow DNS configuration instructions

## File Structure

```
tanusri-portfolio/
├── index.html      # Main website file
├── netlify.toml    # Netlify configuration
└── README.md       # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

© 2025 Tanusri Jammalamadaka. All rights reserved.
