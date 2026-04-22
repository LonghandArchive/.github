# The Longhand Archive

An independent project that archives UK public sector data and derives intelligence from it.

Public information about UK government is everywhere and nowhere. Departments publish jobs, spending, consultations, and statements across dozens of sites, most of which keep only the current state and discard the past. What is lost is not the information itself, but the shape of how it changed — and that shape is often where the interesting story lives.

The Longhand Archive preserves that shape. It captures public sector data over time with the discipline of archival practice — provenance, versioning, immutability of the record — and then builds analytical views that surface patterns and intelligence that would not be visible from a snapshot of the present alone. The archive is the foundation. The intelligence is the point.

The first collector is live and running against the UK Civil Service Jobs site, building a historical record of every vacancy advertised — including roles that have closed, been withdrawn, or quietly disappeared from the live site. A public analytical surface is in development. Further collectors will follow.

The project is built in the open by one person using AI-assisted tools. The architecture, decisions, and working method are documented as they happen — the reasoning is as much the point as the artefact.

This is a personal project. It is not affiliated with or endorsed by any UK government department or any other organisation. Data used is published under the [Open Government Licence v3.0](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/).

---

**Repositories**

- [`governance`](https://github.com/longhandarchive/governance) — cross-cutting decisions and operating principles
- [`archive-contract`](https://github.com/longhandarchive/archive-contract) — the specification of what collectors produce and platforms consume
- `platform` — the public analytical site and its supporting services *(private, in development)*
- `civilservicejobs-collector` — the first collector, archiving UK Civil Service Jobs *(private)*

---

*The Longhand Archive is a project by [Andrew Allen](https://andrewallen.uk/), undertaken in a personal capacity.*
