# Enkhjin Gan-Erdene — Portfolio Site

A simple static site (HTML/CSS, no build step) — Home, About, Projects, and Contact pages.

## Files
```
index.html      Home page
about.html      Education, experience, skills, awards, hobbies
projects.html   Project showcase
contact.html    Contact details
style.css       Shared styling
assets/         Images (profile photo)
```

## Deploy with GitHub Pages (free hosting)

1. **Create a GitHub account** if you don't have one: https://github.com/join

2. **Create a new repository**
   - Go to https://github.com/new
   - Name it exactly `your-username.github.io` (replace `your-username` with your actual GitHub username) — this special name makes GitHub host it at the root of that URL automatically.
   - Set it to **Public**.
   - Don't add a README/gitignore (we already have files).
   - Click **Create repository**.

3. **Upload the files**

   **Option A — no command line (easiest):**
   - On the new repo page, click **"uploading an existing file"**.
   - Drag in `index.html`, `about.html`, `projects.html`, `contact.html`, `style.css`, and the whole `assets` folder.
   - Scroll down, click **Commit changes**.

   **Option B — using git:**
   ```bash
   cd cvsite
   git init
   git add .
   git commit -m "Initial portfolio site"
   git branch -M main
   git remote add origin https://github.com/your-username/your-username.github.io.git
   git push -u origin main
   ```

4. **Enable GitHub Pages**
   - In the repo, go to **Settings → Pages**.
   - Under "Build and deployment" → Source, select **Deploy from a branch**.
   - Branch: `main`, folder: `/ (root)`. Click **Save**.

5. **Visit your site**
   - After a minute or two, it will be live at:
     `https://your-username.github.io`

## Updating later
Edit any `.html` file, commit, and push (or re-upload via the web UI) — GitHub Pages redeploys automatically within a minute or so.

## Custom domain (optional)
If you own a domain, add a `CNAME` file with your domain name, and point your domain's DNS to GitHub Pages following: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
