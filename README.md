# Perlan Bookings (ops dashboard)

Single-file ops UI for **Perlan monthly bookings / seats** (title: “2026 · Perlan Bookings”).

> Repo path is still `enrique-perlan/world-cup-2026-bracket` — **rename in GitHub Settings** when convenient (no rename API for agents). Vercel project is already **`perlan-bookings`**.

## Live

- https://perlan-bookings.vercel.app
- https://world-cup-2026-bracket-two.vercel.app (legacy alias — keep until bookmarks updated)

## Sister app

Executive seats dashboard (static JSON): https://perlan-seats-dashboard.vercel.app · `enrique-perlan/perlan-seats-dashboard`

## Data

Reads `public.bookings_months` from Supabase project `ykxbcwokteambpxpbrxu`. Canonical finance sheet: [Monthly statistic Bókun tickets sold and income](https://docs.google.com/spreadsheets/d/1ZNHAo7-agV57aDGt2K5khK6jDlY7UOwKtme5chEvMvE).

## Files

- `index.html` — main dashboard
- `upload.html` — add/publish a month (passcode gated)

## Run locally

Open `index.html` in a browser (needs network for Chart.js CDN + Supabase).
