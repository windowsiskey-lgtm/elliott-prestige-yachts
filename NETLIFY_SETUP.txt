TRUE FINAL BUILD NOTES

This build includes:
- Buyer-first luxury homepage
- Inventory overlay cards
- Dynamic yacht detail page
- Real inventory JSON used by the public site
- Included admin editor for browser-based inventory editing/export
- Decap CMS config included for Git-backed publishing
- Large multi-page site structure

To make /admin publish changes publicly on Netlify:
1. Put this site in a GitHub repo
2. Import that repo into Netlify
3. Enable Identity
4. Enable Git Gateway
5. Invite yourself
6. Replace /admin/index.html with /admin/decap.html or point admin to decap.html
   (The included /admin/index.html is the browser editor you can use immediately.
    /admin/decap.html is the Decap CMS entrypoint for Git-backed publishing.)

Public inventory source:
- content/inventory.json

Main live pages:
- index.html
- inventory/index.html
- inventory/view.html
- about.html
- contact.html
- power-cruisers.html
- motor-yachts.html
- sell-your-yacht.html

This version is intentionally larger and more production-like than the small CMS scaffold.
