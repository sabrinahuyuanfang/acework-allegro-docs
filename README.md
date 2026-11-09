# AceWork — Allegro Application Registration Documents

This repository contains the documentation supporting our application registration request to the **Allegro Developer Portal**.

It is published so that the Allegro application review team can read the material referenced in the `Documentation link` field of our application.

---

## Document

**[AceWork Platform Overview and Purpose Statement](AceWork-Platform-Overview-and-Allegro-Advertising-Data-Integration-Purpose-Statement.md)**

The document explains, in eight sections:

| Section | Content |
|---|---|
| Executive Summary | One-page summary of the application and its boundaries |
| 1 | Purpose and scope of the document |
| 2 | What the AceWork platform is, who it serves, and how it is deployed |
| 3 | Core functional modules |
| 4 | Why we need to integrate Allegro data |
| 5 | Analytics scenarios in detail |
| 6 | Data flow and security boundaries |
| 7 | Compliance and declaration |
| 8 | Terminology mapping to Allegro platform terms |
| Appendix A | Application information at a glance |

---

## Key facts about the application

| Item | Detail |
|---|---|
| Application type | Internal, self-use, **read-only** |
| Seller account | Our own Allegro seller account only |
| Permissions requested | `allegro:api:profile:read`, `allegro:api:sale:offers:read`, `allegro:api:orders:read` |
| Write operations | **None requested** — disabled in configuration |
| External users | **None** |
| Data resale or disclosure | **None** |
| Advertising metrics | Obtained from Allegro Ads **reporting exports**, not from the Allegro Ads API |

The final row is worth noting: our analysis uses advertising figures from the Ads back-office export function. The application itself reads only offer, order and account data through the API.

---

## Status

Submitted for review to the Allegro Developer Portal.

**Contact:** the account owner of the Allegro seller account this application belongs to.