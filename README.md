# Fiverse Help Center — Mintlify

Ready-to-deploy Mintlify project. 10 MDX articles, full `docs.json` navigation config.

## Deploy in 5 minutes

### 1. Push to GitHub
```bash
git init
git add .
git commit -m "feat: initial help center content"
git remote add origin https://github.com/YOUR_ORG/fiverse-helpcenter.git
git push -u origin main
```

### 2. Connect on Mintlify
1. Go to [dashboard.mintlify.com](https://dashboard.mintlify.com)
2. Click **New Project** → **Import from GitHub**
3. Select `fiverse-helpcenter`
4. Set your custom domain (e.g. `help.fiverse.io`) under **Settings → Domain**
5. Click **Deploy** — live in ~60 seconds.

## File structure
```
fiverse-helpcenter/
├── docs.json                        ← navigation, branding, colors
├── help/
│   ├── linking-accounts.mdx         Article 1a
│   ├── first-sync.mdx               Article 1b
│   ├── smart-budgets.mdx            Article 2a
│   ├── spending-trends.mdx          Article 2b
│   ├── subscription-manager.mdx     Article 2c
│   ├── setting-goals.mdx            Article 3a
│   ├── ai-suggestions.mdx           Article 3b
│   ├── automated-savings.mdx        Article 3c
│   ├── ai-insights.mdx              Article 4a
│   └── total-balance.mdx            Article 4b
└── logo/                            ← add fiverse-light.svg + fiverse-dark.svg
```

## Add your logo
Drop `fiverse-light.svg` and `fiverse-dark.svg` into the `/logo/` folder.
Update the paths in `docs.json` if needed.
