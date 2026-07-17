PGPR ECO-CARE — UPDATE INSTRUCTIONS
=====================================

This package adds:
- Product photo uploads
- A website logo upload
- Green PGPR Eco-Care branding
- A website description editable from the admin panel
- Shared Supabase storage, so changes persist for all visitors

IMPORTANT: You already ran the original Supabase setup.
Use the UPGRADE SQL, not the full setup file.

STEP 1 — UPGRADE SUPABASE
-------------------------
1. Open your Supabase project.
2. Go to SQL Editor.
3. Click New query.
4. Open supabase-eco-care-upgrade.sql from this package.
5. Copy the entire file into the SQL Editor.
6. Click Run once.

This safely adds:
- products.image_path
- the site_settings table
- the public shop-assets bucket
- the required security policies

STEP 2 — UPDATE GITHUB
----------------------
1. Open your GitHub repository.
2. Delete or replace the current index.html.
3. Upload the index.html from this package to the repository root.
4. Commit the change.
5. Wait for GitHub Pages to redeploy.
6. Refresh the website with Ctrl + Shift + R.

STEP 3 — EDIT THE WEBSITE
-------------------------
1. Click the lock icon and sign in with your Supabase admin account.
2. Open CATALOG to add/edit items and upload a product photo.
3. Open SETTINGS to edit the public website description and upload a logo.
4. Click Save.

The title is fixed as PGPR Eco-Care in both the browser tab and website header.
Product photos and logos support JPG, PNG, WebP and GIF files up to 5 MB.

FILES
-----
index.html                         Upload this to GitHub Pages.
supabase-eco-care-upgrade.sql     Run this once on your existing project.
supabase-setup-eco-care.sql       Full setup only for a brand-new database.
