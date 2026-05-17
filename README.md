# Developer VPS Notes

This folder is a GitHub Pages-ready Jekyll site containing five RackNerd affiliate articles.

## Publish to GitHub Pages

1. Create a new GitHub repository.
   - Recommended name: `developer-vps-notes`
   - If you want the site at `https://YOUR_USERNAME.github.io/`, name the repo `YOUR_USERNAME.github.io`.

2. Upload all files in this folder to the repository.

3. In GitHub, go to:
   - `Settings`
   - `Pages`
   - `Build and deployment`
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
   - Save

4. Wait a few minutes. GitHub will show your Pages URL.

5. Update `_config.yml` after you know the URL:

   ```yaml
   url: "https://YOUR_USERNAME.github.io"
   baseurl: "/developer-vps-notes"
   ```

   If your repository is named `YOUR_USERNAME.github.io`, use:

   ```yaml
   url: "https://YOUR_USERNAME.github.io"
   baseurl: ""
   ```

6. Commit the `_config.yml` change.

## Article URLs

After GitHub Pages finishes building, your posts should look like:

- `/vps/web-hosting/linux/2026/05/16/racknerd-vps-review.html`
- `/vps/cloud-hosting/2026/05/16/racknerd-vs-digitalocean.html`
- `/vps/developers/linux/2026/05/16/best-cheap-vps-hosting-for-developers.html`
- `/wordpress/vps/web-hosting/2026/05/16/best-vps-for-wordpress-beginners.html`
- `/linux/vps/hosting/2026/05/16/cheap-linux-vps-deals.html`

## Medium Workflow

Publish each article on GitHub Pages first, then copy the article into Medium.

In Medium story settings:

- Add the same title and subtitle.
- Add the suggested tags from the original Medium draft files.
- Set the canonical URL to the matching GitHub Pages article URL.

This makes GitHub Pages your primary content asset hub and Medium your distribution channel.

## GEO Tracking

Record each published URL in your GEO/content asset tracker:

- Title
- GitHub Pages URL
- Medium URL
- Main keyword
- Publication date
- Affiliate link
- AI test questions
- Whether AI mentions RackNerd
- Whether AI mentions your article

