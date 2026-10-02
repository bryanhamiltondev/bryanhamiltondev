# Bryan Hamilton

**Full-Stack Web Engineer - Founder, The DJ Calendar - New Jersey, USA**

> **Resume: [thedjcalendar.com/resume](https://thedjcalendar.com/resume/)** - Same guy. Two ways to hire him. [Tech](https://thedjcalendar.com/resume/bryan-hamilton-tech.html) - [Retail](https://thedjcalendar.com/resume/bryan-hamilton-retail.html)

---

## About

I've been building for the web since the late 90s - from KPMG back-office systems and the NY Daily News CMS to out-of-home media platforms at OUTFRONT Media, reaching millions of commuters daily.

Today I run [The DJ Calendar](https://thedjcalendar.com), an electronic music event discovery platform I founded in 2015: ~1,000 schema.org-rich pages, a custom PHP/MySQL stack, newsletter infrastructure, and zero-dependency tooling I build when off-the-shelf answers aren't good enough.

I like my software the way I like my sets: **no bloat, every element intentional.**

---

## Featured Demo

> **[dj-card-preview - Live Demo](https://bryanhamiltondev.github.io/dj-card-preview/)**
>
> Hover over a DJ card. A 30-second iTunes preview plays. An 8-bar EQ springs to life, driven by the real audio frequencies via Web Audio API. Touch-friendly. Reduced-motion-aware. One click to consent, then it just works.
>
> *Production behavior, extracted as a pattern. This is what vanilla JS looks like when it's trying to impress you.*

---

## What I'm building

A series of production-derived repos - each one isolates a single engineering problem from The DJ Calendar and publishes the pattern, not the infrastructure.

### Frontend & UX

| Repo | What it does |
|------|-------------|
| [**dj-card-preview**](https://github.com/bryanhamiltondev/dj-card-preview) | Hover preview card: iTunes audio + Web Audio analyser EQ + consent-first contract for touch/reduced-motion. Live demo at [bryanhamiltondev.github.io/dj-card-preview](https://bryanhamiltondev.github.io/dj-card-preview/) |
| [**instant-search-index**](https://github.com/bryanhamiltondev/instant-search-index) | Client-side search from a prebuilt JSON index: scored AND matching, weighted fields, ARIA combobox. Runs ~1,000 pages - no search server, no frameworks, zero round-trips. |
| [**next-show-radar**](https://github.com/bryanhamiltondev/next-show-radar) | Geolocation-aware tour map: consent-first, haversine radius fitting, race-safe Leaflet boot. Stays excellent when they say no. |
| [**eq-visualizer**](https://github.com/bryanhamiltondev/eq-visualizer) | 8-bar sensory equalizer: pure CSS animation, optional 1 KB injector, reduced-motion respect built in. Zero JS required. |
| [**sri-lazy-loader**](https://github.com/bryanhamiltondev/sri-lazy-loader) | Race-safe lazy script loader with Subresource Integrity: concurrent-caller dedupe, timeout + cleanup. Brings Leaflet in safely for next-show-radar. |
| [**csrf-json-fetch**](https://github.com/bryanhamiltondev/csrf-json-fetch) | Hardened vanilla-JS fetch wrapper: CSRF token lifecycle, header+body dual injection, single-retry on expiry, typed errors. |

### Backend & Data

| Repo | What it does |
|------|-------------|
| [**tour-feed-pipeline**](https://github.com/bryanhamiltondev/tour-feed-pipeline) | Bandsintown + Ticketmaster feeds normalized into one row shape, deduped, cached, pruned. CI-tested PHP 8.1/8.3. |
| [**event-calendar-schema**](https://github.com/bryanhamiltondev/event-calendar-schema) | MySQL schema + PDO repository: idempotent event upserts, double opt-in subscribers, query-shaped indexes. Inline design docs. |
| [**jsonld-schema-audit**](https://github.com/bryanhamiltondev/jsonld-schema-audit) | Zero-dependency PHP CLI that audits JSON-LD: validates required properties, resolves @id refs, fails CI on regressions. Took The DJ Calendar from hundreds of Rich Results warnings to zero. |
| [**wp-schema-audit**](https://github.com/bryanhamiltondev/wp-schema-audit) | WordPress plugin port of the schema auditor: WP-CLI command, admin Tools page, CI self-test with pass/fail fixtures. |

---

## The toolkit

| Layer | What I reach for |
|---|---|
| Languages | PHP, vanilla JavaScript, MySQL, JSON, Bash/Shell, HTML/CSS |
| CMS | WordPress (21 years), custom plugins, ACF, WP-CLI |
| Data & SEO | schema.org / JSON-LD, PDO, Leaflet, structured-data auditing |
| Quality | GitHub Actions CI, fixture-based self-tests, zero-dependency design |

---

## Find me

- **Resume:** [thedjcalendar.com/resume](https://thedjcalendar.com/resume/) - both packages, live on my site
- **The DJ Calendar:** [thedjcalendar.com](https://thedjcalendar.com) - electronic music event discovery, live in production
- **LinkedIn:** [linkedin.com/in/bryanhamilton-nj](https://www.linkedin.com/in/bryanhamilton-nj)
- **Email:** [bryan_hamilton@me.com](mailto:bryan_hamilton@me.com)

---

*Built with PHP, vanilla JS, and the conviction that the best code is the code you don't have to install.*