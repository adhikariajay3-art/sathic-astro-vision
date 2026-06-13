# SATHIC ASTRO VISION™ — Project Rules

This project is a Hindi-first static business system for astrology, vastu, remedies, digital products, memberships, workshops, CRM, orders, and revenue tracking.

## Permanent Rules

1. Keep UI Hindi/Hinglish-first and mobile-first.
2. Keep customer pages separate from admin tools.
3. Homepage must remain customer-facing, not admin-facing.
4. Do not claim full automation unless Razorpay/Gumroad/database/email delivery are actually connected.
5. Current payment flow is manual UPI + WhatsApp screenshot verification.
6. Every selling page should include UPI ID, WhatsApp number, clear price, and disclaimer.
7. Every admin tool should be simple, mobile-friendly, and usable without backend dependency.
8. Never expose private keys, API keys, Razorpay secrets, or database credentials in frontend code.
9. Before changing existing files, fetch current file content and update carefully.
10. After every feature, update navigation/dashboard links when useful.

## Business Details

- Brand: SATHIC ASTRO VISION™
- UPI ID: adhikari.ajay3-2@okicici
- WhatsApp: 9680446551
- Customer homepage: customer-dashboard.html
- Admin dashboard: admin-dashboard.html
- Admin login page: admin-login.html

## Product Stack

- 108 Jyotish Remedies PDF/product: ₹299
- Vastu Checklist: ₹499
- Premium Kundli Report: ₹2,100
- Vastu Consultation: ₹5,100
- Monthly Membership: ₹499/month
- Astrology Workshop: ₹999–₹2,999

## Verification Loop

For every meaningful update:

1. Plan the change.
2. Modify the smallest required file set.
3. Check that links still work.
4. Confirm mobile layout remains usable.
5. Keep customer flow simple: view → pay → WhatsApp screenshot → delivery.
6. Keep admin flow simple: lead → order → payment confirmation → delivery → upsell.

## Security Notes

This is a static Vercel/GitHub site. Static PIN pages are only basic deterrents, not real server security. Real admin security requires backend authentication, server-side sessions, and protected routes.

## Future External Integrations

These require external setup outside GitHub/Vercel static hosting:

- Razorpay/Gumroad payment gateway
- Automatic PDF delivery
- Google Sheet/Firebase/Supabase database
- Custom domain
- Server-side admin authentication
