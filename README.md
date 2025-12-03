# Mantasha Beg - Portfolio

A stunning, modern portfolio website built with HTML5, CSS3, and Vanilla JavaScript featuring an AI-themed design with animations and interactive elements.

## 🚀 Live Demo

Visit the portfolio at: [Your Vercel URL will appear here after deployment]

## 📋 Features

- **AI-Themed Design** - Futuristic neon aesthetics with gradient colors
- **Smooth Animations** - Scroll animations and interactive UI elements
- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Interactive Carousel** - Showcase projects with smooth transitions
- **Smooth Scrolling** - Navigation links with smooth page scrolling
- **Contact Form** - Easy way for visitors to reach out
- **Social Links** - Connected to LinkedIn, GitHub, Twitter, Discord, Instagram, and Unstop
- **Performance Optimized** - Fast loading with optimized assets and caching

## 📁 Project Structure

```
.
├── 6h/
│   ├── index.html          # Main portfolio HTML
│   └── mantasha.png        # Profile image
├── vercel.json             # Vercel configuration
├── package.json            # Project metadata and scripts
├── .gitignore              # Git ignore file
└── README.md               # This file
```

## 🛠️ Technologies Used

### Frontend
- **HTML5** - Semantic markup
- **CSS3** - Advanced styling with animations
- **JavaScript (Vanilla)** - Interactive features
- **Google Fonts** - Exo 2 and Orbitron fonts

### Design Elements
- Neon color scheme
- Gradient effects
- Keyframe animations
- Neural network background effects
- AI nodes and binary rain animations
- Carousel with 3D transformations

## 📦 Installation & Local Development

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn
- Git

### Setup Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/Moonmakere/portfolio.git
   cd portfolio
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Run locally**
   ```bash
   npm start
   ```
   Then visit `http://localhost:8000` in your browser

## 🚀 Deployment to Vercel

### Method 1: Using Vercel CLI

1. **Install Vercel CLI**
   ```bash
   npm install -g vercel
   ```

2. **Deploy**
   ```bash
   npm run deploy
   # or
   vercel
   ```

3. **Follow the prompts** to complete deployment

### Method 2: Using GitHub & Vercel Dashboard

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Prepare portfolio for Vercel deployment"
   git push origin main
   ```

2. **Connect to Vercel**
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import your GitHub repository
   - Click "Deploy"

3. **Wait for deployment** - Vercel will automatically build and deploy your site

## 📝 Configuration

### vercel.json
The `vercel.json` file contains Vercel-specific configurations:
- **Framework**: static (plain HTML/CSS/JS)
- **Redirects**: Routes to serve from the `6h` folder
- **Headers**: Security headers and cache control
- **Clean URLs**: Removes `.html` extensions from URLs

### package.json
Contains project metadata and build scripts:
- `npm start` - Local development server
- `npm run build` - Build command (no-op for static site)
- `npm run deploy` - Deploy to Vercel

## 🔒 Security Headers

The portfolio includes important security headers:
- **X-Content-Type-Options** - Prevents MIME type sniffing
- **X-Frame-Options** - Prevents clickjacking
- **X-XSS-Protection** - Enables XSS protection
- **Referrer-Policy** - Controls referrer information

## ⚡ Performance Optimizations

- Long cache times for assets (1 year)
- Short cache times for HTML (no cache, must revalidate)
- Minified CSS and JavaScript
- Optimized animations
- Lazy loading of images

## 📱 Responsive Breakpoints

- **Desktop**: 1400px and above
- **Tablet**: 768px to 1399px
- **Mobile**: Below 768px

## 🎨 Customization

### Changing Colors
Edit the CSS variables in `6h/index.html`:
```css
:root {
    --glow-primary: rgba(236, 72, 153, 0.7);
    --glow-secondary: rgba(167, 139, 250, 0.6);
    --neon-pink: rgba(236, 72, 153, 0.9);
    --neon-purple: rgba(167, 139, 250, 0.9);
    --neon-blue: rgba(147, 197, 253, 0.8);
    --neon-cyan: rgba(34, 211, 238, 0.8);
}
```

### Updating Personal Information
1. Change the profile image (`mantasha.png`)
2. Update text content in the HTML sections
3. Modify social media links in the hero section
4. Update projects in the carousel

## 🔗 Social Links

Current social links in the portfolio:
- LinkedIn: [linkedin.com/in/mantashabeg](https://www.linkedin.com/in/mantashabeg/)
- GitHub: [github.com/Moonmakere](https://github.com/Moonmakere)
- Twitter/X: [@Shelovestech03](https://x.com/Shelovestech03)
- Discord: [Discord Link](https://discord.com/channels/@me)
- Instagram: [@tech.sheloves](https://www.instagram.com/tech.sheloves/)
- Unstop: [unstop.com/u/mantashabeg](https://unstop.com/u/mantashabeg)

## 📋 Sections

1. **Header** - Navigation menu
2. **Hero** - Introduction and profile image
3. **About** - Brief bio and background
4. **Experience** - Work experience and hackathons
5. **Projects** - Interactive carousel of projects
6. **Skills** - Technical skills overview
7. **Achievements** - Awards and recognitions
8. **Contact** - Contact form
9. **Footer** - Copyright information

## 🚦 Deployment Checklist

Before deploying to Vercel:
- [x] HTML is properly formatted
- [x] Image paths are correct
- [x] All links are working
- [x] Responsive design tested
- [x] vercel.json is configured
- [x] package.json is setup
- [x] .gitignore is in place
- [x] Social links are updated
- [x] Portfolio content is accurate

## 🐛 Troubleshooting

### Images not showing after deployment
- Check that `mantasha.png` is in the `6h/` folder
- Verify the image path in HTML uses `./mantasha.png`

### Navigation links not working
- Ensure all section IDs match the href attributes
- Check that `vercel.json` rewrites are configured correctly

### Styles not applying
- Clear browser cache (Ctrl+Shift+Delete or Cmd+Shift+Delete)
- Check network tab in DevTools for CSS loading

## 📜 License

This portfolio is licensed under the MIT License. See LICENSE file for details.

## ✉️ Contact

For inquiries about this portfolio or my services:
- Email: mantashabeg@email.com (update with actual email)
- LinkedIn: [linkedin.com/in/mantashabeg](https://www.linkedin.com/in/mantashabeg/)
- GitHub: [github.com/Moonmakere](https://github.com/Moonmakere)

## 🙏 Acknowledgments

- Google Fonts for typography
- Vercel for hosting and deployment
- All who have inspired this portfolio

---

**Last Updated**: December 2, 2025
**Status**: Ready for Vercel deployment ✅
