# VÉRA REALTY

A fictional premium real-estate discovery portfolio for exploring, saving, comparing, and enquiring about demo properties.

## Run & Operate

- `pnpm --filter @workspace/vera-realty run dev` — run the Véra Realty web app
- `pnpm --filter @workspace/vera-realty run typecheck` — typecheck the web app
- `pnpm --filter @workspace/vera-realty run build` — create a production build
- No API service or database is required for this fictional client-side demo

## Stack

- pnpm workspaces, React, TypeScript, and Vite
- Client-side navigation with Wouter
- Browser local storage for saved homes, comparisons, and demo enquiries
- Responsive CSS, local image assets, and reduced-motion-aware interactions

## Where things live

- `artifacts/vera-realty/src/App.tsx` — routed pages and interactive discovery flows
- `artifacts/vera-realty/src/data/properties.ts` — editable fictional property listings and filter options
- `artifacts/vera-realty/src/index.css` — brand styling, responsive layout, and motion preferences
- `artifacts/vera-realty/public/` — local architectural imagery and site icon

## Architecture decisions

- Property search, saved properties, comparison, calculators, and forms are client-side demo features; forms do not contact an agent or create bookings.
- All listings, location details, statistics, agents, testimonials, estimates, and article content are fictional demonstration data.

## Product

Visitors can search and filter listings, inspect property details and illustrative locations, save and compare up to three homes, estimate loan payments, and submit local-only demo enquiries.

## User preferences

- Preserve the quiet-luxury editorial direction and clearly identify all VÉRA REALTY content and form behavior as fictional demo material.

## Gotchas

- Demo enquiries are stored only in the current browser's local storage; nothing is transmitted.

## Pointers

- See the `pnpm-workspace` skill for workspace structure, TypeScript setup, and package details
