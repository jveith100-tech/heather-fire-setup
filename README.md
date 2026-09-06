# Heather Fire - Tablet Setup

GitHub Pages site for field tablet deployment support during the Heather Fire incident.

## Live Site

https://jveith100-tech.github.io/heather-fire-setup/

## Pages

| File | Purpose |
|------|----------|
| index.html | Main setup guide with step-by-step instructions for field tablets |
| qr.html | QR code page - scan to open the setup site on any device |

## Auto-Deploy

This repository uses a GitHub Actions workflow (.github/workflows/deploy.yml) that automatically deploys to GitHub Pages on every push to main.

Triggers:
- push to main
- workflow_dispatch (manual trigger)
- repository_dispatch (external API trigger)

## GitHub Pages Configuration

- Source: Deploy from main branch, root directory (/)
- URL: https://jveith100-tech.github.io/heather-fire-setup/

## Usage

Technicians can scan the QR code at qr.html or navigate directly to the live URL to access tablet setup instructions in the field.
