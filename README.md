# Poultry Supply Store Management System

> **Client project** · Built by [Rahimi Tech Solution](https://github.com/rahimiabdulrahmanab) · The source code is private to the clients.

A complete management system for poultry supply businesses in Afghanistan. It is built as a **reusable product**: every client gets their own database, deployment and branding. It runs today for **Royani Poultry Supply Store**, **Hadi Poultry Services** and **Anas Hadi Poultry**.

## Features

- **Point of sale** with a barcode scanner and printed receipts
- **Inventory** of products and medicine
- **Dispatches to farms** and per-farm accounts
- **Suppliers**: general, medicine and chick (choza) suppliers, with payments and statements
- **Market sellers and commission** tracking for dealers and customers
- **Cash ledger and daily cash book** (Roznamcha), store cash, expenses and payments
- **Reports and dashboard**, plus data-health and reconciliation checks
- **WhatsApp messages** to customers straight from the app
- **User accounts** with secure, hashed-password logins
- **English and Pashto** interface

## Tech stack

| Layer | Tools |
|---|---|
| Frontend | React, Vite, React Router, Recharts |
| Backend | Supabase: PostgreSQL, RPC login functions, Row Level Security |
| Other | SheetJS (Excel export), barcode scanning |
| Hosting | Vercel (one deployment per client) |

---

Designed, built and deployed by **Abdul Rahman Rahimi**.
