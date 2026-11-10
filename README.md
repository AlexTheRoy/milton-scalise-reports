# Milton-Scalise Agency Reporting Site

Static client reporting site for Milton-Scalise Agency (GOAL account #779), deployed on Vercel.

## Structure

- `index.html`: hub with Campaign Reports and Website & Research sections
- Campaign Reports (11-10-26 edition, data through Nov 10, 2026):
  - `Milton-Scalise-Campaign-Overview-Last-3-Months-11-10-26.html`
  - `Milton-Scalise-Home-Campaign-Performance-Last-3-Months-11-10-26.html`
  - `Milton-Scalise-Monthly-Sales-by-Source-11-10-26.html`
  - `Milton-Scalise-Source-ZIP-Sales-11-10-26.html` and `Milton-Scalise-ZIP-Sales-11-10-26.csv`
  - `Milton-Scalise-Producer-Pipeline-11-10-26.html`
  - `Milton-Scalise-Inbound-Call-Review-11-10-26.html`
  - `Milton-Scalise-Lead-to-Sale-Gap-Analysis-11-10-26.html`
- Website & Research:
  - `Milton-Scalise-SEO-Audit-11-10-26.html`: audit of the agency's own website, miltonscaliseagency.com (measured Nov 10, 2026); replaces the Oct 12 audit of the carrier-hosted agent page
  - `Milton-Scalise-GA-Storm-Risk-10-12-26.html`, `Milton-Scalise-GA-Demographic-Research-10-12-26.html` and `Milton-Scalise-GA-ZIP-Data-10-12-26.csv`: Georgia research
- `vercel.json`: clean URLs, redirects from earlier file names (including `Milton-Scalise-SEO-Audit-10-12-26`) to the current ones, security headers, `noindex`

No build step. Push to `main` and Vercel redeploys.
