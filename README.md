# Enrico Giuliano

**Pharmacist · Founder & Product Lead of [SOPHIA](https://github.com/EG2025-lab/sophia-pharmacy) · Italy**

I am building SOPHIA to help pharmacists navigate official medicines documentation, Italian pharmaceutical legislation, clinical evidence and guidelines in one professional conversation. Our goals are to reduce information fragmentation and workload, help reduce errors and improve pharmacy service. Their impact still needs to be measured.

FarmAI is available as original custom GPTs and private Business plugins derived from their copies. SOPHIA is a separate application under development, with its own restricted beta. The public repository shares documentation, evaluation proposals and collaboration opportunities; application source code is not published there.

The deployed professional beta is **0.7.126-beta**, restricted to owner-approved users; payments and answer charging remain inactive. [Current status](https://github.com/EG2025-lab/sophia-pharmacy/blob/main/docs/STATUS.md).

126 improves shared AIFA document reading, generated-text privacy diagnostics and request-local evidence reuse. Original text, exact package identity, source hashes, pages and formulation-specific conditions remain distinct. **1,931 offline checks, 58 interface checks and 195 image runtime files** passed qualification. The selected 1,266-case privacy regression set still accepts 1,170 admissible cases and blocks 96 adverse cases; it is not a general benchmark.

Exactly **four real AIFA replays** used the **same questions and two-conversation pairing as 124**, once each after final 126 publication. Fourteen official PDFs were freshly reread with unchanged hashes; six catalogue checks preceded submission. All four questions were admitted: **three useful answers within internal documentary scope and one generated-output privacy failure**. The previously partial comparison now covers the requested facts; another uses structured FI/RCP without web recovery or generic incomplete-verification text. Ingredient-label reconciliation remains open in both cases, despite bound text and complete requested sections. The fourth request failed after three semantic repairs: diagnostics now identify **PHONE_LIKE / BLOCK_TEXT**, but the discarded draft was not retained, so the exact number and false-positive character remain unproved. All 18 model calls have known usage. Engine timings124→126:78.23→49.50s,29.71→31.66s,76.74→24.13s; the fourth failed at78.36s versus34.30s. This small nonrandomized replay establishes no general speed, cost or accuracy guarantee.

Post-battery candidate **127** handles the reproducible family of already-observed structured AIFA references in short output fields. **1,937 offline and 58 interface checks** pass, but **127 is not deployed, has zero own real questions and remains NO-GO for own real acceptance**. It does not prove resolution of the exact fourth draft or its preceding semantic issues. Report126 and RC127 are separately sealed; no fifth question. No general FarmAI parity, professional rollout, SLA or human clinical validation. FarmAI original GPTs and private Business plugins retain content **0.7.7.155**.


### Let's build and evaluate together

I welcome **developers, AI researchers, pharmacists and research groups** interested in source retrieval, RCP/FI document reading, grounded answers and meaningful professional evaluation. A first contribution can be small and use public-source metadata or a protocol review without paid model calls.

**[Project and opportunities](https://github.com/EG2025-lab/sophia-pharmacy) · [How to contribute](https://github.com/EG2025-lab/sophia-pharmacy/blob/main/CONTRIBUTING.md) · [Proposed 20-question pilot](https://github.com/EG2025-lab/sophia-pharmacy/blob/main/pilot/README.md)**

**[SOPHIA website](https://sophia-pharmacy.enricogiuliano.chatgpt.site/) · [Status and architecture](https://sophia-pharmacy.enricogiuliano.chatgpt.site/transparency) · [Roadmap](https://sophia-pharmacy.enricogiuliano.chatgpt.site/roadmap) · [Contact](https://sophia-pharmacy.enricogiuliano.chatgpt.site/#partners)**

### In italiano

Sono farmacista e sto sviluppando SOPHIA per avvicinare le fonti utili al lavoro in farmacia. Cerco persone con cui migliorare e valutare il progetto: farmacisti, sviluppatori, esperti AI e ricercatori. Puoi iniziare dalla [presentazione italiana](https://github.com/EG2025-lab/sophia-pharmacy/blob/main/README.it.md) o contattarmi attraverso il sito.

Technical progress, answer usefulness and clinical validation are reported separately. No university partnership, clinical performance certification or overall regulatory conformity is claimed. Please keep patient data, credentials and confidential information out of public contributions.
