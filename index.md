# Lumen — Theme Documentation

> Lumen theme documentation (v1.0.0, commits 9ae3c39 + 637b9ed).

## What Lumen is

Lumen is a Shopify theme built for selling digital products: video courses,
ebooks, templates, and other downloads. There is no shipping story anywhere in
the theme — no shipping estimators, no returns language, no weight or delivery
windows. Buyers get instant delivery after checkout.

## Presets

Lumen ships with two presets. They share every section and feature; they differ
in brand, color, and typography.

- **Lumen** — dark, cinematic academy look for video courses. Ink navy
  backgrounds, amber calls to action, Fraunces headings with Inter body text.
- **Quill** — light, editorial shop look for ebooks and templates. Paper-white
  backgrounds, deep green accents, Newsreader headings with Inter body text.

Choose a preset when you add the theme, or switch later in
**Online Store → Themes → Customize → Theme settings**.

## Setting up your store

1. Add Lumen to your store and publish it.
2. Pick the preset that matches what you sell (courses → Lumen, ebooks and
   templates → Quill).
3. Add your products. Use **variants for license tiers** (for example Personal,
   Team, Enterprise) — the product page renders them as license pills, and the
   license-tier table links directly to each variant.
4. For delivery, use Shopify's Digital Downloads app or your delivery app of
   choice. The theme's product page explains to buyers that the download link
   appears on the confirmation page and is also emailed.
5. Fill the home page sections (below) with your own content. Do not ship with
   placeholder text — the theme's demo content is an example, not a default.

## Home page sections

- **Hero with trailer** — headline, subheading, cover image, and an optional
  YouTube/Vimeo trailer that opens in a modal. Set the trailer button label; if
  no trailer is set, the secondary button is used instead.
- **Curriculum accordion** — modules and lessons for a course. Each row expands
  to show its lessons.
- **Sample preview** — blurred preview pages or lesson samples. Buyers can peek
  inside before they pay without getting the paid content.
- **License tiers** — a comparison table across your license variants (seats,
  client-work use, team dashboard, support, updates). Each column links to its
  variant.
- **Bundle & upsell** — a bundle offer with savings computed from compare-at
  prices.
- **Sticky buy bar** — stays visible while the buyer scrolls the product page.
- **Creator bio** — your portrait, role, and story.
- **Student outcomes** — results and testimonials.
- **Inside look** — a gallery of what buyers actually get.
- **Digital FAQ** — questions and answers. Edit the questions to match your
  product; the defaults cover devices, refunds, and delivery.
- **Custom Liquid** — for anything else, add your own Liquid/HTML.

## Product page features

- **License picker** — variant pills with per-license pricing. Prices update
  when the buyer switches licenses.
- **Selling plans** — if you offer subscriptions or installment-style purchase
  options, they appear as purchase options next to the one-time price.
- **Shop Pay Installments messaging** — appears automatically under the buy
  button when the buyer's cart qualifies.
- **Unit pricing** — shown automatically when a variant carries unit-price data.
- **Pickup availability** — shown when a variant is stocked at a location with
  pickup enabled.
- **Related products** — "You may also like", powered by Shopify's product
  recommendations.
- **Complementary products** — "Pairs well with", from the products you
  configure in the Search & Discovery app.
- **Dynamic checkout** — accelerated checkout buttons, toggleable per product
  in the Buy buttons block.

## Search, collections, and cart

- **Predictive search** — the header search suggests products as the buyer
  types; submitting goes to the full search page.
- **Filters and sorting** — collection and search pages offer faceted filters
  (availability, price range, vendor, type, tags) and sorting, with active
  filters shown as removable pills.
- **Newsletter** — the footer form subscribes buyers to your mailing list.
- **Discounts** — line-level and cart-level discounts are shown in the cart,
  with the discount name and amount.
- **Accounts** — the header uses Shopify's account component, so buyers sign
  in, follow the shop, and reach their library and downloads.
- **Country and language selectors** — appear in the footer when your store
  offers more than one market or language.
- **Gift cards** — a dedicated gift-card template is included.

## Theme settings

Under **Theme settings** you control colors (background, surface, foreground,
accent, success), typography (heading and body fonts), button corner radius,
and input corner radius. The two presets are saved combinations of these
settings — changing them after choosing a preset customizes that preset.

## Frequently asked questions

**Do my buyers need an app to receive downloads?**
No app is required from the buyer. You, the merchant, choose a delivery method
(Digital Downloads or another delivery app); the theme only presents the
download messaging consistently.

**Can I sell physical products with Lumen?**
Technically yes, but the theme is designed for digital goods and deliberately
omits shipping language. A mixed catalog will feel inconsistent.

**How do refunds work?**
Refunds are your store policy, not the theme's. The demo's "14-day money-back
guarantee" line is example copy — replace it with your actual policy in the
footer and product-page settings.

**Which payment methods are shown?**
The footer shows icons for the payment methods you have enabled in
**Settings → Payments**.

## Support

- Documentation: this page (https://chungsubeen0.github.io/lumen-docs/).
- Contact form: https://tally.so/r/J19oDr
- Issues and feature requests: the theme's GitHub repository issues page.
