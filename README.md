# Thaiproex: Tally-Inspired ERP Accounting System

Thaiproex is a modern, full-stack ERP accounting system inspired by Tally. The goal is to deliver keyboard-driven entry, master-centric architecture, robust double-entry accounting, and multi-dimension (company, branch, cost center, investor, currency) support, all on the web.

## Key Features & Principles
- **Masters & Vouchers:**
  - Ledger, Company, Group, Item, Branch, Cost Center, Currency, Investor, etc. managed as master records
  - Transactions as Vouchers: Double-entry Payment, Receipt, Journal, etc. with voucher configuration
- **Multi-Dimensional:**
  - Every record dimensioned by company, branch, cost center; supports cross-company and branch operations
- **Investor/Partner Capital Tracking**
- **Cost Centers**
- **Multi-Currency**
- **Modern, Keyboard-Friendly UI:**
  - Navigation and entry optimized for keyboard, styled with a modern component library

## Tech Stack
- Backend: Node.js, Express, TypeScript, MongoDB
- Frontend: React, TypeScript, Chakra UI or Material UI
- API-first, JWT for user/account security

## Project Structure

```
thaiproex/
├── backend/
│   ├── src/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── controllers/
│   │   ├── utils/
│   ���   └── app.ts
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── contexts/
│   │   ├── utils/
│   │   └── App.tsx
│   └── package.json
├── README.md
└── .env.example
```

## Next Steps
1. Build Master Schemas (Ledger, Company, Branch, Cost Center, etc.)
2. Build Voucher schemas for double entry
3. Standard REST API for CRUD and voucher entry
4. Frontend: Keyboard-friendly forms, masters, voucher entry screens
5. Reporting, investor capital, cost center/currency modules

_This system is in early development. Feedback, suggestions, and contributions are welcome!_