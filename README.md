# Project n8n — Personal Automation

A personal, self-hosted automation project (single user, not a public service).

## What it does

Project n8n runs on the owner's home server using [n8n](https://n8n.io). It connects to the owner's own Gmail account and watches for auction invoice emails. When one arrives, the invoice PDF is read and its details — auction house, invoice number, lot numbers, prices, and totals — are filed into the owner's personal purchase tracker, and a notification is sent to the owner's phone.

A second small workflow sends the owner a weekly summary of his home server's health (disk space, running services, tracker totals).

## Who uses it

Only the owner. The app is not distributed, has no sign-up, and collects no data from anyone else.

## Privacy

See [PRIVACY.md](PRIVACY.md) for how the app handles the owner's Google data.
