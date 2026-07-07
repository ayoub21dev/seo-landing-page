# SEO Landing Page — Section Spec

Blueprint for the **SEO offer landing page** on rhillane.com (+ country variants). It maps the copy modules of the master ([RHILLANE_SEO_v4.4_MASTER_FR_2026-05-14.html](../../../RHILLANE_SEO_v4.4_MASTER_FR_2026-05-14.html), tab *Modules de pages de conversion*) onto the locked **12-block CRO sequence** ([design-system/components.md](../../../design-system/components.md)) using the copy method in [cro-playbook.md](cro-playbook.md).

> **Rule:** the LP is a CRO condensation of the master, not a new document. Every word of copy already exists in the master — pull it via the Copy buttons, don't rewrite it. Target volume: **2 500–3 500 words**.

***

## Page-level requirements (before any section)

From the master's "Exigences SEO" intro (LP tab):

* **Primary keyword** placed in: first H1 of the DOM, first 100 words, ≥3 H2s, URL slug (`/agence-seo-maroc/` pattern), title tag (≤60 chars), meta description (≤155 chars, keyword in first 90), main image alt + 2 secondary alts, 3–5 internal inbound links.
* If the commercial H1 doesn't fit the keyword: discreet SEO H1 at top of DOM + the commercial headline styled as visual H2. **One H1 per page.**
* **8–15 NLP/semantic terms** woven into body copy (extract from RankNinja clustering).
* Schema: `Service` / `LocalBusiness` / `FAQPage` as flagged per block below, + `Organization` in footer.
* **Locales:** country-based multisite per [brand-guide §7](../../../brand/brand-guide.md) — 4 hreflang alternates + `x-default`.
* **Named-client rule:** only Iman Dental, Mariner Underwear, Lily Billy, Maes Débouchage, Écran Moderne appear by name. Sotheby's/Shatao et al. stay anonymized ("marque internationale d'immobilier de luxe, opérations Maroc").
* **Brand:** tokens from [tokens.md](../../../brand/tokens.md) only. Poppins, closed 8-color palette, no red for negatives, one gradient keyword per heading, no external JS libs.

> ⚠️ **Open decision — currency.** The CRO playbook says MAD HT (website-creation, Morocco market); the SEO master prices in **€ HT** across all markets. Recommendation: follow the SEO master (€ HT), localizing per country variant. Confirm before build.

***

## The 12 blocks

| # | DS block | Master source (tab → module) | Status |
|---|----------|------------------------------|--------|
| 1 | Header | — (DS pattern) | Required |
| 2 | Hero | LP Module 1 | Required |
| 3 | Trust bar | LP Module 1 (trust banner) + Module 10 (logos) | Required |
| 4 | Problem stack | LP Module 2 | Required |
| 5 | Méthode | LP Module 3 (RankNinja) | Required |
| 6 | Engagements / differentiators | LP Modules 5b + 5c | Required |
| 7 | Selected work | LP Module 4 | Required |
| 8 | Pricing + value + bonuses | LP Modules 5 + 6, tabs *Tarification* & *Bonus* | Required |
| 9 | Garanties | LP Module 7, tab *Garantie* | Required |
| 10 | FAQ | LP Module 8, tab *Objections* | Required |
| 11 | Final CTA + form | LP Module 9 | Required |
| 12 | Footer | LP Module 10 | Required |

### 1. Header

DS pattern: sticky, shrinks on scroll, logo + 3 nav links + `btn-cta`.
* CTA label: **« Demander mon plan de revenus SEO »** — same offer as hero (hot CTA #1 of the 2 above the fold).
* Nav links anchor to: Méthode (block 5) · Résultats (block 7) · Tarifs (block 8).

### 2. Hero — pain reframe + free value stack

Source: **Module 1**. Centered, dual CTA, gradient on one keyword.
* **H1**: pick one of the master's 3 options (A: « Davantage de clients depuis Google. Chaque mois. Garanti par contrat. » / B: competitor loss / C: CAC −40 % guarantee). A is the default; B/C are A/B test variants.
* **Sub**: the master's mechanism+guarantee paragraph (top-5 in 6 months written into contract, or mission continues free).
* **Primary CTA**: « Demander mon plan de revenus SEO » — *(valeur 2 800 € HT, sans frais)*. Secondary CTA: outline, scrolls to block 7 (proof).
* **Value stack line under CTAs**: Plan de revenus = free lead magnet, delivered in 48 h, prospect keeps it either way.
* SEO: keyword in H1 (or discreet SEO-H1 pattern), keyword in first 100 words, main image alt.

### 3. Trust bar

Source: Module 1 trust banner + Module 10 logos. DS: `py-10`, tagline + marquee.
* Marquee items: Google Premier Partner · 4,9★ / 400+ avis · 6 années · 1 200+ clients · 240 M$ de revenus générés · 70 études de cas SEO / 300 projets · bureaux Tanger, Dubaï, Californie.
* Markets line: FR, MA, BE, USA/UK, Dubaï/EAU, Qatar (KSA en développement).

### 4. Problem stack — the pain layer

Source: **Module 2**. DS: sticky-left intro + text-only numbered rows (no cards).
* H2: « Vos concurrents captent les clients que Google vous envoie. Voici ce que cela vous coûte. »
* Rows 01–04 from the master's 3 pain paragraphs, split as: 01 paying 5 €/click while a competitor ranks free · 02 failed hires/agencies/tools · 03 content that ranks for nothing · 04 the compounding gap (cost of inaction).
* SEO: H2 = pain-phrased keyword variant; 4–6 NLP terms in body; internal link on « agence SEO ».

### 5. Méthode — the mechanism (RankNinja)

Source: **Module 3**. DS: sticky-left + vertical timeline with dots.
* H2: « Le fonctionnement de RankNinja, le système qui sous-tend la garantie. »
* **6 steps** (not the website LP's 4 — extend the timeline): Diagnostic (48 h) → Cadrage de la stratégie → Fondations (4 sem.) → Production de contenu → Construction de l'autorité → Effet de capitalisation. ~50 words each, verbatim from master.
* SEO: each step name is a **real H3**; icon alts = step name + keyword variant; H2 contains a methodology keyword variant.

### 6. Engagements — the differentiators

Source: **Modules 5b + 5c**. DS: sticky-left + full-gradient-SVG cards (374 px). *This block carries what competitors don't have; guarantees live in block 9.*
* **Card 1 — SEO local** (5b): « Un SEO local qui remplit votre agenda… » + 3 quick proofs (Lily Billy +732 % vues GBP en 3 mois · Maes 12 → 100+ appels/mois · Iman Dental #1 « dentiste tangier »).
* **Card 2 — GEO / recherche IA** (5c): « Devenez la marque que les moteurs de recherche IA citent… » — ChatGPT, Perplexity, Claude, Gemini, AI Overviews named explicitly (NLP entities); Écran Moderne proof.
* **Card 3 — Garantie contractuelle** (teaser of block 9): top-5 sous 6 mois inscrit au contrat, sinon poursuite sans facturation.
* SEO: 5b wants a city+service H2 variant (« Référencement local Tanger ») + `LocalBusiness` schema; 5c wants an AI-search keyword variant + `FAQPage` on GEO questions.

### 7. Selected work — proof

Source: **Module 4** (10 case cards). DS: centered H2 + grid (image + brand H3 + 3 stats + context line).
* H2: « Des marques qui occupent désormais leurs requêtes. »
* Grid: **6 of the 10 cards** to keep the DS 2×3 grid — priority: Iman Dental, Mariner, Maes, Lily Billy, Écran Moderne, promoteur immobilier BE. The remaining 4 (agence de voyage, RHILLANE, luxe anonymisé, affiliation UK) go to a « + voir plus » row or per-locale swaps.
* **Anti-cherry-picking callout** under the grid (mandatory — verbatim from master): "these 10 are the publicly authorized ones; 60+ more documented cases behind them…".
* SEO: card titles = H3 in format keyword + result verb; internal link per card to deep case-study page when it exists; `Review`/`Article` schema; alts = « [client] [mot-clé] étude de cas ».

### 8. Pricing — offer, value math, bonuses

Source: **Modules 5 + 6**, tabs *Tarification* and *Bonus*. DS: pricing block with vanilla-JS toggle.
* H2: « Quatre formats de mission. La même architecture de garantie. À choisir selon votre situation. »
* **4 cards**: Essentiel 2 000 · **Croissance ★ 3 500** (recommended, `shadow-growth`) · Performance 5 000 · Privé 12 000 € HT/mois (anchor — Hormozi 3–5× rule: Privé = 3,4× Croissance).
* **Value math first, price after** (cro-playbook §3): Croissance perceived value 24 100 € HT vs 3 500 € = **6,9×**; Privé 74 200 € vs 12 000 € = 6,2×.
* **Bonus stack (M.A.G.I.C.)**: the 9 named bonuses with attributed € value, footer line per bonus stating which formats include it.
* Secondary cards: Moteur de Conversion add-on + downsell paths (Cadrage Stratégique, Kit d'Auto-Diagnostic) for non-qualified visitors.
* SEO: each format name = H3; `Service`/`Product` schema per format with `PriceSpecification` (recurring); anchor links card → detail section.

### 9. Garanties — risk reversal

Source: **Module 7**, tab *Garantie*. DS: 1×3 cards + pill.
* 3 cards = the 3 guarantee levels: **G1** remboursement intégral de la stratégie (mois 1) · **G2** positionnement top 5 (mois 6, sinon poursuite sans facturation) · **G3** atteinte des jalons (M2/M4/M6 au contrat).
* Pill under the cards: the force-majeure clause phrased as « clause de fair-play ».
* SEO: guarantee-keyword H2 variant; each guarantee = H3; `Offer` schema with `warranty` where applicable.

### 10. FAQ — objection handling

Source: **Module 8** (condensed from tab *Objections*). DS: vertical accordion, vanilla JS.
* The **9 questions** from the master (garantie au contrat? · délais? · déjà déçus? · internaliser? · l'IA tue le SEO? · trafic ou CA? · pourquoi 6 mois? · mises à jour Google? · combien en pratique?), 3–4 sentences each, each answer citing its source (Hormozi ch., Backlinko 2024…).
* SEO: **`FAQPage` schema mandatory** (highest-impact markup on the page — PAA, AI Overviews, ChatGPT citations); each question = H3 phrased in natural user language; question wording from RankNinja PAA extraction.

### 11. Final CTA — the form

Source: **Module 9**. DS: split 60/40 — value recap left + CTA card right.
* H2: « Demandez votre Plan de revenus, sans frais. Livré sous 48 heures. »
* Left: the 3 master paragraphs (every result started with this plan · 2 min to ask, 48 h to deliver, yours to keep · no 90-min pitch, 45-min strategist call, 2 800 € HT value).
* Right: form, single column, **5 fields max**: Prénom · E-mail · Téléphone (qualif niveau 4) · Le site à auditer (keyword-bearing label) · CA annuel (dropdown, qualification).
* Micro-copy under button: « Sans engagement. Demande en deux minutes. Le Plan de revenus vous reste acquis, même si nous ne travaillons jamais ensemble. »
* SEO: transactional H2 (« Demandez votre audit SEO gratuit » pattern); CTA button label repeats the keyword variant.

### 12. Footer

Source: **Module 10**. DS: 3 columns (Services / Agence / Contact) + legal line.
* Badges: Google Premier Partner, Meta Business Partner, client logos (authorized only), 4,9★ / 400+ avis.
* Markets line verbatim from master.
* SEO: `Organization` JSON-LD (raison sociale, logo, sameAs, contactPoint); **NAP identical** to GBP/Trustpilot/LinkedIn; homepage links = brand anchor or bare URL, service links = exact-match anchor.

***

## CTA logic (one offer, everywhere)

Single conversion goal: **le Plan de revenus SEO** (2 800 € HT value, free, 48 h). It appears in header (1), hero (2), after proof (7), after pricing (8), and the form (11). No competing offers — downsells (Kit d'Auto-Diagnostic) only render for the non-qualified path.

## SEO content zone (below the form — added for long-form ranking, ~8k words total)

The conversion funnel (blocks 1–12) stays intact. Below the form, before the footer, an educational
zone gives Google the content mass for the competitive « agence SEO Maroc » keyword. Every section is
sourced from the master or tied to a real client — no generic filler. Scannable patterns only
(cards, accordions), never paragraph walls. All backgrounds alternate `bg-white` / `bg-nuk`.

| # | id | Section | Pattern |
|---|-----|---------|---------|
| S1 | `#definition` | Qu'est-ce que le référencement naturel (SEO) ? — 3 piliers, SEO vs Ads, IA band | sticky-left + cards + chips |
| S2 | `#pour-qui` | À qui s'adresse notre SEO — 4 personas + "82 % refusés" | 4 persona cards + exclusion list |
| S3 | `#expertises` | Nos expertises SEO — 6 piliers (technique, on-page, netlinking, local, international, GEO) | 2×3 cards + CTA |
| S4 | `#secteurs` | Le SEO par secteur — each card backed by a real client | card grid |
| S5 | `#inclus` | Ce qui est inclus dans chaque mission — 7 chantiers | native `<details>` accordion |
| S7 | `#valeur` | Combien rapporte le SEO — multiplicateurs 4,8×–9,1× + market rates | stat cards + table |
| S8 | `#villes` | Le SEO local, ville par ville (Tanger, Marrakech, Casa, Rabat, Fès, Agadir) | sticky-left + city cards |
| S6 | `#faq-seo` | FAQ éducative — 23 questions | JS accordion (`.faq-toggle`) |

**FAQPage schema:** all questions (objection FAQ block 10 + educational FAQ S6) merged into a single
`FAQPage` JSON-LD graph — 32 Q total. Keep schema count == visible question count on every edit.

## Build order

1. Skeleton from the 5 Figma patterns (header, hero, sticky-left ×3 differentiated, grid, footer) — [components.md](../../../design-system/components.md).
2. Paste copy from master via Copy buttons, module by module.
3. Keyword pass: H1/H2/H3 placements + NLP terms (RankNinja cluster for the target locale keyword).
4. Schema pass: FAQPage, Service×4, Organization, LocalBusiness, Review.
5. Locale variants: root `/` (MA) first, then `/fr-fr/`, `/en-us/`, `/en-ae/` with adapted proof ordering and local-SEO H2.
