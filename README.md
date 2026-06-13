# Iron Vault Full Web App Starter

This is a real Next.js + Supabase starter for an Iron Vault dropshipping/product store.

## What it includes

- Public storefront
- Product grid
- Product detail page
- Cart foundation using browser storage
- Admin dashboard
- Add/edit/delete product screens
- Supplier fields
- Margin tracking
- Active/hidden products
- Supabase schema
- Starter seed products

## What it does NOT include yet

- Real Stripe checkout
- Real supplier API fulfillment
- Real image upload storage
- Real customer accounts
- Real order payment capture

Those are next steps after deployment.

## Setup

1. Create a Supabase project.
2. Run the SQL in `supabase/schema.sql`.
3. Run the SQL in `supabase/seed.sql`.
4. Copy `.env.example` to `.env.local`.
5. Fill in Supabase keys.
6. Run:

```bash
npm install
npm run dev
```

7. Open `http://localhost:3000`.

## Deploy

Use Vercel:
1. Push this folder to GitHub.
2. Import the repo into Vercel.
3. Add environment variables.
4. Deploy.

## Admin

Go to `/admin`.

This starter uses a simple admin gate placeholder. For production, connect Supabase Auth and restrict admin access by email.
