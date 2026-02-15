# Quick Setup Guide - Deploy Your Resume in 5 Minutes

## Step 1: Create GitHub Repository

1. Go to https://github.com/new
2. Repository name: `resume` (or any name you like)
3. Description: "Professional Resume Website"
4. Make it **Public**
5. **Don't** add README, .gitignore, or license (we already have them)
6. Click "Create repository"

## Step 2: Upload Your Files

### Using Git (Command Line)

```bash
# Navigate to the folder containing your resume files
cd path/to/resume/folder

# Initialize git
git init

# Add all files
git add .

# Make your first commit
git commit -m "Initial commit: Professional resume website"

# Set the default branch name
git branch -M main

# Add your GitHub repository as remote (replace YOUR_USERNAME and resume with your info)
git remote add origin https://github.com/YOUR_USERNAME/resume.git

# Push to GitHub
git push -u origin main
```

### Using GitHub Website (Drag & Drop)

1. On your new repository page, click "uploading an existing file"
2. Drag and drop ALL files from your resume folder
3. Make sure to include:
   - index.html
   - styles.css
   - script.js
   - README.md
   - .gitignore
   - Ujwal_Bukka_Resume.pdf
   - The `.github` folder with `workflows/deploy.yml` inside
4. Scroll down and click "Commit changes"

## Step 3: Enable GitHub Pages

1. In your repository, click **Settings** (top navigation)
2. Click **Pages** in the left sidebar
3. Under "Build and deployment":
   - **Source**: Select "GitHub Actions"
4. That's it! The deployment will start automatically

## Step 4: Wait for Deployment

1. Click the **Actions** tab at the top
2. You'll see a workflow running called "Deploy to GitHub Pages"
3. Wait 2-3 minutes for it to complete (green checkmark)

## Step 5: View Your Website

Your website is now live at:
```
https://YOUR_USERNAME.github.io/resume/
```

Replace `YOUR_USERNAME` with your actual GitHub username.

## 🎉 You're Done!

Your professional resume website is now live and accessible to anyone!

---

## Quick Customization Checklist

After deployment, edit `index.html` to update:

- [ ] Your name in the header
- [ ] Your current job title and company
- [ ] Professional summary
- [ ] Key expertise areas
- [ ] Work experience details
- [ ] Education information
- [ ] Email address in contact section
- [ ] LinkedIn profile URL
- [ ] Phone number

After making changes:
```bash
git add .
git commit -m "Update resume content"
git push
```

Your site will auto-update in 1-2 minutes!

---

## Troubleshooting

**Site not showing up?**
- Wait 3-5 minutes after first deployment
- Check the Actions tab to see if deployment completed
- Make sure repository is Public (not Private)

**Changes not appearing?**
- Clear browser cache (Ctrl+Shift+R or Cmd+Shift+R)
- Check Actions tab to confirm deployment finished
- Wait 1-2 minutes after pushing changes

**404 Error?**
- Verify file is named `index.html` (exact lowercase)
- Make sure it's in the root directory (not in a subfolder)
- Check Settings → Pages to see the deployment status

---

## Need More Help?

See the full README.md for detailed documentation and customization options.
