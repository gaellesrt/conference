# Data Mesh Belgium — contenu du deck

*État au 2026-10-09, après les modifications d'Axel. Ce fichier reprend, slide par slide, le texte exact du deck publié (18 slides). Speakers : Gaëlle Seret, Axel Mercier.*

**Pour modifier :** change directement les champs `Kicker`, `Titre`, `Texte`, `Cartes` ou `Visuel` ci-dessous. Pour supprimer une slide, efface son bloc ; pour en ajouter une, copie un bloc à l'endroit voulu. Renvoie-moi le fichier et je mets le deck à jour à l'identique.

Le texte des slides est en anglais. Les lignes en *italique* sont des notes pour nous, elles n'apparaissent pas dans le deck. Plus aucune slide n'affiche de ligne de source.

---

## Slide 1 — Ouverture

- **Sur-titre :** Clean Data Architecture · Field notes
- **Titre :** Federation is an organisational principle, not an execution model
- **Texte :** How product thinking, platform engineering and organisational design turn governance into executable capabilities.
- **Ligne du bas :** Gaëlle Seret & Axel Mercier · Data Mesh Belgium · 2026

*Titre et texte viennent du pitch, pas de la structure.*

## Slide 2 — Speakers

- **Kicker :** Speakers
- **Titre :** Who's speaking today
- **Speaker 1 :** Gaëlle Seret — Head of Data Governance — Works for leboncoin as Head of Data Governance.
- **Speaker 2 :** Axel Mercier — Head of Data Platform — Works for Kering as Head of Data Platform.

## Slide 3 — Contexte

- **Kicker :** 01 — Context
- **Titre :** Federation has become one of the standards
- **Texte :** Example of a pragmatic data strategy:
- **Carte Data for all (icône éclair) :** Fast access to information. Capacity to do agentic.
- **Carte Data by all (icône réseau : trois nœuds reliés) :** Clear, distributed responsibility.
- **Encadré chiffré (aligné sur les deux cartes : le chiffre à la hauteur des icônes, le texte à la hauteur des titres) :** 99.9% of people we work with agree that it is a good idea

## Slide 4 — Problématique (fond sombre)

- **Kicker :** 02 — Problem
- **Titre :** Why is federated governance not adopted?
- **Trois encadrés de même style, de plus en plus appuyés (gris → dégradé léger → dégradé plein) :**
  - Because it **adds problems** to people who already have enough.
  - We need to **bring something to the table**.
  - Governance must **solve user problems** and start with discovery.

## Slide 5 — Discovery

- **Kicker :** 03 — Discovery
- **Titre :** Problem discovery and prioritization
- **À droite — phrase d'intro (style texte, pas en gras) :** Where can you deliver the most value and create future allyship?
- **Carte Executive Committee :** For the value I have invested in governance, are we doing better or worse?
- **Carte Privacy teams :** Where are our risks, and how can we update this map regularly?
- **Carte Architecture teams :** How do we design the organisation as one team?
- **Carte Chief Data Officer :** How do we kill the legacy?
- **À gauche — phrase d'intro (style texte, pas en gras) :** Mapping your users into personas, knowing their pain points and expectations in detail
- **À gauche — visuel :** matrice Excalidraw « The users of governance » (fichier `dmbe-governance-users-matrix.excalidraw`) : axe vertical de Detailed granularity (bas) à High level (haut), axe horizontal Data maturity. Grille 3 × 3 — colonne 1 : Operations, Controlling, Business directors ; colonne 2 : Product teams, Privacy teams, Data Privacy Officer ; colonne 3 : Engineering teams, Architecture teams, Chief Data Officer. Toutes les cases en blanc, contour gris en pointillés et texte gris, sans mise en avant ni légende.

*Les alliés ne sont pas dans le schéma : tu les présentes à l'oral. Executive Committee n'apparaît plus dans la matrice (remplacé par Data Privacy Officer), mais reste dans les cartes.*

*Les kickers suivants sont numérotés de 04 à 10.*

## Slide 6 — Killing the legacy

- **Kicker :** 04 — Focusing on killing the legacy
- **Titre :** A key foundation for future federation
- **Texte (deux phrases) :** **First,** we map existing data assets to functional domains. / **Then,** we create functional domains not as teams but as sets of nodes that make sense together: multiple teams that functionally need to work together.
- **Visuel :** pyramide « Scale of what could be built in 4 years » : 1 company, 100 teams, +500 contributors, +1000 data & AI assets, +10 domains, 1 shared platform

## Slide 7 — Architecture (domaines)

- **Kicker :** 05 — Computational by design
- **Titre :** Computational supports Domain-Driven Design
- **Texte :** **Every node** is a data asset, owned by a domain. / **Every asset** is built and exposed as a product. / **Every link** is a partnership, on the terms the asset publishes.
- **Phrase mise en avant :** Data outlives the organisation. It is always accessible, with an owner accountable for what it exposes.
- **Visuel :** grille des domaines Finance, Client, Supply Chain, HR, Sales reliés par leurs contrats

## Slide 8 — So much people, that policy as code was non negotiable

- **Kicker :** 06 — Supporting teams in the process
- **Titre :** Computational makes compliance a feature
- **Texte (trois paragraphes) :** Governance is here to reduce risks, not block delivery, or even worse innovation. / The platform blocks only what breaks production and computes everything else as a signal. / To do that, everything is designed within teams' ways of working, from creation to deprecation.
- **Carte 1 — Service · Enable :** Compliant by construction. / *One common access process.*
- **Carte 2 — CI · Block :** Only what breaks production. / *Contracts, breaking changes, builds.*
- **Carte 3 — Monitoring · Guide :** Signals, not stop signs. / *Open PRs, budgets, quotas.*
- **Carte 4 — Reporting · Arbitrate :** Contested rules go to council. / *Policies nobody values.*

*Les textes en italique dans les cartes sont affichés dans le deck (sous-ligne en italique).*

## Slide 9 — Policy as code · Users (fond sombre)

- **Kicker :** 07 — Enabling policy as code
- **Titre :** The benefits of policy as code for each user
- **Carte 1 — Product :** What is a quality data product?
- **Carte 2 — Engineering :** What is the technical debt and how mature are the teams?
- **Carte 3 — Chief Data Officer :** Can we monitor costs and compliance with security standards?

## Slide 10 — Policy as code · Arbitration

- **Kicker :** 08 — It shows that we need federation
- **Titre :** Policies alone are not enough
- **Texte :** Delivering policies shows that federation is now necessary. The teams who comply are rarely the ones who suffer from the problem the policies address.
- **Phrase mise en avant (deux lignes) :** Computation makes every problem visible and its impact understood. / Remediation requires federation.
- **Encadré chiffré :** Example · Policy — dbt tests on every data product — 28% still do not comply — Complying is costly, and many producers sit outside the organisation. — Our path: **data product health** → quality framework → dbt tests.

## Slide 11 — Engineering and Product teams have strong incentive to participate in federation

- **Kicker :** 09 — Working to incentivise teams
- **Titre :** Going back to our 4 personas
- **Texte :** The computational design solves problems for the users and for the teams participating in the mesh.
- **Cartes (titre seul, numérotées 1 à 4) :** Reporting by design / Privacy by design / Architecture by design / Migration by use cases
- **Phrase mise en avant (taille réduite) :** Engineering and Product teams have a strong incentive to participate in federation, even though we don't directly address their problems.

## Slide 12 — En pratique · COMEX

- **Kicker :** 09 — Real life example · Executive committee
- **Titre :** Measuring the cost of debt
- **Visuel :** Excalidraw « Debt indicators governance can act on » (fichier `dmbe-debt-indicators.excalidraw`), six cartes illustrées, sans chiffres : Mapping (How many assets are mapped to a domain?) · Ownership (How many assets have an accountable owner?) · Lifecycle (How many users still use deprecated assets?) · Contracts (How many data flows are declared as binding commitments?) · Broken contracts (How many contracts broke in production?) · Impact on KPIs (What was the impact on key performance indicators?)

*Indicateurs choisis parce que la gouvernance peut agir dessus directement (proposés par Claude, à valider).*

## Slide 13 — En pratique · Privacy

- **Kicker :** 09 — Real life example · Privacy
- **Titre :** Add privacy features to contracts
- **Texte :** *(aucun)*
- **Visuel :** schéma Excalidraw « Data Contract » (fichier `dmbe-data-contract.excalidraw`) : producer → output port ← consumer. Étiquettes producteur : data modeling, SLA, versioning + en **violet** (privacy) declared purpose, retention period, action at end of retention. Étiquettes consommateur : en **violet** purpose of use, use case, usage retention. Les étiquettes privacy sont directement sur le schéma, sans encadré séparé.

## Slide 14 — En pratique · Architecture

- **Kicker :** 09 — Real life example · Architecture
- **Titre :** Use lineage to give feedback to architects
- **Visuel :** Excalidraw de lineage pondéré (fichier `dmbe-lineage-teams.excalidraw`), style de la slide 05, sans titre, sans nom de domaine et sans légende : les domaines s'attirent selon le nombre de flux de données entre eux (disposition par forces) ; liens gris entre domaines ; en rouge : le weak link (un data point cerclé de rouge) et les flèches de la référence circulaire entre trois domaines. Les dots et les liens sont commentés à l'oral.

*Liens illustratifs, pas les vrais chiffres.*

## Slide 15 — Opening (fond noir)

- **Kicker :** Opening
- **Titre :** Opening on what we are still exploring today
- **Texte :** How to adapt policies and guidelines with AI.

## Slide 16 — L'AI

- **Kicker :** 10 — What about AI?
- **Titre :** Governance usually gives guardrails to humans. Now the guardrails go to agents
- **Carte Before :** **Service** makes compliance a feature. / **CI and monitoring** block and guide. / **Reporting** arbitrates.
- **Carte Now :** **Policies** become platform documentation. / **Practices** write skills, **governance** curates. / **Agents** use them as skills and context.
- **Encadré — Goodhart trap :** An agent will cover a policy without thinking. A proxy rule like "at least one test" gets satisfied, not served. Policies have to be adapted for agents.

## Slide 17 — Conclusion (fond sombre)

- **Kicker :** Conclusion
- **Titre :** In the end, it's product
- **Carte 1 — A product :** Governance is a product that serves users.
- **Carte 2 — Delivery :** To be adopted, governance needs to serve the delivery process.
- **Carte 3 — Strategy and debt :** Governance is there to drive the product strategy and the technical debt.

*Les trois intitulés de cartes sont de Claude.*

## Slide 18 — Clôture

- **Kicker :** Closing
- **Titre :** Thank you for spending this time with us
- **Texte :** To think outside the box, come and do multidisciplinary work with us.
- **QR code (à la place du bouton) :** vers cleandataarchitecture.substack.com, avec « Read the newsletter » et le lien à côté
- **Ligne du bas :** Governance · Product · Policy as code

---

## Annexe — sources d'appui disponibles

*Aucune n'est affichée dans le deck actuel. Elles peuvent étayer une slide si besoin.*

| # | Source | URL | Date | Peut servir pour |
|---|---|---|---|---|
| S1 | Starting a Data Mesh: a Field Guide | cleandataarchitecture.substack.com/p/starting-a-data-mesh-a-field-guide | 09/04/2026 | Problématique, discovery, platform |
| S2 | Ensuring Data Contracts adoption across an organization | cleandataarchitecture.substack.com/p/ensuring-data-contracts-adoption | 01/04/2025 | Governance-as-a-service, CI/CD |
| S3 | Building a Data Domain: Return on Experience | cleandataarchitecture.substack.com/p/building-a-data-domain-return-on | 28/10/2025 | COMEX |
| S4 | From strategic design to engineering execution: the IT domain | cleandataarchitecture.substack.com/p/from-strategic-design-to-engineering | 08/09/2025 | Architecture / DDD |
| S5 | Building a Map, Not a Maze | cleandataarchitecture.substack.com/p/building-a-map-not-a-maze | 26/05/2025 | DDD appliqué à la data |
| S6 | Z. Dehghani — Data Mesh Principles and Logical Architecture | martinfowler.com/articles/data-mesh-principles.html | 03/12/2020 | Federated computational governance |
| S7 | RGPD — Règlement (UE) 2016/679, art. 5(1)(b) | eur-lex.europa.eu/eli/reg/2016/679/oj | 2016 | Privacy : limitation des finalités |
| S8 | Anthropic — Introducing Agent Skills | anthropic.com/news/skills | 10/2025 | Définition d'un skill |

## Annexe — format

Deck construit sur le template CDA v3 avec les ajouts du deck TF1 : titres sur toute la largeur, une slide par écran, titres longs réduits automatiquement, protection contre la copie, graphes zoomables au clic. Slides 06 et 09 : texte à gauche, étapes numérotées 1 à 4 à droite, en grille 2 × 2. Les trois slides « Real life example » : titre en haut, visuel centré dessous. Marges haut et bas proportionnelles à la hauteur d'écran : chaque slide tient sur un écran à 100 % de 1280×680 à 2560×1300.
