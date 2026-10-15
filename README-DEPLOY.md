# Combined Vercel deployment
Upload the **contents** of this folder to the repository root, not the enclosing folder. Keep `index.html`, `assets/`, `data/`, `admin/`, `press-centre/`, and `gallery/` at the repository root.

Vercel: Framework Preset `Other`; Root Directory `.`; Build Command empty; Output Directory `.`; Production Branch `main`. Commit to GitHub and confirm the newest deployment is Ready. Add `babatundeogunlade.com` and optionally `www.babatundeogunlade.com` in Vercel → Project Settings → Domains. Apply the exact DNS values Vercel shows in GoDaddy; do not copy generic DNS values.

The CMS is at `/admin/`. It will not commit changes until a trusted OAuth service is configured in `admin/config.yml`. The public website and CMS are separate folders in the ZIP for easy identification, but are arranged together in this deployment folder so they can share one domain and repository.
