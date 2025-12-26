# Salamat Tussupbekov Portfolio

## 📁 File Structure

```
portfolio/
├── css/
│   ├── styles.css          # Global design system
│   └── home.css            # Homepage-specific styles
├── js/
│   └── main.js             # Shared JavaScript
├── assets/                 # ADD YOUR FILES HERE
│   ├── favicon.ico
│   ├── favicon-16x16.png
│   ├── favicon-32x32.png
│   ├── favicon-180x180.png
│   ├── logo.png            # Your Sx logo
│   └── Salamat_Tussupbekov_Resume.pdf
├── index.html              # Homepage
├── work.html               # Projects listing
├── about.html              # About page
├── contact.html            # Contact page
├── case-clever-market.html # Case study
├── case-vettime.html       # Case study
├── mindlogistics-case-study-web.html
├── baiterek-case-study-v2.html
└── Vacuumon_Website_CaseStudy.html
```

## 🚀 Deployment Options

### Option 1: Vercel (Recommended - You already have this set up)

1. **Download all files** from this output
2. **Add your assets** (favicon, logo, resume PDF) to the `assets/` folder
3. **Push to your GitHub repo** that's connected to Vercel:
   ```bash
   git add .
   git commit -m "Updated portfolio with new design system"
   git push origin main
   ```
4. Vercel will **automatically deploy** within minutes

### Option 2: Manual Vercel Deploy

1. Go to [vercel.com](https://vercel.com)
2. Drag and drop the entire portfolio folder
3. Done!

### Option 3: Netlify

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the folder to deploy
3. Or connect your GitHub repo

### Option 4: GitHub Pages

1. Push to a GitHub repo
2. Go to Settings → Pages
3. Select "Deploy from a branch" → main → / (root)
4. Your site will be at `username.github.io/repo-name`

## ⚠️ Before Deploying

Make sure to add these files to the `assets/` folder:

- [ ] `favicon.ico` - Browser tab icon
- [ ] `favicon-16x16.png`
- [ ] `favicon-32x32.png`  
- [ ] `favicon-180x180.png` - Apple touch icon
- [ ] `logo.png` - Your Sx logo (if using image instead of CSS)
- [ ] `Salamat_Tussupbekov_Resume.pdf` - Your resume

## 🎨 Customization

### Colors (in `css/styles.css`)
```css
:root {
  --crimson: #DC2626;        /* Primary brand color */
  --crimson-deep: #B91C1C;   /* Darker variant */
  --ink: #18181B;            /* Text color */
  /* ... more variables */
}
```

### Fonts
The portfolio uses:
- **Fraunces** - Serif for headings
- **Outfit** - Sans-serif for body text

Both are loaded from Google Fonts.

## 📧 Contact Form

The contact form uses a placeholder action. To make it work:

1. Sign up at [Formspree](https://formspree.io) (free)
2. Create a new form
3. Replace `action="https://formspree.io/f/your-form-id"` with your actual form ID

## 🔗 Links to Update

- LinkedIn URL in footer and contact page
- Email address (hello@salamxt.com)
- Resume download link

---

Built with ❤️ for Salamat Tussupbekov
