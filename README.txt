Luxtory Bd — FINAL READY

Files: index.html (customer site), admin.html (admin), SUPABASE-FINAL-SETUP.sql.
1. Run SUPABASE-FINAL-SETUP.sql in Supabase SQL Editor.
2. Authentication > Users > create admin email/password.
3. Copy that user UUID and run: insert into public.store_admins(user_id) values ('USER-UUID');
4. GitHub Pages: upload the FILES inside this ZIP to the repository root (not the ZIP itself).
5. Customer: index.html. Admin: admin.html.
6. Never expose any secret/service_role key.
