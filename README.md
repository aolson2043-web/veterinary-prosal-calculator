# SalaryNspect Website


## v6.3 — Conversion upgrade

This release keeps all existing indexable URLs unchanged and adds:
- Apple Smart App Banner meta tag on every main page
- desktop-only QR handoff card on every main page
- veterinary QR routes to the veterinary App Store custom product page
- Other Careers QR routes to the main SalaryNspect App Store page
- post-calculation SalaryNspect CTA that appears only after the user presses Calculate
- standardized `app_store_click` analytics with `placement` values
- QR scans attributed as `app_store_click` with `placement=qr`
- a fix for the duplicated "SalaryNspect works beyond veterinary compensation" heading

New helper pages `app-vet.html` and `app.html` are marked `noindex,nofollow` and should NOT be added to the sitemap.

No existing page URL was moved or renamed. Manual re-indexing is not required for this conversion update.
