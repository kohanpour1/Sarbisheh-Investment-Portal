# Sarbisheh Investment Portal | درگاه سرمایه‌گذاری سربیشه

A bilingual (Persian/English), responsive static portal presenting investment opportunity concepts for Sarbisheh County, South Khorasan, Iran.

## Included
- Responsive RTL Persian / LTR English interface
- Search and sector filters for 23 preliminary opportunity concepts
- Agriculture, canola value chain, greenhouse town, drip irrigation equipment, aquaculture, ostrich production and processing, mining, solar energy, tourism and supporting services
- Investor interest form that opens a pre-filled email draft locally; it does not transmit data to a server
- All projects are labeled: «نیازمند امکان‌سنجی و برآورد مالی»

## Run locally
Open `index.html` in a browser, or serve the folder with any static web server.

## GitHub Pages
The workflow in `.github/workflows/pages.yml` publishes this static site to GitHub Pages on pushes to `main`. In the repository settings, ensure Pages uses **GitHub Actions** as the build/deployment source.

## Important limitations
This repository currently contains a static frontend only. It does **not** implement a secure admin panel, GapGPT investor discovery, a database, or server-side bulk email sending. Those features require a separately deployed backend and secure environment secrets. Never commit API keys, SMTP passwords, `.env` files, or other credentials to GitHub. Rotate any credentials that may have been exposed in source or chat history.

## Accuracy
Opportunity listings are preliminary concepts, not verified claims of available land, water rights, permits, reserves, investment returns or economic viability. Complete due diligence and official approvals are required before investment decisions.
