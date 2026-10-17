# DailyFit static support pages

Static support pages for the public `prxem-stack/privacy` GitHub Pages repository, in its `dailyfit/` subdirectory. Public routes:

- https://prxem-stack.github.io/privacy/dailyfit/
- https://prxem-stack.github.io/privacy/dailyfit/privacy.html
- https://prxem-stack.github.io/privacy/dailyfit/deletion.html

Publish this directory in the repository’s `dailyfit/` folder. Preserve existing repository-root files and other product policies. GitHub Pages serves the repository’s publishing branch. Keep the report service separate when updating this public site.

These are buildless HTML/CSS/SVG pages with relative internal navigation. No JavaScript, external fonts, analytics, account system, contact form, report-submission form, runtime secrets, backend or admin code are included. The support address is the existing public developer contact, `premharsh.official@gmail.com`. No phone number is published.

`privacy.html` preserves the existing DailyFit policy paragraphs and adds a website-hosting section. Public pages use GitHub Pages, whose security logs include visitor IP addresses. The separate optional in-app report backend remains on OpenAI Sites/Cloudflare, with its existing consent, private review, receipt deletion and retention behavior. The deletion page reflects the current app actions. Do not move report API/admin routes or server secrets into this public repository.

The empty `.nojekyll` file is harmless in this folder. If the repository owner wants to disable Jekyll for the whole Pages source, that marker belongs at the publishing-source root; do not overwrite an existing root configuration solely for this subfolder.

Local validation checks HTML structure, local links and fragments, referenced assets, preserved source-policy paragraphs, and absence of scripts/forms/backend or secret files. Verify deployed routes and mobile browser rendering after changes; static checks alone do not establish deployment success.

Hosting references checked 17 October 2026:
- https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages#data-collection
- https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement
