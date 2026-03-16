# Interview Prep — Full Stack (Beginner to Pro)

Structured interview-prep notes: **Gen AI & LLM** and **Python**. Each topic has a learning path from fundamentals to production. Use this page to navigate by **level** or by **topic**.

---

## Topics by level

### Beginner

Foundations: how things work and core concepts.

| Topic | Description | Link |
| :--- | :--- | :---: |
| **[LLM Fundamentals](GEN-AI/LLM-Fundamentals/README.md)** | How LLMs work: tokens, context window, attention, temperature, sampling | [Open](GEN-AI/LLM-Fundamentals/README.md) |
| **[Prompt Engineering](GEN-AI/Prompt-Engineering/README.md)** | What is prompt engineering, system vs user prompts, zero-shot vs few-shot | [Open](GEN-AI/Prompt-Engineering/README.md) |
| **[Python](Python/README.md)** | Types, namespaces, control flow, mutability basics | [Open](Python/README.md) |

---

### Intermediate

Core building blocks: retrieval, evaluation, safety, and language depth.

| Topic | Description | Link |
| :--- | :--- | :---: |
| **[RAG](GEN-AI/RAG/README.md)** | Retrieval-Augmented Generation: chunking, embeddings, retrieval, vector stores, generation | [Open](GEN-AI/RAG/README.md) |
| **[Evaluation](GEN-AI/Evaluation/README.md)** | Eval sets, retrieval/generation metrics, LLM-as-judge, RAGAS, regression, CI | [Open](GEN-AI/Evaluation/README.md) |
| **[Guardrails](GEN-AI/Guardrails/README.md)** | Input/output validation, PII, safety, prompt injection, implementation | [Open](GEN-AI/Guardrails/README.md) |
| **[Memory](GEN-AI/Memory/README.md)** | Conversation memory, buffer/summary, entity memory, RAG + memory, privacy | [Open](GEN-AI/Memory/README.md) |
| **[Structured Output](GEN-AI/Structured-Output/README.md)** | Reliable JSON/schema from LLMs, parsing, validation, JSON mode, function calling | [Open](GEN-AI/Structured-Output/README.md) |
| **[Hallucination](GEN-AI/Hallucination/README.md)** | What hallucination is, causes, mitigation (RAG, grounding, citations), detection | [Open](GEN-AI/Hallucination/README.md) |

---

### Advanced

Agents, model improvement, and infrastructure.

| Topic | Description | Link |
| :--- | :--- | :---: |
| **[Agents](GEN-AI/Agents/README.md)** | LLM agents, tools, ReAct, plan-and-execute, implementation, safety | [Open](GEN-AI/Agents/README.md) |
| **[Fine-Tuning](GEN-AI/Fine-Tuning/README.md)** | When to fine-tune vs RAG, LoRA/QLoRA, instruction tuning, data, deployment, RLHF/DPO | [Open](GEN-AI/Fine-Tuning/README.md) |
| **[Inference & Serving](GEN-AI/Inference-Serving/README.md)** | Serving LLMs: vLLM, TGI, batching, PagedAttention, quantization, deployment | [Open](GEN-AI/Inference-Serving/README.md) |
| **[Cost Optimization](GEN-AI/Cost-Optimization/README.md)** | Token usage, caching, model choice, budgets, tracking, API vs self-host | [Open](GEN-AI/Cost-Optimization/README.md) |

---

### Expert

Multi-agent systems, workflows, protocols, and multimodal.

| Topic | Description | Link |
| :--- | :--- | :---: |
| **[Multi-Agents](GEN-AI/Multi-Agents/README.md)** | Multi-agent systems, orchestrator, handoffs, debate, role specialization | [Open](GEN-AI/Multi-Agents/README.md) |
| **[Agentic Workflow](GEN-AI/Agentic-Workflow/README.md)** | Agentic workflows, decision points, human-in-the-loop, state, observability | [Open](GEN-AI/Agentic-Workflow/README.md) |
| **[MCP](GEN-AI/MCP/README.md)** | Model Context Protocol: servers, tools, resources, clients, security | [Open](GEN-AI/MCP/README.md) |
| **[Multimodal](GEN-AI/Multimodal/README.md)** | Vision + language, VLMs, CLIP, image understanding, multimodal RAG | [Open](GEN-AI/Multimodal/README.md) |

---

### Pro

Production readiness, operations, and scale.

| Topic | Description | Link |
| :--- | :--- | :---: |
| **[Observability](GEN-AI/Observability/README.md)** | Logging, tracing, metrics, trace_id, redaction, SLOs, debugging LLM apps | [Open](GEN-AI/Observability/README.md) |

*(Production and advanced material for other topics live inside each topic’s **Production & Advanced** doc.)*

---

## How to use

- **By level:** Start with **Beginner**, then move through **Intermediate**   **Advanced**   **Expert**   **Pro**.
- **By topic:** Open a topic’s **Entry point** (README) and follow its learning path (e.g. Fundamentals   Strategies   Implementation   Production).
- **By question:** Use each topic’s **Quick reference** (“If they ask…”) inside its README to jump to the right doc.

---

## Folder structure

```
interview-prep/
├── README.md                 ← you are here (all topics by level)
├── Python/                   ← Python interview prep (Beginner–Intermediate)
│   ├── README.md
│   ├── python-fundamentals.md
│   ├── python-object-model-identity-mutability-memory.md
│   └── python-implementation.md
└── GEN-AI/                   ← Gen AI & LLM (Beginner to Pro)
    ├── README.md             ← Gen AI topic index
    ├── LLM-Fundamentals/
    ├── Prompt-Engineering/
    ├── RAG/
    ├── Agents/
    ├── Multi-Agents/
    ├── Agentic-Workflow/
    ├── MCP/
    ├── Memory/
    ├── Evaluation/
    ├── Guardrails/
    ├── Structured-Output/
    ├── Hallucination/
    ├── Inference-Serving/
    ├── Multimodal/
    ├── Cost-Optimization/
    └── Observability/
```

---

## Quick links

- **Gen AI only:** [GEN-AI/README.md](GEN-AI/README.md) — all Gen AI topics in one index.
- **Python only:** [Python/README.md](Python/README.md) — Python fundamentals, object model, implementation.
