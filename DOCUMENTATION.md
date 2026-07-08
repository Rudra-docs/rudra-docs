# Flagship Theme — Merchant Documentation

Version 1.0.0 · Shopify Online Store 2.0 · 40+ sections · no apps required

Flagship is a premium fashion theme that works as a single-product store or a
full multi-product catalog. Everything below is done in the Shopify admin and
theme editor — **no code, ever**.

---

## 1. Quick start (10 minutes)

1. **Online Store → Themes → Add theme → Upload zip file.**
2. Click **Customize** → the **Flagship** preset (black & white editorial)
   loads by default. Every color, font, corner radius and spacing value is
   yours to change under **Theme settings** — two minutes of tweaks give
   you a warm-light or dark look without touching code.
3. Add products and collections (sections 2–3 below) — the homepage fills
   itself. Until then, designed placeholder imagery keeps every section
   looking finished.
4. Publish.

---

## 2. Products — how to add them so every feature activates

**Products → Add product.** For each product:

- **Photos**: 2–5 images, portrait (4:5) works best.
- **Options**: click *"+ Add options like size or color"*.
  - Add **Color** with values (e.g. Black, Beige) → the theme renders
    **round color swatches** on cards and the product page.
  - Add **Size** (S, M, L, XL…) → rendered as **size boxes**.
  - When Shopify prompts **"Add images for Color"**, assign one photo per
    color → the gallery **switches image when a shopper picks a color**.
- **Sale badge**: set **Compare-at price higher than Price**
  (e.g. Price 189, Compare-at 240) → automatic **“−21%” badge**, strike-through
  pricing, and sale styling everywhere. Compare-at must be the higher number.
- **Low-stock alert**: enable *Track quantity* and keep stock at or below the
  threshold (default 5, configurable in the product section) → shows
  **“Hurry — only X left in stock.”**
- **Pre-order**: set *Continue selling when out of stock* with 0 stock →
  the buy button reads **Pre-order**.
- **Product type**: fill it in (Outerwear, Knitwear…) — it powers automated
  collections and a free filter.

---

## 3. Collections (categories) — how the automatic system works

**Products → Collections → Create collection.**

- **Automated** (recommended): condition *Product type equals Outerwear* →
  every matching product joins forever.
- **Image**: upload one — it becomes the tile image on the homepage, the
  mega menu, and the /collections page. No image? The first product’s photo
  is used automatically.
- Make sure **Online Store** is checked under sales channels.

Once saved, with zero extra steps the collection appears in:
- the homepage **Shop by category** grid (top N, editorial layout),
- the header **Categories mega menu**,
- the **/collections** page,
- and clicking any of these opens `/collections/<name>` showing **only that
  category’s products**, with filters scoped to it.

The homepage grid has settings (Customize → Shop by category): Automatic /
Manual source, number of tiles (3–12), layout (editorial tall-tile or even
grid), and a “View all” button.

---

## 4. Navigation & header

**Content → Menus** (older admins: Online Store → Navigation):

- **Main menu** = the header links. Drag an item slightly **right under
  another** to nest it → nested items become a **dropdown**; two levels of
  nesting become **mega menu columns**.
- **Footer menu** = the footer’s Support column.

**Customize → Header section** gives you:

| Setting | What it does |
| --- | --- |
| Logo image / **Logo text override** | Upload a logo, or type a short name (great for mobile) |
| Utility bar | The trust line + promo code strip above the header (both texts editable, can be hidden) |
| Header style | Light, or Dark (inverse) |
| **Mega menu blocks** | Add a block, type a menu item’s exact title (e.g. *Men*) → that dropdown becomes a **full-width mega menu with a promo image** you upload. Others stay compact. Up to 3. |
| **Categories mega menu** | The automatic collections menu: toggle, label, promo image/heading/link |
| Sticky header | On/off |

The search icon opens **predictive search** (live product suggestions);
pressing Enter opens the full results page with the filter sidebar.

---

## 5. Pages — ready-made templates

Create pages under **Online Store → Pages**, then assign a **Theme template**
in the right sidebar:

| Template | Gives you |
| --- | --- |
| `about` | Editorial Our-Story page: photo banner, mission/vision splits, values, press logos, newsletter, Instagram grid |
| `faq` | Photo banner + accordion FAQ with **category headings** + “Didn’t find your answer?” banner |
| `contact` | Photo banner + **info cards** (phone/email/hours/address) + styled form with custom fields |

Every banner photo, heading and section on these pages is editable per page
in the theme editor. Policies created in **Settings → Policies** list
automatically in the footer’s Policies column.

---

## 6. Homepage sections (the full toolbox)

Add, remove and reorder everything in the editor. Highlights:

- **Split hero** — dark editorial hero: swaying 3D image, floating
  thumbnails, drifting watermark text, pulsing button
- **Slideshow** — autoplay photo carousel with 3D text flips and cinematic zoom
- **3D silk hero** — live GPU fabric animation (colors + speed settings)
- **3D product spotlight** — color swatches swap the floating image in 3D;
  one “Colorway” block per look
- **Promo tiles** — 2–4 photo tiles with overlay captions
- **Featured collection** — product grid with quick view / quick add
- **Shop by category** — the automatic category grid (§3)
- **Collection carousel** — staggered “shop by season” cards
- **Scrolling text** — marquee ticker
- **Countdown banner** — deal timer (end date, hide-when-expired)
- **Lookbook** — image with shoppable hotspots
- **Before & after** — draggable comparison slider
- **Image with text · Image banner · Video banner** — editorial blocks
- **Featured blog · Testimonials · FAQ · Logo list · Newsletter ·
  Social gallery** — content sections
- **Popup** — newsletter capture or age verification (delay + frequency)

All scroll animations, parallax and hover effects are built in, GPU-only,
and automatically disabled for reduced-motion visitors.

---

## 7. Collection, search & product pages

- **Filter sidebar** (collections + search): enable filters once in the free
  **Shopify Search & Discovery app** (Filters → add Color, Size, Price,
  Availability, Product type). Color values render as swatch dots; fashion
  names like *Sand* map to real colors automatically.
- **Sorting**, product counts, active-filter pills, Clear all — built in.
- **Pagination style** per section: numbered / Load-more / infinite scroll.
- **Product card style** (Theme settings → Layout): *Standard* or *Overlay*
  (caption bar on the image with a corner cart button).
- **Product page**: image-grid or thumbnail gallery (setting), zoom lightbox,
  product videos, 3D/AR models with “View in your space”, sticky details,
  quantity + side-by-side **Add to cart / Buy It Now**, Shop Pay Installments,
  collapsible tabs (size chart / care — rich text or a page),
  back-in-stock email form on sold-out items, local pickup availability,
  trust badges block, optional floating “ghost image” effect,
  **You may also like** (with smart fallback) and **Recently viewed**.

### Product ratings & reviews (stars with customer photos)

The theme shows **star ratings** on every product card and on the product
page, and marks them up for **Google rich results** (stars in search).

1. **Install a reviews app** — for example **Judge.me (free plan)** from the
   Shopify App Store. Reviews need an app because customer-submitted content
   (text + photos) must be stored somewhere; every Shopify theme works this
   way. The app writes each product’s average rating and review count to
   Shopify’s standard rating fields — the theme’s stars read those
   automatically. No extra setup needed for the stars themselves.
2. **Let customers write reviews with photos**: in the theme editor open a
   product page → **Add block** inside the product section → pick the app’s
   review widget block (apps appear in the block list once installed). The
   widget shows full reviews with photo uploads right below the buy box.
3. **Turning ratings on/off (admin control)**:
   - Cards everywhere: **Theme settings → Layout → Product ratings →
     “Show star ratings on product cards.”**
   - Product page: product section settings → **“Show star rating.”**
   - Untick either to hide stars there; uninstalling the app hides all
     ratings automatically.

---

## 8. Cart & customer accounts

- **Cart**: slide-out drawer (or cart page — Theme settings), live count,
  order notes, quantity editing.
- **Accounts**: full styled pages — sign in, register, password reset,
  order history, order detail **with tracking links**, address book.
  Works with either Shopify customer-account mode
  (Settings → Customer accounts).

---

## 9. Selling globally & SEO

- **Markets**: add countries in Settings → Markets → the footer’s
  country/currency selector goes live; language selector likewise
  (Settings → Languages). UI translations included: EN, FR, DE, ES, IT.
- **SEO built in**: JSON-LD structured data (Product/Offer, Organization,
  Breadcrumbs), Open Graph + Twitter cards, lazy responsive images.
  Set your **homepage meta description** in Online Store → Preferences.

---

## 10. Troubleshooting

| Symptom | Fix |
| --- | --- |
| Filter sidebar empty | Enable filters in the Search & Discovery app (§7) |
| Category tiles show placeholder photos | Create collections with images (§3) |
| No sale badge | Compare-at price must be **higher** than Price (§2) |
| Gallery doesn’t change with color | Assign an image to each Color value (§2) |
| Mega menu item is a small dropdown | Add a “Mega menu” block with that item’s exact title (§4) |
| Popup doesn’t reappear | By design — once closed it hides for N days (setting); test in a private window |
| Star ratings not showing | Install a reviews app and collect at least one review (§7); check both rating toggles are on |

---

## 11. Support

Email: **reshmakachhadiya08@gmail.com** — we reply within one business day.
Recommended image sizes: products 1400×1750 · banners 2000×1100 ·
category tiles 1000×750.
