# My Debt Overview ♡

A cute one-page board for tracking my loans, payments, weekly savings and daily spending.

## Deploy
Static site — no build step. Vercel: **Add New → Project → import this repo → Deploy** (Framework preset: *Other*).

## Where data lives
- Starting loans and schedule are in `index.html` (`<script id="app-state">`).
- Everything I add on the site (payments, purchases, check-ins, savings jar) is saved in my browser's localStorage only.
- Use **✿ settings → download backup file** to keep a copy or move to another device.
