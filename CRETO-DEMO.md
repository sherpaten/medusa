# Creto Studio Demo Plan — Medusa Commerce

This repository is the upstream Medusa commerce platform. The Creto demo will be a separately branded sample commerce experience built on Medusa; it is not a claim that the upstream project was authored by Creto Studio.

## Demo concept
**Creto Commerce — Modern online store**

- Create a polished sample storefront with a curated catalogue, product detail pages, search/filtering, cart, and checkout.
- Use fictional products, prices, customers, and orders. Do not use real customer data.
- Connect the storefront to a separately configured Medusa backend and Admin.
- Add Creto Studio branding to the demo presentation layer, while retaining required upstream notices and product attribution.

## Implementation boundary
This repository contains the Medusa platform/framework, not a ready-made Creto storefront. Build the storefront as a separate application using the supported Medusa starter/template for the selected platform version. Keep demo application code separate from upstream framework packages wherever practical.

## Deployment prerequisites
- Node.js version required by the selected Medusa release.
- PostgreSQL and any additional services required by the chosen modules/providers.
- A separately deployed storefront and backend, with secrets stored as environment variables.
- Test payment provider or manual/test checkout only; never enable live payments in a public demo.

## Licensing and attribution
The repository root LICENSE states that non-Enterprise materials are MIT licensed, while Enterprise Edition materials are excluded and governed by ENTERPRISE-LICENSE.md and potentially a commercial agreement. Before using any package or feature, verify its path and applicable licence. Retain MIT notices and do not use Enterprise-only materials without permission.

## Status
- [x] Demo scope documented.
- [ ] Verify exact files/packages to use and their licences.
- [ ] Scaffold Creto storefront and configure sample data.
- [ ] Configure isolated backend/database and test checkout.
- [ ] Deploy and add the verified demo URL to Creto Studio Projects.
