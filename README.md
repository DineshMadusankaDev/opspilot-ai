# OpsPilot AI — Business Operations Intelligence

**Less Manual Work. Smarter Decisions.**

OpsPilot AI is a polished, interactive front-end prototype that demonstrates how an operations team could review orders, understand vendor performance, explore business insights, and preview automation workflows in one workspace.

## Demo features

- Operations overview with KPI cards and order/revenue chart
- Priority order table with status and risk indicators
- Vendor fulfilment performance
- Interactive operations assistant with predefined sample-data responses
- Automation workflow toggles (demo state only)
- Downloadable operations report and orders CSV
- Responsive layout for desktop and mobile

## Important prototype disclosure

This demo uses fictional sample data and predefined response logic. It is **not connected to a live store, live database, external AI model, email provider, or SMS service**. The assistant is an interactive prototype, not a live LLM integration. Workflow toggles only change the local demo UI and do not trigger external actions. KPI totals are illustrative; the table contains a small sample of orders.

A production implementation would require discovery of the target platform, access-controlled APIs, authentication/authorization, server-side validation, audit logging, error handling, testing, and explicit integration of an approved AI provider and notification services.

## Run locally

Open `index.html` in a modern browser. The chart uses Chart.js via CDN and fonts use Google Fonts, so those visual dependencies require an internet connection. The core UI and demo logic are bundled in the HTML file.

## Publish with GitHub Pages

1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the `main` branch and `/(root)`, then Save.
4. Wait for the Pages deployment to complete. GitHub will show the published site URL in Settings → Pages.

For the official steps, see [GitHub Pages Quickstart](https://docs.github.com/en/pages/quickstart).

## Built with

HTML · CSS · JavaScript · Chart.js · Sample data

Created as an independent concept demo by Dinesh Madhusankha.
