# Sathic Astro Vision

A front-end business platform for astrology and vastu consultation work.

## Core App

- `index.html` — client management dashboard
- `revenue-dashboard.html` — ₹1 crore revenue tracker
- `lead-tracking-crm.html` — lead tracking CRM
- `whatsapp-funnel-manager.html` — Day 0 to Day 7 funnel messages
- `digital-product-store.html` — digital product store with UPI payment instructions
- `payment-confirmation.html` — payment confirmation message generator
- `terms-and-disclaimer.html` — terms, refund policy, privacy and astrology disclaimer
- `business-plan-1-year.md` — 1-year business roadmap

## Payment Setup

Current UPI ID added in store and confirmation page:

`adhikari.ajay3-2@okicici`

Customer flow:

1. Open digital product store.
2. Select product or service.
3. Pay by UPI.
4. Copy order details.
5. Send payment screenshot and order details on WhatsApp/DM.
6. Deliver PDF, report, consultation slot, or membership manually.

## Products

- 108 Jyotish Remedies PDF — ₹299
- Vastu Checklist — ₹499
- Premium Kundli Report — ₹2,100
- Vastu Consultation — ₹5,100
- Monthly Membership — ₹499/month
- Astrology Workshop — ₹999–₹2,999

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

This is a front-end manual payment and delivery setup. Data is stored in browser local storage. For automatic payment confirmation, multi-device login, cloud database, OTP, admin security, and automatic PDF delivery, connect Razorpay/Gumroad plus Firebase/Supabase backend.