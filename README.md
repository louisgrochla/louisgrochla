# Louis Grochla

**Final-year BA (Hons) Digital Marketing & Business Analytics — Robert Gordon University, Aberdeen.**
I build end-to-end systems where the data actually drives the product. Focused on a data science and ML career in the UK, starting with a graduate role from 2027.

[LinkedIn](https://www.linkedin.com/in/louisgrochla/) · louisgrochla27@gmail.com · Aberdeen, Scotland

---

## Featured work

### [ds-llm-judge-vs-small-model](https://github.com/louisgrochla/ds-llm-judge-vs-small-model) — when does a fine-tuned in-house model beat the frontier LLM?

A reproducible benchmark on Banking77 (77 banking intents). A fine-tuned DistilBERT matches **Claude Sonnet 4.6** from **n = 2,500** labelled examples and reaches **macro-F1 0.934** at n = 9,000 — at **~750× lower cost** and **~50× faster** per query.

<a href="https://github.com/louisgrochla/ds-llm-judge-vs-small-model">
  <img src="https://raw.githubusercontent.com/louisgrochla/ds-llm-judge-vs-small-model/main/results/figures/crossover.png" width="540" alt="Macro-F1 crossover: fine-tuned DistilBERT vs Claude Sonnet 4.6 by training-set size">
</a>

The part I'd point a recruiter at: the first sweep stalled at F1 0.77. I diagnosed convergence at the conservative learning rate (std 0.009 across seeds confirmed it), made four targeted changes, and retuned to 0.93 on the same model and data. Diagnose → fix → verify, in a clean form.

`Python` · `PyTorch` · `Hugging Face Transformers` · [interactive build-vs-buy calculator](https://louisgrochla.github.io/ds-llm-judge-vs-small-model/)

### [salespatch](https://github.com/louisgrochla/salespatch) — multi-agent LLM platform (closed beta, Aberdeen)

Nine LLM agents research a UK independent business, decode its brand, generate a personalised demo website, QA it, and route the lead — before anyone walks into the shop. Live since May 2026: **5 salespeople in the field, 40+ bespoke demos for real businesses (10 now paying clients), 200+ test demos** held back as training data. A data layer (NERVE) captures every outcome, so LLM stages can later be swapped for fine-tuned critic models — a system that collects its own training data as it runs.

`TypeScript` · `Next.js` · `Python` · `Supabase Postgres` · `Stripe Connect` · [live metrics](https://nerve.salespatch.co.uk)

---

## Focus

- **Applied ML / data science** — classical ML, EDA, statistical inference, and hands-on transformer fine-tuning; building toward deeper DL and causal inference
- **LLM engineering** — agent orchestration, evaluation harnesses, prompt regression testing, retrieval
- **Full-stack delivery** — Next.js, TypeScript, Python, SQL (Postgres + SQLite)

---

## Now

- **Honours dissertation** — an applied ML / NLP study built on salespatch's outcome data
- **In the pipeline** — an LLM eval harness, an end-to-end ML system with a FastAPI deploy, a paper reproduction
- **Applications** — UK DS/ML graduate roles from October 2026

Coursework: Machine Learning · Business Intelligence · Software Design & Development · Data Analytics for Business Decisions

---

📫 [LinkedIn](https://www.linkedin.com/in/louisgrochla/) · louisgrochla27@gmail.com
