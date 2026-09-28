# Bryan Hamilton

**Full-Stack Web Engineer • Founder, The DJ Calendar (https://thedjcalendar.com) • New Jersey, USA**

**Application packages** - interactive HTML, edit in browser, print to PDF: [Tech](https://thedjcalendar.com/resume/bryan-hamilton-tech.html) • [Retail](https://thedjcalendar.com/resume/bryan-hamilton-retail.html)

## About

I've been building for the web since the late 90s - from KPMG back-office systems and
the NY Daily News CMS to out-of-home media platforms at OUTFRONT Media, used by
millions of commuters.
Today I run The DJ Calendar, an electronic music event discovery platform I founded in
2015: ~1,000 schema.org-rich pages, a custom PHP/MySQL stack, newsletter infrastructure,
and zero-dependency tooling I build when the off-the-shelf answers aren't good enough.

I like my software the way I like my sets: no bloat, every element intentional.

## What I'm working on

A series of small, production-derived repos - each one isolates a single engineering
problem from The DJ Calendar and publishes the pattern, not the infrastructure:

- **dj-card-preview** (https://github.com/bryanhamiltondev/dj-card-preview) -
  The homepage hover-preview card: a 30-second iTunes audio preview, an 8-bar EQ
  driven by the real audio frequencies via Web Audio, and a consent-first contract
  for touch, reduced motion, and conflicts. Live demo included.
- **instant-search-index** (https://github.com/bryanhamiltondev/instant-search-index) -
  Instant client-side search from a prebuilt JSON index: scored matching (AND
  semantics, weighted fields, phrase bonus), a fully ARIA-wired combobox, and
  keyboard-first navigation. Runs site search across ~1,000 pages with no search
  server and no library - one file, zero round-trips.
- **tour-feed-pipeline** (https://github.com/bryanhamiltondev/tour-feed-pipeline) -
  Bandsintown + Ticketmaster feeds normalized into one row shape, deduped across
  sources, cached with versioned JSON files, pruned for freshness. CI-tested on
  PHP 8.1/8.3.
- **jsonld-schema-audit** (https://github.com/bryanhamiltondev/jsonld-schema-audit) -
  Zero-dependency PHP CLI that audits JSON-LD structured data: validates required
  properties per schema.org type, resolves every internal @id reference, and fails
  CI on regressions. Took The DJ Calendar from hundreds of Rich Results warnings to zero.
- **csrf-json-fetch** (https://github.com/bryanhamiltondev/csrf-json-fetch) -
  Hardened vanilla-JS fetch wrapper: CSRF token lifecycle, header+body dual injection,
  and a strict single-retry-on-expiry policy.
- **sri-lazy-loader** (https://github.com/bryanhamiltondev/sri-lazy-loader) -
  Race-safe lazy script loader with Subresource Integrity: concurrent-caller dedupe,
  pre-existing-tag detection, timeout with cleanup.
- **event-calendar-schema** (https://github.com/bryanhamiltondev/event-calendar-schema) -
  MySQL schema and PDO data layer: idempotent event upserts, double opt-in subscribers,
  query-shaped composite indexes.
- **wp-schema-audit** (https://github.com/bryanhamiltondev/wp-schema-audit) -
  WordPress plugin port of the schema auditor: WP-CLI command, admin Tools page,
  and a CI self-test that asserts both the pass and fail directions against real
  fixtures.
- **next-show-radar** (https://github.com/bryanhamiltondev/next-show-radar) -
  The geolocation-aware tour map from the platform: consent-first geolocation with
  a documented deny contract (global view + announced fallback), haversine radius
  fitting, and race-safe Leaflet boot. Pairs with sri-lazy-loader, which brings
  the map engine in safely.
- **eq-visualizer** (https://github.com/bryanhamiltondev/eq-visualizer) -
  The 8-bar sensory equalizer from the homepage cards, extracted as a zero-dependency
  widget: pure CSS animation, an optional 1 KB injector, and reduced-motion respect
  built in.
- **The DJ Calendar** - electronic music event discovery: Leaflet-based city maps,
  newsletter infra, and a homegrown SEO/schema pipeline.

## The toolkit

| Layer | What I reach for |
|---|---|
| Languages | PHP, vanilla JavaScript, MySQL, JSON, Bash/Shell, HTML/CSS |
| CMS | WordPress (21 years), custom plugins, ACF, WP-CLI |
| Data & SEO | schema.org / JSON-LD, PDO, Leaflet, structured-data auditing |
| Quality | GitHub Actions CI, fixture-based self-tests, zero-dependency design |

## Find me

- **The DJ Calendar** (https://thedjcalendar.com) - electronic music event discovery, live in production
- **LinkedIn** (https://www.linkedin.com/in/bryanhamilton-nj)
- bryan_hamilton@me.com (mailto:bryan_hamilton@me.com)
