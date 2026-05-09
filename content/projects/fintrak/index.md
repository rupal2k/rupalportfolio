---
title: Fintrak
date: '2025-01-01'
summary: Zero-cost, self-hosted expense engine — snap a receipt in Telegram, get it OCR'd, categorized, and logged to Google Sheets automatically.
tags:
  - n8n
  - Telegram
  - Google Sheets
  - OCR
  - Docker
links:
  - type: site
    url: 'https://github.com/rupal2k/fintrak'
image:
  caption: 'Fintrak — zero-cost expense engine'
  focal_point: Smart
---

Fintrak is a personal expense tracking engine with a ₹0/month operational cost. Four n8n automation pipelines running in Docker handle the full workflow: send a receipt photo to a Telegram bot → OCR.Space extracts the text → a 12-category rule engine categorizes it → the expense logs to Google Sheets with a Google Drive receipt backup. A 9 PM IST cron sends a daily summary back to Telegram.

**Architecture:** Telegram Bot (UI) · n8n on Docker (Engine) · OCR.Space API (Extraction) · Google Sheets (Database) · Google Drive (Storage)

**Key design principles:** Frictionless UI (the interface lives where you already chat) · Zero monthly cost (free-tier APIs only) · Sovereign data (nothing touches a third-party server)

**Stack:** n8n · Docker · Telegram Bot API · OCR.Space · Google Sheets API · Google Drive API · JavaScript
