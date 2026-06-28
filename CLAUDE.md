# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

GitHub Pages portfolio site for Артур Т. (GitHub: `surikatio`). Single-page static site — no build step, no framework. Deploy by pushing to GitHub and enabling Pages on the repo (or naming the repo `surikatio.github.io`).

The live URL will be: `https://surikatio.github.io`

## Structure

```
index.html      — the entire site (HTML + inline CSS + inline JS)
```

No external dependencies. All styles and scripts are inlined so the site works with zero build tooling.

## Owner info (for personalisation)

- Name: Артур Т.
- GitHub: surikatio
- Telegram: @Surikat_io
- Email: arturlev2004@gmail.com

## Projects featured

| Folder (in `../питон проекты/`) | What it is |
|---|---|
| `b2bsk` | Django B2B order-management web app (django-allauth, SQLite) |
| `emias_doc_checker` | Telegram bot that checks EMIAS for available doctor slots (Selenium) |
| `tg_sup_bot` | aiogram v3 customer-support Telegram bot (FSM, SQLite) |
| `MAGNIT_parser` | Magnit supermarket parser + recipe search (CSV/XLSX/SQLite output) |
| `parser_avito` | Avito listings parser (requests) |
| `kwork_sort_tg` | Kwork freelance-order monitor with Telegram notifications (Telethon) |

## Design direction

Modern/vibrant: purple-to-blue gradient, glassmorphism project cards, scroll-triggered reveal animations, CSS custom properties for the palette. No emoji in code unless user asks.
