# Pengyu Zha - Academic Homepage

Personal academic website for Pengyu Zha (查鹏宇), built with Jekyll and hosted on GitHub Pages.

## About

This is a minimal, clean academic personal webpage featuring:
- Personal introduction and bio
- Research interests
- Publications section (expandable)
- Contact information

## Website Information

- **Name**: Pengyu Zha (查鹏宇)
- **Institution**: Shenzhen University (深圳大学)
- **Position**: Undergraduate Student
- **Research Focus**: Image Generation, Face Editing, Computer Vision
- **Website**: https://zpyc1oud.github.io
- **GitHub**: https://github.com/zpyc1oud
- **Email**: zpyc1oud@outlook.com

## Local Development

### Prerequisites

- Ruby (version 2.7 or higher)
- Bundler
- Jekyll

### Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/zpyc1oud/zpyc1oud.github.io.git
cd zpyc1oud.github.io
```

2. **Install dependencies**
```bash
bundle install
```

3. **Run locally**
```bash
bundle exec jekyll serve
```

4. **View the site**
Open your browser and navigate to: `http://localhost:4000`

### Building for Production

To build the static site for deployment:
```bash
bundle exec jekyll build
```

The generated site will be in the `_site` directory.

## Deployment

This site is automatically deployed to GitHub Pages when you push to the `main` branch.

### First-time Setup on GitHub

1. Create a repository named `zpyc1oud.github.io`
2. Push your code to the repository
3. Go to repository Settings → Pages
4. Set Source to "Deploy from a branch"
5. Select branch: `main`, folder: `/ (root)`
6. Save and wait for deployment (usually takes 1-2 minutes)

Your site will be available at: https://zpyc1oud.github.io

## File Structure

```
.
├── _config.yml           # Jekyll configuration
├── _layouts/             # HTML layouts
│   └── default.html     # Main layout template
├── assets/              # Static assets
│   └── css/
│       └── style.css    # Main stylesheet
├── index.html           # Homepage
├── Gemfile              # Ruby dependencies
├── .gitignore           # Git ignore rules
├── robots.txt           # SEO robots file
└── README.md            # This file
```

## Adding Publications

When you have publications to add, edit `index.html` and uncomment the publication template in the Publications section. Use this format:

```html
<div class="publication-item">
  <div class="pub-title">Your Paper Title</div>
  <div class="pub-authors">Author1, Author2, <strong>Pengyu Zha</strong>, Author3</div>
  <div class="pub-venue">Conference/Journal Name, Year</div>
  <div class="pub-links">
    <a href="paper_url" target="_blank">[Paper]</a>
    <a href="code_url" target="_blank">[Code]</a>
    <a href="project_url" target="_blank">[Project Page]</a>
  </div>
</div>
```

## Customization

### Updating Personal Information

1. Edit `_config.yml` to update site metadata
2. Edit `index.html` to update content sections
3. Modify `assets/css/style.css` for styling changes

### Adding New Sections

To add new sections to the homepage:

1. Add a new section in `index.html`:
```html
<section id="new-section" class="section">
  <h2>New Section Title</h2>
  <!-- Your content here -->
</section>
```

2. Add navigation link in `_layouts/default.html`:
```html
<a href="#new-section">New Section</a>
```

## SEO Optimization

The site includes:
- Meta tags for search engines
- Open Graph tags for social media
- Structured data markup
- XML sitemap (auto-generated)
- robots.txt file
- Keywords: Pengyu Zha, 查鹏宇, Shenzhen University, 深圳大学, Image Generation, Face Editing

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

© 2024 Pengyu Zha. All rights reserved.

## Contact

For any questions or suggestions, please contact:
- Email: zpyc1oud@outlook.com
- GitHub: [@zpyc1oud](https://github.com/zpyc1oud)

---

Last Updated: November 2024

