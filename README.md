# Creov Canvas portfolio

Static portfolio site, no build step.

## 1. Publish on GitHub Pages
1. Create a repository and upload everything in this folder (index.html, projects.json, images/).
2. Settings -> Pages -> Deploy from a branch -> `main` and `/ (root)`.
3. Your site appears at `https://<username>.github.io/<repository>/`.

## 2. Use the Admin page (password protected)
Open your site, scroll to the Contact page and click **Admin** at the bottom (or add `#admin` to the web address).

First time on each device:
1. Create a GitHub token: GitHub -> Settings -> Developer settings -> Personal access tokens -> Fine-grained tokens -> Generate. Choose only your portfolio repository and set **Contents: Read and write**.
2. In Admin enter `username/repository`, the branch (`main`), the token, and a new admin password (8+ characters).
3. The token is stored only in that browser, locked by your password. Next time you only type the password.

In Admin you can edit your name, About, skills, contact details, categories, theme and scroll speed, and add or delete projects (max 10 per category). Each save is committed to your repository; the live site updates about a minute later.

Visitors never see Admin controls. Nobody can change the site without your GitHub token, which GitHub enforces.

## Edit by hand instead
Edit `projects.json` on GitHub and put image files in `images/`.
Example project: `{ "category": "Branding", "image": "images/my-file.jpg" }`

## Navigation
Mouse wheel, swipe, arrow keys, or the dots on the right.
