# AI Services Studio Website

A modern, clean, conversion-focused website for a small AI services studio.

## Features

- Single-page responsive design
- Clean, minimal aesthetic with strong typography
- Smooth scrolling navigation
- Contact form with email integration
- Fade-in animations on scroll

## Setup

### Form Email Integration

The contact form is configured to send submissions to **davidemiron30@gmail.com** using Formspree.

**To activate the form:**

1. Go to [formspree.io](https://formspree.io)
2. Sign up with your email (davidemiron30@gmail.com)
3. Create a new form
4. Copy your form ID (it looks like: `xeoqqbbg`)
5. Replace the form ID in `index.html` line 131:

```html
<form id="quote-form" class="quote-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

Replace `xeoqqbbg` with your actual form ID.

### First Submission

The first time someone submits the form, Formspree will send you a confirmation email. Click the confirmation link to activate the form.

## Files

- `index.html` - Main website structure
- `styles.css` - All styling and responsive design
- `script.js` - Form handling and interactions

## Customization

### Colors

Edit CSS variables in `styles.css` (lines 7-17):

```css
--color-bg-light: #ffffff;
--color-bg-dark: #0a0a0a;
--color-text-light: #f5f5f5;
--color-text-dark: #1a1a1a;
--color-accent: #2a2a2a;
```

### Logo/Brand Name

Change "AI Studio" in `index.html` line 14.

### Content

All text content is directly in `index.html` and can be edited as needed.

## Deployment

### Quick Deploy Options

1. **Netlify**: Drag and drop the folder
2. **Vercel**: Import from Git repository
3. **GitHub Pages**: Push to repository and enable Pages
4. **Any web host**: Upload all files via FTP

## Browser Support

Modern browsers (Chrome, Firefox, Safari, Edge)

## License

All rights reserved.
