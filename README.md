# Lunar Agency Website

A modern, responsive website for Lunar Agency built with HTML, CSS, and Tailwind CSS.

## 🚀 Deployment Ready

This project is configured for easy deployment on Netlify with automatic builds.

## 📁 Project Structure

```
lunar/
├── index.html          # Main website file
├── 404.html           # Custom 404 page
├── src/
│   └── input.css      # Tailwind CSS source file
├── dist/
│   └── tailwind.css   # Built CSS file
├── package.json       # Node.js dependencies and scripts
├── tailwind.config.js # Tailwind CSS configuration
├── netlify.toml       # Netlify deployment configuration
└── .gitignore         # Git ignore rules
```

## 🛠️ Development

### Prerequisites
- Node.js (v18 or higher)
- npm

### Local Development
1. Install dependencies:
   ```bash
   npm install
   ```

2. Build CSS:
   ```bash
   npm run build
   ```

3. Watch for changes (optional):
   ```bash
   npm run build-css
   ```

4. Open `index.html` in your browser

## 🌐 Deployment

### GitHub + Netlify (Recommended)

1. **Push to GitHub:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/lunar.git
   git push -u origin main
   ```

2. **Deploy on Netlify:**
   - Go to [netlify.com](https://netlify.com)
   - Click "New site from Git"
   - Connect your GitHub repository
   - Netlify will automatically detect the build settings from `netlify.toml`
   - Click "Deploy site"

### Build Settings (Auto-configured)
- **Build command:** `npm run build`
- **Publish directory:** `.` (root)
- **Node version:** 18

## ✨ Features

- ⚡ Fast loading with optimized CSS
- 📱 Fully responsive design
- 🎨 Modern UI with Tailwind CSS
- 🔒 Security headers configured
- 📈 Performance optimized
- 🌍 SEO friendly

## 📝 Notes

- The website uses locally built Tailwind CSS for optimal performance
- All build processes are automated via Netlify
- Custom 404 page included
- Security and performance headers configured
