# OnePlum Games static website

Simple static landing page for GitHub Pages.

## Files

- `index.html`
- `styles.css`
- `assets/favicon.svg`

## GitHub Pages setup

1. Create a new GitHub repository, for example `oneplumgames-site`.
2. Upload these files to the repository root.
3. Go to repository Settings -> Pages.
4. Under "Build and deployment", choose:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: /root
5. Save.

## Custom domain

In GitHub Pages settings, set custom domain:

`oneplumgames.com`

GitHub will create a `CNAME` file automatically, or you can manually add a file named `CNAME` containing:

`oneplumgames.com`

## Namecheap DNS

Use these records:

A @ 185.199.108.153
A @ 185.199.109.153
A @ 185.199.110.153
A @ 185.199.111.153
CNAME www YOUR_GITHUB_USERNAME.github.io

Replace `YOUR_GITHUB_USERNAME` with your actual GitHub username.

Then enable "Enforce HTTPS" in GitHub Pages after DNS propagates.
