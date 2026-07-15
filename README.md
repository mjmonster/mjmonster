## Mengyan Ji

Full-stack engineer building **LLM agent systems** — agents that are safe, evaluated, and cheap to run. 7+ years of backend depth (Java / Spring, security-critical banking platforms at Citibank), now designing and shipping AI agent products end to end.

What I care about isn't just wiring up an agent — it's *knowing it works and shipping it safely*: evaluation harnesses, red-line / anti-hallucination guardrails, retrieval quality, safe tool/data integration, and cost/latency you can actually measure.

### Featured

- **[llm-agent-evals](https://github.com/mjmonster/llm-agent-evals)** — a runnable harness for evaluating LLM agents: behavioural / tool-routing + red-line evals, RAG recall@k, LLM-as-judge, and cost/latency benchmarking. Runs offline with zero API cost. Distilled from the eval tooling I built for two production agent systems.
- **[fit-agent-mcp](https://github.com/mjmonster/fit-agent-mcp)** — a security-conscious **MCP** integration: a health-data **MCP server** with per-user authorization (identity derived from a JWT `sub` claim only, least-privilege scopes, audit log) and a **LangGraph** coach agent that consumes it as a host. The point is the security model — it defeats the confused-deputy / prompt-injection attack because the user's identity never comes from the model.
- **[auto_grad](https://github.com/mjmonster/auto_grad)** — a small autograd / backprop engine built from scratch (following Karpathy's *Neural Networks: Zero to Hero*), to understand what's under the models I build on.

### Background

- Built and shipped **two production agent platforms**: a WeChat customer-service AI agent in **Python** (function-calling harness, RAG, evaluation tooling) sold to 50+ clients, and a **Java** multi-provider agent (OpenAI / Anthropic / GLM, tool-calling, its own eval harness). These are commercial and private — the public repos above are neutral-domain demos of the same techniques.
- 7+ years at **Citibank** on security-critical platforms — encryption, HSM, messaging durability, and vulnerability remediation under MAS / HKMA / OJK compliance. I bring that governance instinct to AI systems.

### Currently

Deepening ML fundamentals, and open to **AI-agent / applied-LLM engineering** roles.

**Reach me:** [LinkedIn](https://linkedin.com/in/mengyan-ji-83641b347) · mengyanji1996@163.com
