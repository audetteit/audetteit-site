# Audette IT Landing Page

A professional, enterprise-style landing page for Audette IT, featuring a dark technical theme, service overview, and placeholders for status pages and employee portals.

## Project Structure

```
/audette-it
  /assets        # Images and resources
  index.html     # Main landing page
  style.css      # Custom styles (Dark theme, responsive)
  README.md      # This file
```

## deployment Instructions (GitHub Pages)

1. **Initialize Git Repository**:
   Open a terminal in the `audette-it` folder and run:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```

2. **Push to GitHub**:
   - Create a new repository on GitHub (e.g., `audette-it-site`).
   - Link your local repo:
     ```bash
     git remote add origin https://github.com/YOUR_USERNAME/audette-it-site.git
     git branch -M main
     git push -u origin main
     ```

3. **Enable GitHub Pages**:
   - Go to your repository **Settings** > **Pages**.
   - Under **Build and deployment**, select **Source** as `Deploy from a branch`.
   - Select `main` branch and `/ (root)` folder.
   - Click **Save**.

Your site will be live at `https://YOUR_USERNAME.github.io/audette-it-site/`.

## Customization

- **Status Page**: Look for `<!-- Replace the content of this div with your status page embed -->` in `index.html` to add your OneUptime or other status dashboard.
- **Employee Portal**: Update the link in the `#portal` section in `index.html` to point to your internal login page.
