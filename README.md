# Tidy Ledger: storefront

A static storefront for the Tidy Ledger template line for cleaning businesses, hosted on GitHub Pages.

## Go live checklist

1. **Turn on Pages:** go to Settings → Pages → Build and deployment. Set Source to *Deploy from a branch*, then pick `main` and `/ (root)`.
2. **Create your checkout links.** Use Gumroad, Lemon Squeezy, Payhip or Stripe Payment Links. Upload the paid files there, not to this repo. Make one product per template, plus the bundle.
3. **Paste the links** into the `STORE` block near the bottom of `index.html` (`checkout.bundle`, `checkout.invoice` and so on). Set `contactEmail` too.
4. Commit. The site updates within a minute or two.

## Important

This repo is public. **Never commit the paid `.xlsx` and `.pdf` files here.** Anyone could download them for free. Only the free checklist in `/free` belongs in this repo.

## Prices

| Product | Price |
|---|---|
| Invoice and Quote Kit | $9 |
| Cleaning Pricing Calculator | $12 |
| Client and Job Manager | $17 |
| Bookkeeping and Profit Tracker | $19 |
| Cleaning Checklist Pack | $7 |
| Complete bundle | $39 |

To change a price, edit the `PRODUCTS` array and the bundle section in `index.html`.
