# Rajkumar Vijayan

**Business Analysis · Data Analytics · Technology Consulting**
MSc Software Development (International Systems), University of Limerick — graduating May 2027

> I read event logs and P&Ls with the same discipline: find where the process leaks, size the recovery conservatively, and stage the fix so the client can stop after Phase 1 if the numbers don't hold.

[Email](mailto:vijayanrajkumar478@gmail.com) · [LinkedIn](https://www.linkedin.com/in/rajkumar-vijayan-0135a8338/) · [Tableau Public](https://public.tableau.com/app/profile/rajkumar.vijayan2695/vizzes)

**Currently:** finishing Microsoft PL-300 · applying to 2027 graduate programmes in technology consulting and business analysis · available full-time from May 2027, Dublin or Limerick.

---

## Featured Projects

Three self-directed consulting studies built on public datasets. Every dataset, notebook, dashboard and deck below is in the linked repository — including the working, not just the conclusions.

### 01 — ConsultLab: process mining and business analysis on a loan-application process
*Public dataset: BPI Challenge 2017 — 1.2M events, 31,509 applications, 149 staff, 13 months*
**[Recommendation deck (PDF)](https://github.com/Rajkumar0863/consultlab/raw/main/05-deliverables/recommendation-deck.pdf) · [Repository](https://github.com/Rajkumar0863/consultlab)**

**Question:** where does a loan-application process lose value, and what should be fixed first?

- **33.1% of applications cancel after the offer is issued.** Post-offer follow-up holds **65.5% of total queue time** — 40,321 waiting days against 181 days of active handling. The bottleneck is silence, not workload.
- **73.4%** of successful applications pass through a document-incompleteness loop, adding ~5.6 days each.
- **15,930 distinct process variants**, none above 3.4% of volume — the documented process barely exists in practice.

**Recommendation:** reprioritise post-offer queues by lapse risk, then automate reminders — delivered in two stages with a decision gate. The programme breaks even at a **2.4% recovery rate** (233 of 9,629 lost applications), and Stage 1 puts €125,000 at risk instead of €245,000 while the assumption is tested.

Ten artifacts delivered: project brief, stakeholder map and RACI, as-is/to-be BPMN 2.0, BRD, user stories, traceability matrix, options assessment, business case, executive deck.

`Process Mining` · `BPMN 2.0` · `Requirements Engineering` · `BABOK v3 (applied)` · `Business Case Development`

### 02 — B2B sales pipeline: where the revenue leaks
*Public dataset: Maven CRM Sales Opportunities — 8,800 opportunities across four linked tables*
**[Interactive Tableau dashboard](https://public.tableau.com/app/profile/rajkumar.vijayan2695/viz/CRMSalesPipelineAnalysis/CRMSalesDashboard) · [Repository](https://github.com/Rajkumar0863/crm-sales-pipeline-analysis)**

- Agent win rates spread from **55% to 70%** across 30 agents, with lost revenue concentrated in three product tiers.
- Sized a conservative **~$237K recoverable opportunity** — the gain from lifting below-median agents to the team median, not the headline lost-revenue figure.
- Found and fixed a silent join failure (`GTXPro` vs `GTX Pro`) that was understating product-level loss. Every finding cross-validated across SQL, pandas and Tableau.

`SQL` · `Python` · `pandas` · `Tableau` · `Commercial Analytics`

### 03 — Retail customer growth and churn prevention
*Public dataset: UCI Online Retail — 700K+ transactions, 5,350 customers*
**[Power BI file](https://github.com/Rajkumar0863/retail-customer-growth/raw/main/customer_growth_dashboard.pbix) · [Recommendation deck](https://github.com/Rajkumar0863/retail-customer-growth/raw/main/customer_growth_deck.pptx) · [Repository](https://github.com/Rajkumar0863/retail-customer-growth)**

- RFM segmentation showed **Champions are 34.8% of customers but 75.4% of revenue** — retention spend was being distributed evenly across a base that isn't.
- Isolated high-value cohorts showing early disengagement and quantified a **£144K base-case retention opportunity**.
- Delivered as a 10-slide executive deck plus a Power BI dashboard with scenario controls.

`Python` · `RFM Segmentation` · `Power BI` · `Cohort Analysis`

*Figures are in each dataset's native currency.*

---

## How I work

1. **Start from the decision, not the dataset.** Analysis earns its place by changing what someone does on Monday.
2. **Say what the evidence cannot prove.** Co-occurrence isn't causation — which is why recommendations come staged, with a gate.
3. **Size conservatively.** Net recoverable, sensitivity-tested, never the gross figure.

---

## Also on GitHub

- **[TradeMatch Exchange](https://github.com/Rajkumar0863/TradeMatchExchange)** — Java order-matching engine: real-time order book, price-time priority matching, trade history, custom priority queues, unit-tested.
- **[C# Task Manager](https://github.com/Rajkumar0863/csharp-task-manager)** — .NET 8 backend using the repository pattern, tested with xUnit.

`Java` · `C#` · `.NET 8` · `Object-Oriented Design` · `Data Structures`

---

## Experience

**VRBB & Associates — Business Consulting Intern** · May–Jul 2024
Mapped end-to-end business development and CRM workflows and wrote the SOPs; built legal, financial and secretarial due-diligence checklists for client onboarding; designed an MIS reporting structure for visibility across active engagements.

**Amazon Development Centre — ML Data Associate** · Feb 2022–Jan 2023
Annotated and curated 100,000+ production ML data points against SLA quality targets, inside pipelines where labelling accuracy fed directly into model performance.

---

## Education and credentials

- **MSc Software Development (International Systems)** — University of Limerick, 2025–2027
- **PGDM Business Analytics** — Thiagarajar School of Management, 2023–2025
- **BCA Data Science** — B.S. Abdur Rahman Crescent Institute, 2017–2020
- Google Agile Essentials · McKinsey Forward Program · Microsoft PL-300 (in progress)

---

*Understand the problem. Establish the evidence. Design the change.*
