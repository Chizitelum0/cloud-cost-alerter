# Cloud Cost Alerter 🚨

A high-performance, multi-tenant B2B infrastructure SaaS designed to eliminate surprise cloud billing spikes. It monitors live spending metrics across multiple providers and alerts teams instantly when budgets are breached.

## 🚀 Tech Stack
- **Frontend:** React, Vite, Tailwind CSS
- **Backend:** Node.js, Express, Node-Cron
- **Database:** PostgreSQL
- **Integrations:** AWS Cost Explorer SDK, Supabase Management API

## 📂 Repository Structure
- `apps/frontend` - The customer-facing analytics and onboarding dashboard.
- `apps/backend` - The Express API server and background cron monitoring engines.

## 🔒 Security Note
Never commit raw environment variables or API keys. Ensure a local `.env` file is created inside `apps/backend/` and that it is fully ignored by Git.
