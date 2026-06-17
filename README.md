# AI Governance & Observability Scorecard

An interactive reference scorecard covering **42 AI metrics** across **11 lifecycle layers** — designed to help AI practitioners, data engineers, and governance teams understand what to measure, how to compute it, when to start tracking it, and which tools to use.

**Live:** https://luispsalas.github.io/ai-observability-scorecard/

---

## What's inside

Each metric card covers:

- **Description** — what the metric actually measures
- **Calculation** — the formula or method
- **Example** — a concrete worked value
- **Use cases** — where it applies (RAG, agents, local LLMs, knowledge bases, compliance, etc.)
- **When to implement** — the trigger that makes it relevant
- **Healthy target** — a practical reference range
- **Watch out for** — common pitfalls and measurement traps
- **Tooling** — relevant open-source and vendor tools (RAGAS, DeepEval, Evidently, Presidio, promptfoo, and more)

---

## The 11 layers

| Layer | Focus |
|---|---|
| **Retrieval (RAG)** | Precision, recall, relevance, ranking — how well the system finds the right context |
| **Generation** | Faithfulness, relevance, correctness, hallucination — quality of the produced answer |
| **Prompt Engineering** | Prompt reliability, injection and jailbreak defense |
| **Agentic AI** | Tool calls, task completion, multi-agent handoffs, planning, memory |
| **Safety & Trust** | Toxicity, policy violations, refusal accuracy |
| **Data Governance** | Classification accuracy, PII detection, data quality, metadata, lineage |
| **AI Governance** | Explainability, citation accuracy, human override, audit trail coverage |
| **ML Observability** | Model drift and data drift detection |
| **Operations** | Latency, TTFT, availability, error rates |
| **Cost & FinOps** | Token consumption, cost per request |
| **Business Value** | User satisfaction, outcome lift, adoption rate |

---

## How to use

- **Search** — type any term in the search bar to filter by metric name, description, or tool
- **Goal filter** — narrow to *Technical Quality*, *Governance & Risk*, or *Business Value*
- **Maturity filter** — browse by adoption stage: *Foundational*, *Intermediate*, or *Advanced*
- **Layer filter** — focus on a specific lifecycle layer
- **Expand a card** — click any card to reveal the full detail (calculation, targets, pitfalls, tooling)
- **Build your scorecard** — scroll to the bottom section for a maturity-tiered checklist of the 42 metrics

Filters combine — select one from each row to narrow down simultaneously.

---

## Maturity tiers

A practical governance scorecard is typically **20–25 metrics** (4–5 per category), not all 42.

| Tier | When to adopt |
|---|---|
| **Foundational** (17 metrics) | Table-stakes metrics — add these from day one or first production release |
| **Intermediate** (15 metrics) | Add as you productionize — scaling, compliance, and monitoring needs emerge |
| **Advanced** (10 metrics) | Mature or regulated programs — multi-agent systems, audit requirements, ROI reporting |

---

## License

MIT — free to use, adapt, and share with attribution.
