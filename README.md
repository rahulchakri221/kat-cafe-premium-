# KAT CAFE Premium — Repository Upload

Upload ALL files and the `assets` folder to the ROOT of your new GitHub repository. `index.html` must sit beside `styles.css` and `app.js`, not inside an extra nested folder.

## GitHub Pages
Repository → Settings → Pages → Build and deployment → Deploy from a branch → `main` → `/ (root)` → Save. Wait for GitHub Pages to publish the URL.

## Included
- Premium responsive black-and-gold homepage
- Restaurant front, signage and cat/tea logo crops in `assets/`
- Menu category filters, cart and total calculation
- WhatsApp checkout flow (requires official number in `app.js`)
- PWA manifest and service worker
- Starter Supabase schema

## Before real launch
- Replace sample menu items/prices in `app.js` with the actual menu.
- Set `KAT_CAFE_WHATSAPP` to the official WhatsApp number, country code included, digits only.
- Add verified address, opening hours and contact details in `index.html`.
- Create Supabase project, run `supabase-schema.sql`, configure secure RLS and server-side functions.
- Develop authenticated admin dashboard and connect menu/orders to Supabase.
- Integrate Razorpay via secure server/Edge Functions and verify payment signatures. Never put secret keys in frontend code.
- Test ordering and payment flows before accepting real orders.

## Android
This starter is an installable PWA where supported (Chrome → Install app / Add to Home screen). A native APK can be packaged later using Capacitor after backend and checkout flows are complete.

## Image note
The supplied images are crops from the generated KAT CAFE frontage visual, not original vector logo artwork. Replace them with official logo files if you obtain them.
