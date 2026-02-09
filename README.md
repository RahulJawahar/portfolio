# Portfolio Website - Rahul J

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## 🚀 Live Demo
Visit: `https://YOUR_GITHUB_USERNAME.github.io/portfolio`

## ✨ Features
- Modern dark theme with gradient accents
- Smooth scroll animations
- Responsive design for all devices
- Contact form integration with Formspree

## 📧 Setting Up Contact Form

1. Go to [Formspree.io](https://formspree.io) and sign up (free)
2. Create a new form
3. Copy your Form ID (looks like `xyzabcde`)
4. In `index.html`, replace `YOUR_FORM_ID` with your actual Form ID:
   ```html
   action="https://formspree.io/f/YOUR_ACTUAL_FORM_ID"
   ```

## 🌐 Deployment to GitHub Pages

1. Create a new repository on GitHub named `portfolio`
2. Run these commands:
   ```bash
   git add .
   git commit -m "Initial portfolio commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/portfolio.git
   git push -u origin main
   ```
3. Go to repository Settings → Pages
4. Set Source to "Deploy from a branch" → select `main` branch
5. Your site will be live at `https://YOUR_USERNAME.github.io/portfolio`

## 📝 Customization
- Update social links in the Contact section
- Add your actual LinkedIn and GitHub profile URLs
- Modify colors in `style.css` (CSS variables at the top)

## 📄 License
MIT License
