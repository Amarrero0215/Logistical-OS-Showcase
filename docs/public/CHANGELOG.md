# LOS Showcase — Public Changelog

This is the **public** (sanitized) changelog for LOS. It highlights
what’s shipped visually and at a high level. Implementation details,
internal docs, and code remain private.

---

## Week 4 — Theme locked, dashboard + workspace mockups

**Shipped**

- Finalized dark theme and grid-first workspace design (desktop + mobile).
- Dashboard card layout for Territories, Map, LOA History, and Sales Log.
- Mobile-first patterns (tab bar, card edit drawer, map bottom sheet).

**Why it matters**

- Establishes the look/feel users will recognize in MVP.
- Reduces future rework by fixing the design system early.

**Screenshots**

- `docs/public/screenshots/desktop-workspace.png`
- `docs/public/screenshots/desktop-dashboard.png`
- `docs/public/screenshots/mobile-dashboard.png`
- `docs/public/screenshots/mobile-workspace.png`

**Next**

- Scaffold tabbed Workspace (Grid | Map | LOA | History).
- Wire counters to a public-safe mock query.

---

## Week 3 — Auth baseline & data flows (private)

**Shipped (summary)**

- Login/Register screens and token handling.
- Basic queries/mutations for clients and visits (private code).

**Why it matters**

- Enables protected routes and real user sessions.

**Next**

- Refresh token flow polish and role-gated routes.

---

## Week 2 — Models & schema outline (private)

**Shipped (summary)**

- Initial domain models and GraphQL schema outline (private).

**Why it matters**

- Defines the contract the UI will consume.

---

## Week 1 — Repo scaffolding & CI plan

**Shipped**

- Monorepo structure; environment templates.
- CI/mirror plan for public showcase.

**Why it matters**

- Clean dev velocity and safe public updates.
