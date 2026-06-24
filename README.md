# Sathic Astro Vision

A front-end business platform for astrology and vastu consultation work.

## Start Here

- `index.html` — main homepage running SATHIC ASTRO VISION V2.2 protected dashboard
- `navigation.html` — central launch page for all dashboards and business tools
- `v2-67-ai-agents-dashboard.html` — alternate entry for the V2.2 67 AI agents dashboard

## V2.2 Features

- Admin PIN gate for dashboard access
- 67 AI agents with category, work, input, output, next automation, and status
- Lead capture form
- Local storage CRM
- WhatsApp booking and payment follow-up buttons
- Basic Kundli Report Generator draft tool
- Report copy function
- SEO meta tags
- Trust/disclaimer notice
- Shared files:
  - `assets/sathic-v2.css`
  - `assets/sathic-v2.js`

Default frontend PIN: `9680`

Note: This PIN is only a frontend access gate. For real security, add backend authentication with Firebase/Supabase/Auth0 or a custom server.

## Core App

- `index.html` — client management dashboard / V2.2 homepage
- `revenue-dashboard.html` — ₹1 crore revenue tracker
- `lead-tracking-crm.html` — lead tracking CRM
- `order-dashboard.html` — orders, payments and delivery tracking
- `whatsapp-funnel-manager.html` — Day 0 to Day 7 funnel messages
- `digital-product-store.html` — digital product store with UPI payment and WhatsApp order button
- `payment-confirmation.html` — payment confirmation message generator
- `ai-team-dashboard.html` — SATHIC AI agent team dashboard with 10 core agents, 7 Master Sutra steps, and Phase 2 future agents
- `terms-and-disclaimer.html` — terms, refund policy, privacy and astrology disclaimer
- `108-jyotish-remedies-sample.html` — sample product page
- `business-plan-1-year.md` — 1-year business roadmap

## Payment Setup

Current UPI ID:

`adhikari.ajay3-2@okicici`

WhatsApp for order/payment screenshot:

`9680446551`

Customer flow:

1. Open `digital-product-store.html`.
2. Select product or service.
3. Pay by UPI.
4. Click WhatsApp order button.
5. Send payment screenshot.
6. Add customer order in `order-dashboard.html`.
7. Deliver PDF, report, consultation slot, or membership manually.

## Products

- 108 Jyotish Remedies PDF — ₹299
- Vastu Checklist — ₹499
- Premium Kundli Report — ₹2,100
- Vastu Consultation — ₹5,100
- Monthly Membership — ₹499/month
- Astrology Workshop — ₹999–₹2,999

## Kickbacks AI / Codex Setup

Use this project with VS Code, Codex CLI, and Kickbacks AI.

### Steps

1. Create an account at Kickbacks AI.
2. Install the Kickbacks AI VS Code extension.
3. Sign in from VS Code.
4. Open this repository in VS Code.
5. Use Codex CLI inside VS Code to edit, improve, and ship features.
6. Check Kickbacks dashboard for earnings and activity tracking.
7. After earnings reach $10, add payout method from the Kickbacks account page.

### Recommended Codex Tasks for This Project

- Connect Firebase/Supabase for multi-device lead CRM.
- Connect WhatsApp Business API for scheduled booking reminders.
- Connect Razorpay payment links and webhooks.
- Add astrology API for D1, D9, Dashas, Gochar and Navtara.
- Add PDF report generation.
- Add real backend admin login.
- Add better Hindi copywriting for astrology/vastu products.
- Add SEO schema markup and Open Graph image.
- Prepare pages for Vercel deployment.

## Deploy instructions

### Deploy on Vercel

1. Go to Vercel and sign in.
2. Click **Add New Project**.
3. Import this GitHub repository.
4. Keep framework preset as **Other** or **Static**.
5. Keep deploy branch as `main`.
6. Click **Deploy**.
7. Vercel will provide a live URL.

## Important Notes

This is currently a front-end dashboard with local browser storage. For automatic payment confirmation, multi-device login, cloud database, OTP, admin security, and automatic PDF delivery, connect Razorpay/Gumroad plus Firebase/Supabase backend.
