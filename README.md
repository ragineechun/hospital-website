# Hospital Website (Marathi)

A five-page informational website in Marathi for Late Sakharam Kundlik Kodre Maternity Home, a Pune Municipal Corporation hospital in Mundhwa, Pune. It is built with plain HTML, CSS and a little JavaScript, with no frameworks.

Built by Raginee Chunkhare during a summer internship at the hospital (10 June – 10 July 2025), as part of the MIT School of Computing Summer Internship 2025 programme.

## About the internship

The goal was a simple, reliable, Marathi-friendly website that presents the hospital's departments, facilities, timings and health programs to the local community.

| Week | Work |
|---|---|
| 1 | Data collection, staff interviews, floor mapping |
| 2 | Marathi translation, floor-plan diagrams, wireframes |
| 3 | HTML structure and CSS styling of the pages |
| 4 | Browser testing, image optimization, documentation and handover |

What I learned:

- Rendering Marathi text correctly with Unicode and Devanagari web fonts.
- Translating medical terms with help from hospital staff.
- Responsive layouts with CSS Grid and Flexbox.
- Testing across Chrome, Firefox and Edge, and keeping pages light for slow connections and older devices.

Possible next steps: online appointment booking, real-time bed availability, emergency alerts and a patient feedback form.

## Pages

| Page | File | What it shows |
|---|---|---|
| Home | `index.html` | Introduction, key numbers, core values |
| Departments | `departments.html` | OPD, IPD, family planning, OT, sonography, X-ray, lab and pharmacy, each with a details pop-up |
| Infrastructure | `infrastructure.html` | Floor map and list of facilities |
| Gallery | `gallery.html` | Before/after photos with category filter buttons |
| Programs | `programs.html` | Hospital and national health programs as expandable cards |

## Features

- Entire site in Marathi (Devanagari), marked up with `lang="mr"`.
- Responsive layout that works on phones and desktops.
- Gallery filtering and program cards driven by vanilla JavaScript.
- Shared navigation bar and footer with contact details and opening hours.

## Tech stack

HTML5, CSS3 (Flexbox, Grid, media queries), JavaScript.

## Run it locally

No setup needed. Download the repository and open `index.html` in a browser.

## Project structure

```
index.html
departments.html
infrastructure.html
gallery.html
programs.html
CSS_SHEETS/       one stylesheet per page
images/           photos used on the site
```
