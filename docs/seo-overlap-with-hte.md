# HMS and hteny.com: search overlap audit

Audited Oct 29, 2026. Read-only: nothing changed on hteny.com or on the HMS site.

## Short answer

HMS does not hurt HTE today. It is one page on a preview URL, its copy is original (the only shared text is the showroom address and one FAQ question), and its structured data already credits Home Technology Experts as the provider.

The overlap exists, though, and most of it comes from HTE's side: **hteny.com already calls itself "Hamptons Motorized Shades."** `/windows` is titled "Hamptons Motorized Shades" and `/automated-shades` is titled "Hamptons Motorized Shades + Lighting Controls." Once HMS launches on its own domain, Google will see two sites claiming the same name. HTE also competes with itself: four pages target the main "motorized shades Hamptons" search, and several articles are duplicated.

## What could not be checked

- **Search Console.** I could not get ranking data. The HLD config lists Search Console as `"configured": false`, there is no `gsc.py` in the HLD repo (`C:\mig\hld-site`), and searching the machine for the service account key was blocked. Until Search Console is connected for `sc-domain:hteny.com`, nobody knows which HTE shade page actually earns clicks. That matters for every recommendation below that says "pick a winner."
- **Live rankings.** A general web search for "motorized shades Hamptons" and "Hamptons Motorized Shades" returned Audio Den, Budget Blinds of the Hamptons and Makris, plus one HTE article. That search tool is not Google, so treat it as a rough signal only.
- **Google Business Profile.** I can't see your GBP account. See section 5.

## 1. HMS today

One page, preview at https://hms-site-rfckhhik.onslate.com/. No final domain yet.

| Field | Value |
|---|---|
| Title | Hamptons Motorized Shades \| Custom Motorized Window Treatments |
| Meta description | Custom motorized shades, drapery and exterior screens for Hamptons homes. Design consultation, precision measuring, white-glove installation and smart-home integration from Westhampton to Montauk. |
| H1 | Effortless light, from sunrise to sunset. |
| Eyebrow | Custom Motorized Window Treatments · East End |
| Sections (H2/H3) | Collections (roller, drapery, exterior screens, blackout, Roman and woven, skylights), Smart Living, Process, Our Work, Service Area (10 towns), HTE services, FAQ, Contact |
| Schema | `Service` "Hamptons Motorized Shades", provider = Home Technology Experts at 241 County Rd 39A, Southampton |
| Target phrases | Hamptons motorized shades (brand), motorized shades Hamptons / East End, motorized drapery, exterior screens, custom window treatments, town names |

Housekeeping gaps (separate from overlap): no canonical tag, no Open Graph tags, no robots.txt or sitemap.xml, and 7 em dashes in the copy, which breaks the HTE copy rule.

## 2. HTE shade pages (live, Oct 29)

28 shade-related URLs in https://hteny.com/sitemap.xml (734 URLs total).

| URL | Title | H1 | Main search target |
|---|---|---|---|
| /motorized-shades | Motorized Shades \| Upgrade Your Home Today | Light. Managed. | motorized shades Hamptons and NYC |
| /automated-shades | **Hamptons Motorized Shades** + Lighting Controls | Motorized Window Treatments | motorized shades Hamptons |
| /windows | **Hamptons Motorized Shades** | Light, Mastered. Privacy, Perfected. | Hamptons motorized shades |
| /lighting-control-and-motorized-shading | Lighting Control & Motorized Shades for Luxury Homes | Lighting Control & Motorized Shades That Make Home Feel Natural | lighting control + shades |
| /hamptons-shade-store | Lutron Palladiom Dealer Hamptons The Shade Store Alternative | MASTER YOUR LIGHT. | Shade Store Hamptons, Palladiom dealer Hamptons |
| /nyc-shade-store | Manhattan Shade Store Alternatives \| Luxury Lutron Shading NYC | MASTER YOUR VIEW. | Shade Store NYC |
| /lutron-palladiom-shades | Lutron Palladiom Shades | Lutron Palladiom Shades | Palladiom shades |
| /lutron-palladiom-nyc | Lutron Palladiom Shades Installation \| New York & Hamptons | Lutron Palladiom. | Palladiom installation NY and Hamptons |
| /lutron-palladiom-drapery-hamptons | Lutron Palladiom Drapery | Lutron Palladiom Drapery Arrives in the Hamptons & Manhattan | Palladiom drapery |
| /hunter-douglas | Hunter Douglas Shade Dealer | (none) | Hunter Douglas dealer |
| /lutron-shade-gallery | Lutron Luxury Shade Gallery | Experience the Lutron Shade Gallery | Lutron shades photos |
| /what-should-i-consider-when-selecting-motorized-window-treatments-for-my-home | Selecting Motorized Window Treatments \| HTE Buyer's Guide | Selecting Motorized Window Treatments. | choosing motorized window treatments |
| /case-studies/motorized-shade-project-takeover | Costly Shade Installation Mistakes to Avoid | When Expertise Matters: Restoring Precision in a Modern Waterfront Home | shade installation mistakes |
| /control4-videos/v/how-to-control-shades-blinds-on-contol4 | How to control shades & blinds on Contol4 | (none) | Control4 shades how-to |

Blog posts (14): choosing-motorized-window-treatments, lutron-palladiom-motorized-drapery, wiring-for-motorized-shades-in-new-construction, wiring-for-motorized-shades-in-new-construction-1, wired-vs-battery-powered-motorized-shades..., wired-or-wireless-how-to-choose-a-motorized-shade-solution, smart-shade-fabrics, introducing-lutron-triathlon-select-shades, experience-the-future-of-shading-with-aura-illuminated-shades..., motorized-shades-offer-comfort-privacy-and-energy-efficiency, dont-believe-these-myths-about-motorized-shades, 4-things-to-consider-when-choosing-motorized-shades, bring-the-wow-factor-to-your-design-projects-with-motorized-shades, 4-motorized-blinds-that-add-more-luxury-to-your-life.

## 3. Overlaps

| # | Search | HMS | HTE | Severity |
|---|---|---|---|---|
| A | "Hamptons Motorized Shades" (the brand name) | Title, logo, schema name | /windows title, /automated-shades title | **High.** Two domains claim one name. |
| B | motorized shades Hamptons / East End | Whole page | /motorized-shades, /automated-shades, /windows, /lighting-control-and-motorized-shading | **High**, mostly HTE against itself |
| C | motorized drapery Hamptons | Motorized Drapery card | /lutron-palladiom-drapery-hamptons, blog/lutron-palladiom-motorized-drapery | Medium |
| D | custom / motorized window treatments | Title, eyebrow | /automated-shades H1, buyer's guide pages | Medium |
| E | Shade Store alternative Hamptons, Palladiom dealer | Not targeted | /hamptons-shade-store, /lutron-palladiom-* | None now. Keep it that way. |
| F | wired vs battery, pre-wiring, fabrics, myths | FAQ touches battery life and retrofits | 6 blog posts | Low |
| G | Copy reuse | Original | Original | None (only the address and "can motorized shades be added to an existing home") |

HTE duplicates found along the way (these split HTE's own ranking power more than HMS does):
- /what-should-i-consider-when-selecting-motorized-window-treatments-for-my-home and /blog/choosing-motorized-window-treatments answer the same question.
- /blog/wiring-for-motorized-shades-in-new-construction and its `-1` copy.
- /blog/wired-vs-battery-powered-motorized-shades... and /blog/wired-or-wireless-how-to-choose-a-motorized-shade-solution.
- /lutron-palladiom-shades, /lutron-palladiom-nyc and /hamptons-shade-store all chase "Palladiom Hamptons."
- /lutron-palladiom-drapery-hamptons and /blog/lutron-palladiom-motorized-drapery.

## 4. Recommendations, ranked

**1. Give the brand name to HMS. Take "Hamptons Motorized Shades" out of HTE's titles.** (Overlap A)
Retitle HTE `/windows` and `/automated-shades` to describe what HTE does, for example "Motorized Shades and Window Treatments, Hamptons and NYC | Home Technology Experts." This is a title change only: same URLs, no redirects, low risk. Do it when HMS goes live on its own domain.

**2. Split the work by intent instead of fighting over one search.** (Overlaps B, C, D)
- **HMS owns** the brand name and the window-treatment shopper: someone choosing fabrics, drapery, exterior screens and a design consultation for one home. Lean into collections, fabrics, the in-home visit and the towns.
- **HTE owns** the integrator and technical searches: Lutron Palladiom and Hunter Douglas dealer pages, Shade Store alternatives, shades with lighting control, pre-wiring for new construction, wired vs battery, NYC, commercial and the takeover case study.
- **Contested:** the generic "motorized shades Hamptons." Leave it with HTE `/motorized-shades` for now, because HTE has the authority and HMS is a new single page. Revisit after 90 days of Search Console data on both sites. If HMS starts outranking HTE there, move HTE's page toward "motorized shades and smart-home integration" rather than letting both sites chase the same phrase.

**3. Connect Search Console before consolidating anything.** Give the read-only service account access to `sc-domain:hteny.com` and to the HMS domain at launch. Without it, a redirect could remove the one shade page that actually earns traffic.

**4. Consolidate HTE's own duplicates** (listed in section 3) once Search Console shows which version wins: 301 the weaker page into the stronger one and merge any unique content. This is the biggest SEO gain in the shade category, and it doesn't depend on HMS.

**5. Link once, with plain or brand anchors.**
- HTE to HMS: one contextual link from `/motorized-shades` (and optionally an "Our studios" line on the About page), anchored "Hamptons Motorized Shades." No sitewide footer link and no keyword anchors such as "best motorized shades Hamptons."
- HMS to HTE: keep the existing links (service names, "Discover HTE," showroom). Add one or two depth links where they help the reader, such as "the Palladiom collection at Home Technology Experts" or the pre-wiring article in a new-construction FAQ answer.

**6. HMS housekeeping before launch** (needs approval, not done): add a canonical tag pointing to the final domain, keep the onslate.com preview out of the index, add robots.txt, sitemap.xml and Open Graph tags, and replace the 7 em dashes. The title and meta description are good as written.

## 5. Google Business Profile

Nothing in the HMS repo creates a profile, and the schema correctly names Home Technology Experts at 241 County Rd 39A as the provider rather than declaring HMS a separate local business. Keep it that way. **Do not create a separate Google Business Profile for HMS at HTE's Southampton address.** Google allows one profile per business per location, and a second brand name at the same address risks suspension of both profiles, including HTE's. If HMS needs map presence, add "motorized shades" and "window treatments" as services or categories on HTE's existing profile, and use the HMS site as a link in posts. I could not see the GBP account, so check whether anyone has already started a "Hamptons Motorized Shades" listing and remove it if so.
