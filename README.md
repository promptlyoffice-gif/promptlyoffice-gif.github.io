
Promptly — Minimal Hugo site (PaperMod-like) for GitHub Pages
===========================================================

This archive contains a ready-to-edit Hugo site optimized for a bilingual blog (Ukrainian + English)
with a minimal PaperMod-like theme. It's prepared for deployment to GitHub Pages on the repository:
https://github.com/promptlyoffice-gif/promptlyoffice-gif.github.io

What is included
- config.toml (baseURL already set)
- content/uk and content/en with a home page and first blog post
- a lightweight theme "papermod-lite" under themes/ to make the site functional without external download
- Utterances comments integrated (configured to use the repo promptlyoffice-gif/promptlyoffice-gif.github.io)
- basic layouts and CSS so the site looks good out of the box

Quick deploy (upload to GitHub)
1. Create a repository named: promptlyoffice-gif.github.io under your GitHub account (promptlyoffice-gif).
2. Upload the contents of this archive to the repository (drag-and-drop in GitHub web UI or push via git).
3. (Optional) If you have Hugo locally, you can `hugo server` to preview. Otherwise, after pushing to GitHub:
   - Go to the repository Settings → Pages and enable GitHub Pages from the main branch (or use GitHub Actions).
4. Wait a few minutes and visit: https://promptlyoffice-gif.github.io/

Utterances comments
- The site includes Utterances configured to use the repository:
  promptlyoffice-gif/promptlyoffice-gif.github.io
- After publishing the site on GitHub Pages, enable Utterances for the repo:
  1) Go to https://utteranc.es/ and authorize with GitHub
  2) Choose the repository "promptlyoffice-gif/promptlyoffice-gif.github.io"
  3) Configure labels (e.g., "comment") and install.
- Comments will then appear on each post page.

Editing content
- Edit /content/uk/_index.md and /content/en/_index.md for home content.
- Add blog posts to /content/uk/blog/ and /content/en/blog/ as needed.

Enjoy your Promptly site!
