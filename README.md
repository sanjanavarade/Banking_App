# Horizon Banking 💼

A modern fintech **SaaS platform** built with Next.js that unifies multiple bank accounts, provides real-time transaction insights, and enables smooth fund transfers. This repo includes the complete source code powering the JavaScript Mastery tutorial.

---
## ⚙️ Tech Stack

- **Framework**: Next.js (React-based SSR)
- **Language**: TypeScript  
- **Backend Services**:
  - Appwrite (database & auth)
  - Plaid (bank account linking)
  - Dwolla (fund transfers)
- **UI & Validation**:
  - TailwindCSS (styles)
  - React Hook Form + Zod (form validation)
- **Charts**: Chart.js
- **Components**: shadcn/ui
- Monitoring: Sentry

---

## 🚀 Features

- **Secure Authentication** (SSR-based, with proper validations)  
- **Bank Account Integration** using Plaid API  
- **Overview Dashboard**: Consolidated balance, spending insights, charts  
- **Transaction History**: Filterable, paginated transaction logs  
- **Fund Transfers**: Send money via Dwolla integration  
- **Responsive Design**: Supports desktop to mobile views  
- **Live Sync**: Real-time updates across all user sessions  

---

## 🛠️ Quick Start

1. **Clone the project**
    ```bash
    git clone https://github.com/adrianhajdin/banking.git
    cd banking
    ```
2. **Install dependencies**
    ```bash
    npm install
    ```
3. **Setup environment variables**  
   Copy `.env.example` to `.env` and fill in your credentials:
    ```env
    NEXT_PUBLIC_SITE_URL=
    NEXT_PUBLIC_APPWRITE_ENDPOINT=https://cloud.appwrite.io/v1
    NEXT_PUBLIC_APPWRITE_PROJECT=
    APPWRITE_DATABASE_ID=
    APPWRITE_USER_COLLECTION_ID=
    APPWRITE_BANK_COLLECTION_ID=
    APPWRITE_TRANSACTION_COLLECTION_ID=
    APPWRITE_SECRET=
    PLAID_CLIENT_ID=
    PLAID_SECRET=
    PLAID_ENV=
    PLAID_PRODUCTS=
    PLAID_COUNTRY_CODES=
    DWOLLA_KEY=
    DWOLLA_SECRET=
    DWOLLA_BASE_URL=https://api-sandbox.dwolla.com
    DWOLLA_ENV=sandbox
    ```
4. **Run the app**
    ```bash
    npm run dev
    ```
5. Visit `http://localhost:3000` to interact with Horizon Banking.

---

## 📦 Available Scripts

- `npm run dev` – Start dev server  
- `npm run build` – Generate production build  
- `npm run start` – Start production server

---
