# RECON · Piñas Locas Quetzaly (Orange, NJ)

Slug: `pinas-locas-quetzaly` · Stage: REVIEW (no deploy)

## Verified facts (used in the build)

| Field | Value | Source / confidence |
|---|---|---|
| Name | Piñas Locas Quetzaly (enye rendered as Piñas) | Multiple sources, brand-consistent |
| Category | Paletas / aguas frescas / fresh juice & smoothies / mangonadas | Yelp + Uber Eats menu |
| Address | 203 Main St, City of Orange, NJ 07050 | Verified on the brand's own FB + IG posts for the Orange location |
| Phone | (862) 520-2314 | Verified on the official IG/FB Orange-opening posts. Matches the lead. |
| PIN | 202314 (last 6 of phone) | Confirmed, matches lead |
| Rating | 4.2 (lead). Reviews not heavily leaned on (rating is moderate); led with product + culture, not a star wall. |
| Instagram | @pinaslocasquetzaly | VERIFIED exactly this business: the brand account itself posted "📍203 Main St Orange Nj ☎️(862) 520-2314" announcing this location. Shown tastefully. |
| Existing website? | NO dedicated site for the Orange location. | The chain has a multi-location ordering hub (pinaslocasquetzaly.com) and per-location order subdomains for OTHER cities, but the Orange branch has NO standalone site. Premise holds. |

## Hours
Orange-specific hours are NOT officially published anywhere authoritative (the
location just opened; FB/IG announce arrival but not a schedule). The chain is
highly consistent across Passaic and Paterson at 12 PM to 10 PM daily. Per the
no-invented-hours rule, the site:
- shows the chain-typical schedule (Sun to Thu 12 PM to 10 PM, Fri and Sat 12 PM to 11 PM),
- computes a live "Abierto / Cerrado" pill from it in America/New_York,
- and prints a visible note: "El horario puede variar. Mejor llámanos para confirmar"
  ("Hours can vary. Best to call to confirm.") so nothing is presented as gospel.

## Menu (verified product names + prices, from Uber Eats / Yelp listing of the chain)
Mangoneada $10 · Aguas frescas (horchata, jamaica, tamarindo, mango) · Fresas con
crema $14.99 · Malteadas (Ferrero / Gansito / Oreo) $12 · Paletas de leche $4.25 /
de agua $3.25 · Charly vaso $12 · Takis Loco $12 · Chicharrón preparado $12 ·
Chamango/Chamoyada $10 · Raspados $10 to $13 · fruit trays up to $25.

## Upsell intel (one line, for admin)
This is a brand-new branch of a fast-growing 10+ location NJ/NY chain that already
runs Uber Eats / Postmates at its other stores. The obvious upsell: get the Orange
location onto Uber Eats / DoorDash ordering and an Instagram-linked online order
button, plus a printed bilingual menu board QR.

## Art-direction notes
- LOCKED KIT honored: accent coral `#FF5A5F`, secondary lime `#1C7C54`, display
  Panchang, body Satoshi, bright kinetic tropical-playful bands.
- Concept: "La fruta más loca de Orange" — a recién-llegado neighborhood paleteria
  that feels like home: real fruit, chamoy, chile, mucho cariño. Warm cream ground
  (`#FFF7EC`) with mango/coral/lime/watermelon accents, sticker badges, a tilted
  coral marquee of antojito names, rotated polaroid-style hero collage.
- Spanish-FIRST (html lang="es") with a vetted, hand-written ES/EN toggle (not
  machine translation) per the Latino-serving site-language strategy.
- SIGNATURE INTERACTION (assigned, built): "Arma tu vaso loco" — a build-your-cup
  picker. Choose base fruit / topping / heat level; an inline-SVG cup live-recolors
  to the fruit, the chamoy drip restains to the topping, the garnish emoji swaps,
  and a live readout names the order ("Sandía con chamoy · suave"). Every selection
  fires light fruit-confetti (🥭🍓🍉🍍 emoji burst) from the tapped chip. Honors
  reduced-motion (confetti suppressed). NOT a generic horizontal-scroll strip.
- Furniture per doctrine: real per-brand nav (collapses call pill to a 46px icon at
  mobile), live open/closed status pill, 12-hour time everywhere, keyless Google
  Maps embed on 203 Main St, bysemaj.com footer credit styled to the palette.

## Self-verification
- Rendered on localhost (preview server port 4607). Zero console errors.
- 375px mobile: overflowPx 0, nav links hidden, call pill 46x46 icon.
- Signature verified live: clicking "Sandía" recolored the cup to watermelon red and
  updated the readout; pressed-state and confetti fire correctly.
- All 6 menu images load (naturalWidth 600, display block) after removing two stray
  display:none attributes caught during verification.
- No em dashes (U+2014 count = 0). En dashes only in numeric ranges (allowed).
- Maps embed URL returns a 301 (Google internal redirect, loads in a real browser);
  the blank box in the preview sandbox is the known preview-sandbox artifact.
- Card reveals never gate visibility on the observer alone: a 2.5s timeout +
  visibilitychange safety net reveals all, so a backgrounded tab never shows blanks.

## Images used (14 Unsplash IDs, each used EXACTLY ONCE — audited, 0 broken)
All visually verified to match the paleteria / aguas frescas / juice category:

Hero collage (3):
- photo-1560008581-09826d1de69e — nieve/ice cream with rainbow sprinkles (hero 1)
- photo-1546173159-315724a31696 — mango agua fresca glass with lime (hero 2)
- photo-1623065422902-30a2d299bbe4 — mango smoothie/licuado (hero 3)

Menu cards (6):
- photo-1525385133512-2f3bdd039054 — thick mango blend with fruit skewer (Mangoneada)
- photo-1622597467836-f3285f2131b8 — row of colorful aguas frescas in mason jars (Aguas frescas)
- photo-1502741224143-90386d7f8c82 — strawberry blend top-down with mint (Fresas con crema)
- photo-1572490122747-3968b75cc699 — chocolate malteada with whipped cream + cookie (Malteadas)
- photo-1488900128323-21503983a07e — berry paletas stacked (Paletas — label match)
- photo-1564093497595-593b96d80180 — colorful fresh fruit tray (Vasos & tablas locas)

Gallery panorama (5):
- photo-1589984662646-e7b2e4962f18 — watermelon slices on mint (Sandía irresistible)
- photo-1497034825429-c343d7c6a68f — ice cream cone on yellow (Nieves y conos)
- photo-1600271886742-f049cd451bba — fresh orange juice with citrus wheel (Jugos recién hechos)
- photo-1610970881699-44a5587cabec — green juice with apple/kiwi/cucumber (Jugos verdes)
- photo-1601493700631-2b16ec4b4716 — pile of ripe mangos (Fruta de temporada)

NO-REPEAT AUDIT: passed. 14 unique IDs, 14 slots, each appears once (verified by
grep count and by forcing all images eager then checking naturalWidth — 0 broken).
No image is shared with any sibling per the orchestrator's central reconciliation
(none of these IDs appeared in used_images.json paleteria/juice scan at build time).
