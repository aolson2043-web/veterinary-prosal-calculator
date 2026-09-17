# Veterinary ProSal Calculator — SalaryNspect

This folder contains a complete, static GitHub Pages site.

## What is included

- `index.html` — the entire website and calculator
- No server, database, framework, or build step required
- Calculator inputs stay in the visitor's browser
- Mobile responsive
- Search-engine metadata for veterinary ProSal / production-pay searches
- Optional negative-accrual carry-forward estimate
- SalaryNspect App Store call-to-action
- Google Analytics event hooks for:
  - `prosal_calculation`
  - `app_store_click`

## Before publishing

### 1. Veterinary Custom Product Page URL

The accepted Veterinary Custom Product Page URL is already installed in `index.html`:

`https://apps.apple.com/us/app/salarynspect/id6804337327?ppid=01a1049a-da74-4cf5-8b1e-59e2d75da25f`

### 2. Google Analytics 4

Google Analytics is already configured in `index.html`.

Measurement ID:

`G-GW2DQVL5QP`

The calculator sends these custom events:
- `prosal_calculation` when a visitor uses the calculator
- `app_store_click` when a visitor clicks through to the SalaryNspect veterinary custom product page

Standard GA4 page-view and referral tracking is also enabled.


## Publish on GitHub Pages

1. Create a new public GitHub repository named:
   `veterinary-prosal-calculator`
2. Upload `index.html`.
3. Open the repository's **Settings**.
4. Choose **Pages**.
5. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
6. Save.

Your expected page address will be:

`https://aolson2043-web.github.io/veterinary-prosal-calculator/`

## Important calculator note

The calculator is intentionally an educational estimate. Veterinary compensation agreements differ. The negative-accrual option uses a simplified carry-forward model and should not be represented as a universal ProSal formula.

## Veterinary App Store destination

The calculator currently points to the accepted Veterinary Custom Product Page:

`https://apps.apple.com/us/app/salarynspect/id6804337327?ppid=01a1049a-da74-4cf5-8b1e-59e2d75da25f`

