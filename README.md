# Enrico Giuliano

**Pharmacist · Founder & Product Lead of [SOPHIA](https://github.com/EG2025-lab/sophia-pharmacy) · Italy**

I am building SOPHIA to help pharmacists navigate official medicines documentation, Italian pharmaceutical legislation, clinical evidence and guidelines in one professional conversation. Our goals are to reduce information fragmentation and workload, help reduce errors and improve pharmacy service. Their impact still needs to be measured.

FarmAI is available as original custom GPTs and private Business plugins derived from their copies. SOPHIA is a separate application under development, with its own restricted beta. The public repository shares documentation, evaluation proposals and collaboration opportunities; application source code is not published there.

The deployed professional beta is **0.7.122-beta**, restricted to owner-approved users; payments and answer charging remain inactive. [Current status](https://github.com/EG2025-lab/sophia-pharmacy/blob/main/docs/STATUS.md).

Exactly **four new real AIFA questions** were submitted once each on **122**: **one useful documentary answer in the assessed scope, one partial answer with package-identity and structured-reader gaps, one engine failure without a final answer, and one erroneous privacy rejection before inference**. Two final answers were delivered. Fourteen current official AIFA PDFs were independently reread against a frozen oracle. This is internal AI-assisted assessment, not human clinical validation.

**122** introduces request-local exact-document pooling, broader source-section coverage and provenance-preserving AIFA handling derived from the FarmAI corpus. **1,881 offline checks, 58 interface checks and 195 exact runtime files** passed technical qualification. The real results are mixed: observed engine times were approximately **29.10 seconds** for the useful answer, **89.63 seconds** for the partial answer and **101.45 seconds** for the failed request. Different tasks and no matched live baseline mean no causal speed, accuracy or cost gain is established.

Post-battery candidate **123** repairs the demonstrated false contact-intent detection for labelled medicine codes with contact-lens terminology. **1,893 offline checks and 58 interface checks** pass, including phone and personal-data counterexamples; **123 is not deployed, has zero own real questions and remains NO-GO for own real acceptance**. The generation failure, exact-dose selection and structured Tirosint reading remain open. Report122 and RC123 are separately sealed. No fifth question, general FarmAI parity, SLA, professional rollout or human clinical validation is claimed. FarmAI GPTs and Business plugins retain content **0.7.7.155**.


### Let's build and evaluate together

I welcome **developers, AI researchers, pharmacists and research groups** interested in source retrieval, RCP/FI document reading, grounded answers and meaningful professional evaluation. A first contribution can be small and use public-source metadata or a protocol review without paid model calls.

**[Project and opportunities](https://github.com/EG2025-lab/sophia-pharmacy) · [How to contribute](https://github.com/EG2025-lab/sophia-pharmacy/blob/main/CONTRIBUTING.md) · [Proposed 20-question pilot](https://github.com/EG2025-lab/sophia-pharmacy/blob/main/pilot/README.md)**

**[SOPHIA website](https://sophia-pharmacy.enricogiuliano.chatgpt.site/) · [Status and architecture](https://sophia-pharmacy.enricogiuliano.chatgpt.site/transparency) · [Roadmap](https://sophia-pharmacy.enricogiuliano.chatgpt.site/roadmap) · [Contact](https://sophia-pharmacy.enricogiuliano.chatgpt.site/#partners)**

### In italiano

Sono farmacista e sto sviluppando SOPHIA per avvicinare le fonti utili al lavoro in farmacia. Cerco persone con cui migliorare e valutare il progetto: farmacisti, sviluppatori, esperti AI e ricercatori. Puoi iniziare dalla [presentazione italiana](https://github.com/EG2025-lab/sophia-pharmacy/blob/main/README.it.md) o contattarmi attraverso il sito.

Technical progress, answer usefulness and clinical validation are reported separately. No university partnership, clinical performance certification or overall regulatory conformity is claimed. Please keep patient data, credentials and confidential information out of public contributions.
