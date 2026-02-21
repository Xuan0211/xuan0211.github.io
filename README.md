# Academic Personal Website

A clean, simple, and professional academic website template hosted on GitHub Pages.

## Quick Start

### 1. Create a GitHub Repository

```bash
# Navigate to the website directory
cd /Users/xuan/.openclaw/workspace/academic-website

# Initialize git repository
git init

# Create a new repository on GitHub (do this in browser at github.com)
# Repository name: yourusername.github.io

# Add remote and push
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git add .
git commit -m "Initial commit - academic website"
git push -u origin main
```

### 2. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Source", select **Deploy from a branch**
4. Choose branch: **main**, folder: **/** (root)
5. Click **Save**

Your site will be live at: `https://yourusername.github.io`

### 3. Customize Your Website

Edit `index.html` to add your information:

- **Header**: Update your name, title, and affiliation
- **About**: Add your bio and profile photo (save as `profile.jpg` in the same folder)
- **Research**: List your research interests
- **Publications**: Add your papers with links
- **Contact**: Update your email and office information

### 4. Add a Profile Photo

1. Save your photo as `profile.jpg` in the `academic-website` folder
2. The photo will automatically appear in the About section
3. Recommended size: 300x400 pixels

## File Structure

```
academic-website/
├── index.html          # Main website file
├── profile.jpg         # Your profile photo (optional)
└── README.md          # This file
```

## Customization Tips

### Colors
Change the color scheme by editing the CSS variables at the top of `index.html`:

```css
:root {
    --primary-color: #2c3e50;    /* Dark blue */
    --accent-color: #3498db;     /* Light blue */
    --text-color: #333;
    --bg-color: #fff;
    --section-bg: #f8f9fa;
}
```

### Adding More Sections
Copy an existing section and modify it. Common additions:
- Teaching
- Awards & Honors
- Presentations
- Blog

### Updating Content
Simply edit `index.html`, commit, and push. GitHub Pages will automatically update your site within 1-2 minutes.

## Advanced: Custom Domain

1. Buy a domain (e.g., from Namecheap, Google Domains)
2. In GitHub repo: Settings → Pages → Custom domain
3. Enter your domain and save
4. Configure DNS records with your domain provider

## Support

For GitHub Pages documentation: https://pages.github.com/

---

**Template created for Yuan Xu** | February 2026
