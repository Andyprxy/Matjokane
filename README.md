# Matjokane Funeral Services — website & operations demo

## GitHub upload
Extract this ZIP. Upload its CONTENTS to your repository publishing root: `index.html`, `assets/`, `admin/` and the other page folders must sit alongside each other. Do not upload only the ZIP or nest the entire project in another folder.

In GitHub repository Settings → Pages, publish from your chosen branch and the root folder. The included `.nojekyll` supports plain static hosting. No build tools or installation are required. Relative links support both a custom domain and a GitHub project subdirectory. Configure your custom domain separately after you own and connect it; no CNAME has been included.

| Page | File | Clean route |
|---|---|---|
| Home | index.html | / |
| Our story | ourstory/index.html | /ourstory/ |
| Services | services/index.html | /services/ |
| Gallery | gallery/index.html | /gallery/ |
| Contact | contact/index.html | /contact/ |
| Service guide | brochure/index.html | /brochure/ |
| Privacy | privacy/index.html | /privacy/ |
| Admin demo | admin/index.html | /admin/ |

Directory routes use trailing slashes and never expose index.html in the navigation. For local use, extract the whole ZIP first and double-click the root index.html. To open the admin directly, double-click admin/index.html. Local links explicitly open each page’s index.html; when hosted, the routing helper automatically keeps clean directory URLs. Do not browse files inside the compressed ZIP. Browser-local storage behaviour depends on browser settings; keep the same browser and folder path and export important demo work.

## Media and presentation
See IMAGE-GUIDE.md for exact filenames. The latest supplied convoy image is included as a real WebP hero with the left navy gradient. Home and Services now include the three supplied service photographs and a generated floral image, all WebP. Story and gallery photographs are installed. Optional admin fleet photos still use designed placeholders. Add your approved team, service, gallery and fleet images at the documented paths.

## Admin
Open /admin/. See ADMIN-GUIDE.md. Includes editable A4 documents, local draft saving, customer and payment records, claims tracking, coffin stock movements and fleet records. All seed records and prices are fictional demonstration data.

This is a static, browser-local demonstration, not a secured production system. There is no authentication, shared database, server backup, automatic communication or insurance adjudication. Do not enter real customer or claim data. Production needs protected access, a secure backend, role permissions and audit records before real use.

## Public interactions
Responsive navigation, gallery filters/lightbox, optional video players, printable service guide and service selection on the contact form. Contact prepares a WhatsApp message for a visitor to review and send; it does not silently send a message.

## Validation
JavaScript syntax and local static references checked. Browser checks covered the latest hero, document calculations, draft save/reopen after reload, customer prefill and stock movement recording. Confirm business details, product terms, media rights and company identity fields before publication; see SOURCES.md.

## Updated navigation
Admin groups: Workspace (Overview), Documentation (Document studio), Customers & accounts (Customers, Payments, Claim requests), Resources (Fleet management, Coffin inventory), Administration (Business details). A moving blue glass bubble highlights the active tab; reduced-motion preferences disable animation.

Latest update: founding year corrected to 2008 from client confirmation; Oupa tribute expanded from the supplied remembrance. Header admin icon opens the portal. The floating Let’s talk button opens WhatsApp at +27 83 304 2400.

## Phone layout update
The hero keeps its horizontal navy fade with the vehicle on the right. Story, tribute and service sections retain left-aligned text and right-hand images. Service cards use horizontal layouts, gallery uses two columns, and buttons and form inputs accommodate touch. Browser checks at 320px and 390px frame widths verified the hero, story and services; sampled narrow layouts had no horizontal overflow. Desktop styling is preserved. Image paths are unchanged.

## Navy brand palette
Primary colour #1C315E, sampled from the supplied Oupa tribute background. Navy replaces navy across the public website, admin interface and printable document accents. Gold remains the accent; mobile and desktop heroes retain their horizontal fades. Image files are unchanged.
