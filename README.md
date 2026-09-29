<div align="center">

# Xinyang Wu

**Software Engineer · Applied ML · Zürich**

Building AI applications with traceable sources, measurable behavior, and reliable delivery.

[Website](https://xinyangwuethz.github.io/) · [Engineering notes](https://xinyangwuethz.github.io/notes/) · [LinkedIn](https://www.linkedin.com/in/xinyangwu) · [Email](mailto:xinyangwuethz@gmail.com)

</div>

---

I'm a software engineer at **Miltenyi Biotec** and an **ETH Zürich MSc graduate in Information Technology and Electrical Engineering**. I build Python/FastAPI services and React/TypeScript interfaces for scientific software, including retrieval assistants and human-review workflows.

Previously, I worked on ML engineering at **Bosch** and generative AI at **ETH's Computer Vision Lab**. My interests connect applied ML with the engineering around it: data pipelines, evaluation, observability, and the decisions that turn model outputs into useful products.

## Selected projects

| Project | What to explore |
| :--- | :--- |
| **[citechunk](https://github.com/XinyangWuEthz/citechunk)**<br>RAG tooling · Python | Turn HTML and Markdown into citation-ready chunks with heading breadcrumbs, stable IDs, and source links. A dependency-free core, CLI, and offline retrieval example. [Quickstart](https://github.com/XinyangWuEthz/citechunk#quickstart-library) |
| **[Review Router](https://github.com/XinyangWuEthz/review-router)**<br>ML evaluation · Queue simulation | Compare human-review admission and queue ordering with a frozen classifier and fixed reviewer capacity. Explore reproducible results and the trade-offs behind prioritization. [Experiments](https://xinyangwuethz.github.io/review-router/) · [Write-up](https://xinyangwuethz.github.io/notes/same-model-different-review-queue/) |
| **[Abuse Signals](https://github.com/XinyangWuEthz/abuse-signals)**<br>SQL · Detection · FastAPI | Build 13 behavioral signals and compare rules with classifiers using grouped splits, calibrated thresholds, and regression gates. A personal prototype evaluated on **synthetic data**. [Reference results](https://github.com/XinyangWuEthz/abuse-signals/blob/main/benchmarks/reference/summary.md) |
| **[CoTracker for MRI](https://github.com/XinyangWuEthz/co-tracker-for-MRI)**<br>Computer vision · PyTorch | Apply Meta's CoTracker to medical-image sequences with interactive point selection and trajectory visualization. My contribution is the application workflow around the upstream tracking model. [Demo and code](https://github.com/XinyangWuEthz/co-tracker-for-MRI#readme) |

**One result, with its trade-off.** In Review Router's overloaded simulation, severity ordering completed **53.75 more high-risk reviews per 8-hour shift than FIFO**, and **53.75 fewer other reviews**, with unchanged throughput. This is an average over 20 paired seeds at 180 admitted jobs/hour; it measures allocation of simulated review capacity. [Method, assumptions, and limits →](https://github.com/XinyangWuEthz/review-router/blob/main/record/severity-sensitivity.md)

## Engineering notes

- **[RAG beyond the demo](https://xinyangwuethz.github.io/notes/rag-beyond-the-demo/)** — ingestion, citations, evaluation, and when retrieval earns its complexity.
- **[Same model, different review queue](https://xinyangwuethz.github.io/notes/same-model-different-review-queue/)** — what changes when reviewer capacity stays fixed.
- **[Observability for AI services](https://xinyangwuethz.github.io/notes/ai-service-red-metrics/)** — RED metrics, tail latency, tracing, and runbooks.

## Tools I work with

**Backend & data:** Python · FastAPI · SQL · Docker<br>
**Interfaces:** TypeScript · React · Next.js<br>
**ML & evaluation:** PyTorch · scikit-learn · retrieval pipelines · reproducible experiments<br>
**Delivery & observability:** CI/CD · GitHub Actions · OpenTelemetry · Datadog

---

Based in Zürich. Happy to connect with engineers building useful AI products, dependable backend services, and thoughtful evaluation tools.
