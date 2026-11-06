# GREAT ENOCOM GLOBAL VENTURES — Storefront

This is the Codex-ready working folder for the existing GREAT ENOCOM GLOBAL VENTURES storefront.

## Existing project — continue, do not rebuild
The approved Step 2 storefront is the baseline. Preserve the existing customer journey, official logo, product records and brand identity. Make only small, reversible, owner-approved changes.

## Mobile-first workflow
The owner works strictly from an Android phone. Keep catalogue maintenance and GitHub/Codex workflows practical on mobile. Do not require a laptop, command line or Termux.

## Catalogue data
The product catalogue is stored separately in data/products.json. The storefront loads it at runtime. To edit catalogue information, use GitHub's mobile website to edit data/products.json. Preserve product IDs and the existing field structure. Do not invent prices, weights, packaging sizes, specifications or stock information.

The JSON file is static project data, not a database. Changes become part of the website when the updated project is published through the static hosting workflow.

## Current architecture
- Single-page static HTML with inline CSS and JavaScript.
- Product data in data/products.json.
- Hash-based navigation.
- Browser localStorage order list under key gegv-cart.
- Owner-supplied product image URLs and existing fallback behaviour.
- WhatsApp enquiry and copy-summary workflow.
- No backend, package manager or build step.

## Hosting
Netlify free static hosting on a .netlify.app subdomain. No paid services or backend are required for this catalogue approach.
