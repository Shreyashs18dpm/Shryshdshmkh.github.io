# Academic Research Webpage

A modern, professional academic webpage with a sleek black theme. Perfect for showcasing your research, publications, and teaching experience.

## Features

✨ **Modern Design**
- Clean, professional black theme with cyan accents
- Fully responsive design for all devices
- Smooth animations and hover effects

📚 **Complete Sections**
- Hero section with introduction
- About/Bio section
- Research interests
- Publications showcase
- Projects portfolio
- Teaching & courses
- Contact information

🎨 **Customization**
- Easy to customize colors in CSS variables
- Add your own content to each section
- Responsive grid layouts
- Mobile-friendly navigation

## Setup & Deployment

### Option 1: GitHub Pages (Recommended)

1. **Create a GitHub Repository**
   - Go to github.com and create a new repository
   - Name it: `yourusername.github.io` (replace with your username)
   - This will create a GitHub Pages site

2. **Clone and Add Files**
   ```bash
   git clone https://github.com/yourusername/yourusername.github.io.git
   cd yourusername.github.io
   ```
   - Copy `index.html` and `styles.css` to this directory

3. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit: Academic webpage"
   git push origin main
   ```

4. **Access Your Site**
   - Your site will be live at: `https://yourusername.github.io`
   - It may take a few minutes to deploy

### Option 2: Local Testing

Open `index.html` directly in your browser to test locally before deploying.

## Customization Guide

### 1. Update Personal Information

Edit `index.html` and replace:
- "Dr. Academic" with your name
- "Your Name" throughout the file
- Contact email and institution details
- Add links to your CV, GitHub, LinkedIn, etc.

### 2. Change Colors

Edit `styles.css` and modify the `:root` variables:
```css
:root {
    --accent-color: #00d4ff;  /* Change this to your preferred color */
    --primary-color: #1a1a1a; /* Dark background */
    --secondary-color: #2d2d2d; /* Card background */
    /* ... other colors */
}
```

Popular color options for academia:
- Cyan: `#00d4ff` (current)
- Blue: `#0066ff`
- Green: `#00ff88`
- Purple: `#bb86fc`
- Gold: `#ffd700`

### 3. Add Your Publications

In the Publications section, update:
```html
<div class="publication-item">
    <h4>Your Paper Title</h4>
    <p class="authors">Author Names</p>
    <p class="venue">Journal/Conference Name, Year</p>
    <p class="description">Brief description...</p>
    <div class="publication-links">
        <a href="link-to-pdf" class="link">PDF</a>
        <a href="doi-link" class="link">DOI</a>
    </div>
</div>
```

### 4. Add Your Projects

In the Projects section, update project cards with:
- Project title
- Description
- Technology tags
- Link to GitHub or project page

### 5. Update Teaching Courses

Add your courses to the Teaching section with:
- Course title
- Course code
- Level (Undergraduate/Graduate)
- Description

### 6. Add Contact Links

Update the contact section with:
- Your email
- Institution and office location
- Social media links (LinkedIn, GitHub, Google Scholar, etc.)

## File Structure

```
your-repo/
├── index.html      # Main webpage structure
├── styles.css      # Styling and layout
└── README.md       # This file
```

## Tips for Best Results

- **Keep it updated**: Regularly add new publications and projects
- **Add profile picture**: You can add an image to the About section by modifying the HTML
- **Use short descriptions**: Keep text concise and professional
- **Test on mobile**: Use your browser's device testing tools
- **Check links**: Ensure all external links work properly

## Adding a Profile Picture

To add a profile picture to the About section:

1. Save your image as `profile.jpg` in your repository
2. Add this line after the `<div class="about-text">` opening tag:
```html
<img src="profile.jpg" alt="Profile Picture" style="width: 200px; border-radius: 50%; border: 3px solid #00d4ff;">
```

## Deploy Updates

After making changes:
```bash
git add .
git commit -m "Update: Add new publications"
git push origin main
```

Changes will be live within minutes!

## Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## License

Feel free to customize and use this template for your academic webpage. No attribution required.

## Need Help?

- Check GitHub Pages documentation: https://pages.github.com
- CSS Variables guide: https://developer.mozilla.org/en-US/docs/Web/CSS/--*
- HTML basics: https://developer.mozilla.org/en-US/docs/Web/HTML

---

Happy publishing! 🎓
