# Quick Start Guide - Professional Portfolio

## 🚀 Get Started in 5 Minutes

### Step 1: Personalise Your Information

Open `index.html` and update these sections:

#### Your Name & Title
```html
<div class="logo">
    <h1>YOUR NAME</h1>
    <p class="tagline">Professional Profile</p>
</div>
```

#### Professional Headline
```html
<p class="role">Your Professional Title | Specialisation | Industry</p>
```

#### Professional Summary
Replace the summary section with your bio:
```html
<section id="summary" class="summary">
    <div class="container">
        <h2>Professional Summary</h2>
        <div class="summary-content">
            <p>Your professional summary here...</p>
        </div>
    </div>
</section>
```

### Step 2: Update Your Experience

Replace the experience items with your career history:

```html
<div class="experience-item">
    <div class="experience-header">
        <h3>Your Job Title</h3>
        <span class="company">Company Name</span>
        <span class="period">2023 - Present</span>
    </div>
    <ul class="experience-description">
        <li>Your achievement or responsibility</li>
        <li>Another key accomplishment</li>
    </ul>
</div>
```

### Step 3: Add Your Expertise

Customise the expertise grid with your areas:

```html
<div class="expertise-item">
    <h3>Your Expertise Area</h3>
    <p>Description of your skills and specialisations</p>
</div>
```

### Step 4: Showcase Your Projects

Update the projects section with your work:

```html
<div class="project-card">
    <div class="project-header">
        <h3>Project Name</h3>
        <span class="project-status">Completed</span>
    </div>
    <p class="project-description">Project description...</p>
    <div class="project-tags">
        <span class="tag">Skill Tag</span>
        <span class="tag">Another Tag</span>
    </div>
</div>
```

### Step 5: Add Your Skills

Update the skills and certifications:

```html
<div class="skill-category">
    <h3>Your Skill Category</h3>
    <ul class="skill-list">
        <li>Skill 1</li>
        <li>Skill 2</li>
        <li>Skill 3</li>
    </ul>
</div>
```

### Step 6: Update Social Links

Add your social media profiles in the footer:

```html
<div class="social-links">
    <a href="https://linkedin.com/in/yourprofile" class="social-link">LinkedIn</a>
    <a href="https://twitter.com/yourhandle" class="social-link">Twitter</a>
    <a href="mailto:your.email@example.com" class="social-link">Email</a>
</div>
```

## 🎨 Customisation Tips

### Change Colours
Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-green: #004B49;      /* Main colour */
    --secondary-green: #00A499;    /* Accent colour */
    --dark-grey: #2D2D2D;          /* Dark text */
    --medium-grey: #6F6F6F;        /* Medium text */
    --light-grey: #F5F5F5;         /* Background */
}
```

### Adjust Font Sizes
Modify heading sizes in the responsive sections:

```css
.hero-content h1 {
    font-size: 48px;  /* Desktop */
}

@media (max-width: 768px) {
    .hero-content h1 {
        font-size: 36px;  /* Tablet */
    }
}
```

### Add a Profile Picture
Insert an image in the hero section:

```html
<div class="hero-content">
    <img src="your-photo.jpg" alt="Your Name" class="profile-photo">
    <h1>Your Name</h1>
    <!-- rest of hero content -->
</div>
```

Then add CSS styling:

```css
.profile-photo {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    margin-bottom: 20px;
    border: 3px solid var(--secondary-green);
}
```

## 📱 Testing Responsiveness

1. Open the portfolio in your browser
2. Press `F12` or `Cmd+Option+I` to open Developer Tools
3. Click the mobile device icon to view responsive design
4. Test on different screen sizes:
   - Mobile: 375px - 480px
   - Tablet: 768px - 1024px
   - Desktop: 1200px+

## 🌐 Deployment Options

### GitHub Pages (Recommended)
1. Push your changes to the `main` branch
2. Go to repository Settings
3. Scroll to "GitHub Pages"
4. Select `main` branch as source
5. Your site will be live at `https://yourusername.github.io`

### Other Hosting Services
- **Netlify**: Drag and drop your folder
- **Vercel**: Connect your GitHub repo
- **Traditional Hosting**: Upload files via FTP

## ✅ Quality Checklist

Before publishing, verify:

- [ ] All text is accurate and up-to-date
- [ ] No spelling or grammatical errors
- [ ] All links work correctly
- [ ] Images are optimised and display properly
- [ ] Layout looks good on mobile devices
- [ ] Professional tone throughout
- [ ] Contact information is current
- [ ] Social media links are correct

## 📝 Best Practices

1. **Keep it Concise**: Use bullet points, avoid lengthy paragraphs
2. **Use Action Verbs**: "Led", "Developed", "Implemented" rather than "Worked on"
3. **Quantify Results**: "Increased efficiency by 25%" is better than "Improved efficiency"
4. **Professional Tone**: Write as if for a formal business context
5. **Regular Updates**: Refresh your portfolio quarterly
6. **Mobile First**: Always check mobile view before publishing

## 🆘 Troubleshooting

**Portfolio not displaying correctly?**
- Clear browser cache (Ctrl+Shift+Delete)
- Check that both `index.html` and `styles.css` are in the same directory
- Verify CSS file path in HTML: `<link rel="stylesheet" href="styles.css">`

**Changes not showing after deployment?**
- Wait a few minutes for GitHub Pages to rebuild
- Hard refresh your browser (Ctrl+F5)
- Check that changes are committed and pushed to main branch

**Colours not matching?**
- Ensure CSS variables in `:root` match your colour codes
- Clear browser cache and reload

## 📞 Need Help?

Refer to:
- `README.md` for full documentation
- Inline CSS comments in `styles.css` for styling guidance
- HTML structure in `index.html` for content organisation

---

**Version**: 1.0
**Last Updated**: September 2024
