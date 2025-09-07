# Hudā - Islamic App Website

A simple, clean website for the Hudā Islamic app featuring prayer times, Quran reading, daily duas, and more.

## Features

- **Simple & Clean Design**: Minimal, modern design focused on content
- **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Fast Loading**: Optimized for performance with minimal assets
- **No External Dependencies**: Uses only Google Fonts for typography

## Sections

1. **Hero Section**: Main landing area with app description and call-to-action
2. **Features**: Showcase of 6 key app features with emoji icons
3. **About**: Brief description and user statistics
4. **Contact**: Simple contact information
5. **Footer**: Links and copyright information

## App Features Highlighted

- 🕌 Prayer Times with notifications
- 📖 Quran Reader with translations
- 🤲 Daily Duas and Dhikr
- 🧭 Qibla Direction
- 📚 Islamic Lessons
- 📊 Progress Tracking

## Getting Started

### Prerequisites

- A modern web browser
- No additional setup required

### Installation

1. Download or clone the project files
2. Open `index.html` in your web browser
3. That's it! The site is ready to use

### File Structure

```
hudasite/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── logo.png            # App logo
└── README.md           # This file
```

## Customization

### Colors
The website uses a clean, minimal color scheme:
- Primary: `#333` (Dark Gray)
- Background: `#ffffff` (White)
- Light Background: `#f8f9fa` (Light Gray)
- Text: `#333` (Dark Gray)
- Secondary Text: `#666` (Medium Gray)

### Content Updates

#### Update App Features
Edit the features section in `index.html` to modify:
- Feature descriptions
- Emoji icons
- Feature order

#### Update Contact Information
Edit the contact section in `index.html` to change:
- Email address
- Contact details

#### Update Statistics
Edit the about section in `index.html` to modify:
- User count
- Prayer tracking numbers
- App store rating

### Styling Changes

#### Modify Colors
Edit the CSS variables in `styles.css`:
```css
/* Main color scheme */
--primary-color: #333;
--background-color: #ffffff;
--light-background: #f8f9fa;
```

#### Change Fonts
Update the Google Fonts link in `index.html`:
```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Deployment

### GitHub Pages
1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify
1. Drag and drop the project folder to Netlify
2. Your site will be deployed automatically

### Vercel
1. Connect your GitHub repository to Vercel
2. Deploy automatically on every push

## Performance

This simplified version is optimized for:
- Fast loading times
- Minimal bandwidth usage
- Clean, accessible design
- Mobile-first responsive design

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

For questions or support:
- Email: support@huda.app
- Create an issue in the repository

---

**Hudā** - Your Complete Islamic Companion
To add Google Analytics:
1. Get your tracking ID from Google Analytics
2. Add this code before the closing `</head>` tag in `index.html`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

## Contact Form Integration

To add a working contact form:
1. Use services like Formspree, Netlify Forms, or your own backend
2. Update the form action in the HTML
3. Test the form submission

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

For questions or support:
- Email: support@huda.app
- Create an issue in the repository
- Check the documentation

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

---

**Hudā** - Your Complete Islamic Companion 