# World Rainforest Fund - Modern Tailwind Website

This folder contains a complete, self-contained modern redesign of the World Rainforest Fund website using Tailwind CSS.

## 🚀 Quick Start

This site is completely static and can be hosted from this folder alone. No build process or dependencies required.

To view locally:
```bash
cd new_tailwind
python -m http.server 8000
# Visit http://localhost:8000
```

Or simply open `index.html` in a web browser.

## 📁 Structure

```
new_tailwind/
├── *.html              # 16 HTML pages (homepage, about, contact, etc.)
├── uploads/            # Images and media files (57MB)
│   └── 1/2/3/8/123807695/  # Photo gallery and page images
├── files/              # Original CSS and JavaScript assets (788KB)
│   ├── main_style.css  # Original site styles (for reference)
│   └── theme/          # Theme files
└── apps/               # App integrations (16KB)
```

## 📄 Pages (16 total)

### Core Pages
- `index.html` (22KB) - Modern homepage with hero section and stats
- `contact.html` (12KB) - Contact form
- `donate.html` (18KB) - Donation information
- `mission-statement.html` (16KB) - Organization mission

### Educational
- `all-about-rainforests.html` (27KB) - Comprehensive educational content
- `articles.html` (4.9KB) - Article listings
- `books.html` (5.1KB) - Recommended reading

### Organization
- `advisory-board.html` (13KB) - Board member profiles
- `biographies.html` (12KB) - Team biographies
- `projects-and-grants.html` (7.9KB) - Grant program info
- `grant-application.html` (8.2KB) - Application process

### Resources
- `rainforest-organizations.html` (5.6KB) - Partner organizations
- `partner-organizations.html` (5.3KB) - Collaboration partners
- `photo-gallery.html` (4.9KB) - Image gallery
- `videos.html` (5.3KB) - Video content
- `legal-documents.html` (5.5KB) - 501(c)(3) documentation

## 🎨 Design Features

- **Zero JavaScript required** - Pure HTML/CSS implementation
- **Tailwind CSS via CDN** - No build step needed
- **Fully responsive** - Mobile-first design
- **Minimal custom CSS** - Only 4 lines for mobile menu toggle
- **Modern emerald green color scheme**
- **Accessible** - Semantic HTML and proper ARIA labels
- **Fast loading** - Optimized with Tailwind utility classes

## 📦 Assets Included

- **219 total asset files** (images, CSS, JS)
- **57MB of images** in `/uploads`
- **All original photos** from Chien C. Lee
- **Original theme CSS and JS** (for reference only, not used in new design)

## 🌐 Hosting

This folder can be deployed to any static hosting service:
- GitHub Pages
- Netlify
- Vercel
- AWS S3
- Any web server (Apache, Nginx, etc.)

Simply upload the entire `new_tailwind` folder contents to your hosting provider.

## ✨ Technical Details

- **No JavaScript** - Site works without JS enabled
- **CSS-only navigation** - Hamburger menu uses checkbox hack
- **Tailwind CSS** - Loaded from CDN (https://cdn.tailwindcss.com)
- **Clean URLs** - All pages are top-level .html files
- **Self-contained** - All assets included, no external dependencies

## 📸 Image Attribution

Nature photography copyright © Chien C. Lee (https://photos.chienclee.com/)

## 🔒 Legal

The World Rainforest Fund is a 501(c)(3) tax-exempt non-profit US corporation (EIN: 94-2914127)
