# Dibyajyoti Mohanty - AI/ML Engineer Portfolio

A sleek, modern portfolio website with a **matte black and neon green** theme, showcasing expertise in AI/ML, Generative AI, NLP, Computer Vision, and Real-time Speech Systems.

## 🌟 Features

- **Matte Black & Green Theme** - Cyberpunk-inspired dark theme with neon green accents
- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Professional design with smooth animations and glow effects
- **AI/ML Focus** - Specialized sections for AI projects, skills, and experience
- **SEO Friendly** - Properly structured with meta tags
- **Fast Loading** - Optimized performance with minimal dependencies
- **Interactive Elements** - Smooth scrolling, navigation highlighting, and hover effects

## 🚀 Quick Start

### Customize Your Content

1. **Update Personal Information** in `index.html`:
   - Replace "your.email@example.com" with your actual email
   - Update social media links (GitHub, LinkedIn, Twitter)
   - Modify the hero section with your name and title

2. **Add Your Experience**:
   - Find the `<!-- Experience Section -->` in `index.html`
   - Update job titles, companies, dates, and responsibilities

3. **Update Skills**:
   - Modify the skill tags in the `<!-- Skills Section -->`
   - Add or remove technologies as needed

4. **Add Projects**:
   - Update project cards in the `<!-- Projects Section -->`
   - Include project names, descriptions, technologies, and links

5. **Update Education**:
   - Modify the education cards with your degrees and universities

6. **Add Your Resume PDF**:
   - Replace `Dibyajyoti_Mohanty_Resume.pdf` with your updated resume
   - Or update the filename in the "Download Resume" button link

## 📦 Hosting on GitHub Pages

### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name your repository (e.g., `portfolio` or `yourusername.github.io`)
5. Set it to "Public"
6. Click "Create repository"

### Step 2: Push Your Code to GitHub

Open your terminal in the project folder and run these commands:

```bash
# Initialize git repository
git init

# Add all files
git add .

# Commit your files
git commit -m "Initial commit: Portfolio website"

# Add your GitHub repository as remote (replace with your repository URL)
git remote add origin https://github.com/yourusername/portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "main" branch
5. Select "/" (root) as the folder
6. Click "Save"
7. Wait a few minutes for deployment

### Step 4: Access Your Website

Your website will be available at:
- If repository name is `yourusername.github.io`: `https://yourusername.github.io`
- If repository name is anything else: `https://yourusername.github.io/repository-name`

## 🔧 Customization Tips

### Colors
The current theme uses a **matte black and neon green** color scheme. Edit the CSS variables in `styles.css` to customize:
```css
:root {
    --primary-color: #00ff88;      /* Neon green */
    --secondary-color: #00cc6f;    /* Darker green */
    --dark-bg: #0a0e27;            /* Dark blue-black */
    --darker-bg: #060913;          /* Deeper black */
    --card-bg: #151a30;            /* Card background */
    /* Modify these values to change colors */
}
```

### Fonts
Replace the font family in `styles.css`:
```css
body {
    font-family: 'Your Font', sans-serif;
}
```

### Hero Background
The hero section features a subtle dark gradient with green glows. Customize in `styles.css`:
```css
.hero {
    background: linear-gradient(135deg, #0a0e27 0%, #1a1f38 50%, #0a0e27 100%);
}
```

## 📁 File Structure

```
portfolio/
├── index.html              # Main HTML file
├── styles.css              # All styling
├── script.js               # JavaScript for interactivity
├── Dibyajyoti_Mohanty_Resume.pdf  # Your resume
└── README.md               # This file
```

## 🛠️ Technologies Used

- **HTML5** - Structure and content
- **CSS3** - Styling and animations
- **JavaScript** - Interactivity and dynamic effects
- **Font Awesome** - Icons
- **GitHub Pages** - Hosting

## 💡 Tips for Success

1. **Keep it Updated** - Regularly update your projects and experience
2. **Add Analytics** - Consider adding Google Analytics to track visitors
3. **Custom Domain** - You can add a custom domain in GitHub Pages settings
4. **SEO** - Update meta tags with relevant keywords
5. **Performance** - Optimize images and minimize code for faster loading

## 📝 License

Feel free to use this template for your own portfolio. No attribution required!

## 🤝 Contributing

Found a bug or want to suggest an improvement? Feel free to open an issue or submit a pull request!

---

**Built with ❤️ and code**
