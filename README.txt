Luxtory Bd FINAL
1. index.html = customer store
2. admin.html = secure admin login/control panel
3. SUPABASE-SETUP.sql = backend/RLS/guest checkout/storage setup

Before going live: run SUPABASE-SETUP.sql once; create a Supabase Auth user; then insert that user's UUID into public.store_admins.
Never use a service_role/secret key in these files.
