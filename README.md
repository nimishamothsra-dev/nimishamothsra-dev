# Nimisha Mothsra
**Financial Crime × AI Evaluation × Workflow Automation**

I build AI workflows that financial crime teams can trust.

AI is moving into AML, KYC, sanctions and fraud work faster than compliance teams can check it. My work sits in that gap: testing whether AI outputs are accurate and backed by evidence, designing the controls and human oversight around them, and building automations in n8n that fail safely instead of silently.

I bring 18+ years in financial crime compliance across global banks, fintech and advisory, in APAC, Australia, the UK/Europe and North America. I now build hands-on in n8n and Arize Phoenix.

---

### How I build
- **Evidence first.** Every AI claim should trace back to a source someone can check.
- **Separate authority.** Generation, QA and publishing are separate steps with separate permissions.
- **Test the tester.** An evaluation is only useful if its grader is checked too.
- **Fail loudly.** Validation, duplicate handling, error branches and human approval gates come as standard.

---

### Current work

| Project | What it does | Status |
|---|---|---|
| **FinCrime Intelligence Ecosystem** | Modular n8n system: collects sources, verifies research, produces evidence-linked briefs and case records. Tracks source and citation lineage and versions models and prompts. | Built and tested in staging; public showcase in preparation |
| **FinCrime AI Evaluation Harness** | Arize Phoenix datasets and experiments. Combines deterministic checks, citation-entailment rubrics and an observation-only LLM-as-judge. | Citation-integrity check working: on a brief with 50 quotation references, removing 3 triggered the expected fail. Write-up in progress. |
| **Alert threshold study** | Score bands, below-the-line sampling and AI-triage cut-offs on 5,000 synthetic alert groups. | Analysis done (16–19 band yield 30.1% vs 21.7% for 20–24); write-up in progress |
| **AI & agent register** | 29-field inventory for AI systems in financial crime: ownership, use case, data, materiality, oversight. | Field dictionary done; materiality method next |
| **Agent incident taxonomy** | 20 public AI-agent incidents classified into eight behaviour classes. | Catalogue done; mapping to financial crime harms next |
| **Sanctions latency KRI** | Measures time from sanctions-list publication to live screening, with thresholds and escalation. | Definition done; measurement harness next |

### Next up
- Tracing and observability for live n8n workflows (OpenTelemetry → Phoenix)
- Judge calibration against human labels, and grader-integrity checks
- An adversarial AML/sanctions test set for red-teaming AI
- n8n + AI demo workflows for other regulated work (insurance, legal and operations)

---

### Services
- **FinCrime AI evaluation and red-teaming:** rubrics, gold-standard test sets and adversarial scenarios
- **AI-agent assurance for RegTech and banks:** failure analysis and human-oversight design, aligned to NIST AI RMF, the EU AI Act and ISO/IEC 42001
- **n8n + AI automation for regulated work:** reliable workflows with validation, error handling and approval gates
- **Alert-threshold and below-the-line testing**

### Stack
n8n · Arize Phoenix · LLM-as-judge · evaluation datasets · HTTP APIs & webhooks · JSON / structured outputs · GitHub · SQL

---

www.linkedin.com/in/nimisha-mothsra-0396a4286
