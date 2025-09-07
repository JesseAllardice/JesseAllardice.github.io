# Jesse Allardice - Personal Website

This repository contains the source code for Jesse Allardice's personal academic website, built with Jekyll and hosted on GitHub Pages at [jesseallardice.github.io](https://jesseallardice.github.io).

## 🎯 Site Overview

Professional academic website showcasing:
- **About**: Detailed biography covering Physics PhD at Cambridge, Apple AI Residency, and current ML research
- **Publications**: Research papers including FlexTok (ICML 2025) and BETR methodology
- **Experience**: Career timeline from Cambridge PhD to Apple ML Researcher
- **News**: Recent achievements and professional updates

## 🚀 Deployment Instructions

### Option 1: Automatic GitHub Pages Deployment (Recommended)

1. **Enable GitHub Pages:**
   - Go to your repository settings on GitHub
   - Navigate to "Pages" section
   - Source: Deploy from a branch
   - Branch: `master` or `main`
   - Folder: `/ (root)`

2. **Your site will be automatically available at:**
   ```
   https://jesseallardice.github.io
   ```

3. **GitHub Actions will automatically build and deploy when you push changes to the master branch**

### Option 2: Manual Local Development

If you want to test locally before deploying:

```bash
# Install Ruby and Bundler first
# Then install dependencies (this may require network access)
bundle install

# Serve locally
bundle exec jekyll serve

# Visit http://localhost:4000
```

## 📁 Site Structure

```
├── _config.yml           # Jekyll configuration
├── _layouts/             # Custom page layouts
├── _includes/            # Reusable components
├── _sass/                # SCSS stylesheets
├── assets/css/           # Compiled CSS
├── .github/workflows/    # GitHub Actions for deployment
├── img/                  # Social media icons and images
├── index.md              # Homepage
├── about.md              # About page
├── publications.md       # Publications page
├── experience.md         # Experience page
├── news.md              # News and updates
└── Gemfile              # Ruby dependencies
```

## 🎨 Design Features

The site features a clean, academic design:

- **Responsive design** that works on all devices
- **Professional typography** with excellent readability
- **Social media integration** (Twitter, LinkedIn, GitHub, Google Scholar)
- **SEO optimized** with proper meta tags
- **Fast loading** with optimized assets

## 🔧 Customization

### Updating Content
- Edit the markdown files (`.md`) to update page content
- Modify `_config.yml` for site-wide settings
- Add new posts to the `news.md` file

### Styling
- Main stylesheet: `assets/css/style.scss`
- Color scheme and fonts can be customized in the CSS variables section

### Social Links
Update social media handles in `_config.yml`:
```yaml
twitter_username: jesse_allardice
linkedin_username: jesse-allardice-phd-1374b5110
github_username: JesseAllardice
scholar_id: k97jb6gAAAAJ
```

## 📊 SEO & Analytics

The site includes:
- **Jekyll SEO Tag** for optimal search engine indexing
- **Open Graph** meta tags for social media sharing
- **Twitter Card** support
- **Structured data** for Google Scholar integration

## 🔄 Updating the Site

1. Edit content files locally or directly on GitHub
2. Commit and push changes to the master branch
3. GitHub Actions will automatically rebuild and deploy
4. Changes appear at jesseallardice.github.io within minutes

## 🎯 Key Features

- ✅ Mobile-responsive design
- ✅ Fast loading and SEO optimized  
- ✅ Professional academic styling
- ✅ Social media integration
- ✅ Google Scholar integration
- ✅ Recent news and updates section
- ✅ Clean typography and navigation
- ✅ Automatic deployment via GitHub Actions

---

**Built with Jekyll • Hosted on GitHub Pages • Designed for Academic Excellence**