### Hi, I'm Louis 👋

I'm a final-year **BA (Hons) Digital Marketing & Business Analytics** student at **Robert Gordon University** (Aberdeen, UK), heading into my honours year in September. Plan: graduate June 2027, gap-year UK DS/ML role, then **MS Data Science** in the US starting autumn 2028.

Most of what I publish here sits at the intersection of **data, ML, and product** — I like building end-to-end systems where the analytics actually drives something a user sees.

---

#### 🔭 What I'm building right now

**[salespatch](https://github.com/louisgrochla/salespatch)** — a 9-agent multi-pipeline platform that researches a UK independent business, decodes its brand, generates a personalised demo website, QA's it, and routes the lead to a salesperson — all before anyone walks into the shop. Closed beta live since May 2026 in Aberdeen: 5 salespeople in the field, 40+ sellable demos for real businesses, 200+ test demos held back as future training data. TypeScript / Next.js 14 / Supabase Postgres / Stripe Connect / Swift (iOS), with a SQLite-backed agent runtime at the core.

Live anonymised platform metrics — pitch flow, conversion, cost per demo, revenue — are published openly at **[nerve.salespatch.co.uk](https://nerve.salespatch.co.uk)**. It's the data source for my 4th-year university dissertation on the self-learning multi-agent system underneath salespatch.

The interesting part for me as a DS-track student: the system has its own data layer (NERVE) that captures every pitch outcome and demo performance metric. Once enough outcomes accumulate, the plan is to replace LLM stages with fine-tuned critic models trained on real field data — a self-improving loop where the system collects its own training data as a byproduct of operating. That's where most of my hands-on ML / agent-eval work lives: prompt versioning, golden-set evaluation, and getting LLMs to produce reliable structured output at production volume.

---

#### 📊 Recent portfolio work

**[ds-llm-judge-vs-small-model](https://github.com/louisgrochla/ds-llm-judge-vs-small-model)** — *when does a fine-tuned in-house classifier beat the frontier LLM?* A real benchmark on Banking77: in-house DistilBERT matches Claude Sonnet 4.6 at **n=2,500 labeled examples**, peaks at macro-F1 = 0.934 at n=9,000 — at **~750× lower cost per query** and **~50× faster latency**. Includes an [interactive build-vs-buy calculator](https://louisgrochla.github.io/ds-llm-judge-vs-small-model/) for teams currently paying for LLM API classification. Python / Transformers / Gradio.

The methodology piece I'd point a recruiter at first: the first sweep with conservative defaults hit macro-F1 = 0.77 — well below the LLM. Diagnosed the issue (model had converged at the conservative LR; std=0.009 confirmed it), made four targeted hyperparameter changes, retuned. Same model, same data: 0.93. The "diagnose → fix → verify" loop in a clean form.

---

#### 📊 What I'm focused on technically

- **Applied ML / data science** — currently strongest in classical ML, EDA, statistical inference; building toward deeper DL + causal inference for grad school
- **LLM engineering** — agent orchestration, evaluation harnesses, prompt regression testing, retrieval
- **Full-stack delivery** — Next.js, TypeScript, Python, SQL (Postgres + SQLite), light DevOps
- **Tools I reach for:** pandas, scikit-learn, PyTorch (learning), TypeScript, Next.js, Prisma, Supabase

---

#### 📚 Coursework this year

Machine Learning · Business Intelligence · Software Design & Development · Data Analytics for Business Decisions

---

#### 📈 What's next

- Honours dissertation (4th year) — pitching it toward an ML / NLP application of the work I'm already doing at salespatch
- Additional DS portfolio projects in the pipeline (LLM eval harness extracted from salespatch, end-to-end ML system with FastAPI deploy, paper reproduction)
- UK grad-year DS/ML applications open October 2026 — that's the immediate focus
- US MS Data Science applications follow in autumn 2027, for autumn 2028 entry

---

#### 📫 Get in touch

- **LinkedIn:** [linkedin.com/in/louisgrochla](https://www.linkedin.com/in/louisgrochla/)
- **Email:** louisgrochla27@gmail.com

---

<sub>Based in Aberdeen, Scotland. Building DS portfolio projects ahead of UK grad-year DS/ML applications opening October 2026.</sub>
