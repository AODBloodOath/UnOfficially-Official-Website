Unofficially Official — GitHub Pages Website (static)

FILES
- index.html
- styles.css
- script.js
- /assets/logo.png
- /assets/gallery/*.webp

GITHUB PAGES (quick setup)
1) Create a new GitHub repository (example: unofficially-official-site)
2) Upload ALL files/folders from this zip to the repo root:
   - index.html, styles.css, script.js, assets/
3) In the repo go to:
   Settings → Pages
4) Under “Build and deployment”:
   Source: Deploy from a branch
   Branch: main (root)
5) Save — GitHub will give you a public URL.

PRIORITY QUEUE CHECKOUT LINK
- Open script.js and replace:
  const PAYMENT_URL = "https://example.com/your-checkout-link";
  with your real Stripe/PayPal subscription link.

RESET BEHAVIOR
- The page displays the next reset time (1st of the month) in each visitor’s local time.

OPTIONAL: CUSTOM DOMAIN
- Settings → Pages → Custom domain, then add the CNAME in your DNS.

