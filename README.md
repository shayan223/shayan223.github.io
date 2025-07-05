# Shayan's Personal Website

A modern, responsive personal website built with HTML, CSS, and JavaScript. Features a sleek design with smooth animations and interactive elements.

## 🌟 Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Responsive**: Fully responsive design that works on all devices
- **Interactive Elements**: 
  - Smooth scrolling navigation
  - Animated skill bars
  - Contact form with validation
  - Mobile-friendly navigation
  - Profile image upload functionality
- **Sections**:
  - Hero section with profile picture
  - Skills & expertise showcase
  - Research papers portfolio
  - Contact form
  - Social media links

## 🚀 Quick Start

1. **Clone or download** this repository
2. **Open** `index.html` in your web browser
3. **Customize** the content to match your information

## 📝 Customization Guide

### Personal Information
Edit the following in `index.html`:

```html
<!-- Update your name and title -->
<h1 class="hero-title">Hi, I'm [Your Name]</h1>
<p class="hero-subtitle">[Your Title]</p>

<!-- Update your description -->
<p class="hero-description">
    [Your personal description here]
</p>
```

### Profile Picture
1. Replace `profile-placeholder.jpg` with your actual profile image
2. Or click on the profile image area to upload a new one (browser feature)

### Skills Section
Update the skills in `index.html`:

```html
<div class="skill-item">
    <span class="skill-name">[Skill Name]</span>
    <div class="skill-bar">
        <div class="skill-progress" style="width: [Percentage]%"></div>
    </div>
</div>
```

### Research Papers
Update each research card in `index.html`:

```html
<div class="research-card">
    <div class="research-icon">
        <i class="fas fa-microscope"></i>
    </div>
    <h3>[Paper Title]</h3>
    <p class="research-abstract">
        [Paper description]
    </p>
    <div class="research-meta">
        <span class="research-year">[Year]</span>
        <span class="research-journal">[Journal/Conference]</span>
    </div>
    <a href="[Paper URL]" class="research-link" target="_blank">
        <i class="fas fa-external-link-alt"></i>
        Read Paper
    </a>
</div>
```

### Contact Information
Update contact details in `index.html`:

```html
<div class="contact-method">
    <i class="fas fa-envelope"></i>
    <span>[your.email@example.com]</span>
</div>
<div class="contact-method">
    <i class="fas fa-map-marker-alt"></i>
    <span>[Your Location]</span>
</div>
<div class="contact-method">
    <i class="fab fa-linkedin"></i>
    <span>[LinkedIn Profile URL]</span>
</div>
```

### Social Media Links
Update the footer social links:

```html
<div class="social-links">
    <a href="[GitHub URL]" target="_blank"><i class="fab fa-github"></i></a>
    <a href="[LinkedIn URL]" target="_blank"><i class="fab fa-linkedin"></i></a>
    <a href="[Twitter URL]" target="_blank"><i class="fab fa-twitter"></i></a>
</div>
```

## 🎨 Styling Customization

### Colors
The website uses a blue color scheme. To change colors, update the CSS variables in `styles.css`:

```css
/* Primary colors */
--primary-color: #2563eb;
--primary-dark: #1d4ed8;
--secondary-color: #3b82f6;

/* Background colors */
--bg-light: #f8fafc;
--bg-dark: #1e293b;
```

### Fonts
The website uses Inter font from Google Fonts. To change fonts:

1. Update the Google Fonts link in `index.html`
2. Change the font-family in `styles.css`:

```css
body {
    font-family: '[Your Font]', sans-serif;
}
```

## 📧 Contact Form Setup

The contact form currently simulates email sending. To make it functional, you have several options:

### Option 1: Formspree (Recommended)
1. Go to [formspree.io](https://formspree.io)
2. Create a free account
3. Create a new form
4. Replace the form action in `index.html`:

```html
<form class="contact-form" action="https://formspree.io/f/[YOUR_FORM_ID]" method="POST">
```

### Option 2: Netlify Forms
If deploying to Netlify, add the `netlify` attribute:

```html
<form class="contact-form" netlify>
```

### Option 3: Custom Backend
Replace the form submission logic in `script.js` with your own API endpoint.

## 🌐 Deployment

### GitHub Pages (Recommended)
1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://[username].github.io/[repository-name]`

### Netlify
1. Drag and drop your website folder to [netlify.com](https://netlify.com)
2. Or connect your GitHub repository for automatic deployments

### Other Hosting Services
- **Vercel**: Connect your GitHub repository
- **Firebase Hosting**: Use Firebase CLI
- **Traditional hosting**: Upload files via FTP

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🔧 Technical Details

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript (ES6+)**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Typography
- **Intersection Observer API**: Scroll animations
- **FormData API**: Form handling

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own use. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## 📞 Support

If you need help customizing or deploying your website, feel free to reach out!

---

**Happy coding! 🚀** 