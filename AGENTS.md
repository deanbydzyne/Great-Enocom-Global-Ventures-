# Codex Instructions — GREAT ENOCOM GLOBAL VENTURES

## Owner rules
- This is an EXISTING storefront. Continue it; do not rebuild, redesign or replace it.
- The approved Step 2 index.html is the baseline.
- Inspect the complete relevant source before editing. Explain scope and impact; make small, reversible changes.
- Preserve all working behaviour, product records, product IDs, descriptions, owner-supplied image URLs, official logo, brand identity and order-enquiry workflow unless explicitly approved.
- Do not invent prices, weights, packaging sizes, specifications, stock levels, credentials or business facts.
- The owner works strictly on Android mobile. Avoid workflows that require a computer, terminal or Termux.
- Keep architecture minimal and compatible with Netlify free static hosting. Do not introduce paid services or backend requirements without explanation and approval.
- After changes, list files changed, run relevant checks and update PROGRESS.md.

## Business facts
- Business: GREAT ENOCOM GLOBAL VENTURES.
- Tagline: Enocom Feeds, Great Harvest.
- Palette: Deep Forest Green #0B3D24, Gold #C9A24A, Light Gold #E3C171, Warm Ivory #FBF7EC, White #FFFFFF.
- Location: Adjacent Ore-Ofe Baptist Church, Along Oba Adeyemi High School Road, Mabolaje, Oyo, Oyo State, Nigeria.
- Phone: 08131211302; phone/WhatsApp: 07062539658; WhatsApp URL number: 2347062539658.
- Preserve the official logo exactly.

## Product-data source of truth
- The current catalogue source of truth is data/products.json. Do not re-embed catalogue records in index.html.
- Preserve the JSON wrapper and product field structure. Before committing catalogue edits, parse the JSON and check unique non-empty product IDs, names and groups. Keep the storefront fetch path working.

## Catalogue integrity
- 22 raw ingredients/additives: GNC (Groundnut Cake), Rosel, Local Fish Meal, Clupeid, Soya Cake, Soybean Seed, Soya Meal, Maize Flour / Maize Seed, Corn Bran, Blood Meal, Poultry Meal, Feather Meal, Cassava Flour / Garri, Bone Meal, DCP (Dicalcium Phosphate), PKC (Palm Kernel Cake), Salt, Methionine, Lysine, Fish Premix, Toxin Binder and Vitamin C.
- 3 finished sinking feeds: 2 mm Starter, 4 mm Grower and 6 mm Finisher.
- Product data is authoritative for IDs, names, descriptions, visibility, image status and references. Do not silently rename or normalize catalogue entries.
- Do not present reference images as actual stock. Respect attribution/licensing and fallback behaviour.
- Pellet illustration may be transparent; the surrounding pellet card/panel background must remain opaque.

## Customer journey to preserve
Homepage; catalogue search/filter; product details; add products to order list; quantity/packaging requests; order summary; WhatsApp enquiry or copy; phone and address details. A WhatsApp enquiry is not a confirmed order.

## Security, quality and accessibility
- Avoid unsafe interpolation of untrusted values into innerHTML.
- Validate form inputs and URLs. Never expose secrets or store plaintext passwords in client code.
- Test mobile and desktop, keyboard/focus behaviour, image failures, empty/populated orders, localStorage failures, and WhatsApp/copy fallbacks.
- SEO should use verified facts only; do not invent reviews or ratings.
- Consider performance, accessibility, HTTPS and Netlify compatibility.

## Future modules — approval required
Product management, inventory, customer profiles/history, order management/fulfilment, milling/pelleting requests, reporting and integrations. Do not assume a database/backend is required.

## Required method
1. Read project instructions and inspect relevant source.
2. Separate verified findings from assumptions.
3. Present risks, tests and minimal plan.
4. Wait for owner approval before new code or architecture changes.
5. Update PROGRESS.md with date, files, changes, tests, blockers and next step.
6. The owner is the decision-maker.
