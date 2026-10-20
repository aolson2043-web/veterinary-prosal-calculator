# Canonical indexing follow-up — 2026-10-20

Preferred page: https://www.salarynspect.com/prosal-guide.html
Old Google-selected URL: https://aolson2043-web.github.io/veterinary-prosal-calculator/prosal-guide.html

Verified in source ZIP: canonical tags on all pages already specify www.salarynspect.com; sitemap already lists the intended URL; no github.io links in site HTML. The old GitHub URL was observed by web fetch redirecting to the www SalaryNspect page; exact HTTP status could not be established.

This update: made in-site links to the ProSal page absolute HTTPS canonical URLs, added og:url to ProSal, and dated the updated ProSal sitemap entry. These are consistency improvements, NOT a guaranteed reversal of Google's canonical selection.

Next: confirm the OLD GitHub Pages repo URL returns HTTP 301/308 (not 302/307 or JavaScript). If it uses a temporary redirect, configure a permanent redirect at that old hosting origin; changes to this ZIP cannot configure the old repo's server. Ensure the live canonical URL returns HTTP 200 and is not blocked/noindexed. In Search Console inspect https://www.salarynspect.com/prosal-guide.html, Test Live URL, request indexing, and resubmit sitemap.xml. Google may take time to reprocess signals.

Deployment note: existing README warns a past site branch could differ from latest GitHub main; compare changes before overwriting newer site files.
