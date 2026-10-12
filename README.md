# Synthetic demo sites

Fictional businesses for demonstrating and testing the Local Business Prospect Qualifier and the Web Design Leads Actor.
None of these companies exists. Phone numbers use the fictional 555-01xx range and emails use the
reserved `.example` domain. Pages never load third-party scripts in a browser: tool markers are inert
(`type="text/plain"` scripts or local files) and forms do not submit anywhere.

| Folder | Demonstrates |
|---|---|
| `summit-ridge-roofing/` | ASSESSED: mailto/tel links, contact form, WordPress/Divi/GA4 markers, strong roofing terms, same-site booking page |
| `clearwater-plumbing/` | ASSESSED with schema.org JSON-LD (`Plumber`), a duplicate page (`service-area.html` = homepage) and a soft-404 page (`services.html`) |
| `brightside-hvac/` | REACHABLE_NO_SUPPORTED_EVIDENCE: JavaScript-only shell with no server-rendered content |
| `parked-domain-demo/` | REACHABLE_NO_SUPPORTED_EVIDENCE: parked/for-sale page |
| `oldtown-plumbing/` | Web Design Leads: an outdated hand-built site (HTML 4 tables/font/marquee, no mobile viewport, © 2013, old jQuery and Universal Analytics markers, phone without tap-to-call, no contact form) |

Hosted on GitHub Pages at https://mortenmyrmel03.github.io/lbpq-demo-sites/ from a separate public
repository that contains only these fictional pages. The Actor itself is not part of this repository.
