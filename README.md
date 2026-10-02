<div align="center">

# Bryan Hamilton

**PHP & vanilla JS engineer** &middot; **Founder, The DJ Calendar** &middot; **Rochelle Park, NJ**

[![Resume](https://img.shields.io/badge/Resume-thedjcalendar.com%2Fresume-00d2ff?style=flat-square&logo=googlechrome&logoColor=white)](https://thedjcalendar.com/resume/)
[![The DJ Calendar](https://img.shields.io/badge/The_DJ_Calendar-ff6b35?style=flat-square&logo=googlechrome&logoColor=white)](https://thedjcalendar.com)
[![GitHub](https://img.shields.io/badge/10_repos_production--derived-24292f?style=flat-square&logo=github&logoColor=white)](https://github.com/bryanhamiltondev?tab=repositories)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bryanhamilton-nj)

---

> **Same guy. Two ways to hire him.**  
> <a href="https://thedjcalendar.com/resume/bryan-hamilton-tech.html">&larrk; Full-Stack Engineer</a> &middot; <a href="https://thedjcalendar.com/resume/bryan-hamilton-retail.html">Service &amp; Retail &rarrk;</a>

<br>

<img src="https://img.shields.io/badge/Status-OPEN%20TO%20WORK-00d2ff?style=for-the-badge&logo=rocket&logoColor=white" alt="Open to work">

</div>

I've been building for the web since the late 90s &mdash; KPMG back-office systems, NY Daily News CMS, OUTFRONT Media reaching millions of commuters daily. Today I run [The DJ Calendar](https://thedjcalendar.com), an electronic music discovery platform I founded in 2015: ~1,000 schema.org-rich pages, a custom PHP/MySQL stack, and zero-dependency tooling I build when off-the-shelf answers aren't good enough.

**Every repo here is extracted from production code.** Not a tutorial. Not a boilerplate. The actual thing, cleaned and documented.

**Currently looking for:** full-stack web engineering roles, PHP/JavaScript-focused, remote or NJ/NY metro. Also open to senior individual contributor or lead developer positions where I can ship production code and mentor junior engineers.

<br>

---

<div align="center">

### &star; Featured

</div>

<table>
<tr>
<td width="50%" align="center">

#### [resume-hub](https://github.com/bryanhamiltondev/resume-hub)

**The landing page that powers [bryanhamilton.info](https://bryanhamilton.info).**  
8-act jQuery animation suite &mdash; particle network, typewriter, 3D card tilt, staggered entrance chain. One file, zero dependencies beyond jQuery. The portfolio anchor that ties everything together.

[`bryanhamilton.info` &rarr;](https://bryanhamilton.info)

</td>
<td width="50%" align="center">

#### [dj-card-preview](https://github.com/bryanhamiltondev/dj-card-preview)

**Hover preview with live audio + reactive EQ.**  
30-second iTunes preview plays via Web Audio API analyser. 8 canvas bars driven by real frequency data. Touch toggle. Reduced-motion-aware. Consent-first autoplay gate.

[`Live demo` &rarr;](https://bryanhamiltondev.github.io/dj-card-preview/)

</td>
</tr>
</table>

<br>

---

## The DJ Calendar Ecosystem

*Everything that powers [thedjcalendar.com](https://thedjcalendar.com) &mdash; extracted as patterns.*

<table>
<tr>
<td width="33%" align="center">

#### [dj-card-preview](https://github.com/bryanhamiltondev/dj-card-preview)

Hover-to-play audio preview card with real Web Audio EQ. The flagship demo.

`#vanilla-js` `#web-audio` `#accessibility`

</td>
<td width="33%" align="center">

#### [instant-search-index](https://github.com/bryanhamiltondev/instant-search-index)

Client-side search from a prebuilt JSON index. Scored AND matching, weighted fields, ARIA combobox. ~1,000 pages, zero server round-trips.

`#vanilla-js` `#aria` `#search`

</td>
<td width="33%" align="center">

#### [next-show-radar](https://github.com/bryanhamiltondev/next-show-radar)

Geolocation-aware tour map. Consent-first, haversine radius, race-safe Leaflet boot. Stays excellent when they say no.

`#leaflet` `#geolocation` `#privacy`

</td>
</tr>
<tr>
<td width="33%" align="center">

#### [tour-feed-pipeline](https://github.com/bryanhamiltondev/tour-feed-pipeline)
[![CI](https://github.com/bryanhamiltondev/tour-feed-pipeline/actions/workflows/ci.yml/badge.svg)](https://github.com/bryanhamiltondev/tour-feed-pipeline/actions/workflows/ci.yml)

Bandsintown + Ticketmaster feeds normalized into one row shape, deduped, cached, pruned. CI-tested PHP 8.

`#php` `#api` `#etl`

</td>
<td width="33%" align="center">

#### [eq-visualizer](https://github.com/bryanhamiltondev/eq-visualizer)

8-bar sensory equalizer. Pure CSS, optional 1 KB injector, reduced-motion respect. Zero JS required to render.

`#css` `#accessibility` `#zero-dependency`

</td>
<td width="33%" align="center">

#### [sri-lazy-loader](https://github.com/bryanhamiltondev/sri-lazy-loader)
[![CI](https://github.com/bryanhamiltondev/sri-lazy-loader/actions/workflows/ci.yml/badge.svg)](https://github.com/bryanhamiltondev/sri-lazy-loader/actions/workflows/ci.yml)

Race-safe lazy script loader with Subresource Integrity. Concurrent-caller dedupe, timeout + cleanup. What loads Leaflet safely.

`#javascript` `#security` `#lazy-loading`

</td>
</tr>
</table>

<br>

---

## Schema &amp; SEO Tooling

*Because structured data isn't set-and-forget.*

<table>
<tr>
<td width="50%" align="center">

#### [jsonld-schema-audit](https://github.com/bryanhamiltondev/jsonld-schema-audit)
[![CI](https://github.com/bryanhamiltondev/jsonld-schema-audit/actions/workflows/audit.yml/badge.svg)](https://github.com/bryanhamiltondev/jsonld-schema-audit/actions/workflows/audit.yml)

Zero-dependency PHP CLI that audits JSON-LD across your content. Validates required properties per schema.org type, resolves `@id` references, fails CI on regressions. **Took The DJ Calendar from hundreds of Rich Results warnings to zero.**

`#php` `#json-ld` `#seo` `#ci`

</td>
<td width="50%" align="center">

#### [wp-schema-audit](https://github.com/bryanhamiltondev/wp-schema-audit)
[![CI](https://github.com/bryanhamiltondev/wp-schema-audit/actions/workflows/audit.yml/badge.svg)](https://github.com/bryanhamiltondev/wp-schema-audit/actions/workflows/audit.yml)

WordPress plugin port of the schema auditor. WP-CLI command, admin Tools page, CI self-test with pass/fail fixtures. Zero dependencies.

`#wordpress` `#plugin` `#structured-data` `#wp-cli`

</td>
</tr>
<tr>
<td width="50%" align="center">

#### [event-calendar-schema](https://github.com/bryanhamiltondev/event-calendar-schema)
[![CI](https://github.com/bryanhamiltondev/event-calendar-schema/actions/workflows/ci.yml/badge.svg)](https://github.com/bryanhamiltondev/event-calendar-schema/actions/workflows/ci.yml)

MySQL schema + PDO repository for an event calendar. Idempotent event upserts, double opt-in subscribers, query-shaped indexes. Inline design decisions.

`#mysql` `#pdo` `#data-modeling`

</td>
<td width="50%" align="center">

#### [csrf-json-fetch](https://github.com/bryanhamiltondev/csrf-json-fetch)
[![CI](https://github.com/bryanhamiltondev/csrf-json-fetch/actions/workflows/ci.yml/badge.svg)](https://github.com/bryanhamiltondev/csrf-json-fetch/actions/workflows/ci.yml)

Hardened vanilla-JS fetch wrapper. CSRF token lifecycle, header+body dual injection, single-retry on expiry, typed errors.

`#javascript` `#csrf` `#security`

</td>
</tr>
</table>

<br>

---

## The Toolbox

| Layer | What I reach for |
|-------|------------------|
| **Languages** | PHP (21+ years), JavaScript (vanilla), MySQL, JSON, Bash, HTML/CSS |
| **CMS** | WordPress since 2004, custom plugins, ACF, WP-CLI |
| **Data &amp; SEO** | schema.org / JSON-LD, PDO, Leaflet, structured-data auditing |
| **Quality** | GitHub Actions CI, fixture-based self-tests, zero-dependency by conviction |
| **Tools** | Git, FTP/SSH, phpMyAdmin, RegEx, browser DevTools, VSCode |

<br>

---

<div align="center">

**Text preferred** &middot; <a href="sms:+12014063595">(201) 406-3595</a>  
<a href="mailto:bryan_hamilton@me.com">bryan_hamilton@me.com</a> &middot; <a href="https://www.linkedin.com/in/bryanhamilton-nj">linkedin.com/in/bryanhamilton-nj</a>

<sub>*Built with PHP, vanilla JS, and the conviction that the best code is the code you don't have to install.*</sub>

</div>
