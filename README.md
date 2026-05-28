# Crown Construction Management — Website

A professional, multi-page static website for Crown Construction Management.  
Built for GitHub Pages hosting.

## Pages

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Hero, About preview, Services overview, Process, Why Crown, CTA |
| About | `about.html` | Company story, values, service area |
| Services | `services.html` | All 9 services in detail, engagement types |
| Contact | `contact.html` | Contact form + company info |

## Setup — GitHub Pages

### 1. Create a GitHub Repository
- Go to [github.com/new](https://github.com/new)
- Name it `crown-construction` (or anything you want)
- Make it **Public**
- Click **Create repository**

### 2. Upload the Files
- Click **"uploading an existing file"**
- Drag the entire contents of this folder (all HTML files, `css/`, `js/`, `images/`)
- Click **Commit changes**

### 3. Enable GitHub Pages
- Go to **Settings** → **Pages**
- Under **Source**, select **Deploy from a branch**
- Select **main** branch and **/ (root)** folder
- Click **Save**
- Your site will be live at `https://yourusername.github.io/crown-construction/`

### 4. Set Up the Contact Form (Formspree)
- Go to [formspree.io](https://formspree.io) and create a free account
- Click **New Form** → name it "Crown Contact" → select your email
- Copy the form endpoint (e.g., `https://formspree.io/f/xpzvnqkl`)
- In `contact.html`, find `YOUR_FORM_ID` and replace with your actual form ID
- Free tier gives you 50 submissions/month

### 5. Custom Domain (Optional)
When you're ready for a custom domain:
- Buy your domain from Namecheap, Google Domains, etc.
- In GitHub repo **Settings** → **Pages** → **Custom domain**, enter your domain
- Add a CNAME record pointing to `yourusername.github.io`
- Check **Enforce HTTPS**

## Customization

### Update Contact Info
Search for `[Phone Number]` and `[Email Address]` across all HTML files and replace with the real values.

### Colors & Fonts
All brand colors and fonts are defined as CSS variables in `css/style.css` at the top. Change once, updates everywhere.

### Adding Content
The site uses semantic HTML with BEM-style CSS classes. Add new sections by following the existing patterns.

## File Structure
```
crown-construction/
├── index.html
├── about.html
├── services.html
├── contact.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── images/
│   ├── logo-full-color.png
│   ├── logo-white.png
│   ├── logo-black.png
│   └── logo-icon.jpg
└── README.md
```

## Tech Stack
- Pure HTML, CSS, JavaScript — no frameworks, no build tools
- Google Fonts (Syne + Outfit)
- Formspree for contact form (free tier)
- CSS custom properties for theming
- Intersection Observer for scroll animations
- Fully responsive (mobile-first)

---

**Crown Construction Management**  
Building Today • Creating Tomorrow
