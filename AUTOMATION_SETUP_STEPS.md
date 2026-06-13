# SATHIC ASTRO VISION™ — External Automation Setup Steps

This file explains what must be done outside GitHub/Vercel to move from manual selling to real automation.

## Phase 1 — Gumroad Auto PDF Delivery

1. Create a Gumroad account.
2. Create product: 108 Jyotish Remedies PDF, price ₹299.
3. Upload the PDF/file.
4. Create product: Vastu Checklist, price ₹499.
5. Upload the PDF/file.
6. Copy both Gumroad product links.
7. Replace website UPI buttons with Gumroad buy links.

Result: Customer pays and PDF is delivered automatically by Gumroad.

## Phase 2 — Razorpay Payment Links

1. Create Razorpay account.
2. Complete KYC.
3. Create payment links:
   - ₹299 remedies
   - ₹499 vastu checklist
   - ₹2,100 premium kundli report
   - ₹5,100 vastu consultation
   - ₹499 membership
   - ₹999 workshop
4. Add these links to website buttons.

Result: Payment collection becomes professional and trackable.

## Phase 3 — Cloud CRM / Orders

Options:

- Google Sheet + Apps Script
- Firebase
- Supabase

Required tables/fields:

### Leads
- name
- phone
- source
- interest
- status
- follow_up_date
- notes

### Orders
- customer_name
- phone
- product
- amount
- payment_status
- delivery_status
- screenshot_reference
- notes

Result: CRM and order data are not lost when phone/browser changes.

## Phase 4 — Real Admin Security

Static PIN is only a basic deterrent. Real security needs:

- backend login
- server-side session
- protected admin route
- database permissions

Suggested options:

- Firebase Auth
- Supabase Auth
- Vercel serverless functions

## Phase 5 — Custom Domain

1. Buy domain such as sathicastrovision.com.
2. Add domain inside Vercel project settings.
3. Update DNS records as Vercel shows.
4. Make custom domain primary.

## Important Rule

Do not claim full automation until payment gateway, auto-delivery, database, and real authentication are connected.

Current system is complete for manual selling. External automation needs the above accounts and links.
