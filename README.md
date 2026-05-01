# Kevin Core® — Premium Software Marketplace

Static website for Kevin Core® — ready to deploy on Vercel or any static host.

## Deploy on Vercel

1. Push this folder to a GitHub repository
2. Go to [vercel.com](https://vercel.com) and click **Add New Project**
3. Import your GitHub repository
4. In the project settings:
   - **Framework Preset**: Other
   - **Root Directory**: `.` (leave as is)
   - **Build Command**: leave empty
   - **Output Directory**: `.` (leave as is)
5. Click **Deploy**

That's it — Vercel will detect `vercel.json` and handle SPA routing automatically.

## Files

```
kevin-core-site/
├── index.html        # Site entry point
├── assets/           # CSS, JS bundle, and logo image
├── opengraph.jpg     # Social preview image
├── vercel.json       # Vercel config (SPA rewrites + cache headers)
└── .gitignore
```
