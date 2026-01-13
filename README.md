# Portfolio Website

A modern, responsive portfolio website to showcase your projects, resume, and skills for internship applications.

## Features

- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Easy to Customize**: Simple HTML/CSS/JS structure that's easy to modify
- **Sections Include**:
  - Hero section with introduction
  - About section with skills
  - Projects showcase
  - Resume section
  - Contact information

## Getting Started

### 1. Customize Your Information

Edit `index.html` and update the following:

- **Personal Information**: Replace "Parker Lemery" with your name
- **Social Links**: Update GitHub, LinkedIn, and email links (search for "yourusername" and "your.email@example.com")
- **About Section**: Update the description and skills to match your background
- **Projects**: Replace the placeholder projects with your own:
  - Update project titles, descriptions, and technologies
  - Add your project links (GitHub repos, live demos)
  - Replace placeholder images (see below)
- **Resume Section**: Fill in your education, experience, and achievements
- **Contact Info**: Update all contact information

### 2. Add Your Resume PDF

- Export your resume as a PDF
- Save it as `resume.pdf` in the portfolio-website folder
- The download button will automatically link to it

### 3. Add Project Images

Replace the placeholder images with screenshots of your projects:

- Create an `images` folder in the portfolio-website directory
- Add your project screenshots (recommended size: 400x250px or similar aspect ratio)
- Update the `<img src="...">` tags in index.html with your image paths

Example:
```html
<img src="images/project1.png" alt="Project 1">
```

### 4. Preview Locally

Open `index.html` in your web browser to preview your portfolio.

## Deployment Options

### Option 1: GitHub Pages (Free & Easy)

1. Create a new GitHub repository
2. Push your portfolio files to the repository
3. Go to Settings > Pages
4. Select your main branch as the source
5. Your site will be live at `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free)

1. Sign up at [netlify.com](https://www.netlify.com/)
2. Drag and drop your portfolio-website folder
3. Your site will be live instantly with a custom URL

### Option 3: Vercel (Free)

1. Sign up at [vercel.com](https://vercel.com/)
2. Import your GitHub repository or upload files
3. Deploy with one click

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
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # JavaScript for interactions
├── resume.pdf          # Your resume (add this)
├── images/             # Project images (create this folder)
│   ├── project1.png
│   ├── project2.png
│   └── ...
└── README.md          # This file
```

## Support

If you need help customizing your portfolio, feel free to reach out or consult online resources for HTML/CSS basics.

Good luck with your internship applications! 🚀
