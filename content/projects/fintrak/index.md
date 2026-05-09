---
title: Fintrak
date: '2025-01-01'
summary: Personal expense tracker via Telegram bot — receipt OCR, auto-categorization, Google Sheets logging, and daily summaries.
tags:
  - n8n
  - Telegram
  - Google Sheets
  - OCR
  - Docker
external_link: 'https://github.com/rupal2k/fintrak'
image:
  caption: 'Fintrak — Telegram-driven expense tracking'
  focal_point: Smart
---

Fintrak is a personal expense tracking system driven by n8n automation workflows running in Docker. Send a receipt photo or text message to a Telegram bot; the system OCRs the image via OCR.Space, categorizes the expense using a rule-based engine, logs it to Google Sheets with a Drive receipt backup, and sends a daily 9 PM IST summary.

**Stack:** n8n · Telegram Bot API · OCR.Space · Google Sheets API · Google Drive API · Docker
