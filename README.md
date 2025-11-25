# Personality & Career Discovery

A comprehensive static website featuring personality assessment resources, astrological insights, and career guidance services. Built with HTML, CSS, and JavaScript for easy deployment on GitHub Pages.

## 🌟 Features

- **Home Page**: Curated collection of free personality and career assessments
  - Big Five (OCEAN) Tests
  - DISC Personality Assessments
  - Strengths-Based Tests (HIGH5)
  - Enneagram Tests
  - Academic Personality Inventories

- **My Analysis Page**: Personal INFJ personality analysis and Aquarius/Scorpio astrological insights
  - Detailed INFJ personality breakdown
  - Career fit analysis
  - Zodiac sign influences and synergies

- **Services Page**: Professional career coaching and guidance services
  - Resume reviews
  - Personal branding
  - Networking preparation
  - Interview coaching
  - Course development
  - Podcast collaboration

- **Astrology Page**: Free birth chart resources and interpretation guides
  - Astro.com integration
  - Café Astrology resources
  - Birth chart element explanations
  - Career astrology insights

## 📁 File Structure

```
.
├── index.html              # Home page with personality tests
├── projects.html           # Personal analysis and career fit
├── about.html              # Services and coaching information
├── astrology.html          # Birth chart resources
├── assets/
│   ├── css/
│   │   └── styles.css      # Main stylesheet
│   ├── js/
│   │   └── main.js         # Navigation and interactions
│   └── images/             # Image assets
├── LICENSE                 # MIT License
└── README.md              # This file
```

## 🚀 Deployment to GitHub Pages

### Option 1: Direct Upload

1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings → Pages
4. Select the `main` branch as the source
5. Your site will be published at `https://[username].github.io/[repository-name]`

### Option 2: Git Command Line

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/[username]/[repository-name].git
git push -u origin main
```

Then enable GitHub Pages in repository settings.

## 🛠️ Local Development

### Using Python

```bash
# Python 3
python -m http.server 5000

# Python 2
python -m SimpleHTTPServer 5000
```

### Using Node.js

```bash
# Install http-server globally
npm install -g http-server

# Run server
http-server -p 5000
```

Then visit `http://localhost:5000` in your browser.

## ✨ Customization

### Update Contact Information

Replace `contact@example.com` in all HTML files with your actual email address.

### Modify Colors

Edit the CSS variables in `assets/css/styles.css`:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #ec4899;
    /* ... */
}
```

### Add Your Own Content

- Update the personal analysis in `projects.html`
- Modify service offerings in `about.html`
- Customize assessment recommendations in `index.html`

## 📱 Responsive Design

The website is fully responsive and optimized for:
- Desktop (1200px+)
- Tablet (768px - 1199px)
- Mobile (< 768px)

## 🔗 External Resources

The site links to various free personality assessment tools:
- [Plum Profile](https://www.plum.io/personality-test)
- [123test Big Five](https://www.123test.com/personality-test/)
- [HIGH5 Strengths](https://high5test.com/)
- [Astro.com Birth Charts](https://www.astro.com)
- [Café Astrology](https://cafeastrology.com)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Support

For personalized career guidance and coaching services, visit:
- **Topmate**: [https://topmate.io/gurmol_singh](https://topmate.io/gurmol_singh)

## 🎨 Credits

- Design & Development: Custom static website
- Assessment Resources: Links to reputable psychology and astrology platforms
- Icons: Unicode emoji characters

---

Built with 💜 for career discovery and personal growth
