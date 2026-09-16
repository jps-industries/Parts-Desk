# JPS Parts Desk

Parts ordering and tracking for JPS Motorsports — a single `index.html` served by GitHub Pages.

- **Data:** Supabase project `reiiivwmumgqtpyfmyja` (JPS INDUSTRIES). Tables `parts_orders`, `parts_order_lines`, `parts_customers`, `parts_vehicles`, `parts_suppliers`.
- **Access:** no sign-in — anyone with the link can view and edit orders (same as Rodi-Workflow). The tables are closed to direct API access; the page works only through the `parts_app_*` database functions.
- **Key in the page:** the Supabase *publishable* key is meant to be public. The tables have row-level security with no public policies, and the page only calls the `parts_app_*` database functions.

## Keeping it private

The link is the only protection. Don't post it publicly. If you later want a login, the database already has a staff list (`parts_staff`) and sign-in-aware functions — ask for the sign-in screen to be switched back on.
