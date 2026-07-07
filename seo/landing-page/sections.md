# SEO Landing Page — Sections

Quick outline (actual order in `index.html`). Full details in [seo-landing-page-spec.md](seo-landing-page-spec.md).

## A. Conversion funnel (top of page → form)

1. **Header** `#site-header` — minimal sticky bar: logo + single CTA « Demander mon plan de revenus SEO » → `#plan-de-revenus`.
2. **Hero** `#hero` — H1 promise (des clients depuis Google, garantie inscrite au contrat), subtitle, dual CTA, free-audit offer band. Animated gradient curves background.
3. **Trust bar** *(no id)* — marquee strip: partenaire, avis, clients, chiffres, marchés.
4. **Problème** `#probleme` — « Vos concurrents captent les clients que Google vous envoie. » 4 pains stacked.
5. **Méthode (RankNinja)** `#methode` — « La méthode SEO RankNinja, le système qui sous-tend la garantie. » 6-step timeline with scroll-fill number circles (1→6) + CTA.
6. **Différenciateurs** `#engagements` — « Ce que les autres agences de référencement ne couvrent pas. » Cards: SEO local, GEO / IA, garantie contractuelle.
7. **Résultats** `#resultats` — « Des marques qui occupent désormais leurs requêtes. » Case-study cards + anti-cherry-picking callout.
8. **Témoignages** `#temoignages` — « Ce que nos clients disent de nous. » 3 quote cards (gradient hover border, photo avatar `assets/avatar-*.jpg`, 5 stars) + SERP capture marquee (« La preuve, capturée directement depuis Google »).
9. **Tarifs** `#tarifs` — « Quatre formats de mission SEO. La même architecture de garantie. » 4 plans (Essentiel · Croissance ★ · Performance · Privé), value before price.
10. **Garanties** `#garanties` — « La garantie de résultats SEO, en trois niveaux. » 3 cards (remboursement · Top 5 · jalons au contrat).
11. **ROI (analytics)** `#roi` — *dark* — « Ils ont investi 1 500 €/mois… Voici ce qu'ils ont gagné. » 3 real Google Analytics captures with ROI badges.
12. **Fondateur** `#fondateur` — *dark* — « Bienvenue chez l'agence Rhillane Marketing. » Founder photo + positioning + CTA.
13. **FAQ** `#faq` — « Vos questions sur le SEO, sans langue de bois. » Accordion (one open at a time), placed right before the form to clear final objections. `FAQPage` JSON-LD must match visible question count (currently 9 = 9).
14. **Plan de revenus (form)** `#plan-de-revenus` — « Demandez votre audit SEO gratuit. » 5-field form (prénom, email, tél, site, CA). **Primary conversion point.**

## B. SEO content zone (below the form — long-form for ranking)

15. **Définition** `#definition` — « Qu'est-ce que le référencement naturel (SEO) ? » Lead + piliers strip (SEO / GEO / SEA framing).
16. **Pour qui** `#pour-qui` — « À qui s'adresse notre accompagnement SEO ? » Buyer-persona cards + honest exclusion note.
17. **Expertises** `#expertises` — « Nos expertises SEO, réunies sous un seul accompagnement. » 6 pillar cards with gradient icon badges.
18. **Secteurs** `#secteurs` — « Le référencement naturel par secteur d'activité. » Industry cards, each backed by a real client.
19. **Valeur** `#valeur` — « Combien rapporte le référencement naturel ? » Value math / ROI reasoning.

## C. Close

20. **Footer** *(no id)* — minimal: logo + © only.
