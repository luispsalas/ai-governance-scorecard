# AI Metrics Scorecard — Team Template

Use this template to build your team's working scorecard. Start with the Foundational metrics and expand as your AI program matures. A focused scorecard is typically **20–25 metrics** (4–5 per layer).

---

## Scorecard info

| Field | Value |
|---|---|
| Team / System | |
| AI system name | |
| Owner | |
| Review cadence | |
| Last updated | |

---

## How to fill this in

1. **Pick your metrics** — use the [AI Metrics Catalog](https://luispsalas.github.io/ai-governance-scorecard/) to browse and select
2. **Set your target** — adapt the healthy range to your use case and risk tolerance
3. **Assign an owner** — one person per metric keeps accountability clear
4. **Track current value** — update on your review cadence
5. **Add notes** — flag trends, blockers, or planned improvements

---

## Foundational metrics — start here

*These 17 metrics are table-stakes for any AI system in production.*

### Retrieval (RAG)

| Metric | Target | Current Value | Owner | Notes |
|---|---|---|---|---|
| Context Precision | ≥ 0.8 | | | |
| Context Recall | ≥ 0.85 | | | |
| Context Relevance | Cosine ≥ 0.75 | | | |
| MRR | ≥ 0.7 | | | |

### Generation

| Metric | Target | Current Value | Owner | Notes |
|---|---|---|---|---|
| Faithfulness | ≥ 0.9 | | | |
| Answer Relevance | ≥ 0.85 | | | |
| Hallucination Rate | < 5% | | | |

### Prompt Engineering

| Metric | Target | Current Value | Owner | Notes |
|---|---|---|---|---|
| Prompt Success Rate | ≥ 0.95 | | | |

### Safety & Trust

| Metric | Target | Current Value | Owner | Notes |
|---|---|---|---|---|
| Toxicity Score | < 1% | | | |

### Data Governance

| Metric | Target | Current Value | Owner | Notes |
|---|---|---|---|---|
| Metadata Completeness | ≥ 0.9 | | | |

### Operations

| Metric | Target | Current Value | Owner | Notes |
|---|---|---|---|---|
| Latency (P95) | < 5s | | | |
| Error Rate | < 1% | | | |
| Time to First Token (TTFT) | < 1s | | | |

### Cost & FinOps

| Metric | Target | Current Value | Owner | Notes |
|---|---|---|---|---|
| Token Consumption | Trending down | | | |
| Cost per Request | Within budget | | | |

### Business Value

| Metric | Target | Current Value | Owner | Notes |
|---|---|---|---|---|
| User Satisfaction Score | ≥ 4/5 | | | |
| Availability / Uptime | ≥ 99.9% | | | |

---

## Intermediate metrics — add as you productionize

*Add these 15 metrics as your system scales and compliance needs emerge.*

### Retrieval (RAG)

| Metric | Target | Current Value | Owner | Notes |
|---|---|---|---|---|
| Noise Sensitivity | < 15% drop | | | |
| NDCG | ≥ 0.85 | | | |

### Generation

| Metric | Target | Current Value | Owner | Notes |
|---|---|---|---|---|
| Answer Correctness | ≥ 0.9 | | | |
| Semantic Similarity | ≥ 0.85 | | | |

### Safety & Trust

| Metric | Target | Current Value | Owner | Notes |
|---|---|---|---|---|
| Safety Violation Rate | < 0.1% | | | |
| Refusal Accuracy | ≥ 0.95 | | | |

### Data Governance

| Metric | Target | Current Value | Owner | Notes |
|---|---|---|---|---|
| Data Classification Accuracy | ≥ 0.95 | | | |
| PII Detection Recall | ≥ 0.98 | | | |
| PII Detection Precision | ≥ 0.9 | | | |
| Data Quality Rule Coverage | ≥ 0.9 | | | |
| Lineage Coverage | ≥ 0.85 | | | |

### Agentic AI

| Metric | Target | Current Value | Owner | Notes |
|---|---|---|---|---|
| Tool Call Success Rate | ≥ 0.95 | | | |

### ML Observability

| Metric | Target | Current Value | Owner | Notes |
|---|---|---|---|---|
| Model Drift Score (PSI) | < 0.2 | | | |
| Data Drift Score (PSI) | < 0.2 | | | |

### Business Value

| Metric | Target | Current Value | Owner | Notes |
|---|---|---|---|---|
| Adoption Rate | Growing | | | |

---

## Advanced metrics — for mature or regulated programs

*Add these 10 metrics when operating at scale, in regulated contexts, or with multi-agent systems.*

### Prompt Engineering

| Metric | Target | Current Value | Owner | Notes |
|---|---|---|---|---|
| Prompt Injection Detection Rate | ≥ 0.95 | | | |

### Agentic AI

| Metric | Target | Current Value | Owner | Notes |
|---|---|---|---|---|
| Agent Task Completion Rate | ≥ 0.8 | | | |
| Agent Handoff Success Rate | ≥ 0.9 | | | |
| Planning Accuracy | ≥ 0.85 | | | |
| Memory Retrieval Accuracy | ≥ 0.9 | | | |

### AI Governance

| Metric | Target | Current Value | Owner | Notes |
|---|---|---|---|---|
| Citation Accuracy | ≥ 0.95 | | | |
| Explainability Score | Context-defined | | | |
| Human Override Rate | Trending down | | | |
| Audit Trail Coverage | ~100% | | | |

### Business Value

| Metric | Target | Current Value | Owner | Notes |
|---|---|---|---|---|
| Business Outcome Lift | Positive vs baseline | | | |

---

## Notes & decisions

*Use this section to log threshold decisions, known gaps, or tracking blockers.*

| Date | Metric | Note |
|---|---|---|
| | | |

---

*Template source: [AI Metrics Catalog](https://luispsalas.github.io/ai-governance-scorecard/) · [GitHub](https://github.com/luispsalas/ai-governance-scorecard)*
