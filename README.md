# Decap CMS Admin — separate package
This folder contains the CMS administration page and its configuration.

## Authentication is required
The `admin/config.yml` contains `https://YOUR-OAUTH-SERVICE-DOMAIN` as an explicit placeholder. Replace it with a trusted, configured Decap-compatible GitHub OAuth service. A GitHub backend alone does not authenticate users. Never put tokens or service-role keys in browser code.

## Paths
Repository: `liberalreporters/babatundeogunladewebsite`; branch: `main`; content JSON under `data/`; uploads under `assets/images/cms/`; public URL: `https://babatundeogunlade.com`.

Copy `admin/index.html` and `admin/config.yml` to the root repository's `/admin/` directory. The public homepage remains `/index.html`.
