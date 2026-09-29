Pay Calc

A quick, mobile-friendly calculator for Kenyan take-home pay. Enter basic salary, allowances and overtime hours; it works out PAYE, NSSF, SHIF, Housing Levy, pension and HELB.

It is a single index.html file with no build step and no server. Nothing you type leaves your phone; your last entries are saved in your own browser.

Put it online with GitHub Pages
Create a new public repository (e.g. pay-calc).
Click Add file → Upload files, drop in index.html (and this README), then Commit changes.
Go to Settings → Pages. Under Build and deployment, set Source to Deploy from a branch, choose main and / (root), then Save.
After a minute or two your link appears at the top of that page: https://<your-username>.github.io/pay-calc/
Updating it

Edit index.html in GitHub (pencil icon) or upload a new version. The live site updates within a couple of minutes.

Where the rates live

All statutory rates are in one block near the top of the <script>, marked // ---------- Rates ----------. When KRA or NSSF change something (e.g. new PAYE bands), update the numbers there.

Item	Current value
PAYE bands	10% to 24,000; 25% to 32,333; 30% to 500,000; 32.5% to 800,000; 35% above
Personal relief	KES 2,400 / month
NSSF	6%, Tier I to 9,000, Tier II to 108,000 (Feb 2026)
SHIF	2.75% of gross, minimum KES 300
Housing Levy	1.5% of gross
Pension + NSSF tax-deductible cap	KES 30,000 / month
Hourly rate	basic ÷ (26 days × 8 hours)
Pension (default)	6% of basic; users can change it or set 0

Estimates only. The official payslip is final.
