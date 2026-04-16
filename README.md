# Motion Portfolio

A sleek single-page portfolio site for motion graphics work.

## Files

- `index.html` — site structure and copy
- `styles.css` — visuals, layout, and responsive styling
- `.github/workflows/deploy.yml` — GitHub Pages deployment workflow

## Current video embeds

These are already wired in:
- `https://youtu.be/Bf5BUrQCoKk`
- `https://youtu.be/Gdk9dRHo3ME`

## Quick edits

### 1. Update contact info
Replace:
- `jack@example.com`

with your real email address in both places.

### 2. Update project details
Edit these sections:
- `Project One Title`
- `Project Two Title`
- the project descriptions
- the bullet points under each project

### 3. Optional polish
You can also tweak:
- hero headline
- about section copy
- "Based In" stat
- available-for list

## Run locally
Open `index.html` directly in a browser, or serve the folder with any static server.

Example:

```bash
cd motion-portfolio
python3 -m http.server 8000
```

Then visit:

```text
http://127.0.0.1:8000
```

## Deploy to GitHub Pages

1. Create a new GitHub repo
2. Push this folder to that repo
3. In GitHub, go to:
   - **Settings → Pages**
4. Ensure **GitHub Actions** is the source for Pages deployment
5. Push to `main` or `master`
6. GitHub will publish the site automatically

Your public URL will look like:

```text
https://YOUR_GITHUB_USERNAME.github.io/REPO_NAME/
```
