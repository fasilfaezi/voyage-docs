# Voyage docs

Source for the Voyage Shopify theme documentation site at [voyage.mintlify.app](https://voyage.mintlify.app).

## Local preview

```bash
npm install -g mintlify
mintlify dev
```

Opens at `http://localhost:3000`.

## Structure

- `docs.json` — site config (name, colors, logo, sidebar navigation)
- `getting-started/` — onboarding pages
- `theme-setup/` — logo, colors, typography, layout, theme styles
- `templates/` — every template explained
- `sections-reference/` — every section, every block, every setting
- `interactive-features/` — cart drawer, quick view, search, page transitions, etc.
- `customization/` — recipes for common merchant tasks
- `reference/` — exhaustive tables (settings, templates, schemas, CSS tokens, JS API)
- `troubleshooting/` — common issues, FAQ, performance, i18n, support
- `logo/` — theme wordmark assets used in the docs header
- `images/` — screenshots and diagrams

## Deployment

This repo is connected to [Mintlify](https://mintlify.com) via their GitHub App. Pushes to `main` trigger an automatic rebuild and deploy.

## Contributing

Documentation lives in MDX (Markdown with embedded JSX). Each page starts with a frontmatter block:

```mdx
---
title: "Page Title"
description: "One-line summary."
---
```

Edit the relevant `.mdx` file, preview locally with `mintlify dev`, commit, push.
