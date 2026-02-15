# Ujwal Bukka - Professional Resume Website

A modern, responsive personal resume website built with HTML, CSS, and JavaScript. Features dark/light theme toggle, smooth animations, and a clean professional design showcasing 20+ years of technology leadership experience.

## 🌟 Features

- **Responsive Design**: Looks great on desktop, tablet, and mobile devices
- **Dark/Light Theme**: Toggle between themes with persistent preference
- **Smooth Animations**: Professional fade-in and scroll animations
- **Modern UI**: Clean, contemporary design with beautiful typography
- **Easy to Customize**: Simple HTML structure, well-organized CSS
- **Fast Loading**: No heavy frameworks, pure vanilla JavaScript
- **Print-Friendly**: Optimized styles for printing/PDF generation
- **Expertise Section**: Highlights key areas of competency with icons
- **Detailed Experience**: Organized subsections for better readability

## 🚀 Quick Start

### 1. Clone or Download

Clone this repository or download the files to your local machine.

### 2. Customize Your Content

Edit `index.html` to add your personal information:

- **Personal Info**: Update name, title, company, and contact information
- **Profile Image**: Replace the placeholder with your photo (see instructions below)
- **Summary**: Edit the professional summary section
- **Expertise**: Update the key expertise areas
- **Experience**: Update work history, achievements, and subsections
- **Education**: Add your educational background
- **Contact**: Update email, LinkedIn, and phone number

### 3. Add Your Profile Photo (Optional)

Replace the placeholder icon with your photo:

1. Add your photo to the project folder (e.g., `profile.jpg`)
2. In `index.html`, replace the `.profile-placeholder` div with:
```html
<img src="profile.jpg" alt="Your Name" style="width: 200px; height: 200px; border-radius: 50%; object-fit: cover; box-shadow: var(--shadow-xl);">
```

### 4. Your Resume PDF is Already Included

The `Ujwal_Bukka_Resume.pdf` file is already included and linked in the download button.

## 📤 Deploy to GitHub Pages

### Option 1: Using GitHub Actions (Recommended)

1. Create a new repository on GitHub (e.g., `resume`)
2. Push your code to the repository:
```bash
git init
git add .
git commit -m "Initial commit: Professional resume website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/resume.git
git push -u origin main
```

3. The GitHub Actions workflow is already configured in `.github/workflows/deploy.yml`
4. Go to your repository Settings → Pages
5. Under "Build and deployment", select "GitHub Actions" as the source
6. Your site will be available at `https://YOUR_USERNAME.github.io/resume/` in 2-3 minutes

### Option 2: Manual Deployment

1. Go to your repository on GitHub
2. Click Settings → Pages
3. Under "Build and deployment":
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)
4. Click Save
5. Wait a few minutes for deployment
6. Your site will be live at `https://YOUR_USERNAME.github.io/resume/`

## 🎨 Customization Guide

### Colors

Edit the CSS variables in `styles.css` under `:root` and `[data-theme="dark"]`:

```css
:root {
    --accent-primary: #2563eb;  /* Primary brand color */
    --accent-secondary: #3b82f6; /* Secondary brand color */
    /* ... other colors */
}
```

### Fonts

The site uses Google Fonts by default:
- **Playfair Display** for headings (serif, elegant)
- **IBM Plex Sans** for body text (sans-serif, clean)

To change fonts, update the Google Fonts link in `index.html` and the font-family in `styles.css`.

### Layout

The site uses CSS Grid and Flexbox for layout. Main sections are in `.container` with a max-width of 1100px. Adjust in `styles.css`:

```css
.container {
    max-width: 1100px; /* Change this value */
}
```

### Expertise Icons

To change the icons in the expertise section, replace the SVG code in the `.expertise-icon` divs. You can find free SVG icons at:
- [Heroicons](https://heroicons.com/)
- [Feather Icons](https://feathericons.com/)
- [Lucide Icons](https://lucide.dev/)

## 📁 Project Structure

```
├── index.html                    # Main HTML file with all content
├── styles.css                    # All styling and themes
├── script.js                     # JavaScript for theme toggle and animations
├── Ujwal_Bukka_Resume.pdf       # Your resume PDF
├── .github/
│   └── workflows/
│       └── deploy.yml           # GitHub Actions deployment config
├── .gitignore                   # Git ignore file
└── README.md                    # This file
```

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 💡 Tips for Best Results

1. **Keep it Updated**: Regularly update your achievements and skills
2. **Professional Photo**: Use a high-quality, professional headshot if adding a photo
3. **Concise Content**: Keep descriptions clear and impactful
4. **Keywords**: Include relevant industry keywords for better visibility
5. **Test Responsiveness**: Check how it looks on different devices
6. **Proofread**: Always double-check for typos and grammatical errors

## 📝 Content Sections Explained

### Expertise Section
Highlights your top 4-6 core competencies with icons. Keep these broad but specific to your niche.

### Experience Subsections
The AWS experience is organized into:
- **Customer Engagements**: Direct customer work and impact
- **Leadership**: Team and organizational contributions
- **Content & Innovation**: Thought leadership and open-source work
- **Speaking Engagements**: Public speaking and visibility

This structure makes it easier for recruiters to quickly find relevant information.

## 🤝 Updating Your Resume

To update content:

1. Edit `index.html` with your changes
2. Commit and push to GitHub:
```bash
git add .
git commit -m "Update resume content"
git push
```
3. Your site will auto-update in 1-2 minutes

## 📧 Contact Information

The site includes three contact methods:
- Email (mailto link)
- LinkedIn (opens in new tab)
- Phone (tel link for mobile click-to-call)

Update these in the contact section of `index.html`.

## 📝 License

This project is open source and available for personal use. Feel free to customize it for your own resume website!

---

Built with ❤️ using HTML, CSS, and JavaScript | No frameworks required
