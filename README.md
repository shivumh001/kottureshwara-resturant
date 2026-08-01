# Shri Kottureshwara Family Restaurant — Website

A single-page restaurant website built with **Bootstrap 5**, featuring an online menu,
shopping cart, and an owner/admin dashboard to view customer orders.

**Managed by:** Shivakumar M Hiremath

---

## Features

### Customer-facing
- Responsive navbar with cart and admin login buttons
- Hero banner with restaurant branding
- Full menu, filterable by category:
  - Starters
  - Roti & Bread
  - Rice
  - Pulav & Biryani
  - North Karnataka Meal (jolada rotti, yennegai badanekai, kharda, kadabu, full thali)
  - South Karnataka Meal (ragi mudde, saaru, akki rotti, set dosa, full thali)
  - Curries
  - Desserts & Beverages
- Add-to-cart with quantity controls (slide-out cart panel)
- Checkout form (name, phone, dine-in table number / parcel)
- Order confirmation with an order number
- Contact section with embedded Google Map

### Owner/Admin
- "Admin Login" button (demo credentials: `shivakumar` / `skfr@123`)
- Dashboard showing every order: order #, time, customer, phone, dine-in/parcel + table,
  items ordered, total, and status (Pending → Preparing → Ready → Served)
- Live stats: total orders, pending orders, total revenue
- Clear-all-orders option

## Tech Stack
- HTML5, CSS3, vanilla JavaScript
- Bootstrap 5.3 (CDN)
- Font Awesome icons (CDN)
- Google Fonts: Playfair Display, Poppins

## Known Limitations
- **Orders are stored in browser memory only** — they disappear on page refresh. There is
  no database or backend, so orders placed by one customer are not visible to another
  visitor or after the page is closed.
- **Admin login is client-side only** — the username/password are visible in the page's
  JavaScript source. This is fine for a demo but is **not secure** for real-world use.
- Menu prices, contact details, and map location are placeholders and should be updated.
- Food and background images are stock photos from Unsplash, not the restaurant's own.

## Running Locally
Just open `index.html` (or whatever you name the file) directly in a browser — no build
step or server required.

## Suggested Next Steps for Production Use
- Add a real backend (Node/Express, PHP, or a service like Firebase/Supabase) to store
  orders in a database so the owner can see them from any device, any time.
- Move admin authentication to the backend with hashed passwords, not hardcoded in
  client-side JS.
- Add real food photography and update contact/location details.
- Consider payment integration if online payment is needed.

## License
No license specified — add one (e.g. MIT) if you plan to make this repository public
and want to clarify reuse terms.
