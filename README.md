# Naija Social — prototype

A mobile-friendly, single-page front-end prototype for a Nigerian social platform.

## Preview locally
Open `index.html` in a browser. No build step or package install is required.

## Included in this prototype
- Responsive home feed and sample posts
- Create posts in this browser
- Like and repost counters
- Search posts
- Explore, demo profile editing, and verification preview
- Local browser storage for demo posts/profile

## Important limitations
This is **not yet a production social network**. Data is stored in the visitor's browser only; other users cannot see it. There is no authentication, shared database, moderation pipeline, secure media upload, payment processing, verification, advertising, or creator payout system. The ₦1,000/month verification figure is an illustrative placeholder only; payments are not enabled.

## Suggested next build phase
1. Add authentication and account recovery.
2. Connect a hosted database and API (for example Supabase).
3. Add server-side validation, rate limits, reporting, blocking, and moderation tools.
4. Add secure image uploads.
5. Integrate a Nigerian payment provider for subscriptions only after backend verification and webhook testing.
6. Build auditable creator-earnings rules and payout/KYC workflows before enabling earnings.
7. Add privacy policy, terms, community guidelines, and data deletion/export.

Do not collect real money or promise creator payouts from this prototype.
