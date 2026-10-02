# Legacy: World Cup 2026 Bracket Predictor (source only)

> **Status (2026-10-02):** This GitHub repo still contains the old single-file **World Cup 2026 bracket predictor** (`index.html`). It is **not** the live Perlan seats/bookings app.
>
> The linked Vercel project was **renamed** to **`perlan-bookings`** and production now serves **Perlan monthly bookings / seats** (title: “2026 · Perlan Bookings”). That production HTML was deployed separately (CLI) and is **not** this GitHub tree.
>
> **Repo rename** to something like `perlan-bookings-legacy-wc26` needs Ricky in GitHub Settings (no rename API available to agents).
>
> Related live apps:
> - Ops / monthly bookings UI: https://perlan-bookings.vercel.app (also still reachable at https://world-cup-2026-bracket-two.vercel.app)
> - Executive seats dashboard: https://perlan-seats-dashboard.vercel.app · repo `enrique-perlan/perlan-seats-dashboard`

---

## Original app (archived in this repo)

A single-file, zero-dependency web app for predicting FIFA World Cup 2026 (48 teams). Rank groups, pick best third-place teams, score knockouts, export poster + wall chart.

## Features (historical)

- Group stage, best 3rds, knockout bracket, bonus picks, canvas snapshots, light/dark theme.

## Run locally

Open `index.html` in a browser — no build step.

## Tech

Plain HTML/CSS/JS. Snapshots used Canvas 2D; gallery previously wrote to Supabase `wc26_*` tables / `wc26` storage (those DB tables were dropped 2026-10-02; storage bucket may still need manual empty/delete).
