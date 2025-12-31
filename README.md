# SCALE Workshop Website

**SCALE: Scalable Optimization for Efficient and Adaptive Foundation Models**

A modern, responsive workshop website template for ICML 2026.

## 🚀 Quick Start

### Option 1: GitHub Pages (Recommended)

1. Create a new repository on GitHub named `scale-workshop.github.io`
2. Push this folder's contents to the repository:
   ```bash
   cd scale-workshop.github.io
   git init
   git add .
   git commit -m "Initial website setup"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/scale-workshop.github.io.git
   git push -u origin main
   ```
3. Go to **Settings** → **Pages** → Enable GitHub Pages from the `main` branch
4. Your site will be live at `https://YOUR-USERNAME.github.io/scale-workshop.github.io/`

### Option 2: Local Preview

Simply open `index.html` in your browser, or use a local server:

```bash
# Python 3
python -m http.server 8000

# Then visit http://localhost:8000
```

## 📁 File Structure

```
scale-workshop.github.io/
├── index.html          # Main HTML file
├── css/
│   └── style.css       # All styles
├── js/
│   └── main.js         # JavaScript functionality
├── images/             # Store speaker/organizer photos here
│   ├── speakers/       # Speaker headshots
│   ├── organizers/     # Organizer headshots
│   └── sponsors/       # Sponsor logos
└── README.md           # This file
```

## ✏️ Customization Guide

### 1. Update Workshop Details

Edit `index.html` to update:

- **Dates**: Search for "TBD" and replace with actual dates
- **Location**: Update the venue information in the hero section
- **Email**: Replace `scale2026@googlegroups.com` with your contact email

### 2. Add Speakers

Replace speaker placeholders with actual information:

```html
<div class="speaker-card">
    <div class="speaker-image">
        <img src="images/speakers/speaker-name.jpg" alt="Speaker Name">
    </div>
    <div class="speaker-info">
        <h3 class="speaker-name">Dr. Jane Smith</h3>
        <p class="speaker-affiliation">Stanford University</p>
    </div>
</div>
```

### 3. Add Organizers

Same pattern as speakers - just update the organizer cards.

### 4. Update Schedule

Modify the schedule items in the Schedule section with actual times and talk titles.

### 5. Add Sponsor Logos

Replace placeholder divs with actual sponsor images:

```html
<div class="sponsors-grid">
    <a href="https://sponsor-url.com">
        <img src="images/sponsors/sponsor-logo.png" alt="Sponsor Name">
    </a>
</div>
```

### 6. Customize Colors

Edit CSS variables in `css/style.css`:

```css
:root {
    --color-primary: #0d3b4c;      /* Deep teal - main color */
    --color-accent: #ff6b4a;       /* Coral - accent color */
    /* ... other colors */
}
```

### 7. Update OpenReview Link

Find the "Submit on OpenReview" button and update the `href`:

```html
<a href="https://openreview.net/group?id=ICML.cc/2026/Workshop/SCALE" class="submit-btn">
    Submit on OpenReview
</a>
```

## 🖼️ Image Guidelines

- **Speaker/Organizer Photos**: Square format, minimum 400x400px, JPG or PNG
- **Sponsor Logos**: Transparent PNG preferred, ~200px width
- **Optimize images** for web to keep page load times fast

## 📱 Responsive Design

The website is fully responsive and works on:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (< 768px)

## 🛠️ Technical Notes

- **No build step required** - pure HTML/CSS/JS
- **Google Fonts**: Outfit (headings) + JetBrains Mono (code/numbers)
- **No external dependencies** except fonts
- **Smooth scroll** and intersection observer animations
- **Mobile-friendly navigation** with hamburger menu

## 📄 License

Feel free to use and modify this template for your workshop!

---

**Need help?** Contact the organizers at scale2026@googlegroups.com

