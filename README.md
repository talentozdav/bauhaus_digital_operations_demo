# Bauhaus Digital Operations Demo

A free, standalone browser prototype for demonstrating paperless workforce attendance, worker records, project sites, daily site reports, dashboard summaries and CSV/JSON exports.

## Run locally
Open `index.html` in a modern browser. No build step, package installation, API key, server, or paid service is required.

## Features
- Fictional seeded workers, project sites, attendance records and daily site reports
- Add/edit worker, site, attendance and report records
- Check-in/check-out and automatic duration calculations
- Search and filter attendance and reports
- Mark site reports as reviewed
- Export attendance, workers, sites and reports to CSV
- Download a JSON backup and reset sample data
- Responsive layout for desktop and mobile
- Browser localStorage persistence

## Important limitations
- All seeded data is fictional and does not represent Bauhaus records.
- Data is stored only in the current browser profile. It is not synchronized between users or devices.
- This prototype has no real login, role-based permissions, server database, audit trail, GPS verification, identity verification, payroll, backups service, or ERP integration.
- Do not enter real personal, employee, financial, or project-confidential information.
- For production use, replace local storage with a secure backend, implement authentication/authorization, audit logging, server-side time validation, backup/retention policies, security review and applicable Nigerian data-protection controls.

## Deploy to Netlify (free tier)
1. Upload the folder to a GitHub repository, or drag the folder into Netlify's manual deploy interface if available in your account.
2. For GitHub deployment, create a new Netlify site from the repository. Publish directory is the repository root (`.`). No build command is needed.
3. Test on desktop and mobile. Keep the site labelled DEMO and do not collect real company data.
4. Free-tier availability and limits may change; confirm current terms before sharing externally.
