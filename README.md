# Caleb Cramer - ML/AI Portfolio

A security-conscious machine learning portfolio showcasing projects in numerical analysis, online learning, and computer vision.

## Features

- **Privacy-First Design**: No personal information (email, location) exposed in HTML or code
- **Hidden from Search Engines**: `robots.txt` blocks indexing while allowing direct access
- **Clean Professional Look**: Built with Minimal Mistakes Jekyll theme
- **Contact Form**: Secure contact via Formspree (email never exposed)
- **Easy Updates**: Simple markdown files for projects and research

## Setup Instructions

### 1. Clone This Repository

```bash
git clone https://github.com/caleb-cramer/caleb-cramer.github.io
cd caleb-cramer.github.io
```

### 2. Set Up Formspree for Contact Form

The contact form uses [Formspree](https://formspree.io) to securely handle messages without exposing your email.

1. Go to [formspree.io](https://formspree.io)
2. Sign up (free)
3. Create a new form
4. Copy your form ID (looks like: `mxxxxx`)
5. Edit `_pages/contact.md` and replace `YOUR_FORM_ID` with your actual form ID

**Example:**
```
action="https://formspree.io/f/mxxxxx"
```

### 3. Update Profile Links

In the following files, replace placeholder links with your actual URLs:

**`_pages/about.md` and `_pages/contact.md`:**
- Replace `[Your LinkedIn profile]` with your actual LinkedIn URL
- Replace `caleb-cramer` with your GitHub username if different

### 4. Add Your Projects

Edit `_pages/portfolio.md` and fill in your 4-7 projects with:
- Project title
- Technologies used
- GitHub link
- Description (2-3 sentences)
- Key results/metrics

**Example format:**
```markdown
### Project Name: Neural Network Optimizer

**Technologies:** Python, PyTorch, NumPy  
**GitHub:** https://github.com/caleb-cramer/project-name  
**Duration:** 3 months, 2024

Description of what you built and the problem it solves.

**Key Results:**
- Achieved 95% accuracy on test set
- 2x speedup compared to baseline
```

### 5. Add Your Research Papers

Edit `_pages/research.md` and add your papers with:
- Paper title
- Publication date
- Link to PDF or arXiv
- Type (peer-reviewed, technical report, blog post)
- Brief abstract

### 6. Test Locally (Optional)

```bash
# Install Jekyll (requires Ruby)
gem install bundler jekyll

# Serve locally
bundle exec jekyll serve

# Visit http://localhost:4000
```

### 7. Deploy to GitHub Pages

The site deploys automatically when you push to GitHub.

```bash
git add .
git commit -m "Add portfolio content"
git push origin main
```

Visit: `https://caleb-cramer.github.io`

## Security Features

✅ **What's Protected:**
- Email address (hidden behind Formspree contact form)
- Physical location (not listed anywhere)
- Phone number (not included)
- Personal social media (only professional links shown)

✅ **What's Hidden:**
- Site is blocked from search engines via `robots.txt`
- Sensitive files ignored via `.gitignore`
- No cookies, tracking, or analytics

✅ **What's Public & Safe:**
- Your name and professional focus
- Project titles and GitHub links (already public anyway)
- Research paper titles and links
- Professional contact methods (LinkedIn, GitHub)

## Customization

### Change Theme Skin

Edit `_config.yml` and change the `minimal_mistakes_skin` option:

```yaml
minimal_mistakes_skin: "dark"  # Try: air, aqua, contrast, dark, default, dirt, neon, mint, plum, sunrise
```

### Add a Header Image

Place an image in `assets/images/header-bg.jpg` (or any image) and it will display on the homepage.

### Update Title & Description

Edit `_config.yml`:
```yaml
title: "Your Name"
description: "Your professional description"
```

## Directory Structure

```
.
├── _config.yml                 # Site configuration
├── _pages/                     # Page files
│   ├── about.md
│   ├── portfolio.md
│   ├── research.md
│   └── contact.md
├── assets/
│   └── images/                 # Project screenshots, header image
├── index.md                    # Homepage
├── robots.txt                  # Search engine blocking
├── .gitignore                  # Git security
└── README.md                   # This file
```

## Frequently Asked Questions

**Q: How do recruiters find my portfolio if search engines can't index it?**  
A: Share the direct URL in your resume, LinkedIn profile, email signature, etc. Recruiters who look at your application will have the direct link.

**Q: Is my email really safe?**  
A: Yes! The contact form uses Formspree, so your email is never exposed in the HTML source code or in your GitHub repository.

**Q: Can I add a blog?**  
A: Yes! Create files in `_posts/` with the format `YYYY-MM-DD-title.md` and they'll appear as blog posts.

**Q: How do I remove robots.txt to allow search indexing?**  
A: Delete the `robots.txt` file and push to GitHub. Your site will be indexed within weeks.

## Support

For issues with Jekyll or Minimal Mistakes, see:
- [Jekyll Documentation](https://jekyllrb.com/)
- [Minimal Mistakes Documentation](https://mmistakes.github.io/minimal-mistakes/)
- [Formspree Documentation](https://formspree.io/docs/)

## License

This portfolio template is yours to use and modify.

---

**Note:** Remember to update placeholder text before sharing your site!
