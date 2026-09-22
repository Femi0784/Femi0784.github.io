# Femi Akerele — Cloud Database Administrator

Public resume site for GitHub Pages.

**Live URL (after publish):** https://femiakerele.github.io/

## Publish (one-time)

1. Create a **public** GitHub repo named exactly `femiakerele.github.io` under the GitHub user `femiakerele`  
   (user site Pages requires that repo name).
2. From this folder:

```bash
git init
git add index.html README.md .gitignore 404.html
git commit -m "Initial Cloud DBA resume site"
git branch -M main
git remote add origin https://github.com/femiakerele/femiakerele.github.io.git
git push -u origin main
```

3. In the repo on GitHub: **Settings → Pages → Build and deployment**  
   - Source: **Deploy from a branch**  
   - Branch: `main` / `/ (root)`  
   - Save

GitHub Pages usually goes live within a minute or two.

## Custom domain later (optional)

1. Buy `femiakerele.com` (or similar).
2. Add a `CNAME` file in this repo containing only:

```
femiakerele.com
```

3. At your DNS provider, point the domain at GitHub Pages (A/AAAA or CNAME per [GitHub’s docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site)).
4. In Pages settings, enter the custom domain and enable HTTPS.

## Edit

Edit `index.html` and push to `main`. Pages redeploys automatically.
