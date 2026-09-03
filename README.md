# Paycheck Planner

A private, mobile-first bill planner backed by Supabase. It tracks biweekly paycheck bills, paid status, paid timestamps, and a monthly view.

## Publish with GitHub Pages

1. Run `supabase/schema.sql` in the Supabase SQL Editor.
2. Commit the project files to the `main` branch.
3. In GitHub: **Settings → Pages → Deploy from a branch → main → /(root)**.
4. In Supabase: **Authentication → URL Configuration**, add the GitHub Pages URL as the Site URL and Redirect URL.

The application uses a Supabase publishable key in the browser. This is safe because all tables are protected by Row Level Security; never add a secret or service-role key to this repository.
