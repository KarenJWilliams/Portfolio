# Karen Joseph Williams - Portfolio Website

A modern, responsive personal portfolio website showcasing my education, projects, skills, and contact information.

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Sections](#sections)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Customization](#customization)
- [Browser Support](#browser-support)
- [Contact](#contact)

## 🌟 Overview

This is a single-page portfolio website designed with a modern aesthetic, featuring smooth animations, gradient backgrounds, and an intuitive user interface. The website is fully responsive and works seamlessly across all devices.

## ✨ Features

- **Responsive Design** - Adapts to all screen sizes (mobile, tablet, desktop)
- **Smooth Scrolling** - Navigate seamlessly between sections
- **Modern UI/UX** - Contemporary design with gradients and animations
- **Interactive Elements** - Hover effects and transitions throughout
- **Sticky Navigation** - Easy access to all sections from anywhere on the page
- **Fast Loading** - No external dependencies, pure HTML/CSS/JS
- **Accessibility** - Semantic HTML and proper contrast ratios

## 📑 Sections

### 1. **Home/Hero**
- Eye-catching introduction with animated gradient background
- Call-to-action button

### 2. **About Me**
- Personal information cards
- Education timeline with visual representation
- Professional background

### 3. **Portfolio**
- Showcase of top 3 projects:
  - Library Management System
  - Airplane Booking System
  - Taxi Booking System

### 4. **Skills**
- Interactive skill cards displaying proficiency in:
  - Java
  - Python
  - C
  - C++
  - HTML

### 5. **Contact**
- Multiple contact methods:
  - Email
  - Phone
  - Location
  - LinkedIn profile

## 🛠 Technologies Used

- **HTML5** - Structure and content
- **CSS3** - Styling and animations
  - Flexbox & Grid for layout
  - Custom CSS variables
  - Gradient backgrounds
  - Smooth transitions and animations
- **Vanilla JavaScript** - Interactive features
  - Smooth scroll navigation
  - Navbar scroll effects

## 📦 Installation

1. **Download the HTML file**
   ```bash
   # Clone or download the repository
   git clone <your-repo-url>
   ```

2. **No build process required** - This is a static HTML file with embedded CSS and JavaScript

3. **Open in browser**
   ```bash
   # Simply open the HTML file in your preferred browser
   open index.html
   # or
   double-click the file
   ```

## 🚀 Usage

### Local Development
1. Open the HTML file in any modern web browser
2. Edit the HTML directly to update content
3. Refresh the browser to see changes

### Deployment Options

#### GitHub Pages
1. Push the HTML file to a GitHub repository
2. Go to Settings → Pages
3. Select the branch and save
4. Your site will be live at `https://yourusername.github.io/repo-name`

#### Netlify
1. Drag and drop the HTML file to Netlify
2. Your site is instantly deployed

#### Any Web Hosting
1. Upload the HTML file to your hosting provider
2. Access via your domain

## 🎨 Customization

### Changing Colors
Modify the CSS variables at the top of the `<style>` section:

```css
:root {
    --primary: #6366f1;        /* Main brand color */
    --primary-dark: #4f46e5;   /* Darker shade */
    --secondary: #8b5cf6;      /* Secondary color */
    --accent: #ec4899;         /* Accent color */
    --dark: #0f172a;           /* Dark text/backgrounds */
    --light: #f8fafc;          /* Light backgrounds */
    --gray: #64748b;           /* Gray text */
}
```

### Updating Content

**Personal Information:**
```html
<!-- Find and update in the About section -->
<div class="info-card">
    <h3>👤 Name</h3>
    <p>Your Name Here</p>
</div>
```

**Projects:**
```html
<!-- Update in the Portfolio section -->
<div class="project-card">
    <div class="project-number">1</div>
    <h3>📚 Your Project Title</h3>
    <p>Your project description</p>
</div>
```

**Contact Information:**
```html
<!-- Update in the Contact section -->
<a href="mailto:youremail@example.com">youremail@example.com</a>
```

### Adding New Sections
1. Add a navigation link in the navbar
2. Create a new section with class `section-white`
3. Use existing styling classes for consistency

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)

## 📱 Responsive Breakpoints

- **Mobile:** < 768px
- **Tablet:** 768px - 1024px
- **Desktop:** > 1024px

## 🔧 Troubleshooting

### Email link not working on mobile
- Ensure the email has `mailto:` prefix
- Check device's default email app settings

### Smooth scroll not working
- Verify JavaScript is enabled in browser
- Check for console errors

### Sections not aligning properly
- Clear browser cache
- Check for conflicting CSS

## 📄 File Structure

```
portfolio/
│
├── index.html          # Main HTML file (includes CSS and JS)
└── README.md          # This file
```

## 🔄 Updates & Maintenance

To update your portfolio:
1. Open the HTML file in a text editor
2. Locate the section you want to modify
3. Update the content
4. Save and refresh your browser

## 📝 License

This project is open source and available for personal use. Feel free to customize it for your own portfolio.

## 👤 Contact

**Karen Joseph Williams**

- 📧 Email: karenjosephwilliams@gmail.com
- 📱 Phone: +91 8113015240
- 💼 LinkedIn: [karen-joseph-williams-35987821a](https://www.linkedin.com/in/karen-joseph-williams-35987821a)
- 📍 Location: Kerala, India 

## 🙏 Acknowledgments

- Design inspired by modern web design trends
- Built with clean, semantic HTML5
- Optimized for performance and accessibility

---

**Last Updated:** November 2024

**Version:** 1.0.0

Made with 💜 by Karen Joseph Williams