# IKEJIMBA SITE — EVOLUTION PLAN (v2)

**Site:** Ikejimba Age Grade Association — *Aku Ruo Ulo* (Akorufu Alayi, Abia State)
**File:** `index.html` (single-file site; images under `assets/`)
**Zip:** `ikejimba-aku-ruo-ulo-site-EVOLVED.zip`

---

## 1. Design evolution — premium glassmorphic cinematic layer

New `<style id="glass-evolution">` block (no base CSS removed — pure additive):

- **Floating glass-island nav** — detached pill, `blur(18px) saturate(1.25)`, gold hairline, inner-top highlight.
- **Gold-thread glass cards** — pillars/events/steps/bcards: translucent layered gradient + hairline gold border + inset highlight + deep shadow; hover lift with elastic easing.
- **Double-bezel image frames** — `.shell` frames: glass padding bezel, gold hairline, top light-catch line, hover depth.
- **Cinematic aurora mesh** — subtle gold/emerald/ruby radial gradients layered under every section and page hero.
- **Film grain** — fixed non-scrolling SVG-turbulence layer at 5% opacity (auto-disabled under reduced motion).
- **Buttons** — gold pill with nested trailing-arrow circle ("button-in-button"), ghost variant.
- **Inputs, chips, gallery tiles, footer** — refined to the same radius/hairline language.
- Accessibility kept: focus-visible outlines, reduced-motion gates, aria labels unchanged.

## 2. Content evolution

- **Home:** new "Working Network" image band + 4-photo rail; events rail + Gallery cross-link.
- **About:** "Bound by Birth, Growing Into an Institution" band + leadership photo rail.
- **Age Grades:** "The Ladder of Responsibility" band (young grade → mid years → elder council).
- **Events:** festival scene rail with captions.
- **Projects:** 4 full program subsections (Green Drive, Education Fund, Community Works, Enterprise Network), each with editorial copy + photo band.
- **Contact:** send button restyled; footer quick-nav added.
- Reworded dev-notes; kept "Name to be added" placeholders and `info@example.org` (no facts invented).

## 3. Blog — 7 original essays

`#blog` listing + `#post-0…6` reader pages in the hash router (`route()` extended, dynamic META titles/descriptions per post, related-stories strip, back/next nav).

1. **CULTURE** — The Return of the Returning (cultural engagement)
2. **TECHNOLOGY** — ICT and AI Are the New Soil (early youth empowerment; links Masakhane)
3. **CAREERS** — SAP and the Quiet Skill (SAP path for Nigerian youth; links learning.sap.com, community.sap.com)
4. **EDUCATION** — Scholarships: The Doors (fully-funded schemes + official links: Chevening, Commonwealth, DAAD, Erasmus Mundus, Fulbright, Mastercard Foundation, PTDF, NLNG)
5. **WORK** — The Virtual Workforce — Nigeria in Context
6. **COMMUNITY** — The Digital Age Grade (WhatsApp meets umunna)
7. **IMPACT** — Aku Ruo Ulo in the 21st Century

All copy original to this site; external links point to official domains only; no invented statistics, no fake dates.

## 4. Gallery — real media

20 gallery slots mapped to 17 local photos by title (Events/Masquerade/Environment/Community/Videos — video items keep play badge as "coming soon").

## 5. Delivery & verification log

- All images verified: HTTP 200, JPEG magic bytes, ≤300 KB (CONTENT-GUIDE rule).
- 22 photos downloaded to `assets/` (see IMAGE-ATTRIBUTIONS.md).
- Syntax check: all 3 inline scripts pass `node --check`.
- Headless browser (Edge/Playwright) smoke test: **0 page errors, 0 console errors, 0 broken images** across 11 routes (home, about, grades, events, projects, gallery, contact, blog, post-0, post-3, ev-0) + mobile 390px pass.
- Screenshots verified: glass nav, aurora heroes, blog cards with real photography, orbit gallery with real media.

## 6. Next steps for the association (optional)

- Replace "Name to be added" leaders + add WhatsApp/phone/bank details in Contact.
- Swap video gallery items for real mp4 files (`items` array keeps `video:` hook).
- Add more photos: drop files in `assets/` + extend the `SRC` map in the gallery script.

## 7. Social row (added 2026-10-23)

- Six linkable brand icons in the footer (between foot nav and motto): Facebook, Instagram, X (Twitter), TikTok, WhatsApp, Telegram.
- Icons are inline SVG glyphs from the official Simple Icons set (no network dependency), rendered from one editable SOCIALS array in script 1 - swap name, URL and path there to change links.
- Links: 	arget="_blank" rel="noopener noreferrer", ria-label per network, gold disc hover/focus glow, prefers-reduced-motion-safe (CSS transitions only), keyboard focus outline.
- Placeholder state: links point to platform root URLs until the association shares its handles (no facts invented).
- Verified: all scripts pass 
ode --check; live check - 6 links with correct href/target/rel/SVG, 0 console/page errors; footer + hover + 390px mobile screenshots reviewed.

## 8. Alayi location map + live weather (added 2026-10-23)

- Contact view: the Find-us column now holds an interactive Leaflet map of Akorufu, Alayi (verified OSM node 501492582 - Alayi village, Bende LGA: 5.7333, 7.6000) with a gold-ring coverage glow, Ikejimba-emblem pin, popup label, and plain-OSM raster tiles CSS-filtered to the black/gold palette (no API keys anywhere).
- Below the columns: full-width live weather strip for Alayi powered by Open-Meteo (current temp, condition, feels-like, humidity, wind + TODAY + 3-day forecast) with hand-drawn gold WMO glyph icons; 	imezone=auto keeps local days.
- Graceful degradation: no network / CDN blocked -> map falls back to a themed "MAP UNAVAILABLE" panel with the links below it untouched; weather fetch failure shows a themed retry note. Links: Open in OpenStreetMap + Get directions (Google Maps query).
- Lazy loading: Leaflet CSS/JS + first weather fetch trigger only when the map scrolls into view (IntersectionObserver, one-shot).
- Legal lines: map attribution @ OpenStreetMap contributors (Leaflet control + strip footer); data attribution OPEN-METEO.COM.
- Verified live: tiles load, marker/emblem render, computed tile filter applied, live readout 30C overcast feels 34C humidity 71% wind 8 km/h, 4 forecast days correct weekday sequencing (TODAY/SAT/SUN/MON); 0 console errors, 0 failed requests; desktop + 390px mobile screenshots reviewed (map + weather).

### 8b. Landing page vitrine + global social cluster (added 2026-10-23)

- The map + weather were promoted from the contact view to a dedicated landing section: Home Ground - Akorufu Alayi, Abia State (#h-ground, data-v=home, placed between About and Events). Contact keeps its Find-us text + links.
- Aerospace-luxe articulation per the high-end-visual-design skill: double-bezel vitrine (outer gradient shell with hairline border + inner machined plate), Z-axis cascade (perspective stage, floor at translateZ(26px), floating weather observatory at translateZ(64px) overlapping the map plate), gold hairline arc rings around the stage, engraved data plates (region + verified coordinates 05 44 00 N / 07 36 00 E), corner compass dial, staggered float-up entrances (cubic-bezier(.32,.72,0,1), floor delay .18s / side delay .42s).
- Pointer tilt: on pointer:fine only and skipped under reduced motion, the stage reads --rx/--ry custom props (max ~3deg) so the map stays interactive while layers parallax; flattened below 900px.
- Live-verify 2026-10-23: 0 console errors, tiles 9 (desktop) / 6 (mobile), emblem pin, real Open-Meteo readout (26-27C overcast, feels 31-33C, humidity 87-89%, wind 10-12 km/h), TODAY/SAT/SUN/MON forecast correct; graceful offline fallback state confirmed live during a network drop.
- Social row elevated (46px radial-sheen discs, hover ring halo, gold hairline top rule) AND mirrored into the fixed nav as .soc-mini (32px rings, populated from the same SOCIALS array in script 1) - icons now visible on every page without scrolling; soc-mini hides below 1160px (footer row covers small screens).
