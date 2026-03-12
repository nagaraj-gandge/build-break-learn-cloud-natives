
# Jekyll Portfolio with Topics (GitHub Pages Ready)

A modern portfolio template that also includes a **Topics** section with pre-created directories (Kubernetes, Dev-ops, ML-ops-Tools, AI-Tools, AI-Infrastructure, Data-AI, Virtualization, Cloud, Network, Storage, Compute). Each topic has an `index.md` starter page.

## Features
- Portfolio (custom `projects` collection)
- Topics index page with links
- Prebuilt topic folders
- Responsive, clean UI
- SEO via `jekyll-seo-tag`

## Getting Started
1. Install Bundler: `gem install bundler`
2. Install dependencies: `bundle install`
3. Run locally:
   ```bash
   bundle exec jekyll serve
   ```
4. Visit `http://127.0.0.1:4000`

## Add Your Content
- **Projects**: Add Markdown files to `/_projects/` with front matter:
  ```yaml
  ---
  title: My Project
  description: One-line summary.
  ---
  ```
- **Topics**: Add more pages under any topic directory, e.g. `/Kubernetes/architecture.md`.

## Deploy
Push to GitHub and enable **Settings → Pages**. Select `Deploy from a branch` and choose `main`.
