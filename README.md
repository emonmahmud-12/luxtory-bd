Luxtory BD V4: single-file frontend + Supabase cloud submission/library backend.
Use supabase_setup.sql once, create an admin Auth user, insert its UUID into public.admins, then paste Project URL + publishable key into the site's Owner Tools.
Never put a Supabase service_role key in index.html. RLS is required.
