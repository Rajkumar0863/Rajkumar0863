# Rajkumar Vijayan

**Business Analysis · Data Analytics · Technology Consulting**  
MSc Software Development (International Systems), University of Limerick — graduating May 2027

[Email](mailto:vijayanrajkumar478@gmail.com) · [LinkedIn](https://www.linkedin.com/in/rajkumar-vijayan-0135a8338/) · [Tableau Public](https://public.tableau.com/app/profile/rajkumar.vijayan2695/vizzes)

> I came to software development from business analytics, so I tend to arrive at a technical problem asking what decision it is supposed to change. Most of my work sits in that overlap — reading a process closely enough to find where it actually fails, then building the analysis and the documentation that let someone act on it.

**Currently:** preparing for Microsoft PL-300 · applying to 2027 graduate programmes in technology consulting and business analysis · open to Dublin or Limerick.

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

### VRBB & Associates (Chartered Accountants) — Business Consulting Intern
*Sivakasi, India · May – July 2024*

Supported the partner team on advisory engagements for owner-managed businesses, across due diligence, process analysis and management reporting.

- **Due diligence.** Reviewed financial and legal documents provided for client engagements, working through them for inconsistencies, missing evidence, and assumptions that weren't yet supported by what the client had supplied. Turned each gap into a specific follow-up question rather than a general flag, and surfaced findings for partner review. The habit it built: keep what is verified, what is stated, what is assumed and what is still open in separate columns before anyone acts on any of it.
- **Lead-generation intake.** Enquiries arrived with inconsistent levels of detail, which made it slow to see where an opportunity stood or who owned the next step. I analysed the intake process end to end and proposed a consistent capture structure — prospect, requirement, source, stage, next action, ownership — treating enquiries as one pipeline rather than separate conversations. The constraint wasn't generating more leads; it was seeing the ones already there.
- **Management information.** Information on enquiries and ongoing work existed but sat fragmented, so partners had to assemble the picture case by case. I worked backwards from the questions management actually needed answered — what's active, what's stuck, who owns the next action — and contributed to structuring reporting around status, ownership, next action and outcome.
- **Client-facing work.** Sat in on client meetings and translated open-ended discussion into documented requirements and agreed follow-ups. Most of consulting turned out to be exactly this: getting a vague conversation into a written form both sides will stand behind.

### Amazon Development Centre — ML Data Associate
*Chennai, India · February 2022 – January 2023*

A year in the data layer that every downstream model quietly depends on.

- **Annotation at volume.** Annotated and curated 100,000+ production data points against defined guidelines and SLA quality targets, on a consumer robotics programme.
- **Pattern, not symptom.** A run of annotation errors kept recurring across scenarios. Rather than correcting each as an isolated case, I compared the affected scenarios to isolate what they had in common, found the errors concentrated around one scenario category the guidelines didn't cleanly cover, and reframed the issue as a probable gap in the annotation framework rather than a labelling mistake. I raised the pattern with the team and recommended the category be captured explicitly so future data would represent it properly. The adoption decision wasn't mine — the contribution was the pattern and the recommendation.
- **Why it still shapes how I work.** Mislabelled data doesn't announce itself; it surfaces months later as model behaviour that modelling alone can't fix. That year is why I look at errors collectively before fixing them individually — and why the silent `GTXPro` / `GTX Pro` join failure in Project 02 got caught rather than quietly understating the numbers.

---

## Leadership

**Core Committee Member, Entrepreneurship Cell — Thiagarajar School of Management** · 2023–2025  

- **Sponsorship.** Held 15–20 sponsor relationships directly — negotiating terms, closing arrangements and managing them through to delivery. One collaboration was still unconfirmed in the final week before a major event; understanding what was actually blocking the sponsor, rather than pressing for a commitment, got it agreed without the negotiation turning adversarial.
- **Event delivery.** Responsible for IT and promotions for an entrepreneurship event with 1,000+ attendees — translating what non-technical event teams needed into technical requirements, coordinating the IT team, and proposing a targeted promotional approach that identified the audience before choosing channels.
- **Event website.** Built the event site carrying information, registration and sponsor presence, replacing scattered communication with a single point of reference.
- **External engagement.** Coordinated E-Cell participation at a Tamil Nadu startup event in Madurai, putting members in front of founders, investors and senior industry leaders outside the college environment.

---

## Education and credentials

- **MSc Software Development (International Systems)** — University of Limerick, 2025–2027
- **PGDM Business Analytics** — Thiagarajar School of Management, 2023–2025
- **BCA Data Science** — B.S. Abdur Rahman Crescent Institute, 2017–2020
- Google Agile Essentials · McKinsey Forward Program · Microsoft PL-300 (exam preparation)

---

*Understand the problem. Establish the evidence. Design the change.*
