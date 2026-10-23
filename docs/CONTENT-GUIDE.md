# Content guide (no coding tools needed, just a text editor)

Open `index.html` and use Find (Ctrl+F) for the keywords below.

| To change | Search for | Notes |
|---|---|---|
| Event names, stories, programmes | `const EV=[` | Each event has t (title), tag, m (month), s (story), sch (schedule), bring (list). Keep the quotes and commas. |
| Gallery photos and videos | `const items=[]` and `src:''` | Gallery items are generated from the `T` list. To use real media, add objects with `src:'assets/photo1.jpg'` or `video:'assets/clip.mp4'`. |
| Page titles and descriptions (SEO) | `const META=` | One entry per page. |
| Leadership names | `Name to be added` | Replace per role. |
| Contact email | `info@example.org` | Appears in the footer button, RSVP links and contact form. |
| Home headline text | `AKU RUO ULO` | Slide 2 copy sits in `id="copy2"`. |
| Domain / canonical link | `rel="canonical"` | Uncomment and set your real address. |

Tips: put images in an `assets/` folder next to `index.html`, keep images under 300 KB (use WebP), and always write descriptive text for each photo (accessibility and SEO).
