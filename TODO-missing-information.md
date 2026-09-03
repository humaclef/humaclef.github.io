# Missing information and points to check

Working document, not published on the site (it is excluded in `_config.yml`). Delete it once everything is resolved.

## Blocking (the site is not publishable without these)

- [ ] **Edition and venue.** Confirm whether the lab runs at CLEF 2027 (Bucharest, 14–17 September 2027) or CLEF 2026 (Jena, 21–24 September 2026). The site currently assumes 2027. Files: `index.md`.
- [ ] **Contact email.** No address appears anywhere in the proposal. Files: `contact.md`, `_config.yml`.
- [ ] **Site URL and `baseurl`.** Depends on the repository name. File: `_config.yml`.
- [ ] **Important dates.** Nothing is fixed. Both `index.md` and `participate.md` carry an empty table; keep the two in sync or, better, keep the dates in one page only and link to it.
- [ ] **Task chairs.** CLEF requires the person or persons formally responsible for running the lab to be identified. The proposal lists organisers without designating them. File: `organisers.md`.

## Content still to be supplied

- [ ] Keynote speaker (not named in the proposal). File: `programme.md`.
- [ ] Status of each invited speaker (invited, confirmed, declined). Publishing unconfirmed names carries a reputational risk. File: `programme.md`.
- [ ] Steering committee: names, addresses and homepage links. The proposal deferred these until formal acceptance, which has now happened. File: `organisers.md`.
- [ ] Programme committee: full membership and review policy. File: `organisers.md`.
- [ ] Submission details: contribution types, peer review, page limits, template, submission system, whether contributions appear in the CLEF working notes (CEUR-WS). File: `participate.md`.
- [ ] Poster selection procedure and format. File: `programme.md`.
- [ ] Registration link and whether remote attendance is possible. File: `participate.md`.
- [ ] Dissemination channels and social media handles. File: `participate.md`.
- [ ] Licence for the site content, and repository link. File: `contact.md`.
- [ ] Logos and permission to use them. File: `index.md`.
- [ ] Whether the roadmap will be published as a citable output. File: `scope.md`.
- [ ] Email, homepage and ORCID for each organiser. File: `organisers.md`.

## Errors and inconsistencies found in the proposal

- [ ] **"Cross Lingual Evaluation Forum"** (in the request, not in the PDF). CLEF has been the Conference and Labs of the Evaluation Forum since 2010; Cross-Language Evaluation Forum was the name from 2000 to 2009. The site uses the current name.
- [ ] **"PressMint"** appears twice and could not be verified as an existing project. Possibly a variant of another name. It has been removed from `resources.md` and flagged there; it still appears in the coordination paragraph of `organisers.md`.
- [ ] **"Parliamint"** is almost certainly **ParlaMint**. Corrected on the site.
- [ ] **Matteo Romanello's affiliation** is given as ETHZ. Worth verifying, as it has changed in recent years.
- [ ] **Session timing.** The four programme slots total 185 minutes with no break, which is tight for a half-day session. Check against the slot CLEF allocates.
- [ ] Typographical errors in the PDF, corrected on the site: "evaluation oand benchmarking", "robust ben marking expertise", "The Neatherlands", "https://clarin.eu" left with an unclosed parenthesis.
- [ ] Abbreviated affiliations (UAH, FUB, UJA, UvA, EPHE-PSL, ETHZ) have been expanded on the site. Check each expansion.

## Structural decisions worth taking now

- [ ] Whether the site should be edition-specific (`/2027/`) or persistent across editions. HUMANITAS is presented as a sustainable umbrella initiative, so a persistent site with an archive per edition suits the stated ambition better.
- [ ] Whether to keep the dates in a single page to avoid the two tables drifting apart.
