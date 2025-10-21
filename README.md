# Platform Engineering Static Website

A modern, responsive static website about Platform Engineering built with HTML, Tailwind CSS (via CDN), and shadcn/ui styling conventions.

## 🌟 Features

- **Fully Static**: No build process required - ready for GitHub Pages
- **Responsive Design**: Mobile-first approach that works on all devices
- **Dark Mode**: Toggle between light and dark themes with persistent preference
- **Smooth Scrolling**: Navigation with smooth scroll to sections
- **Modern UI**: shadcn/ui inspired design system with beautiful components
- **Accessible**: Built with accessibility best practices
- **Performance**: Lightweight and fast-loading

## 📋 Sections

1. **Hero Section**: Eye-catching landing with title, tagline, and call-to-action buttons
2. **About Section**: Detailed explanation of Platform Engineering
3. **Key Principles**: Six beautifully designed cards highlighting core concepts
4. **Contact Section**: Social links and email contact options
5. **Footer**: Copyright and GitHub repository link

## 🚀 Deploy to GitHub Pages

### Method 1: Using GitHub UI (Recommended for beginners)

1. **Create a new repository on GitHub**
   - Go to [github.com/new](https://github.com/new)
   - Name it `staticPE` (or any name you prefer)
   - Make it public
   - Don't initialize with README (we already have one)

2. **Push your code**
   ```bash
   cd /Users/chris/Developer/staticPE
   git init
   git add .
   git commit -m "Initial commit: Platform Engineering website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/staticPE.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Click **Settings** > **Pages** (in the left sidebar)
   - Under "Source", select **Deploy from a branch**
   - Select **main** branch and **/ (root)** folder
   - Click **Save**

4. **Access your site**
   - Your site will be live at: `https://YOUR_USERNAME.github.io/staticPE/`
   - It may take a few minutes for the first deployment

### Method 2: Using GitHub CLI

```bash
# Install GitHub CLI if you haven't: brew install gh
cd /Users/chris/Developer/staticPE
git init
git add .
git commit -m "Initial commit: Platform Engineering website"
gh repo create staticPE --public --source=. --remote=origin --push
gh browse --settings
# Then manually enable Pages in Settings > Pages
```

## 🛠️ Customization

### Change Colors

Edit the CSS custom properties in `style.css`:

```css
:root {
  --background: 0 0% 100%;
  --foreground: 222.2 84% 4.9%;
  /* ... other color variables */
}
```

### Update Content

- **Hero text**: Edit lines 72-80 in `index.html`
- **About section**: Edit lines 93-107 in `index.html`
- **Principles**: Edit cards starting at line 127 in `index.html`
- **Contact links**: Update lines 249-263 in `index.html`

### Add More Sections

1. Add a new `<section>` in `index.html`
2. Add a navigation link in the `<nav>` (line 50)
3. The smooth scroll will work automatically

## 🎨 Technologies Used

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **CSS3**: Custom properties for theming
- **Vanilla JavaScript**: Theme toggle and smooth scrolling
- **shadcn/ui**: Design system inspiration

## 📱 Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

Feel free to use this template for your own projects!

## 🤝 Contributing

If you'd like to improve this website:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -m 'Add some improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📞 Contact

- GitHub: [@platformengineering](https://github.com/cvs79/platformengineering)

---

**Built with ❤️ for the Platform Engineering community**
