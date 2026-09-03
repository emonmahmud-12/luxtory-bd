# Luxtory BD — Real Admin V4

This package fixes the V3 Admin Panel database/functionality issues.

## Supabase
Run `admin_v4_migration.sql` once in Supabase SQL Editor.

The migration adds:
- real admin profile storage
- real image uploads through Supabase Storage bucket `luxtory-media`
- analytics duration fields and indexes
- secure admin profile RLS policies

## Admin login
Use the existing Supabase Auth Administrator account. Never put a secret/service_role key in this website.

## Important
Upload the included `index.html` and `CNAME` to the same GitHub Pages repository used for Luxtory BD. Do not unpublish the site.
