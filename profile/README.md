<div align="center">

<img src="https://raw.githubusercontent.com/K11-Software-Solutions/.github/main/assets/K11_Hero_banner.png" alt="K11 Software Solutions — AI-Powered Software and Digital Platforms" width="100%">

# K11 Tech Lab

**Open-source labs for testing AI systems the way we test software: runnable, measurable, gated in CI.**

Every lab runs locally with **no API key**. Clone, `pytest`, and watch an AI system pass or fail.

[![Follow on GitHub](https://img.shields.io/github/followers/K11-Software-Solutions?label=Follow&style=social)](https://github.com/K11-Software-Solutions)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Kavita%20Jadhav-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kavita-jadhav-tech/)
[![Newsletter: Trustworthy AI Engineering](https://img.shields.io/badge/Newsletter-Trustworthy%20AI%20Engineering-0A66C2)](https://www.linkedin.com/newsletters/trustworthy-ai-engineering-7521267953363832832/)
[![Newsletter: SDET Insights](https://img.shields.io/badge/Newsletter-SDET%20Insights-0A66C2)](https://www.linkedin.com/newsletters/sdet-insights-7354009267919613954/)

</div>

---

## 🧭 Start here: the AI Quality Engineering curriculum

New to testing AI? Start with the roadmap, then work through the labs in order. Each one ends with CI quality gates and negative controls, so you can see the tests catch real failures.

| # | Lab | What you'll learn to test |
|---|-----|---------------------------|
| 0 | [**becoming-ai-quality-engineer**](https://github.com/K11-Software-Solutions/becoming-ai-quality-engineer) | The roadmap: skills, tools, and a runnable RAG project with pytest, Playwright, Promptfoo and DeepEval |
| 1 | [llm-model-testing-lab](https://github.com/K11-Software-Solutions/llm-model-testing-lab) | Build a tiny GPT, then evaluate a real open-weights LLM: calibration, safety, bias, memorisation, quantization drift |
| 2 | [ai-evaluation-science-lab](https://github.com/K11-Software-Solutions/ai-evaluation-science-lab) | How far to trust an evaluator: LLM-judge bias, reliability statistics, sample sizes, drift |
| 3 | [ai-data-quality-lab](https://github.com/K11-Software-Solutions/ai-data-quality-lab) | Eval contamination, wrong labels, stale RAG documents, personal data, data contracts |
| 4 | [ai-security-testing-lab](https://github.com/K11-Software-Solutions/ai-security-testing-lab) | Prompt injection, jailbreaks, prompt leakage, exfiltration, excessive agency, with attack success rates |
| 5 | [agent-testing-lab](https://github.com/K11-Software-Solutions/agent-testing-lab) | Agents that take real actions: tools, approvals, trajectories, pass^k reliability |
| 6 | [multi-agent-testing-lab](https://github.com/K11-Software-Solutions/multi-agent-testing-lab) | Agent handoffs, relayed injection, blame assignment, loops, compounding failure |
| 7 | [mcp-testing-lab](https://github.com/K11-Software-Solutions/mcp-testing-lab) | The MCP supply chain: tool poisoning, rug pulls, cross-server shadowing |
| 8 | [ai-performance-cost-lab](https://github.com/K11-Software-Solutions/ai-performance-cost-lab) | Latency percentiles, time to first token, retry storms, cost per resolved request |
| 9 | [ai-production-monitoring-lab](https://github.com/K11-Software-Solutions/ai-production-monitoring-lab) | Tracing, online evals, drift, guardrails, shadow releases, incident triage |
| 🎓 | [**ai-assurance-case-lab**](https://github.com/K11-Software-Solutions/ai-assurance-case-lab) | Capstone: turn the evidence into one release argument mapped to NIST AI RMF, ISO/IEC 42001 and the EU AI Act |

> ⭐ **Star the labs you use.** It's the fastest way to help other engineers find them.

---

## 📄 Research: Agentic AI Quality Engineering (IJECS, 2026)

A six-paper, peer-reviewed series. Every paper ships with open-source reference code.

| Paper | Code |
|-------|------|
| [Autonomous CI/CD Quality Assurance Using LangGraph Multi-Agent Orchestration and Risk-Proportionate Human-in-the-Loop Control](https://doi.org/10.18535/ijecs/v15i06.5563) | [agentic-ai-qa-system](https://github.com/K11-Software-Solutions/k11techlab-agentic-ai-qa-system) |
| [LLM Safety as a Quality Gate: Bias, Fairness and Robustness Evaluation in CI/CD via GitHub Apps](https://doi.org/10.18535/ijecs.v15i07.5576) | [llm-eval-agent-app](https://github.com/K11-Software-Solutions/llm-eval-agent-app) |
| [Beyond Static Gates: Closing the Detect–Fix–Learn Loop in Agentic CI/CD Quality Assurance](https://doi.org/10.18535/ijecs.v15i07.5577) | — |
| [Cross-Repository Contract Testing and Change Impact Analysis in Microservice CI/CD](https://doi.org/10.18535/ijecs.v15i07.5599) | [microservice-qa-system](https://github.com/K11-Software-Solutions/k11techlab-microservice-qa-system) |
| [Beyond Binary Verdicts: Aleatoric Uncertainty Quantification in Agentic CI/CD Quality Pipelines](https://doi.org/10.18535/ijecs.v15i07.5614) | — |
| [Beyond a Single Threshold: Uncertainty Source Classification and Type-Stratified Conformal Prediction for Agentic CI/CD](https://doi.org/10.18535/ijecs.v15i08.5684) | — |

---

## 🛠️ Tools you can use today

- **[LLM Assurance Toolkit](https://github.com/K11-Software-Solutions/k11techlab-llm-assurance-toolkit)**: 41 OWASP LLM Top 10 probes, a CI quality gate, audit-ready HTML reports, an LLM judge, and an MCP server for agent-driven red-teaming.
- **[LLM Eval Agent](https://github.com/K11-Software-Solutions/llm-eval-agent-app)**: a GitHub App that posts bias, fairness and robustness scorecards as Check Runs on every pull request.
- **[Microservice QA System](https://github.com/K11-Software-Solutions/k11techlab-microservice-qa-system)**: catches breaking API contract changes at PR time (100% precision and recall across 74 real pull requests).
- **[Carbon-Aware CI Scheduler](https://github.com/K11-Software-Solutions/k11techlab-carbon-aware-ci-scheduler)**: routes test suites to low-carbon grid windows, cutting CI emissions by 31.4% with no quality regression.
- **[LLM Testing Hub](https://github.com/K11-Software-Solutions/llm-testing-hub)**: prompt regression, red-teaming and risk audits with Promptfoo, LangTest and DeepEval.

## 🧪 Test automation frameworks

Production-style starters with page objects, CI pipelines, reporting and AI-assisted test generation.

| Stack | Repository |
|-------|------------|
| Playwright + Python | [playwright-python-ai-assisted-framework](https://github.com/K11-Software-Solutions/k11techlab-playwright-python-ai-assisted-framework) |
| Playwright + TypeScript | [playwright-typescript-ai-augmented-framework](https://github.com/K11-Software-Solutions/K11TechLab-playwright-typescript-ai-augmented-framework) |
| Playwright + JavaScript | [playwright-javascript-ai-augmented-framework](https://github.com/K11-Software-Solutions/K11TechLab-playwright-javascript-ai-augmented-framework) |
| Vibium + Jest + TypeScript | [vibium-jest-ai-test-framework](https://github.com/K11-Software-Solutions/k11TechLab-vibium-jest-ai-test-framework) |
| Selenium + Java | [selenium-java-fullstack-framework](https://github.com/K11-Software-Solutions/k11TechLab-selenium-java-fullstack-framework) |
| Cucumber BDD + Java | [cucumber-bdd-java-fullstack-framework](https://github.com/K11-Software-Solutions/k11TechLab-cucumber-bdd-java-fullstack-framework) |
| Serenity BDD Screenplay | [serenity-screenplay-framework](https://github.com/K11-Software-Solutions/k11TechLab-serenity-screenplay-framework) |

---

## 👩‍💻 Who's behind this

K11 Tech Lab is run by **[Kavita Jadhav](https://www.linkedin.com/in/kavita-jadhav-tech/)**, Senior SDET and AI Quality Engineer with 12+ years of test automation for VMware, E\*TRADE/Morgan Stanley, Verizon, Delta Dental and Wells Fargo.

**Stay in the loop**
- 📬 [Trustworthy AI Engineering](https://www.linkedin.com/newsletters/trustworthy-ai-engineering-7521267953363832832/): practical AI assurance, every two weeks
- 📬 [SDET Insights](https://www.linkedin.com/newsletters/sdet-insights-7354009267919613954/): test automation, weekly
- 🌐 [k11softwaresolutions.com](https://k11softwaresolutions.com/) · [softwaretestautomation.org](https://www.softwaretestautomation.org/)

<div align="center">

**If these labs save you time, follow the org and star a repo. That's how this stays free.**

</div>
