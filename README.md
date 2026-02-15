# Optics Force — Field Journal Redesign (Static)

This repo is a **static** redesign of https://opticsforce.com (frontend only).
It keeps **your existing image URLs** (hosted on opticsforce.com) but uses a **completely different** layout + UI system.

## Pages included
- `index.html` (Home)
- `shop.html` (Collections)
- `product.html` (Product)
- `brands.html`
- `blog.html`
- `article.html`
- `about.html`
- `contact.html`
- `cart.html` (LocalStorage demo cart)

## Run locally
Because this project uses `type="module"` JS, run a local web server:

```bash
python3 -m http.server 5173
# then open http://localhost:5173
```

## Deploy on GitHub Pages
1. Push this folder to a GitHub repo (root of repo).
2. In GitHub: **Settings → Pages**
3. **Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: `main` (or `master`)
   - Folder: `/ (root)`
4. Visit the Pages URL GitHub gives you.

## Customize content
Edit JSON files in `/data`:
- `data/products.json`
- `data/collections.json`
- `data/brands.json`
- `data/articles.json`

## Notes
- Checkout is demo-only. Wire to Shopify Storefront API / Shopify Checkout / Stripe to go live.
