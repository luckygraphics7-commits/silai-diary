# Silai Diary – Tailor Manager

Professional Gujarati tailor PWA with:
- Email/password login and password reset
- Cloud backup through Supabase Auth + Postgres
- Customer name, mobile, village
- Shirt/Jubba measurements
- Pant/Lengha measurements
- Daily sewing entries by customer and date
- Today/month/year/all-time totals
- Responsive mobile-first design and PWA manifest

## Deployment
Upload all files to any static HTTPS host (GitHub Pages, Netlify, Vercel static hosting, etc.). The project is already connected to the configured Supabase project using a browser-safe publishable key.

## Database
The required `tailor_customers`, `tailor_measurements`, and `tailor_sewing_entries` tables have been created in the connected Supabase project with RLS policies restricting rows to the signed-in user.
