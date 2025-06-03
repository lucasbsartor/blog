# The Software Engineer Playbook

This repository contains the source for my personal knowledge base/blog, supporting both English (en-US) and Brazilian Portuguese (pt-BR) content.

## Directory Structure

- `/en-US/` — English articles and resources
- `/pt-BR/` — Portuguese articles and resources
- `/assets/` — CSS and static assets
- `index.md` — Main landing page (with language links)
- `_layouts/` — Jekyll HTML layouts
- `_config.yml` — Jekyll configuration
- `robots.txt` — Prevents search engine indexing

## How to Deploy on GitHub Pages

1. **Push to GitHub:**

   - Push this repository to GitHub as `software-engineer-playbook` under your account.

2. **Enable GitHub Pages:**

   - Go to your repository settings on GitHub.
   - Under "Pages", select the `main` branch and root (`/`) as the source.
   - Save. Your site will be available at `https://lucasbsartor.github.io/software-engineer-playbook`.

3. **Prevent Search Engine Indexing:**

   - `robots.txt` and meta tags are already set up to block indexing.

4. **Add New Content:**

   - Place English articles in `/en-US/` and Portuguese in `/pt-BR/` as Markdown files.
   - Use the provided layout and navigation structure for consistency.

5. **Update the Site:**
   - Commit and push changes. GitHub Pages will auto-build your site.

## Adding Articles

- Add new Markdown files to the appropriate language folder.
- Update navigation menus in each language as needed.
- Use the language switcher links for cross-language navigation.

## Minimal Dependencies

- No plugins or complex tooling required. Just Git, Markdown, and Jekyll (built-in to GitHub Pages).

---

For questions or improvements, open an issue or PR!
