# Prompt scripts (copy, paste, fill the brackets)

Use these with Claude (attach `index.html` each time).

## 1. Test and polish what exists
```
Attached is the Ikejimba Age Grade Association site (Aku Ruo Ulo). Review slide 2 (the WebGL Golden Doorway) and the whole home page for visual quality at 390px, 768px and 1440px widths. List every visual or timing flaw, then fix them without changing the concept. Keep the CSS fallback working. Report what you changed.
```

## 2. Replace placeholder content with real content
```
Using the facts below, replace every sample text in the attached site: history [paste], founding year [__], leaders [names and roles], events [name, month, venue, programme], projects [list with results], contact [email, phone, address, social links]. Do not invent facts. Mark anything missing with a visible TODO list at the end of your reply.
```

## 3. Add a new event page
```
Add a new event to the EV array in the attached site: title [__], tag [__], date [__], venue [__], story [__], schedule [time and item list], what to bring [list]. Keep the existing format, update the home event cards, the events list and the page metadata. Add Event structured data (schema.org) with the real date and location.
```

## 4. Build the real gallery
```
Wire these media files into the gallery of the attached site: [list file names, category, title, year, caption]. Use real images (WebP, lazy-loaded, with alt text) and videos (poster image, no autoplay). Add album filters by year and category, and keep the 3D orbit and mosaic views. Replace the generated placeholder art.
```

## 5. Split into real SEO pages
```
Convert the attached single-file site into a multi-page static site: index.html, about.html, age-grades.html, events.html, one page per event, projects.html, gallery.html, contact.html. Share one style.css and one script.js. Give each page its own title, meta description, canonical URL for [domain], Open Graph image, and structured data. Add sitemap.xml and robots.txt. Keep all animations.
```

## 6. Content management system
```
Design and build a simple content management setup for this site so non-technical members can add events, photos and news. Recommend the best option for a volunteer team with a small budget (for example a headless CMS or a spreadsheet-driven approach), explain trade-offs in plain language, then implement it: content types for Event, Project, GalleryItem, NewsPost, Leader. Include a step-by-step guide for the secretary.
```

## 7. Performance and accessibility audit
```
Audit the attached site for Lighthouse performance, accessibility (WCAG 2.2 AA), and mobile usability. Fix: image sizes, font loading, animation cost on low-end phones, keyboard access to the 3D gallery, colour contrast, focus outlines, reduced-motion behaviour. Give before and after notes.
```

## 8. Member portal and dues
```
Add a members area: sign-up and login, member directory by age grade and city, dues payment and receipts, and an announcements feed. Recommend a secure approach, list what data we must protect, and add a privacy policy page suitable for Nigeria (NDPA).
```

## 9. Donations and trust
```
Add a donation page for the Ikejimba Age Grade Association: one-off and monthly gifts, project-specific funds (Green Drive, Education Fund), clear receipts, and a transparency section showing how funds are used. Use [payment provider]. Add testimonials, partner logos and an annual report download.
```

## 10. Yearly evolution
```
Create this year's update of the site: new hero story for [year/theme], impact numbers [list], a recap film section, photo albums for the year's events, and an archive page for previous years. Keep the visual identity and the Aku Ruo Ulo doorway concept.
```

## Rules to add to any prompt
- Never invent facts, dates, names or statistics.
- Keep the black, gold and oxblood palette and the Uli and Nsibidi motifs.
- Keep reduced-motion support and a non-WebGL fallback.
- Ask for consent notes whenever photos of people are involved.

## Social links rule
- Footer social icons live in the SOCIALS array (script 1): [name, url, svg path].
- Currently placeholder platform-root URLs - never invent @handles; ask the association for the real page URLs before filling them.
