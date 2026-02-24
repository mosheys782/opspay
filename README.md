# OpsPay — Payment Operations Dashboard

A single-page payment management dashboard built with React, backed by SharePoint Online via Microsoft Graph API.

## Features
- 📅 Calendar view with clickable dates
- 💰 Multi-select bulk actions (paid, cleared, delete)
- 📊 Cash flow forecast
- 👥 Employee payroll (bi-weekly)
- ⟳ Recurring payment templates with start/end dates
- 💳 Credit card statement alerts
- 🔄 Auto-refresh every 60 seconds
- 🔒 MSAL authentication (Microsoft 365)

## Deployment
Hosted on Azure Static Web Apps. Auto-deploys from `main` branch.

## Setup
1. Deploy this repo to Azure Static Web Apps
2. Open `/setup.html` to create SharePoint lists
3. Open `/` to use the dashboard

## Tech Stack
- React 18 (via CDN + Babel standalone)
- MSAL.js 2.x for authentication
- Microsoft Graph API for SharePoint
- Azure Static Web Apps for hosting
