Bryan Hamilton

Full-Stack Web Engineer • Founder, The DJ Calendar (https://thedjcalendar.com) • New Jersey, USA

About

I've been building for the web since the late 90s - from KPMG back-office systems and
the NY Daily News CMS to out-of-home media platforms used by millions of commuters.
Today I run The DJ Calendar, an electronic music event discovery platform I founded in
2015: ~1,000 schema.org-rich pages, a custom PHP/MySQL stack, newsletter infrastructure,
and zero-dependency tooling I build when the off-the-shelf answers aren't good enough.

I like my software the way I like my sets: no bloat, every element intentional.

What I'm working on

A series of small, production-derived repos - each one isolates a single engineering
problem from The DJ Calendar and publishes the pattern, not the infrastructure:

- jsonld-schema-audit (https://github.com/bryanhamiltondev/jsonld-schema-audit) -
  Zero-dependency PHP CLI that audits JSON-LD structured data: validates required
  properties per schema.org type, resolves every internal @id reference, and fails
  CI on regressions. Took The DJ Calendar from hundreds of Rich Results warnings to zero.
- csrf-json-fetch (https://github.com/bryanhamiltondev/csrf-json-fetch) -
  Hardened vanilla-JS fetch wrapper: CSRF token lifecycle, header+body dual injection,
  and a strict single-retry-on-expiry policy.
- sri-lazy-loader (https://github.com/bryanhamiltondev/sri-lazy-loader) -
  Race-safe lazy script loader with Subresource Integrity: concurrent-caller dedupe,
  pre-existing-tag detection, timeout with cleanup.
- event-calendar-schema (https://github.com/bryanhamiltondev/event-calendar-schema) -
  MySQL schema and PDO data layer: idempotent event upserts, double opt-in subscribers,
  query-shaped composite indexes.
- wp-schema-audit (https://github.com/bryanhamiltondev/wp-schema-audit) -
  WordPress plugin port of the schema auditor: WP-CLI command, admin Tools page,
  and a CI self-test that asserts both the pass and fail directions against real
  fixtures.
- In progress: an ingestion-pipeline excerpt covering tour-date normalization
  and dedupe.
- The DJ Calendar - electronic music event discovery: Leaflet-based city maps,
  8-bar sensory equalizer, newsletter infra, and a homegrown SEO/schema pipeline.

The toolkit

Find me

 (https://thedjcalendar.com)
 (mailto:bryan_hamilton@me.com)
