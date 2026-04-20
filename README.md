# Rohan Yadav — Portfolio

## Deploy to GitHub Pages

1. **Create a repo** on GitHub named `your-username.github.io` (for your main site) or any name (for a project site).

2. **Push this file:**
   ```bash
   git init
   git add index.html
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to **Settings → Pages**
   - Under **Source**, select **Deploy from a branch**
   - Choose **main** branch and **/ (root)** folder
   - Click **Save**

4. Your site will be live at `https://YOUR-USERNAME.github.io/` (or `https://YOUR-USERNAME.github.io/YOUR-REPO/` for project sites) within a minute or two.

## Adding Project Videos

Replace any `ADD VIDEO` placeholder with a YouTube embed. Find this block in `index.html`:

```html
<svg class="play-icon" ...>...</svg>
<span class="hint">ADD VIDEO</span>
```

Replace it with:

```html
<iframe src="https://www.youtube.com/embed/YOUR_VIDEO_ID" allowfullscreen></iframe>
```

## Customising

- **GitHub link:** Search for `YOUR-USERNAME` in `index.html` and replace it with your actual GitHub username.
- **Colours:** Edit the CSS hex values at the top of the `<style>` block.
- **Add projects:** Copy any `project-card` block and update the content.
