# Berry Vibes Studio × CCD — GitHub Pages Website

A **static multi-page website** built with plain HTML, CSS and JavaScript for GitHub Pages. It is intentionally a website, not an app shell and not a single long landing page.

## Main pages
- `index.html` — timely greeting + Today dashboard + water + horizontal macros + horizontal food pyramid + timeline + playable 3D character shortcuts
- `foods.html` — food logger + **17 SOTD presets** + scroll-wheel time selector
- `recipes.html` — searchable recipe vault + vertical ingredient chart + serving sliders + tsp/tbsp/cup calculator + playable recipe-builder lab
- `movement.html` — preset exercise selector + minute slider + automatic calorie-burn estimate
- `fasting.html` — fasting presets + start/break logging with the scroll-wheel time selector (**not a timer**)
- `restaurants.html` — 7 saved restaurant groups plus custom restaurant-food entry with calories/macros/price/photo
- `battle.html` — interactive Food Comparison Battle + winner crown
- `shop.html` — Berry Brunch character shop for **Rosette, Zing, Mallow, Sourpop and Truffle only**; no portfolio/design work
- `checkout.html` — cart/checkout preview
- `facts.html` — three daily recipe facts/CCD one-liners plus daily exercise lines
- `about.html` — project explanation
- `profile.html` — profile photo, height, weight, reason, themes and custom accent color
- `login.html` — local sign-up/sign-in + forgot username + local password reset

## Data included
- **212 CCD recipe cards**
- **8 recovered food-log entries**
- **220 total searchable food/recipe entries**
- **17 SOTD presets**
- **7 restaurant groups:** Chick-fil-A, Shake Shack, Dunkin, Starbucks, Cheesecake Factory, Uncle Julio's and Sweet Paris Crêperie & Café
- Maintenance reference: **2,100–2,150 kcal**

## Shop
The shop contains character-merch concepts only. It supports:
- search + category filter
- quantity steppers
- add to cart
- wishlist
- saved items
- recommendations
- proceed to checkout
- checkout preview

No personal design portfolio work is included in the shop.

## Authentication note
Because GitHub Pages is static, the included sign-up/sign-in/recovery flow stores demo accounts in the current browser with `localStorage`. It functions locally across the site, but it is **not secure production authentication and does not sync between devices**. Production auth would require a real backend/auth provider.

## GitHub Pages deployment
1. Create a GitHub repository.
2. Upload **all files and the `assets/` folder to the repository root**.
3. Make sure `index.html`, `style.css`, `data.js`, and `script.js` remain together at the root.
4. In GitHub: **Settings → Pages → Deploy from a branch → `main` → `/ (root)`**.
5. Open the Pages URL after deployment completes.

## Important project behavior
- Daily data, cart, profile and local account data persist in that browser via `localStorage`.
- Normal CCD foods/SOTD/movement use presets and automatic estimates; manual nutrition entry is reserved for new restaurant foods.
- Ingredient charts are vertical; macro and food-pyramid charts are horizontal.
- Motion respects `prefers-reduced-motion`.
