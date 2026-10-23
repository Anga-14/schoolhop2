# SchoolHop Foundation Campaign Website

Responsive campaign prototype for SchoolHop Foundation, a nonprofit focused on rural learner transport in South Africa's Eastern Cape.

## Live site

Live GitHub Pages site: <https://anga-14.github.io/schoolhop2/>

GitHub repository: <https://github.com/Anga-14/schoolhop2>

Changes pushed to `main` trigger the repository's GitHub Actions Pages workflow.

## Run locally

Open `index.html` in a modern browser. React, React DOM, React Router, and the optional EmailJS client are loaded from public CDNs, so an internet connection is needed for the React campaign hub and router. There is no build step or local server requirement for the prototype.

## Features

- Responsive landing page with React Router hash-based navigation.
- Interactive hero A/B test and campaign hub.
- Validated contact and sponsorship forms.
- Newsletter opt-in form and welcome/promotional email previews.
- Campaign dashboard with editable illustrative rates, funnel calculations, KPIs, and recommendations.
- Local browser storage for prototype enquiries, applications, subscriptions, click events, experiment counts, and individual reflection drafts.
- Marketing strategy content: audience profile/persona, funnel, SEO plan, search-ad proposal and budget assumptions, social calendar and five post drafts.

## Data and privacy

This is a front-end prototype, not a production application or shared CRM. Data is stored in the current browser's `localStorage`, is not transmitted to SchoolHop, and can be removed by clearing browser storage. Do not enter real personal, learner, donor, or sensitive data. Production use requires an approved secure backend/API, privacy review, access controls, retention rules, and verified consent.

Email delivery is not configured by default. To test EmailJS, configure the service ID, public key, and template IDs in the inline `emailjsConfig` object. Do not publish private credentials in a public repository; use a backend for secrets.

## Campaign data

Dashboard rates and social engagement examples are illustrative assumptions, not actual campaign results. The paid-search budget is a planning scenario (R6,000 over four weeks, with an assumed R15 CPC) and must be validated and approved before use. No advertising or email campaign is represented as having run.

## Test checklist

1. Navigate with the top menu and verify browser back/forward on hash routes.
2. Submit valid and invalid contact and sponsorship forms; confirm messages and local dashboard counts.
3. Submit a newsletter signup with consent and verify duplicate email feedback.
4. Change dashboard rates and confirm funnel counts/recommendation update.
5. Test narrow mobile viewport, keyboard-only navigation, and storage-disabled/error cases.
6. Before release, retest the complete flow on the deployed HTTPS URL and verify analytics/CRM integration.

## Deployment status

The static site is live via GitHub Pages from `main`. Forms still use browser-local storage; there is no production API/CRM, and email delivery is not configured. Do not use this prototype to collect real personal, learner, donor, or sensitive data.
