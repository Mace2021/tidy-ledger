# Tidy Ledger: storefront

The public storefront for Tidy Ledger, a set of templates and a tablet app for cleaning businesses. It's hosted on GitHub Pages.

## How selling works

1. A buyer clicks **Buy now**, which opens a **Stripe Payment Link**.
2. After paying, Stripe sends them to their product's **private download page**. That page lives on a separate, unlisted delivery site, not in this repo.
3. Stripe emails the receipt.

## Connecting Stripe

1. In Stripe, open Product catalog and create one product per item. Use the prices in the table below.
2. Create a **Payment Link** for each product. Under **After payment**, choose *Don't show confirmation page* and enter that product's private download URL.
3. Paste each `https://buy.stripe.com/...` link into the `STORE.checkout` block near the bottom of `index.html`.
4. Commit. The site updates within a minute or two.

## Important

This repo is public. **Never commit the paid files, the delivery site or its private URL here.** Only the free checklist in `/free` belongs in this repo.

## Prices

| Product | Price |
|---|---|
| Invoice and Quote Kit | $9 |
| Cleaning Pricing Calculator | $12 |
| Client and Job Manager | $17 |
| Bookkeeping and Profit Tracker | $19 |
| Cleaning Checklist Pack | $7 |
| Tablet Field App | $19 |
| Complete kit (all of the above) | $49 |
