PGPR SHOP — SUPABASE SETUP

1. Open your Supabase project.
2. Go to SQL Editor -> New query.
3. Paste everything from supabase-setup.sql and click Run.
4. Go to Authentication -> Users -> Add user. Create ONE admin user using your email and a NEW strong password.
   Do not use 1234pgpr! because that password was previously embedded in public HTML.
5. In Authentication settings, disable public user sign-ups if the option is enabled.
6. Upload index.html to the root of your GitHub repository, replacing the old file.
7. Wait for GitHub Pages to deploy, then press Ctrl+Shift+R.
8. Click the lock icon and sign in using the Supabase admin email/password.

The catalogue and orders are now shared across devices. Product edits update the live shop.
Payment proofs are stored in the private payment-proofs bucket and can only be opened by a signed-in admin.
