# PPEGC Documentation Site

This repository contains the documentation and governance materials for the **Platform for Exceptional Genomic Cancer Cases (PPEGC)**.

🌐 **Live Site:** [https://ppegc.github.io/ppegc-docs](https://ppegc.github.io/ppegc-docs/

---

## 📄 Pages

### Core Documentation
- **[index.md](index.md)** — Homepage with platform overview, statistics, and quick links
- **[ABOUT.md](ABOUT.md)** — Mission, history, team, values, and impact
- **[GOVERNANCE.md](GOVERNANCE.md)** — Complete governance framework, organizational structure, and processes
- **[FAQ.md](FAQ.md)** — Frequently asked questions for contributors, patients, and researchers

### Legal and Compliance
- **[PRIVACY.md](PRIVACY.md)** — Privacy Policy (GDPR-compliant)
- **[TERMS.md](TERMS.md)** — Terms of Submission with clickwrap agreement
- **[PATIENT-INFO-EN.md](PATIENT-INFO-EN.md)** — Patient information notice (English)
- **[PATIENT-INFO-FR.md](PATIENT-INFO-FR.md)** — Notice d'information patient (Français)

### Configuration
- **[_config.yml](_config.yml)** — Jekyll/GitHub Pages configuration

---

## 🚀 Quick Start

This site is powered by **GitHub Pages** and uses the Jekyll static site generator.

### Viewing Locally

1. Install Ruby and Jekyll:
   ```bash
   gem install bundler jekyll
   ```

2. Clone this repository:
   ```bash
   git clone https://github.com/[username]/ppegc-docs.git
   cd ppegc-docs
   ```

3. Install dependencies:
   ```bash
   bundle install
   ```

4. Serve locally:
   ```bash
   bundle exec jekyll serve
   ```

5. Open http://localhost:4000 in your browser

### Editing Content

All content is in **Markdown** format (`.md` files). To update:

1. Edit the relevant `.md` file
2. Commit and push to the `main` branch
3. GitHub Pages will automatically rebuild and deploy (takes 1-2 minutes)

---

## 📝 Content Guidelines

### Markdown Basics

```markdown
# Heading 1
## Heading 2
### Heading 3

**bold text**
*italic text*

- Bullet list item
- Another item

1. Numbered list
2. Second item

[Link text](URL)

> Blockquote
```

### Internal Links

Link to other pages using relative paths:
```markdown
[Read our Governance](GOVERNANCE.md)
[Privacy Policy](PRIVACY.md)
```

### Front Matter (Optional)

Add metadata to any page:
```yaml
---
title: Custom Page Title
layout: default
---
```

---

## 🎨 Customization

### Theme

Current theme: **minima** (default)

To change theme, edit `_config.yml`:
```yaml
theme: cayman  # or minimal, architect, slate, etc.
```

Available GitHub Pages themes: https://pages.github.com/themes/

### Custom CSS

Create `assets/css/style.scss`:
```scss
---
---

@import "{{ site.theme }}";

/* Your custom CSS here */
body {
  font-family: 'Arial', sans-serif;
}
```

### Logo

Place your logo in `/assets/images/ppegc-logo.png` and it will automatically appear (configured in `_config.yml`).

---

## 📊 Analytics

Google Analytics can be enabled by adding your tracking ID to `_config.yml`:

```yaml
google_analytics: G-XXXXXXXXXX
```

---

## 🔧 Maintenance

### Regular Updates Required

- **Statistics** (index.md) — Update quarterly
- **Team members** (ABOUT.md, GOVERNANCE.md) — Update when changes occur
- **FAQ** — Add new Q&As as questions arise
- **Revision history** (GOVERNANCE.md) — Update when governance changes

### Version Control

All changes are tracked by Git. To view history of a file:
```bash
git log GOVERNANCE.md
```

To revert to a previous version:
```bash
git checkout [commit-hash] GOVERNANCE.md
```

---

## 🤝 Contributing

If you'd like to contribute improvements:

1. Fork this repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit (`git commit -m "Description of changes"`)
5. Push to your fork
6. Open a Pull Request

---

## 📞 Support

**Technical issues with the site:**  
Open an issue in this repository or contact support@ppegc.org

**Content questions:**  
Contact contact@ppegc.org

---

## 📜 License

**Content License:** Creative Commons Attribution 4.0 (CC BY 4.0)  
**Code License:** MIT License

See [LICENSE.txt](LICENSE.txt) for details.

---

## 🔗 External Links

- **REDCap Submission Form:** [Link to your REDCap instance]
- **Main PPEGC Website:** https://ppegc.org *(if different from this docs site)*
- **Gustave Roussy:** https://www.gustaveroussy.fr

---

*Last updated: February 15, 2026*
