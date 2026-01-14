# Parker Lemery - Portfolio Website

A modern, responsive portfolio website showcasing my projects, resume, and skills for software engineering internship applications.

**Live Site:** https://plemery.github.io

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Projects Showcase**: Three featured projects with live demos and source code
- **Image Gallery**: Dedicated gallery page for wheelchair assistive device project (23 images)
- **Sections Include**:
  - Hero section with introduction
  - About section with technical skills
  - Projects showcase with working links
  - Resume section with downloadable PDF
  - Contact information with email, phone, and social links

## Current Projects

### 1. Academic Performance App & Grade Tracker
- Full-stack iOS app with AI-powered grade tracking
- Tech: Swift, SwiftUI, Node.js, Express.js, OpenAI API, Vision Framework, PDFKit
- Features natural language processing and OCR document parsing

### 2. Wheelchair Assistive Device
- Lead Engineer role designing ratchet mechanism for wheelchair propulsion
- 23 CAD images showcasing mechanical design and prototyping
- View full gallery at `wheelchair-gallery.html`

### 3. Real Time Currency Converter
- Web application with live exchange rates for 5 major currencies
- Tech: JavaScript, HTML/CSS, ExchangeRate API
- **Live Demo:** https://plemery.github.io/currency-converter/
- **Source Code:** https://github.com/PLemery/currency-converter

## Deployment

This portfolio is deployed using **GitHub Pages**:
- **Repository:** https://github.com/PLemery/PLemery.github.io
- **Live Site:** https://plemery.github.io
- Automatically deploys when changes are pushed to the `main` branch

## Customization Tips

### Colors

Edit the CSS variables in `styles.css` to change the color scheme:

```css
:root {
    --primary-color: #3b82f6;  /* Main accent color */
    --secondary-color: #8b5cf6; /* Secondary accent */
    /* ... other colors */
}
```

### Hero Background

Change the gradient background in `styles.css`:

```css
.hero {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

### Adding More Projects

Copy and paste a project card in `index.html` and update the content:

```html
<div class="project-card">
    <!-- Update content here -->
</div>
```

## Tips for Internship Applications

1. **Keep it updated**: Regularly add new projects and update your resume
2. **Quality over quantity**: Showcase your 3-5 best projects
3. **Add metrics**: Include specific achievements (e.g., "Improved performance by 40%")
4. **Make it easy to contact you**: Ensure all contact links work
5. **Proofread**: Check for typos and grammatical errors
6. **Test on mobile**: Many recruiters will view your site on their phones

## File Structure

```
portfolio-website/
├── index.html                    # Main portfolio page
├── wheelchair-gallery.html       # Wheelchair project gallery
├── styles.css                    # All styling
├── script.js                     # JavaScript for interactions
├── resume.pdf                    # Resume PDF (downloadable)
├── images/
│   └── wheelchair/               # Wheelchair project images (23 images)
│       ├── wheelchair-image-1.png
│       ├── wheelchair-image-2.png
│       └── ...
└── README.md                     # This file
```

## Contact

- **Email:** parkerlemery@gmail.com
- **Phone:** (802) 238-8293
- **LinkedIn:** https://www.linkedin.com/in/parker-lemery
- **GitHub:** https://github.com/PLemery
- **Location:** Columbus, OH

---

© 2026 Parker Lemery. All rights reserved.
