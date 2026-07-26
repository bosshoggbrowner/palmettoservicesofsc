Palmetto Services LLC of SC — redesigned site
==============================================

WHAT'S IN THIS FOLDER
- index.html, services.html, portfolio.html, about.html, contact.html
- css/style.css        (all styling, one shared file)
- Images/palmetto-logo.png   (your new logo, cropped from the photo you sent)

HOW TO USE IT
This is a drop-in replacement for your current site's HTML files. Your
existing Images folder (Feature1.jpg–Feature6.jpg, About2.jpg, fblogo.png,
etc.) is NOT included here — the pages reference those by their existing
filenames, so just add these files into your current site alongside your
existing Images folder rather than replacing it. The only new image is
Images/palmetto-logo.png, which needs to be added in.

If you deploy via GitHub → Netlify (or similar), that means:
1. Copy index.html, services.html, portfolio.html, about.html, contact.html
   into the root of your site, overwriting the old versions.
2. Copy the css folder in as-is.
3. Copy Images/palmetto-logo.png into your existing Images folder.
4. Commit and push — Netlify will redeploy automatically.

NOTES
- Nav, page names, and structure are unchanged from your original site.
- The phone number is now a tap-to-call link (tel:8034678308) — double
  check the number is right before you publish.
- The portfolio lightbox uses a lightweight CSS-only technique (no
  JavaScript), so it'll keep working even if scripts are blocked.
- The logo is a cropped photo of the wood sign you sent over, not a clean
  vector cutout — there's a faint grey background visible around it. For a
  fully seamless look, a transparent-background version of that sign photo
  would drop in as a straight swap for Images/palmetto-logo.png.
