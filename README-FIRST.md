# BABS Website — Start Here

This ZIP has three clearly separated folders:

1. `public-website/` — premium public-facing site.
2. `decap-cms-admin/` — Decap CMS interface and config.
3. `combined-deployment/` — recommended upload folder, with the public site at the root and CMS at `/admin/` so both work in one Vercel project and domain.

For the simplest deployment, upload the **contents** of `combined-deployment/` into the root of `liberalreporters/babatundeogunladewebsite` on the `main` branch. Vercel should build as a static site with Framework Preset Other, no build command, output directory `.`. Then add the custom domain in Vercel and follow the exact DNS instructions there in GoDaddy.

Important: Decap CMS needs a configured trusted GitHub OAuth service. The config has a visible placeholder `YOUR-OAUTH-SERVICE-DOMAIN`; publishing will not work until it is configured. Do not expose GitHub tokens in client-side files. All starter data feeds are empty so no unverified sample news is published. Biography and priority copy must be fact-checked and approved before publication.
