# Rishabh Banola | Revenue Operations & GTM

MBA (STEM, Business Analytics) · 8+ years across biotech, SaaS, EdTech, healthcare, manufacturing and infrastructure.
I build the systems behind revenue: CRM architecture, lead gen, outbound GTM, channel sales, forecasting, KPI reporting and P&L.

> **All data in these repositories is synthetic.** The fictional company is **RB Tech**. Real employers, customers, prices and contacts never appear here. Only the methods, structures and logic come from real work.

---

## Highlights

Illustrative results from the synthetic projects below. Each links to the full write-up, diagrams, data and a script that regenerates it.

| Area | What it shows | Headline result |
|---|---|---|
| Lead scoring | Engagement-only score replaced by fit + engagement + intent, back-tested | MQL buy rate 3.3% to 11.2%; ranking power (AUC) 0.58 to 0.73 |
| CRM data | Marketing-tier cleanup and a clean segment field | Tier 94% full to 58%; classified contacts 55% to 88% |
| Service desk | Ticketing, phone menu, SLAs, AI triage, loop guardrails | First-response SLA met 29% to 88%; 92% of tickets auto-routed at 99% accuracy |
| Systems | Six-layer lead-to-cash architecture with a 12-connection register | Deal-won to invoice 7.8 to 4.4 days; order exceptions 19% to 5% |
| Pricing | Four-method shipping cost analysis with Monte Carlo | All methods agree near $211 a shipment against a $100 charge; zone tiers cut below-cost shipments 55% to 33% |
| Channel | Distributor scorecard, marketplace feeds, duplicate and discrepancy checks | Channel share planned from 2% to 21% of revenue; every listing verified against the master before launch |
| Voice of customer | Capture standard and post-event dashboard across six events | Stem cell summit turned 52% of VOC entries into leads and 15% into deals; webinars 20% and 3% |
| Pipeline | Stage conversion, ageing, coverage and a CRM-as-a-factory utilisation model | Coverage 2.4x against a 3x target; only 41% of CRM records ever worked, 2% won |
| Events | Full-cost trade show model with repeat, change or drop rule | Best shows return $1.7 to $2.0 gross profit per $1; weakest $0.4 to $0.7 |
| Data governance | CRM migration with reconciliation, quality score and tested backups | Data-quality score 69% to 92%; 312 silently missing records caught and reloaded |
| Partners | Onboarding steps, partner scorecard and cross-partner catalog audit | marketplace onboarding about half the time of distributors |
| Territory and pay | Balanced territories, international routing, quota blend, compensation design | Territory gap 40% to under 1%; simulated cost of sales about 15% |
| Operating system | Goal tracker, RACI with one owner per process, KPI dictionary | 12 of 12 processes with a single accountable role; one source of truth per KPI |
| Forecasting | Sales scenarios by forecast category (commit, best case, pipeline) and product demand with stock cover | Two simple forecasts instead of many financial models: scenarios for leaders, reorder flags for operations |
| Planning | Reverse-funnel lead plan, budget, driver-based forecast, cash flow | Plan versus actual by channel; scenarios from -15% close rate to +10% pipeline |
| Outbound | Suppress-first lead pilot and send discipline | 473 usable leads vs 128 for the same budget; 38 sends per reply vs 947 |

## The company in this portfolio (RB Tech)
| Item | Value used throughout |
|---|---|
| Annual revenue | About $3.8M plan, about $3.2M forecast |
| Catalogue products | About $1.7M a year, low ticket (about $2,000 per order, range $100 to $12,000) |
| Custom projects | About $2.1M a year, high ticket (about 14 projects at about $150,000, billed as a deposit plus milestones) |
| Free samples | About 220 a year, no revenue, tracked separately |
| CRM pipelines | Three separate pipelines: catalogue products, custom projects and free samples |
| Team and data | 4 reps, about 60,000 CRM contacts, about 1,500 orders and 2,400 support tickets a year |
All data is synthetic, and every project uses these same figures.

## How I work
- **Six Sigma (DMAIC)** for funnel and process improvement: define, measure, analyse, improve, control. See the [sales funnel and its factors](https://github.com/rbanola1/RevOps-Portfolio/blob/main/11-pipeline-health-analysis/docs/sales_funnel_and_factors.md) and the [Green Belt project](https://github.com/rbanola1/SixSigma_Green_Belt).
- **STAR stories:** every project README opens with Starting point, Situation, Task, Action and Result.
- **Built from scratch:** most systems here started with no usable history, so first versions used labelled assumptions that were replaced by actual data as it accumulated.

## Experience map

```mermaid
mindmap
  root((RevOps & GTM))
    Revenue Operations
      CRM architecture
      Lifecycle and lead scoring
      Forecasting and sales velocity
      KPI and BI dashboards
      Data quality and hygiene
    GTM Strategy
      ICP and segmentation
      Outbound plays and sequences
      Signals and intent
      Pricing and positioning
      Product launches
    Channel Sales
      Distributors
      B2B marketplaces
      Partner programs
    Systems Integration
      HubSpot Sales and Service Hub
      ERP and accounting sync
      Ecommerce to fulfilment
      Support ticket automation
    Finance and P&L
      Cash flow projections
      Demand planning
      Business cases and ROI
    Industries
      Biotech and life sciences
      SaaS and EdTech
      Healthcare and medtech
      Manufacturing
      Infrastructure
```

## Career timeline

```mermaid
timeline
    title Where the skills were built
    2016-2017 : EdTech SaaS : Territory growth, referral loops, churn reduction
    2018-2021 : Infrastructure and SaaS : $1.2M P&L, 40+ channel partners, subscription launch
    2021-2022 : Pharma : Product launches, forecasting, collections
    2023-2024 : MBA and internships : Medtech strategy, BI for audit, SaaS GTM
    2024-Now : Biotech : Full RevOps stack, GTM engine, channel build-out
```

## Skills by domain

| Domain | What I do | Tools |
|---|---|---|
| RevOps | Funnel design, scoring, routing, forecasting, reporting | HubSpot, Salesforce, Power BI, Tableau |
| GTM | ICP, outbound plays, sequences, signal-based prospecting | HubSpot, Clay, LinkedIn |
| Channel | Distributor and marketplace programs, partner onboarding | B2B platforms, pricing sheets |
| Systems | CRM to order to invoice integration, support automation | HubSpot, Fishbowl, QuickBooks, WooCommerce |
| Analytics | KPI frameworks, dashboards, data quality monitoring | Power BI, Alteryx, Python, SQL |
| Quality | Process improvement | Six Sigma Green Belt |

## Certifications

- [HubSpot Revenue Operations Certification](https://app.hubspot.com/academy/achievements/fh840wh9/en/1/rishabh-banola/revenue-operations)
- Six Sigma Green Belt (see [project](https://github.com/rbanola1/SixSigma_Green_Belt))

## Projects

### [RevOps-Portfolio](https://github.com/rbanola1/RevOps-Portfolio): revenue operations
| # | Project | What it shows |
|---|---|---|
| 01 | [Sales KPI dashboard](https://github.com/rbanola1/RevOps-Portfolio/tree/main/01-sales-kpi-dashboard) | Executive and weekly team reporting, KPI definitions, funnel and forecast views |
| 02 | [CRM cleanup, segmentation and scoring](https://github.com/rbanola1/RevOps-Portfolio/tree/main/02-crm-cleanup-and-scoring) | Marketing-tier audit, clean segment field, lead score with decay |
| 03 | [Lead generation plan](https://github.com/rbanola1/RevOps-Portfolio/tree/main/03-lead-gen-plan) | Reverse-funnel revenue model, channel ROI, plan versus actual |
| 04 | [Channel sales](https://github.com/rbanola1/RevOps-Portfolio/tree/main/04-channel-sales) | Distributor scorecard, marketplace feeds and duplicate checks, channel economics |
| 05 | [Shipping cost optimization](https://github.com/rbanola1/RevOps-Portfolio/tree/main/05-shipping-cost-simulation) | Monte Carlo pricing analysis and recommendation |
| 06 | [Service Hub, phone lines and AI support agents](https://github.com/rbanola1/RevOps-Portfolio/tree/main/06-service-hub-and-support-agents) | Ticketing, SLAs, phone menu, refund process, loop guardrails, AI triage |
| 07 | [Commercial systems architecture: lead to cash](https://github.com/rbanola1/RevOps-Portfolio/tree/main/07-commercial-systems-architecture) | Six-layer system map, integration register, data ownership, channel order path, reconciliation |
| 08 | [Budget, forecast and P&L](https://github.com/rbanola1/RevOps-Portfolio/tree/main/08-budget-forecast-pnl) | Variance analysis, driver-based forecast, cash flow, scenarios |
| 09 | [Lead ownership and the warm-lead model](https://github.com/rbanola1/RevOps-Portfolio/tree/main/09-sales-model-and-lead-ownership) | Territory rules, research-first check, association labels |
| 10 | [Voice of customer program](https://github.com/rbanola1/RevOps-Portfolio/tree/main/10-voice-of-customer-program) | Feedback capture standard, tagging, post-trade-show dashboard, action loop |
| 11 | [Pipeline health and the CRM as a factory](https://github.com/rbanola1/RevOps-Portfolio/tree/main/11-pipeline-health-analysis) | Stage conversion, coverage, stalled deals, idle-inventory model, weekly review |
| 12 | [Trade show budget and return](https://github.com/rbanola1/RevOps-Portfolio/tree/main/12-tradeshow-budget-and-return) | Full event cost, cost per lead, gross-profit return, repeat or drop scorecard |
| 13 | [CRM migration and data governance](https://github.com/rbanola1/RevOps-Portfolio/tree/main/13-crm-migration-and-data-governance) | Migration plan, reconciliation, quality score, ownership rules, backup and restore |
| 14 | [Partner onboarding and pricing governance](https://github.com/rbanola1/RevOps-Portfolio/tree/main/14-partner-onboarding-and-pricing-governance) | Eight-stage distributor journey, partner scorecard, master pricing sheet, catalog check |
| 15 | [Territory, quota and compensation plan](https://github.com/rbanola1/RevOps-Portfolio/tree/main/15-territory-and-quota-design) | Potential-balanced territories, international lead routing, quota blend, pay plan |
| 16 | [Goal tracker, RACI and KPI dictionary](https://github.com/rbanola1/RevOps-Portfolio/tree/main/16-goals-raci-and-kpi-dictionary) | Goal-to-project tracker, one accountable role per process, KPI definitions and executive pack |
| 17 | [Order fulfillment and ERP rollout](https://github.com/rbanola1/RevOps-Portfolio/tree/main/17-order-fulfillment-and-erp-rollout) | Order-email intake, PO SOP, web-store integration, trained backup operator, outage recovery lessons |
| 18 | [AI-assisted scientific prospecting over MCP](https://github.com/rbanola1/RevOps-Portfolio/tree/main/18-ai-scientific-prospecting-mcp) | Lead database + Claude over MCP: signal search, CRM suppression, tiers, email gap-fill and bulk merge, reviewed outreach |

### [GTM-Strategy](https://github.com/rbanola1/GTM-Strategy): go-to-market engine
| # | Project | What it shows |
|---|---|---|
| 01 | [Signal-based outbound GTM engine](https://github.com/rbanola1/GTM-Strategy/tree/main/01-outbound-gtm-engine) | Three-engine architecture, fit x intent routing, guardrails |
| 02 | [Lead scoring redesign](https://github.com/rbanola1/GTM-Strategy/tree/main/02-lead-scoring-redesign) | Back-tested score and lifecycle definitions |
| 03 | [ICP, tiers and nurture](https://github.com/rbanola1/GTM-Strategy/tree/main/03-icp-and-nurture) | ICP cards from won deals, account tiers, nurture tracks |
| 04 | [Net-new lead generation pilot](https://github.com/rbanola1/GTM-Strategy/tree/main/04-net-new-lead-gen-pilot) | Suppress-first, tier-first enrichment, cost control, reply forecast |
| 05 | [Sequence discipline](https://github.com/rbanola1/GTM-Strategy/tree/main/05-sequence-discipline) | Pacing, stop rule, targeted versus bulk |
| 06 | [GTM tool stack](https://github.com/rbanola1/GTM-Strategy/tree/main/06-tool-stack) | Weighted evaluation and stage-gated spend |

### [SixSigma_Green_Belt](https://github.com/rbanola1/SixSigma_Green_Belt)
Green Belt project on US refractory products.

## How the work fits together: one GTM engine, two routes to market

```mermaid
flowchart LR
    A[ICP and account tiers] --> B[Signals and sourcing]
    B --> C[Suppress, enrich, verify, score and route]
    C --> D[Direct motion<br/>paced outbound, inbound router,<br/>inside-sales warm-up, nurture]
    C --> E[Channel motion<br/>distributors and B2B marketplaces,<br/>its own targeting and economics]
    D --> F[Order to cash<br/>store, ERP, accounting]
    E --> F
    F --> G[Service desk and phone<br/>tickets, SLAs, AI triage]
    F --> H[KPI dashboards, budget,<br/>forecast and P and L]
    G --> H
    H -.->|re-weight scoring, re-plan channels| A
```

Direct and channel are separate go-to-market motions. They share one data foundation (a single CRM as the source of truth, with agreed ownership of every field) and meet again at order to cash, support and reporting.

## Contact

Cleveland, OH · [LinkedIn](https://www.linkedin.com/in/rishabh-banola/) · rbanola1@gmail.com · open to RevOps, Commercial Operations and GTM roles.
