---
layout: profile
posts_limit: 3
---

# PrimerPages Recommended Template (GitHub Actions Deploy)

Use this template when you want the full recommended plugin set and publish with **GitHub Actions**.

## Contributing

This template is maintained in `primerpages-dev`.

- Source repo: `PrimerPages/primerpages-dev`
- Please open issues and pull requests there, not in the generated template repository.

## What This Template Is For

- `theme: jekyll-theme-primerpages` in `_config.yml`
- Recommended extras enabled through the template config/plugin setup
- A starter site structure (`index`, `blog`, `tags`, `category`, docs, and sample posts)
- A Pages deployment workflow at `.github/workflows/site.yml`
- Pagefind site search enabled by default, with a shared search dialog

## Quick Setup

1. Create a new repository from this template.
2. Update `_config.yml`:
   - `title`
   - `description`
   - `repository` (set to `OWNER/REPO`)
3. Commit and push to your default branch (`main` by default).
4. In GitHub, go to `Settings -> Pages`.
5. Under `Build and deployment`, set:
   - `Source`: `GitHub Actions`
6. Let the workflow run and deploy the site.

## How Deploy Works

- On pushes to `main` (or manual dispatch), the workflow:
  - builds the site with Jekyll,
  - generates the Pagefind index in `_site/pagefind`,
  - uploads `_site` as a Pages artifact,
  - deploys with `actions/deploy-pages`.

## Verify It Works

- Visit `https://<owner>.github.io/<repo>/` for project pages.
- Confirm home, docs, blog, tag, and category pages render.
- Click the search button or press `/`, then search for text from a page or post.

## Reference

- PrimerPages Docs: [Search with Pagefind](https://www.primerpages.com/docs/)

- GitHub Docs: [Configuring a publishing source for your GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
