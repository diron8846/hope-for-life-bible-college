# Hope for Life Bible College - GitHub Pages Deployment

This is a static version of the Hope for Life Bible College website, optimized for GitHub Pages deployment.

## Features

- 🎮 Interactive 3D gaming-style landing page
- ✨ Floating neon icons with 3D effects
- 🎯 Responsive cursor glow effects
- 👨‍🏫 Teacher profiles with ministry team
- 📖 About section with vision and mission
- 📞 Contact form with QR code integration
- 🌟 Dynamic background animations

## Deployment Instructions

### Option 1: Upload to GitHub Repository

1. Create a new repository on GitHub
2. Upload all files from this `github-pages-deploy` folder to your repository
3. Go to repository Settings > Pages
4. Select "Deploy from a branch" as source
5. Choose "main" branch and "/ (root)" folder
6. Click Save

### Option 2: GitHub CLI (if you have it installed)

```bash
# Create new repository
gh repo create hope-for-life-bible-college --public

# Clone and add files
git clone https://github.com/YOUR_USERNAME/hope-for-life-bible-college.git
cd hope-for-life-bible-college

# Copy all files from github-pages-deploy folder here
# Then commit and push
git add .
git commit -m "Initial deployment of Hope for Life Bible College website"
git push origin main

# Enable GitHub Pages
gh repo edit --enable-pages --pages-branch main
```

## File Structure

```
├── index.html              # Main HTML file
├── assets/                 # CSS and JavaScript bundles
│   ├── index-C2TWAvma.js  # Main JavaScript bundle
│   └── index-DvQPJsLl.css # Main CSS bundle
├── attached_assets/        # Images and media
│   ├── logo_1752730242553.png
│   ├── ministry_qr_code_1752730685300.png
│   ├── Ev.Stanley George_1752730221152.jpeg
│   ├── Pastor Jose Mathew_1752730221153.jpg
│   └── Ev.Ronald Maina_1752730221153.jpg
├── teachers-data.js        # Static teacher data
└── README.md              # This file
```

## Ministry Information

- **Location**: Nairobi, Githurai 45, Mwihoko, Kenya
- **Phone**: +254 727691035
- **Email**: dismusmutuku@gmail.com
- **Website**: https://diron8846.github.io/hope-for-life-ministries-international/

## Technical Details

- Built with React 18 and TypeScript
- Styled with Tailwind CSS
- 3D effects using CSS transforms and animations
- Optimized for modern browsers
- Fully responsive design

## Support

For technical support or questions about the website, please contact the ministry team using the information provided above.

---

*Built with ❤️ for Hope for Life Ministry*