# KINETIK — Installation & Setup Guide

Thank you for purchasing **KINETIK**, a premium performance-supplements Shopify theme.
This guide gets you from the downloaded `.zip` to a live, fully configured store.

Live demo: https://kinetik-h73lccse.myshopify.com
Support: blackdynamic.corporate@gmail.com

---

## 1. Requirements
- A Shopify plan (any). KINETIK is an **Online Store 2.0** theme.
- No page-builder app required. No coding required for normal setup.

## 2. Install the theme
1. Unzip is **not** needed — keep `KINETIK-0.3.0.zip` as-is.
2. Shopify admin → **Online Store → Themes**.
3. **Add theme → Upload zip file** → choose `KINETIK-0.3.0.zip`.
4. Click **Customize** to preview, then **Publish** when ready.

> The theme ships with two style presets: **Default** (dark) and **Daylight** (light). Switch in
> Theme settings → **Theme styles**, or in the theme editor's preset picker.

## 3. First-run checklist
KINETIK reads real store data — replace the demo content with yours.

### Products & collections
- Create your products and collections.
- For the **Shop mega menu** and the homepage collection cards, set a **collection image**
  (Collections → *collection* → Image). These power the mega-menu covers.
- Build a **main-menu** navigation: `Home`, `Shop` (with sub-collections as children → these become
  the mega-menu cards), `Journal`, `About`, `Contact`.

### Metafields the theme uses (optional but recommended)
Create these under **Settings → Custom data → Products**:
| Namespace.key | Type | Used for |
|---|---|---|
| `reviews.rating` | Rating | Star rating on cards + product page |
| `reviews.rating_count` | Integer | "· N reviews" count |
| `custom.short_description` | Single-line text | Buy-box short description |
| `custom.badge` | Single-line text | Image badge (e.g. "Bestseller") |
| `custom.subtitle` | Single-line text | Card flavor/subtitle line |
| `custom.servings` | Single-line text | Card "30 servings" tag |

> Tip: the rating metafield is auto-populated if you use the **Shopify Product Reviews** /
> compatible review apps that write to `reviews.rating`.

### Subscriptions (Subscribe & Save)
- Install a selling-plan app (e.g. **Shopify Subscriptions**).
- Create a selling plan group and add it to products → the product page shows the
  **One-time vs Subscribe & Save** selector automatically.

### Reviews / upsell apps (product page)
- Install any review app (**Judge.me, Loox, Stamped**, etc.) or upsell app.
- In the theme editor open a **Product** template → in the section's blocks, **Add block → Apps**
  and drop the app block in. It renders full-width below the buy box (KINETIK's `@app` area).

### Cart & free shipping
- Theme editor → **Cart** section (and **Cart drawer**) → set **Free shipping threshold**
  (default $75). Set to 0 to hide the progress bar.

### Newsletter popup
- Theme editor → **Newsletter popup** section: enable/disable, delay (seconds), heading, text,
  image, button. Connect signups to your email tool (the form tags subscribers `newsletter, popup`).
- To deliver a discount code, set up an automation in your email app for the `newsletter` tag.

### Homepage slideshow
- Theme editor → **Slideshow**: add slides, set each slide's image, heading, text and button.
- Keep **"Use first slide heading as page heading (H1)"** ON when the slideshow is the top section.

## 4. Branding
- **Theme settings → Colors**: 4 editable color schemes (dark, light, volt, midnight).
- **Theme settings → Typography**: heading/body fonts.
- **Theme settings → Logo & favicon**: upload your logo and favicon.

## 5. Before launch
- Replace all demo copy/images with your own.
- Set your **storefront contact email** (Contact section → Email).
- Add your store policies (Settings → Policies) — linked in the footer.
- Run **Online Store → Preferences** for SEO title/description + social share image.

---

Need help? Email **blackdynamic.corporate@gmail.com** with your store URL and a description.
