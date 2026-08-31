# Your Band Website

A modern, responsive website to showcase your band's music, social media, and get in touch with fans.

## Features

- 🎵 **Music Section** - Display your tracks with links to streaming platforms
- 📱 **Social Media Links** - Connect to all your social channels
- ✉️ **Contact Form** - Allow fans to reach out for bookings and collaborations
- 📱 **Fully Responsive** - Works great on desktop, tablet, and mobile devices
- ⚡ **Fast & Lightweight** - Pure HTML, CSS, and JavaScript (no frameworks needed)

## Quick Start

1. Open `index.html` in your web browser
2. Customize the content with your band information:
   - Band name
   - Song titles and album names
   - Social media links
   - Contact email

## File Structure

```
.
├── index.html       # Main HTML file with page structure
├── styles.css       # Styling and responsive design
├── script.js        # JavaScript for interactivity
└── README.md        # This file
```

## Customization Guide

### 1. Update Band Information
Open `index.html` and replace:
- `Your Band Name` with your actual band name
- `Your Band` in the logo
- Song titles and album names in the Music section

### 2. Add Social Media Links
In the Socials section, update the `href="#"` with your actual social media URLs:
```html
<a href="https://instagram.com/yourband" class="social-icon">📷 Instagram</a>
```

### 3. Music Platform Links
Update the Spotify and Apple Music links in the music cards:
```html
<a href="https://open.spotify.com/artist/..." class="music-link">Spotify</a>
```

### 4. Contact Email
Update the contact email at the bottom of the Contact section:
```html
<a href="mailto:your-email@example.com">your-email@example.com</a>
```

### 5. Styling
Customize colors by editing the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #1a1a1a;      /* Dark background */
    --secondary-color: #ff6b35;    /* Orange accent */
    --accent-color: #f7931e;       /* Gold accent */
    --text-light: #f0f0f0;         /* Light text */
    --text-dark: #333;             /* Dark text */
}
```

## How to Deploy

### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Push your files to the repository
3. Go to Settings → Pages
4. Select your branch as the source
5. Your site will be live at `https://yourusername.github.io/repo-name`

### Option 2: Netlify (Free)
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your project folder
3. Your site will be live instantly

### Option 3: Any Web Host
Upload all files to your web host's public directory.

## Features Included

- Smooth scrolling navigation
- Responsive grid layout for music cards
- Form validation
- Hover effects and animations
- Mobile-optimized design
- Sticky navigation bar

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Notes

- The contact form currently shows an alert when submitted. To make it fully functional, you'll need a backend service or use a service like Formspree or Netlify Forms.
- Replace the emoji placeholders (🎵) with actual album artwork or band photos for a more professional look.
- Consider adding a favicon by placing a `favicon.ico` file in the root directory.

## License

This project is open source and available for personal and commercial use.

---

Enjoy! 🎸🎹🎤
