# Visa Restaurant Static — HCMC 1000-Day Anniversary Dining Guide

A self-contained, bilingual (English / Vietnamese) static page for choosing a
Ho Chi Minh City restaurant from Visa's 2026 Premium Dining program — built
around a 1000-day anniversary dinner.

## Contents

- `index.html` — the full interactive guide (no build step, no dependencies).
  - Featured shortlist (steakhouse-led picks + scenic "wow" options)
  - All 31 HCMC restaurants as filterable cards (by cuisine or private rooms)
  - Click any card for a detail view: concept, signature dishes, private-room
    info, price detail, anniversary services, awards, contacts, and reference links
  - **EN / VI language toggle** (top-right) — translates the UI chrome and all
    restaurant content
  - Copy-to-clipboard booking request templates (per restaurant + Visa concierge)
- `HCMC_Visa_Dining_Restaurants.xlsx` — the same data as a sortable spreadsheet
  (two tabs: Anniversary Picks + all 31 restaurants).

## Usage

Open `index.html` in any modern browser. Everything is inlined, so it works
offline. Reference links and the copy buttons require a browser (not a preview
sandbox).

## Data & sources

Prices were researched (11 Jul 2026) from restaurant sites, Michelin, Tatler,
PasGo, and TripAdvisor — they are **not** published in the Visa guide. Confirmed
prices are marked ✓; others are estimates. Always reconfirm price and
private-room availability when booking.

Bookings for the Visa privilege go through the Visa concierge:
**(84-28) 3824 0515 · visadining@aspirelifestyles.com** (Visa Signature /
Infinite / Business; program 1 Jul – 30 Sep 2026).

## Deploy

It's a single static file — host `index.html` anywhere (GitHub Pages, Netlify,
etc.). For GitHub Pages, enable Pages on the `main` branch root.
