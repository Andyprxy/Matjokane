# Operations Studio guide

Open `/admin/` on the hosted site. The portal intentionally has no pretend login: GitHub Pages cannot protect customer data or implement authentication by itself. Use fictional data in this demo.

## Business documents
1. Open Business details and review the company name, address, contact details, registration and optional VAT/banking information. Unknown details are blank.
2. Open Document studio and choose Membership form, Receipt, Quotation, Invoice, Claim form, Letter, Job card or Account statement.
3. Select a demonstration customer to prefill their details, or type a recipient manually. Fill the document-specific fields. The preview updates immediately.
4. For quotes/invoices, add or remove item rows and enter quantities and unit prices. Discount is applied before the selected tax percentage; payments reduce the balance due. Tax defaults to zero. Only enter the applicable verified rate.
5. Save draft to retain a copy in this browser. Open it from Saved documents to continue editing. Unsaved work is lost when the page reloads. Document numbers are editable; confirm numbering before issuing any actual record.
6. Click Print / Save as PDF. In the browser print dialog choose Save as PDF, A4, portrait, 100% scale; disable browser headers and footers. Enable background graphics for the purple ribbons. This uses the browser's PDF destination, not a separate PDF service. Longer documents flow onto additional pages.

Keep the demonstration marker enabled for your presentation. Templates are proposed administrative records, not approved company policy wording. Membership and claim forms must be reviewed against the actual provider's requirements before live use.

## Operational tabs
- Customers: search, add and edit sample member information, monthly amount, paid-through month and manual payment status.
- Payments: record pending, verified or reversed payments. Verified payments can prefill a receipt. Editing payment records does not automatically determine membership coverage or change customer status.
- Claim requests: track request status and checklist notes. Generate a claim form from a request. This records staff decisions; it does not decide eligibility or submit a claim to an insurer.
- Coffin inventory: add/edit stock items, reorder levels and sample selling prices. Movement records received, sold, allocated or returned quantities with a reason. Outgoing movements cannot exceed available stock. Manual stock-count corrections are recorded in the movement history.
- Fleet: manage model, registration, driver, role, status and service date. Save vehicle photos in assets/images/fleet/ and use the filename in the vehicle record. Demo model names do not confirm actual ownership.
- Export demo data: downloads a JSON snapshot for inspection. An import/restore workflow is not included.

## Persistence and limits
Records, settings and saved drafts use this browser's localStorage for the site's origin. They do not sync to other users or devices. Clearing site data removes them. The exported JSON is not a production backup system. No emails, WhatsApp messages, payments or claims are automatically sent from this portal.

For production, connect the portal to an authenticated backend with access controls, server-side validation, reliable identifiers, backups, audit history and approved business rules. Public static hosting alone is suitable only for this demonstration.
