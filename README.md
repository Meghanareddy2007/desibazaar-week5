# Desi Bazaar – Indian E-commerce Frontend

Single-file Vue 3 app (loaded from cdnjs). No build step.

## Run
Open `index.html` in a browser (needs internet for Vue and Google Fonts), or serve it:

    python3 -m http.server 8000

Then visit http://localhost:8000

## Features
- Product grid with category, price, rating and occasion filters, plus sorting
- Search with autocomplete, wishlist, compare (up to 3), reviews
- Cart drawer with GST 18%, shipping rule, coupons (DIWALI10, SHUBH5, LAXMI15, DESI20), Budget Buddy
- Simulated login with protected routes (#/checkout, #/account)
- Checkout with UPI / Card / COD and validation, order history
- Diwali countdown, Lucky Spin, pincode delivery estimator
- English / Hindi / Telugu switcher, light/dark theme
- Cart, wishlist, orders, language saved in localStorage
