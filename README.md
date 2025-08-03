# 🌟 Tonny Kamau Mwangi - Professional Portfolio

A modern, responsive, and accessible portfolio website showcasing IT support expertise and software development skills. Built with semantic HTML5 and clean CSS for optimal performance and maintainability.

Portfolio Preview (https://plp-hackathon-portifolio.vercel.app)

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [File Structure](#file-structure)
- [Customization Guide](#customization-guide)
- [Accessibility Features](#accessibility-features)
- [Browser Support](#browser-support)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

This portfolio website presents Tonny Kamau Mwangi's professional background as an IT Support Professional and Software Developer. The site demonstrates expertise in:

- **IT Support & Implementation** - Enterprise systems and customer support
- **Software Development** - Flutter mobile apps, ReactJS websites, Laravel authentication
- **Database Management** - MySQL, MongoDB, and database administration
- **Cybersecurity** - Expanding expertise in cloud and network security

## ✨ Features

### 🎨 **Modern Design**
- Clean, professional aesthetic matching industry standards
- Responsive design that works on all devices
- Smooth hover effects and subtle animations
- Professional color scheme with excellent contrast

### ♿ **Accessibility First**
- WCAG 2.1 AA compliant contrast ratios
- Semantic HTML5 structure for screen readers
- Keyboard navigation support
- Skip-to-content links
- Proper ARIA labels and landmarks

### 📱 **Responsive Layout**
- Mobile-first design approach
- Flexible grid systems using CSS Grid and Flexbox
- Optimized for phones, tablets, and desktops
- Touch-friendly interface elements

### 🚀 **Performance Optimized**
- Single HTML file with embedded CSS
- No external dependencies
- Optimized images and assets
- Fast loading times

### 🎓 **Educational Value**
- Comprehensive code comments
- Demonstrates modern web development practices
- Example of semantic HTML5 structure
- Professional CSS organization

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with custom properties
- **Responsive Design** - Mobile-first approach
- **Accessibility** - WCAG 2.1 compliance
- **SEO** - Optimized meta tags and structure

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor or IDE (VS Code, Sublime Text, etc.)
- Basic understanding of HTML/CSS (for customization)

### Installation

1. **Clone or download** this repository:
   ```bash
   https://github.com/TonnyKamau/PLP-hackathon-portifolio
   ```

2. **Navigate** to the project directory:
   ```bash
   cd PLP-hackathon-portifolio
   ```

3. **Open** `index.html` in your web browser:
   - Double-click the file, or
   - Right-click → "Open with" → your browser, or
   - Use a local development server

### Live Server (Recommended)
For the best development experience, use a live server:

**VS Code Live Server Extension:**
1. Install the "Live Server" extension
2. Right-click `index.html`
3. Select "Open with Live Server"

Then visit `http://localhost:8000`

## 📁 File Structure

```
portfolio/
├── index.html              # Main portfolio page
├── README.md               # This documentation
├── tonny-kamau-profile.jpg # Profile image
├── tonny-kamau-cv.pdf      # Downloadable CV
└── styles.css              # Additional assets (if any)
    
```

### Key Files

- **`index.html`** - Complete portfolio website 
- **`styles.css`** - style sheet file
- **`tonny-kamau-profile.jpg`** - Professional headshot (200x200px recommended)
- **`tonny-kamau-cv.pdf`** - Downloadable curriculum vitae
- **`README.md`** - Project documentation

## 🎨 Customization Guide

### 1. Personal Information

**Update Profile Information:**
```html
<!-- In the header section -->
<h1>Your Full Name</h1>
<h2>Your Professional Title</h2>
<p>Your professional summary...</p>
```

**Update Contact Details:**
```html
<!-- In the contact section -->
<a href="mailto:your-email@example.com">your-email@example.com</a>
<a href="tel:+your-phone-number">+Your Phone Number</a>
```

### 2. Colors and Branding

**CSS Custom Properties (Design Tokens):**
```css
:root {
    --primary-blue: #3B82F6;        /* Your brand color */
    --dark-text: #1F2937;           /* Dark text */
    --medium-text: #374151;         /* Medium text */
    --light-text: #6B7280;          /* Light text */
    --background-light: #F9FAFB;    /* Page background */
    --background-white: #FFFFFF;    /* Card backgrounds */
}
```

### 3. Content Sections

**Add New Sections:**
```html
<section id="new-section" class="loading">
    <h2>Section Title</h2>
    <p>Section content...</p>
</section>
```

**Update Navigation:**
```html
<nav>
    <a href="#new-section">New Section</a>
    <!-- Add to existing navigation -->
</nav>
```

### 4. Profile Image

**Image Requirements:**
- **Format:** JPG, PNG, or WebP
- **Size:** 200x200px (square aspect ratio)
- **Quality:** High resolution for crisp display
- **File size:** Optimized for web (< 500KB recommended)

**Replace Image:**
1. Add your image to the project folder
2. Update the src attribute:
   ```html
   <img src="your-profile-image.jpg" alt="Your Name - Your Title" class="profile-image">
   ```

### 5. Skills and Experience

**Update Skills:**
```html
<div class="skill-category">
    <h3>Your Skill Category</h3>
    <ul>
        <li><strong>Technology</strong> - Your description</li>
        <!-- Add more skills -->
    </ul>
</div>
```

**Add Work Experience:**
```html
<article>
    <h3>Job Title</h3>
    <p><strong>Company Name, Location</strong> | Start Date – End Date</p>
    <h4>Key Responsibilities:</h4>
    <ul>
        <li>Your responsibility or achievement</li>
        <!-- Add more items -->
    </ul>
</article>
```

## ♿ Accessibility Features

### Semantic Structure
- Proper heading hierarchy (H1 → H2 → H3 → H4)
- Landmark regions (header, nav, main, aside, footer)
- Meaningful link text and alt attributes

### Keyboard Navigation
- Tab-accessible interactive elements
- Skip-to-content link
- Focus indicators on all focusable elements

### Screen Reader Support
- ARIA labels and landmarks
- Descriptive form labels
- Proper table structure with captions

### Visual Accessibility
- High contrast text (WCAG AA compliant)
- Scalable fonts and flexible layouts
- Reduced motion support for sensitive users

### Testing Accessibility
1. **Keyboard Navigation:** Tab through all elements
2. **Screen Reader:** Test with NVDA, JAWS, or VoiceOver
3. **Contrast:** Use tools like WebAIM's contrast checker
4. **Automated Testing:** Use axe-core or Lighthouse

## 🌐 Browser Support

### Fully Supported
- **Chrome** 90+
- **Firefox** 88+
- **Safari** 14+
- **Edge** 90+

### Partially Supported
- **Internet Explorer** 11 (basic functionality)
- **Older mobile browsers** (graceful degradation)

### CSS Features Used
- CSS Custom Properties (CSS Variables)
- CSS Grid and Flexbox
- Responsive units (clamp, vw, vh)
- Modern selectors and pseudo-elements

## 🔧 Development

### Code Quality
- **HTML5 validation** - W3C compliant markup
- **CSS validation** - W3C CSS validator compliant
- **Accessibility testing** - WAVE, axe-core validated
- **Cross-browser testing** - Tested across major browsers

### Code Organization
```css
/* CSS Structure */
1. CSS Custom Properties (Design Tokens)
2. Global Reset and Base Styles
3. Header and Navigation
4. Main Content Sections
5. Form and Interactive Elements
6. Responsive Design (Mobile-first)
7. Accessibility and User Preferences
8. Print Styles
```

### Best Practices
- **Semantic HTML** - Meaningful element usage
- **Progressive Enhancement** - Works without CSS/JS
- **Mobile-first** - Responsive design approach
- **Performance** - Optimized loading and rendering

## 📖 Educational Resources

### Learning More
- **HTML5 Semantic Elements** - [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)
- **CSS Grid Layout** - [CSS-Tricks Complete Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)
- **Web Accessibility** - [WebAIM Guidelines](https://webaim.org/standards/wcag/)
- **Responsive Design** - [Responsive Web Design Basics](https://web.dev/responsive-web-design-basics/)

### Code Comments
This project includes extensive code comments explaining:
- Design decisions and rationale
- CSS custom properties usage
- Responsive design techniques
- Accessibility implementations

## 🤝 Contributing

### How to Contribute
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Test accessibility and responsiveness
5. Commit your changes (`git commit -am 'Add improvement'`)
6. Push to the branch (`git push origin feature/improvement`)
7. Create a Pull Request

### Contribution Guidelines
- Maintain accessibility standards
- Follow existing code style
- Test across multiple browsers
- Update documentation if needed
- Include comments for complex code

## 📞 Support & Contact

### Get Help
- **Documentation Issues:** Open an issue on GitHub
- **Technical Questions:** Contact via the portfolio contact form
- **Professional Inquiries:** Use LinkedIn or email contact

### Professional Contact
- **Email:** tonnykamau6@gmail.com
- **Phone:** +254 798 428 931
- **LinkedIn:** [tonnykamau-mwangi](https://www.linkedin.com/in/tonnykamau-mwangi/)
- **GitHub:** [TonnyKamau](https://github.com/TonnyKamau)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### MIT License Summary
- ✅ Commercial use
- ✅ Modification
- ✅ Distribution
- ✅ Private use
- ❌ Liability
- ❌ Warranty

## 🙏 Acknowledgments

### Inspiration and Resources
- **Design Inspiration:** Modern portfolio trends and best practices
- **Accessibility Guidelines:** WCAG 2.1 and WebAIM resources
- **Code Quality:** W3C standards and MDN documentation
- **Performance:** Google Web Vitals and Core Web Vitals

### Special Thanks
- **Web Development Community** - For open-source resources and knowledge sharing
- **Accessibility Advocates** - For promoting inclusive web design
- **Modern CSS Techniques** - CSS-Tricks, Smashing Magazine, and web.dev

---

**Built with ❤️ by Tonny Kamau Mwangi**  
*IT Support Professional & Software Developer*

**Last Updated:** January 2025  
**Version:** 1.0.0
