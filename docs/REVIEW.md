# Honest project review

**Important limit of this review:** the site was built and syntax-checked, but it was never viewed in a real browser by the builder. Visual quality, animation timing and the WebGL slide are unverified. Ratings below are of the code and design intent, not of a tested screen recording. Test on a phone and a laptop before launch.

## Scorecard (out of 10)

| Area | Score | Honest comment |
|---|---|---|
| Brand and cultural concept | 8 | Strong idea: Aku Ruo Ulo told as a doorway opening on light; Uli, Nsibidi and cowrie references are respectful and meaningful. |
| Hero slide 1 (your original) | 8 | Polished; kept as you built it. |
| Hero slide 2 (Golden Doorway) | 6.5 (unverified) | Concept is strong; WebGL carving, lighting and timing are untested. Needs a real-device pass. Gold-on-oxblood is a safe luxury palette. |
| Information architecture | 7.5 | Clear menu and pages (About, Age Grades, Events, Projects, Gallery, Contact). Event pages are data-driven. |
| Content quality | 5 | Structure is good but most copy is generic sample text. No real history, dates, names, photos or numbers. A premium NGO site lives on real stories and proof. |
| Gallery | 6.5 | Filterable 3D orbit plus mosaic plus lightbox is inventive. But it shows generated placeholder art, not photos or video; no captions, years or albums yet. |
| SEO | 5.5 | Good metadata and structured data, but all pages share one URL (hash routing), so search engines mostly see the home page. Needs real separate pages, sitemap, robots, canonical. |
| Performance | 6 | Single 450 KB file with embedded logo and heavy animations; WebGL only runs when visible. No image optimisation pipeline yet because there are no real images. |
| Accessibility | 6 | Skip link, semantic headings, labels, reduced-motion support. Needs contrast checks, keyboard testing of the 3D gallery, focus styles and alt text for real photos. |
| Mobile experience | 6 | Responsive CSS and mobile menu exist, but untested; 3D scenes may need lighter settings on low-end phones. |
| Trust and conversion | 4 | No donation system, member portal, newsletter, social links, press, partners or testimonials yet. |
| Maintainability | 5 | Everything in one file is easy to deploy but hard to scale. Content lives inside JavaScript arrays. |

**Overall: about 6 out of 10 today.** It is a strong creative prototype with a clear identity, not yet a finished premium NGO website. The gap to 9/10 is mostly real content, real media, separate SEO pages, and device testing, not more animation.

## What premium NGO sites do that this site doesn't yet
1. Lead with real, human photography and short film.
2. Show measurable impact (trees planted, scholarships given, projects completed) with dates.
3. Give every event and project its own indexable page with a story, gallery and call to action.
4. Offer clear ways to give, join and stay informed (donate, member sign-up, newsletter).
5. Publish transparently: annual reports, leadership bios, finances.
6. Keep motion restrained and purposeful, with fast load and strong accessibility.

## Risks to fix before launch
- Test slide 2 in Chrome, Safari and a mid-range Android phone.
- Replace all placeholder emails, names and bank details.
- Do not publish sample event dates as facts.
- Get written consent before showing members' photos, especially children.

## Roadmap
**Phase 1 (1 to 2 weeks) — make it real:** real photos and videos, real event dates, leadership names, history, contact details, device testing.
**Phase 2 (2 to 4 weeks) — make it findable:** split into real pages, sitemap, robots, canonical tags, Event structured data, Google Business and social sharing images, image optimisation to WebP.
**Phase 3 (1 to 3 months) — make it run itself:** CMS for events and gallery, member directory with login, online dues and donations, newsletter, event RSVP with email confirmation.
**Phase 4 (ongoing) — evolve:** yearly impact report, diaspora chapters map, live-streamed events, Igbo and English language toggle, archive of past years.
