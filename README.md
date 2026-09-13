# Hlib Havryliuk

**Product manager, AI builder and pipeline engineer.**

I decide what an AI pipeline should do, then build the runtime that does exactly that. Nine years in product across fintech, mobility and SaaS. Based in Berlin.

---

### What I'm building now

**LeanOS** *(private)* — a deterministic runtime for generative pipelines that cross vendor boundaries. A run cannot report `completed` while a required step is silently absent; it raises. Every step records whether a human or a machine decided it. A raw hand-off between two vendors refuses before the credit is spent, and an override is a logged operator act rather than a quiet fallback.

Proven on real runs: three live vendors (ComfyUI, Magnific, Higgsfield) behind one adapter Protocol, the same captured recipe executed on all three, cross-vendor transfer on two pairs with a gate at the seam — Magnific→Higgsfield image→video 4/4, ComfyUI↔Magnific 13/13 in 684s. Python, FastAPI, Postgres, Pydantic, pytest, strict mypy.

---

### Systems I've shipped in the open

**[AI-interview-](https://github.com/HlibHav/AI-interview-)** — Multi-agent system that runs qualitative interviews end to end: goal clarification, script planning, live conversation, synthesis. Real-time sentiment and dynamic follow-up generation. Next.js + LangChain + Weaviate.

**[AI-webbrowser](https://github.com/HlibHav/AI-webbrowser)** — Agentic research browser. Multi-pass RAG with three-stage reasoning and confidence scoring, unified vector (Weaviate) + full-text (Typesense) retrieval, local model support via Apple OpenELM (270M–3B). React + Node + Phoenix/OpenTelemetry.

**[Carelink](https://github.com/HlibHav/Carelink)** — Elderly-support platform: dialogue, coach and safety agents on event-driven microservices with Weaviate-backed memory.

**[MMS](https://github.com/HlibHav/MMS)** — Six-agent retail campaign co-pilot built in a 14-hour hackathon: briefing, baseline forecast, scenario lab, optimisation, creative, post-mortem. LangChain + FastAPI + DuckDB.

<details>
<summary>Earlier data work</summary>

**[CitiBike Analytics](https://github.com/HlibHav/New-York-s-CitiBike-trips-in-2025)** — 1M+ trips, weather correlation 0.768, geospatial filtering in Streamlit.

**[Taxi Fraud Detection](https://github.com/HlibHav/Taxi)** — 0.94 ROC AUC on 200K+ transactions; clustering plus geographic risk patterns.

</details>

---

### How I work

Product side: discovery, specs, and deciding what is worth building at all. Pipeline side: adapter protocols, gate and override semantics, per-step run accounting, LangGraph state machines, RAG over vector + full-text, observability with Phoenix and OpenTelemetry. I hold the line that a system should refuse rather than lie: if a step didn't run, the record says so.

🌐 [hlib.work](https://hlib.work) · [LinkedIn](https://linkedin.com/in/glebaz) · glib.gavryliuk@gmail.com
