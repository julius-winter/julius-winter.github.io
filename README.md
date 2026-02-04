# Personal CV & Portfolio Template

A minimalist GitHub Pages template for showcasing your CV, projects, and publications.

## Features

- Clean, minimalist design with elegant typography
- Fully responsive layout
- Three main pages:
  - **CV (index.html)**: Main landing page with your resume
  - **Projects**: Showcase your technical work and creative projects
  - **Publications**: Display academic papers and articles
- Smooth animations and transitions
- Easy to customize and extend

## Setup Instructions

### 1. Create a GitHub Repository

1. Create a new repository named `username.github.io` (replace `username` with your GitHub username)
2. Upload all the files from this template to your repository

### 2. Enable GitHub Pages

1. Go to your repository settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select the `main` branch
4. Click "Save"

Your site will be published at `https://username.github.io`

## Customization Guide

### Basic Information

**index.html:**
- Replace "Your Name" with your actual name
- Update the tagline/professional title
- Change email and social links in the contact section
- Fill in the About section
- Add your work experience, education, and skills

**projects.html:**
- Duplicate the `<article class="project-card">` block for each project
- Update project titles, descriptions, tags, and links

**publications.html:**
- Duplicate the `<article class="publication-item">` block for each publication
- Update titles, authors (bold your name), venues, abstracts, and links

### Styling

**styles.css** - Customize the color scheme by editing the CSS variables at the top:

```css
:root {
    --color-bg: #fafaf8;           /* Background color */
    --color-text: #1a1a1a;         /* Main text color */
    --color-text-muted: #666666;   /* Secondary text */
    --color-accent: #2c5f2d;       /* Accent color (links, highlights) */
    --color-accent-light: #4a7c59; /* Lighter accent variant */
    --color-border: #e0e0dc;       /* Border color */
    --color-card-bg: #ffffff;      /* Card backgrounds */
}
```

### Typography

The template uses:
- **Libre Baskerville** for headings (serif, elegant)
- **Work Sans** for body text (sans-serif, clean)

To change fonts, update the Google Fonts import in the HTML files and the CSS variables:

```css
--font-display: 'Your Display Font', serif;
--font-body: 'Your Body Font', sans-serif;
```

### Adding More Pages

To add a new page:

1. Create a new HTML file (e.g., `blog.html`)
2. Copy the structure from one of the existing pages
3. Add a link to the navigation in all pages:

```html
<nav class="nav">
    <div class="nav-content">
        <a href="index.html" class="nav-link">CV</a>
        <a href="projects.html" class="nav-link">Projects</a>
        <a href="publications.html" class="nav-link">Publications</a>
        <a href="blog.html" class="nav-link">Blog</a>
    </div>
</nav>
```

## File Structure

```
.
├── index.html          # Main CV page
├── projects.html       # Projects showcase
├── publications.html   # Publications list
├── styles.css          # Main stylesheet
└── README.md          # This file
```

## Tips

- Keep the design minimal and focused on content
- Use high-quality project descriptions and clear abstracts
- Update regularly with new projects and publications
- Test responsiveness on mobile devices
- Consider adding a favicon for a professional touch
- Add Google Analytics if you want to track visitors

## Optional Enhancements

Consider adding:
- A blog section for technical writing
- Image galleries for project screenshots
- A contact form
- Dark mode toggle
- PDF download of your CV
- Schema.org markup for better SEO

## License

Feel free to use this template for your personal portfolio. No attribution required.
