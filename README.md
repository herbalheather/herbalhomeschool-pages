
# Herbal HomeSchool — Coming Soon Page (Drop-in)

This folder contains a ready-to-upload static site for Cloudflare Pages or any static host.

Files:
- index.html  -> The main coming-soon page (self-contained CSS + JS).
- assets/logo.svg -> Simple SVG logo.
- README.md -> This file.
- deploy_instructions.txt -> Short deploy steps.

Highlights:
- The Pay Stub Calculator link points to your existing deployed calculator at:
  https://herbalhomeschool.pages.dev/tools/paystub-calculator/
  (This ensures the calculator remains discoverable and never lost.)
- Email signups use Formspree by default. To activate:
  1. Create a free Formspree form at https://formspree.io
  2. Replace YOUR_FORMSPREE_ID in the form action in index.html with your form ID.
  If you don't set up Formspree yet, the form will still show a local success message and save addresses in the user's browser (localStorage) as a safe fallback until you configure a real endpoint.

Customization notes:
- Edit text, colors, or content in index.html.
- Remove references to features you don't want displayed yet.
