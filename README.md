# Purser

A personal finance dashboard with a Star Trek LCARS-style interface, built for one user's own accounts. Working name; not final.

This is a hobby project. It is not a commercial product and has no other users. It is intended to read data only from the author's own financial accounts.

## What it does

- A compact desktop widget that expands into a full dashboard.
- Tracks four figures for a chosen period: Spend, Earn, Save, and Net (Earn + Save − Spend).
- Separates available cash, invested money, reserved money for upcoming bills, and free-to-spend money.
- Follows basic accounting rules: transfers, credit card payments and investment purchases are not counted as spending or income.
- Supports project views (for example a hobby budget or resale tracking) without counting any transaction twice.

## Status

- **Phase 1 (done):** interactive prototype using fictional demo data. See `prototype/purser-lcars.html`. It runs in any browser and uses no real financial data.
- **Phase 2 (planned):** a local backend with a SQLite database that reads the author's own account data through Plaid. Access tokens and API secrets stay on the author's machine and are never committed to this repository.
- **Phase 3 (planned):** a native macOS app.

## Privacy

This repository contains source code only. It contains no real financial data, account numbers, tokens or secrets. The demo data is fictional.
