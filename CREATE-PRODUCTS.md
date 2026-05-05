# Seed real Shopify products for the Notify Me! demo

The homepage product grid uses **static cards** that link to these handles. Create matching products in **Shopify Admin → Products → Add product** so PDPs and app widgets work end-to-end.

| Handle | Title | Inventory state to demo |
|--------|--------|---------------------------|
| `shopify-s-best-back-in-stock-app` | Shopify's Best Back-in-Stock App | **Sold out** (0 inventory) |
| `shopify-s-best-preorder-app` | Shopify's Best Preorder App | **Preorder** / selling plan (per your app) |
| `shopify-s-best-wishlist-app` | Shopify's Best Wishlist App | **In stock** |
| `shopify-s-best-low-stock-alert-app` | Shopify's Best Low-Stock Alert App | **Low stock** (e.g. qty 2) |
| `notify-me-ai-for-restock-decisions` | Notify Me! AI for Restock Decisions | **Coming soon** / future preorder |
| `multi-language-widget-bundle` | Multi-Language Widget Bundle | **In stock** |

**Notes**

- Set price to **$0** or your preferred demo price; cards show `$0.00/mo` as label text from the theme.
- Handles must match **exactly** (hyphens, spelling).
- Optional pages to create for nav/footer links: `/pages/how-it-works`, `/pages/pricing`, `/pages/about`, `/pages/compare`.

After products exist, install **Notify Me!** and place app blocks/embeds on the **product** template so sold-out, preorder, and wishlist demos activate on the correct PDPs.
