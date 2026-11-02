# Portfolio site (static, GitHub Pages)

## Files
- `index.html`: the whole site (HTML + CSS, no build step, no external requests)
- `assets/Sudipta_Chowdhury_CV.pdf`: put your resume here (name must match)
- `assets/thesis.pdf`: put your thesis report here

## Deploy on GitHub Pages
1. Create a repo. For a user site, name it `<username>.github.io`; any other name also works.
2. Add `index.html` and the `assets/` folder to the root of the repo and push.
3. Repo Settings > Pages > Build and deployment > Deploy from a branch > `main` / `(root)`.
4. Custom domain: in Settings > Pages enter your domain and tick "Enforce HTTPS".
   At your DNS provider:
   - Apex domain (example.com): four `A` records to
     185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `www`: a `CNAME` record pointing to `<username>.github.io`
5. GitHub creates a `CNAME` file in the repo for you. DNS and HTTPS can take up to a day.

## Before publishing, check
- GitHub and LinkedIn links in `index.html` (search for `SudiptaAChy` and `sudipta-chy`).
- Optional: add `<link rel="canonical" href="https://yourdomain.com/">` in `<head>`.
- Add your Google Scholar / ORCID link in the sidebar once you have one.
