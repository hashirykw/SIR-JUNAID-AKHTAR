# Sir Junaid Akhtar · Pakistan Studies website

A multi-page site for Sir Junaid Akhtar: Cambridge O Level Pakistan Studies 2059 and IGCSE 0448, Karachi and online. Every page is one self-contained HTML file in one flat folder: styles, scripts, the portrait and the map are all inside each page. No admin panel, no database.

## Files

| File | What it is |
|---|---|
| `index.html` | Home: hero with portrait over live survey contours, the interactive 2059 atlas (37 places on a map of Pakistan, each tied to its Paper 1 key question and Paper 2 topic), the 1707–1999 timeline, the “explain, don’t describe” answer ladder, both papers, the 2028 syllabus change, his notes, where he teaches |
| `courses.html` | Paper 1 and Paper 2 in detail, assessment objectives, the full 2028–2030 comparison, how classes run |
| `syllabus.html` | All 16 Paper 1 key questions and 8 Paper 2 topics with key points and terms, a progress tracker and a search box |
| `past-papers.html` | Every session 2018–2026 (PapaCambridge + mirror), score log with grade estimates and trend chart, November 2024 grade thresholds, exam timer with focus mode |
| `study-room.html` | Map quiz (distance-scored), timeline drill, 24 key-term flashcards, 14-mark answer planner |
| `about.html` | His method, his notes, where he teaches |
| `contact.html` | Enrolment form that opens a ready-written WhatsApp message, FAQ |
| `404.html` | Not-found page |
| `junaid-akhtar.jpg` | Share image for WhatsApp and social previews (1200 × 630) |
| `vercel.json`, `robots.txt`, `sitemap.xml` | Hosting and search files |

Every page also has: light and dark themes (light is the default), a `/` or Ctrl K search palette over pages, key questions, places and tools, an “Ask the desk” helper that answers common questions and hands anything else to WhatsApp, smooth scrolling and view transitions.

## Confirm with Sir Junaid before launch

Everything on the site comes from a public source. These are the points to check:

1. **WhatsApp 0300 218 7567.** Taken from the header of his published Pakistan Studies notes, which may be old. To change it, find and replace `923002187567` and `0300 218 7567` across all the HTML files.
2. **“Cambridge-trained in the UK” and the Cambridge exam team.** From his Facebook and Instagram bios and an X post. Confirm the wording.
3. **Director of SWK Solutions / Cambridge Online.** From his Instagram bio and the Cambridge Online faculty page.
4. **Portrait.** Cut out from the Cambridge Online portrait. A sharper photo will look better.
5. **Meritorious College (AKU Board), Gulshan.** A June 2026 video from them came up under his name but is not on the site. Add it if he teaches there.
6. **Fees and timings** are never shown; every such question goes to WhatsApp.
7. **Domain.** Canonical links, the sitemap and robots use `https://sir-junaid-akhtar.vercel.app`. Find and replace if you use another domain.

## Content notes

- Key-question wording follows the current Cambridge 2059 syllabus; the bullet points, card definitions, answer paragraphs and planner questions were written for this site and are labelled as such.
- The 2028 comparison is from Cambridge’s 2059 syllabus for 2028–2030.
- Grade thresholds are Cambridge’s November 2024 2059 table.
- Map outlines are Natural Earth (public domain); rivers are drawn as schematic courses. Boundaries are shown as administered, with Jammu & Kashmir labelled as disputed territory.
- Past papers link to session pages on PapaCambridge’s public archive (© UCLES), with PastPapers.co as a mirror.
- Visitor progress (tracker, scores, streaks, theme) is saved in the visitor’s browser only.

## Deploy

Upload every file to the root of a GitHub repo and import it on Vercel (Framework preset: Other, no build command). `vercel.json` turns on clean URLs, so `/courses` serves `courses.html`.

Website by Nexlyr Solutions.
