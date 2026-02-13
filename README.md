# Nagishetti Kalyan - Personal Portfolio

A modern, responsive personal portfolio website for a Computer Science undergraduate. Built with HTML, CSS, and JavaScript.

![Portfolio Preview](assets/preview.png)

## Features

- **Modern Design**: Clean, professional look suitable for recruiters and internships
- **Responsive**: Works perfectly on mobile, tablet, and desktop
- **Smooth Animations**: Scroll animations and hover effects
- **SEO Friendly**: Proper meta tags and semantic HTML
- **Fast Loading**: No heavy frameworks, pure HTML/CSS/JS

## Sections

1. **Home** - Introduction with name, role, and tagline
2. **About Me** - Brief introduction and personal information
3. **Skills** - Technical skills organized by category
4. **Projects** - Placeholder cards for future projects
5. **Education** - Academic background with timeline
6. **Contact** - Email, LinkedIn, and GitHub links

## Quick Start

### Local Development

1. Clone this repository:
```bash
git clone https://github.com/yourusername/portfolio.git
cd portfolio
```

2. Open `index.html` in your browser:
```bash
# On Windows
start index.html

# On macOS
open index.html

# On Linux
xdg-open index.html
```

### Editing the Portfolio

#### 1. Update Personal Information

Edit the following in `index.html`:

- **Name**: Replace "Nagishetti Kalyan" with your name
- **Role**: Update the subtitle in the Home section
- **About Me**: Modify the description in the About section
- **Contact**: Update email, LinkedIn, and GitHub links
- **Projects**: Add your project details in the Projects section

#### 2. Customizing Colors

Edit CSS variables in `css/style.css`:

```css
:root {
    --primary-color: #2563eb;  /* Change this to your preferred color */
    --accent-color: #06b6d4;
    /* ... other variables */
}
```

#### 3. Adding Projects

Duplicate a project card in the Projects section:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-laptop-code"></i>
    </div>
    <div class="project-content">
        <h3 class="project-title">Your Project Name</h3>
        <p class="project-description">Project description here</p>
        <div class="project-tech">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
        <div class="project-links">
            <a href="https://github.com/yourusername/project" class="project-link">
                <i class="fab fa-github"></i> Code
            </a>
            <a href="https://yourproject.demo.com" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live
            </a>
        </div>
    </div>
</div>
```

#### 4. Adding Profile Image

Replace the profile placeholder in `index.html`:

```html
<div class="home-image">
    <div class="image-wrapper">
        <img src="assets/your-photo.jpg" alt="Nagishetti Kalyan" class="profile-photo">
    </div>
</div>
```

#### 5. Adding Resume

1. Add your resume PDF to `assets/resume.pdf`
2. The download button is already configured in `index.html`

## Hosting on GitHub Pages

### Method 1: Using GitHub Web Interface

1. Create a new repository on GitHub:
   - Go to [GitHub](https://github.com)
   - Click "New repository"
   - Name it `portfolio` (or yourusername.github.io)
   - Make it public

2. Upload files:
   - Click "uploading an existing file"
   - Upload all files from this project

3. Enable GitHub Pages:
   - Go to Repository Settings
   - Click "Pages" on the left sidebar
   - Under "Source", select "main" branch
   - Click Save

4. Your site will be live at `https://yourusername.github.io/repository-name`

### Method 2: Using Git

```bash
# Initialize git repository
git init

# Add files
git add .

# Commit
git commit -m "Initial portfolio commit"

# Create GitHub repository and push
git remote add origin https://github.com/yourusername/portfolio.git
git branch -M main
git push -u origin main
```

Then enable GitHub Pages as in Method 1.

## Hosting on Netlify

1. Create a Netlify account at [Netlify](https://netlify.com)

2. Drag and drop:
   - Drag your project folder to Netlify's dashboard
   - Your site will be deployed automatically

3. Custom domain (optional):
   - Go to "Domain Settings"
   - Add your custom domain

## Hosting on Vercel

1. Install Vercel CLI:
```bash
npm i -g vercel
```

2. Deploy:
```bash
vercel
```

3. Follow the prompts to connect your GitHub account.

## Customization Tips

### Changing Icons

This portfolio uses Font Awesome icons. To change icons:

1. Visit [Font Awesome Gallery](https://fontawesome.com/icons)
2. Search for your desired icon
3. Replace the icon class in `index.html`

Example:
```html
<!-- Change from code icon to rocket icon -->
<i class="fas fa-code"></i>  <!-- Before -->
<i class="fas fa-rocket"></i>  <!-- After -->
```

### Adding New Sections

1. Add the section in `index.html`:
```html
<section id="new-section" class="section">
    <div class="container">
        <h2 class="section-title">New Section</h2>
        <!-- Your content here -->
    </div>
</section>
```

2. Add the nav link in the navbar:
```html
<li class="nav-item"><a href="#new-section" class="nav-link">New Section</a></li>
```

3. Add styles in `css/style.css`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- PageSpeed Insights score: 95+
- Lighthouse score: 95+

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

**Nagishetti Kalyan**
- Email: kalyannagishetti@gmail.com
- LinkedIn: [Profile Link](https://linkedin.com)
- GitHub: [Profile Link](https://github.com)

## Acknowledgments

- [Font Awesome](https://fontawesome.com) for icons
- [Google Fonts](https://fonts.google.com) for typography
- [Unsplash](https://unsplash.com) for placeholder images
