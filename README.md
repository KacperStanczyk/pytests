MS/OMS Validation Platform: VP Meeting Brief and Business Evidence

Research date: 19 August 2026  
Audience: Product Management, Sales and business-development leaders  
Purpose: prepare the presenter for the VP Product Management and Sales meeting, and document who publicly selected, used, bought or partnered around DMS/OMS validation products and close substitutes
Coverage: 17 direct or near-direct offers, named service and adjacent-platform deployments, public commercial models, and 113 unique source URLs; official regulator, buyer and supplier evidence is preferred

Current deck reviewed: [DMS_CMS_Validation_Platform_Product_Proposal.pptx](DMS_CMS_Validation_Platform_Product_Proposal.pptx)

## Executive presenter summary — read this first

Use this section for the pre-meeting briefing. The evidence tables, question bank and pilot plan follow it.

### Bottom line

> Aptiv has a working internal AWS validation asset. The market already pays for DMS/OMS validation outcomes and for adjacent cloud validation platforms. Aptiv has not yet proved that an external customer will buy its complete workflow. Ask the VP to approve a 90-day Product-and-Sales validation phase for a managed service, not a software-product launch.

### Decision requested

Approve:

- one Product Management owner and one Sales owner;
- five to eight interviews with OEM and Tier 1 validation buyers;
- one verified internal benchmark, including KPI parity and AWS cost;
- one non-Aptiv software-under-test feasibility check;
- Security, Legal and Finance checks;
- one fixed-scope paid-pilot hypothesis with price, acceptance criteria and delivery cost;
- a day-90 proceed, change, internal-only or stop decision.

Do not approve an external production launch in this meeting.

### Decision logic

| Question | VP-ready answer |
|---|---|
| **What exists now?** | An internal platform in an AWS development environment. It catalogs recorded data, runs the software under test, aligns results with ground truth, calculates KPIs and shows results in Grafana. Terraform supports repeatable deployment. Production migration is in progress. |
| **What is the first commercial hypothesis?** | A platform-enabled managed validation service. Aptiv operates a controlled campaign and delivers repeatable KPI results, failure analysis and a traceable evidence report. |
| **Why not sell software now?** | External demand for Aptiv's full offer, third-party SUT neutrality, security model, support model, price and unit economics are not proven. |
| **Why act now?** | EU ADDW applies to all new vehicles from 7 July 2026. Euro NCAP's 2026 framework is operational. China adds a mandatory combined-driver-assistance standard from 1 January 2027. |
| **What does the market prove?** | Named organizations buy DMS data, evaluation, homologation and scoring. OEMs also buy or build adjacent cloud validation platforms at scale. |
| **What does the market not prove?** | The scan found no named independent buyer for one external DMS/OMS platform that combines real-data intake, arbitrary customer-SUT replay, ground-truth alignment, cloud batch processing, KPI dashboards and evidence export. |

### Evidence to state aloud

1. One CU toolchain required more than one year of implementation work with GPO support. This is one internal case, not a market benchmark.
2. The team moved the main toolchain elements to the AWS development environment in two Program Increments. Production migration is not complete.
3. One internal comparison showed about 50% shorter reprocessing duration. It does not prove a 50% labor or cost reduction.
4. The closest direct public offer is AUMOVIO's end-to-end Cabin Sensing Validation-as-a-Service. Its named external customer adoption is not public.
5. Named direct or near-direct evidence includes Renault with SKY ENGINE AI, Sony and GMV with Anyverse, and Euro NCAP with IVEX. These cases cover parts of the workflow, not the complete proposed offer.
6. Named service evidence includes TÜV Rheinland work for FAW/Hongqi and Leapmotor, and Applus+ IDIADA work for Toyota Motor Europe.
7. Adjacent platform evidence is strong: BMW, Qualcomm and AWS built a reusable ADAS platform for data quality, labeling, simulation, reprocessing and KPI computation; a BMW architect states that the first platform was built in eight weeks. Capgemini has developed and operated a Mercedes-Benz ADAS Big Data platform since 2019.

### Why now

- **EU:** ADDW is now at the all-new-vehicle deadline. DDAW already reached that deadline in 2024.
- **Euro NCAP:** the current Driver Engagement and Occupant Monitoring protocols are version 1.2. Driver Monitoring is worth 25 points and Occupant Monitoring 30 points in the 100-point Safe Driving stage. The DMS dossier is due at least two months before testing.
- **China:** GB 47955-2026 becomes mandatory on 1 January 2027 for vehicles with combined driver-assistance systems and includes driver-state detection requirements. It is not a blanket DMS/OMS mandate for every vehicle.
- **Standards:** ASAM VOMS targets a platform-independent interface and a validation data model. Release is planned for November 2026; it is not an issued standard yet.

Sources: [EU General Safety Regulation](https://eur-lex.europa.eu/eli/reg/2019/2144/2024-07-07/eng), [Euro NCAP current Safe Driving protocols](https://www.euroncap.com/safe-driving/), [Euro NCAP DMS dossier guidance](https://cdn.euroncap.com/cars/assets/sd_201_driver_monitoring_dossier_guidance_v11_4fbc6a9531.pdf), [China GB 47955-2026](https://openstd.samr.gov.cn/bzgk/std/newGbInfo?hcno=A606486C4B8AFC2BE009FE3705E31B2E&refer=outter), [ASAM VOMS](https://www.asam.net/project-detail/p-2024-08-asam-voms-concept/), [BMW, Qualcomm and AWS](https://aws.amazon.com/blogs/industries/how-bmw-group-and-qualcomm-built-an-automated-driving-platform/), [Mercedes-Benz and Capgemini](https://www.capgemini.com/in-en/news/press-releases/capgemini-extends-its-collaboration-on-big-data-for-automated-driving-with-german-car-manufacturer/).

### Use these exact opening and closing lines

**Opening**

> We have an internal AWS-based validation asset that solves a repeated DMS and OMS delivery problem. The market already buys related validation outcomes. We are not asking to launch software today. We ask Product Management and Sales to help us test a managed-service offer before Aptiv makes a larger investment.

**Closing**

> The internal asset is real. The external service opportunity is credible but not yet proven. Please approve the 90-day phase, assign Product and Sales owners, and give us access to buyers. We will return with evidence for a proceed, change, internal-only or stop decision.

### Do not say

- “There is no competition.”
- “AWS is the product differentiation.”
- “Reprocessing is 50% cheaper.”
- “The platform is production-ready.”
- “The platform certifies the vehicle.”
- “Regulation guarantees that customers will buy our offer.”

## Detailed presenter decision brief

### Recommendation

Approve a **90-day Product-and-Sales market-validation and pilot-readiness phase** for a platform-enabled DMS/OMS managed validation service.

Do not approve an external software-product launch at this stage.

### Decision needed in this meeting

> Will Product Management and Sales approve the 90-day phase, assign one owner from each function, and give the team access to relevant OEM and Tier 1 validation buyers?

At the end of the phase, the team will return with one recommendation: proceed to a controlled external pilot, change the offer, keep the platform internal, or stop.

### The 30-second message

> We have an internal AWS-based validation asset that solves a repeated DMS and OMS delivery problem. It has improved reprocessing performance and can be deployed with Terraform. Regulation and consumer-rating protocols create recurring validation work, and named buyers already purchase related services and tools. We have not yet proved demand for Aptiv's complete offer. We ask Product Management and Sales to test a managed-service offer before Aptiv makes a larger product investment.

### State the offer at the correct maturity level

| Maturity level | Position today | Safe statement |
|---|---|---|
| **Internal platform asset** | Exists | An AWS-based internal platform catalogs recorded data, runs the software under test, aligns results with ground truth, calculates KPIs and presents results in Grafana. |
| **Platform-enabled managed service** | Recommended commercial hypothesis | Aptiv operates a fixed-scope validation campaign and delivers repeatable KPI results, failure analysis and a traceable evidence report. |
| **Customer-operated software product** | Future option; not proven | Self-service software becomes an option only after customers prove that they want direct platform access and that the core workflow is reusable. |

The embedded DMS/OMS application is the software under test. It is not the validation platform.

Use **DMS/OMS** or **in-cabin monitoring** with external customers. Define `CMS` before use because it can mean content management or connected mobility.

### Why now

| Signal | Verified fact | Business meaning | Boundary |
|---|---|---|---|
| **EU market access** | ADDW applies to all new vehicles from **7 July 2026**. DDAW already applies to all new vehicles. | The validation need is current and repeats across vehicle types and software versions. | Regulation creates required work. It does not guarantee demand for Aptiv's offer. |
| **Evidence burden** | EU DDAW rules require human-participant validation, documented statistics, day/night coverage and preserved errors. A Technical Service can inspect raw datasets and rerun part of the validation. | Data lineage, version control, repeatable processing and evidence export are product requirements, not optional features. | Aptiv must map each platform function to a real approval or customer need. |
| **Euro NCAP 2026** | The framework is operational and the current Driver Engagement and Occupant Monitoring protocols are version 1.2. Driver Monitoring is **25 points** and Occupant Monitoring is **30 points** in the 100-point Safe Driving stage. The DMS dossier is due at least **two months before** testing. | DMS/OMS-related work represents 55% of Safe Driving points and has an early evidence deadline. | Euro NCAP is a consumer rating program, not type approval. |
| **China regulation** | Mandatory standard GB 47955-2026 takes effect on **1 January 2027** for vehicles with combined driver-assistance systems. MIIT states that it includes detailed driver-state detection requirements, test scenarios, procedures and pass criteria. | China adds a near-term compliance reason to build configurable protocol and evidence packs. | This is not a blanket DMS/OMS mandate for every vehicle. |
| **China rating** | C-NCAP 2027 adds DMS intervention and false-response tests plus occupant-posture monitoring from **1 July 2027**. | A reusable protocol and evidence layer can support a second priority region. | The regulatory and rating workflows are separate and need separate product checks. |
| **Standardization** | The active ASAM VOMS project targets a platform-independent API and a validation data model, with release planned for **November 2026**. | Early alignment can reduce future integration work and support vendor neutrality. | This is an active project. It is not an issued standard yet. |

Sources: [EU ADDW timing](https://eur-lex.europa.eu/legal-content/EN/TXT/?qid=1770314724523&uri=PI_COM%3AC%282023%294523), [EU DDAW validation](https://eur-lex.europa.eu/eli/reg_del/2021/1341/oj/eng), [Euro NCAP scoring](https://cdn.euroncap.com/cars/assets/euro_ncap_protocol_overall_assessment_v100_24653aec0d.pdf), [Euro NCAP current protocols](https://www.euroncap.com/safe-driving/), [Euro NCAP dossier guidance](https://cdn.euroncap.com/cars/assets/sd_201_driver_monitoring_dossier_guidance_v11_4fbc6a9531.pdf), [China GB 47955-2026](https://openstd.samr.gov.cn/bzgk/std/newGbInfo?hcno=A606486C4B8AFC2BE009FE3705E31B2E&refer=outter), [MIIT explanation](https://www.miit.gov.cn/jgsj/zbys/gzdt/art/2026/art_597aed2718264440a0caa19e883f8d74.html), [C-NCAP 2027](https://www.c-ncap.org.cn/article-detail/2051922917171687426?type=2), [ASAM VOMS project](https://www.asam.net/project-detail/p-2024-08-asam-voms-concept/).

### What is proven and what is not proven

| Area | Status | Evidence or gap |
|---|---|---|
| Internal end-to-end workflow | **Proven internally** | The main workflow exists in an AWS development environment. |
| Reusable infrastructure | **Proven internally** | Terraform supports repeatable deployment between approved AWS environments. |
| Cross-program learning | **Proven internally** | DDMS, VCC and GM requirements shaped the platform concept. |
| Processing improvement | **Partial** | One comparison showed about 50% shorter reprocessing duration. Dataset, run count, KPI parity and cost need a formal benchmark. |
| External category demand | **Proven publicly** | OEMs and assessment bodies buy DMS-related homologation, synthetic data, HIL replay, scoring software and managed validation work. |
| Demand for Aptiv's complete offer | **Not proven** | No external buyer, purchase order or willingness-to-pay evidence exists for this platform. |
| Third-party DMS/OMS neutrality | **Not proven** | A non-Aptiv software-under-test benchmark is required. |
| External security and legal model | **Not proven** | Data rights, tenant isolation, privacy, IP, liability, retention and support need decisions. |
| Price and unit economics | **Not proven** | No approved price, delivery cost or target gross margin exists. |

### Five facts to remember

1. One CU toolchain required more than one year of implementation work with GPO support. This is one internal case, not a market benchmark.
2. The team moved the main toolchain elements to the AWS development environment in two Program Increments. Production migration is not complete.
3. One internal test showed about 50% shorter reprocessing duration. It does not prove a 50% reduction in total labor or cost.
4. Named buyers already purchase outcomes close to this offer. FAW/Hongqi and Leapmotor used TÜV Rheinland for programs that included DDAW or ADDW work. Renault selected DMS synthetic data from SKY ENGINE AI. Sony and GMV use Anyverse in in-cabin workflows. Euro NCAP selected IVEX for test-data processing and scoring.
5. No reviewed source gives a contract value for a complete DMS/OMS cloud-validation platform. The closest integrated public offers also have little named-customer evidence.

### Strategic options

| Option | Benefit | Main limitation | Recommendation |
|---|---|---|---|
| **Keep the platform internal** | Captures reuse and delivery benefits with the lowest commercial risk. | Does not test external revenue. | Keep as the fallback case. |
| **Validate a managed service** | Tests the buyer, price, workflow and operating model with a limited commitment. | Needs Product, Sales, Security, Legal, Finance and delivery ownership. | **Approve now.** |
| **Launch self-service software** | Offers the largest theoretical scale. | Buyer demand, neutrality, security, support and economics are not proven. | Do not approve now. |
| **Partner with an approved test house** | Adds a route to formal tests and market access. | Requires clear ownership of evidence, liability and customer relationship. | Test in parallel as a channel option. |

### Exact approval requested

Approve:

1. one Product Management owner;
2. one Sales owner;
3. structured access to OEM and Tier 1 buyers;
4. a fixed 90-day discovery and pilot-readiness phase;
5. defined support from Security, Legal and Finance;
6. an end-of-phase go, change, internal-only or stop review.

This decision does not approve a product launch, unrestricted customer-data processing or an external production deployment.

### Required 90-day output

The team must deliver:

- one verified internal benchmark with runtime, throughput, KPI parity and AWS cost;
- one selected buyer segment and one named budget-owner profile;
- five to eight structured buyer interviews, with at least three confirming the same costly problem;
- one fixed-scope managed-service pilot specification, acceptance criteria and three price hypotheses;
- one production-like internal reference run;
- decisions on data rights, third-party software rights, privacy, security and liability;
- one delivery-cost and support model;
- one external pilot candidate, only if all entry gates are met;
- one written proceed, change, internal-only or stop recommendation.

If no buyer confirms both the problem and a credible budget path, do not start an external pilot.

### Recommended 60-minute meeting flow

| Time | Topic | Required outcome |
|---:|---|---|
| 0-5 min | Decision context | State the recommendation and exact ask. |
| 5-20 min | Eight-slide story | Explain the repeated problem, asset, proof and market hypothesis. |
| 20-30 min | Proof | Show one workflow, one sanitized Grafana view and the 50% benchmark boundary. |
| 30-45 min | Product and Sales discussion | Test buyer, offer, channel, security and pricing assumptions. |
| 45-55 min | Decision | Confirm owners, discovery access and evidence gates. |
| 55-60 min | Actions | Record owners, dates and the next review. |

Do not spend more than five minutes on AWS implementation detail. Keep at least 25 minutes for questions and the decision.

### Opening

> We have an internal AWS-based validation asset that solves a repeated DMS and OMS delivery problem. It has improved reprocessing performance and can be deployed with Terraform. The market already buys related validation outcomes. Today, we are not asking to launch software. We are asking Product Management and Sales to help us test a platform-enabled managed service before we make a larger investment.

### Closing

> The internal asset is real. The service opportunity is credible but not yet proven. The software-product case is a later decision. Please approve the 90-day phase, assign Product and Sales owners, and give us access to buyers. We will return with evidence for a proceed, change, internal-only or stop decision.

### Red flags

Do not:

- call the internal asset a proven external product;
- present the 50% runtime result as a labor or cost saving;
- state that AWS is the differentiation;
- present accreditation, partnership or a supplier announcement as a confirmed sale;
- claim that regulation guarantees demand for Aptiv's offer;
- claim that there is no competition;
- promise third-party software support before a controlled test;
- state that the platform certifies a vehicle or guarantees a Euro NCAP result;
- start customer-specific development without a reusable pilot scope.

### Internal facts to confirm before the meeting

| Claim | Required evidence |
|---|---|
| More than one year to build the CU toolchain | Start and end dates, team scope, included work and source owner. |
| Moved to AWS in two Program Increments | Exact PI dates, component list, team size and remaining production work. |
| 50% shorter reprocessing | Baseline, dataset, software version, timing boundary, run count, AWS configuration, KPI parity and cost. |
| Reusable across programs | Active program count, common components and program-specific adaptations. |
| More automated and accessible | Manual steps, active users, run volume and access model. |
| Ready for an external pilot | Security status, data rights, support owner, isolated environment and third-party license rights. |

Do not put an unverified number on a slide. Mark it as a hypothesis or move it to the discussion list.

## Executive finding

The market is real, but it is not one mature software category.

| Finding | Evidence | Meaning for Aptiv |
|---|---|---|
| **The validation outcome has buyers.** | FAW/Hongqi and Leapmotor used TÜV Rheinland for programs that included DDAW or ADDW work. HORIBA MIRA reports a full DDAW program for a major OEM. | Lead with an outcome-based managed service, not a software catalog. |
| **Individual workflow components have named users.** | Renault selected SKY ENGINE AI DMS synthetic data. Sony and GMV use Anyverse. Euro NCAP selected IVEX. ZF and Qualcomm use Xylon replay equipment in adjacent ADAS work. | Buyers already understand data, replay, scoring and engineering-service purchase units. |
| **Large managed validation platforms can win OEM work.** | Capgemini has developed and operated a Mercedes-Benz ADAS Big Data platform since 2019, with tens of petabytes, three sites and 24/7 support. BMW, Qualcomm and AWS built a reusable ADAS environment for data quality, labeling, simulation, reprocessing and KPI computation. Porsche and TRATON use Applied Intuition toolchains. | A platform-enabled service is a credible automotive buying model, even if the public cases are not DMS-specific. Reusable infrastructure and managed operation are already accepted purchase patterns. |
| **The direct market is fragmented.** | AUMOVIO offers the closest end-to-end DMS/OMS VaaS. Innov+, iMotions, dSPACE, Anyverse, VAIVA, Xylon, IVEX, Optalert and others cover different parts. | Compete on integrated operations, DMS/OMS evidence and time-to-result. Do not claim an empty market. |
| **External adoption of the exact full workflow is not public.** | No reviewed source names an independent buyer for a complete real-data intake, arbitrary customer-SUT replay, GT alignment, cloud batch, KPI dashboard and evidence-export offer. | This is a differentiation hypothesis. Aptiv must prove it with a non-Aptiv SUT and a paid pilot. |
| **Comparable prices are not public.** | The scan found quote-based enterprise offers. Visible reference points range from USD 10 per analysis minute for Optalert's narrow service to several hundred thousand euros for a full Euro NCAP vehicle assessment. | Use buyer discovery and unit economics. Do not infer a platform price from unrelated offers. |

The strongest named direct or near-direct software and data cases are SKY ENGINE AI with Renault Group, Anyverse with Sony Depthsensing Solutions and GMV, and IVEX with Euro NCAP. None discloses contract value. The strongest named service cases are TÜV Rheinland with FAW/Hongqi and Leapmotor. They also do not disclose the DMS-specific price.

Public sources still do not prove a named customer for the exact validation products from AUMOVIO, iMotions, Innov+, dSPACE AURELION Driver Monitoring, Xylon ARTIEYE, VAIVA ICASIS, the joint Seeing Machines and Devant NCAP Validation Service, ITK iVESS, ACEWORKS, Controlar, ArcSoft, Deep In Sight or Synthera. Absence of public proof is not proof of no sales. Automotive contracts often use non-disclosure agreements.

The safe commercial conclusion is:

> Buyers already spend money on the components and outcomes of DMS/OMS validation. Public proof of one integrated DMS/OMS cloud-operations product is still limited. Aptiv should validate a fixed-scope managed service first and consider a customer-operated software product only after repeatability and willingness to pay are proven.

## Regulatory and standards evidence — why the work repeats

The strongest business case is not “the cloud is modern.” The strongest case is that OEMs must repeatedly connect data, software versions, test conditions, results and evidence.

| Region or program | Current verified requirement or signal | Platform capability that it supports | Commercial priority | Source |
|---|---|---|---|---|
| **EU DDAW** | Manufacturer validation must use human participants or human behavior data. The minimum sample is 10 participants. Results include true positives, false negatives, sensitivity per participant, average sensitivity and standard deviation. Tests cover day and night. Errors and exclusions remain in the evidence package. A Technical Service can review raw datasets and rerun part of the validation. | Versioned datasets, participant and condition metadata, ground-truth lineage, KPI calculation, exclusion audit, repeatable reruns and evidence export. | **Immediate** | [Commission Delegated Regulation (EU) 2021/1341](https://eur-lex.europa.eu/eli/reg_del/2021/1341/oj/eng) |
| **EU ADDW** | The requirement applies to all new vehicles from 7 July 2026. The manufacturer must provide a performance dossier based on repeated human tests, participant demographics, test conditions, repeatability and reproducibility. Technical Services perform gaze-point spot checks. | Controlled protocol versions, test-condition metadata, false-negative analysis, traceable reports and reproducible KPI results. | **Immediate** | [EU timing](https://eur-lex.europa.eu/legal-content/EN/TXT/?qid=1770314724523&uri=PI_COM%3AC%282023%294523), [Commission Delegated Regulation (EU) 2023/2590](https://eur-lex.europa.eu/eli/reg_del/2023/2590/oj/eng) |
| **Euro NCAP 2026-2028** | The framework is in operational use. The current Driver Engagement and Occupant Monitoring protocols are version 1.2. Driver Monitoring is 25 points and Occupant Monitoring is 30 points in the 100-point Safe Driving stage. Assessment uses OEM evidence, laboratory spot checks and an on-road evaluation. The DMS dossier is due at least two months before testing. | Protocol-specific KPI packs, dataset coverage views, false-positive and true-positive analysis, software-version traceability and dossier preparation. | **Immediate** | [Overall Assessment v10.0](https://cdn.euroncap.com/cars/assets/euro_ncap_protocol_overall_assessment_v100_24653aec0d.pdf), [Driver Engagement v1.2](https://cdn.euroncap.com/cars/assets/Euro_NCAP_Protocol_Safe_Driving_Driver_Engagement_v1_2_ebce03a443.pdf), [Occupant Monitoring v1.2](https://cdn.euroncap.com/cars/assets/Euro_NCAP_Protocol_Safe_Driving_Occupant_Monitoring_v1_2_aebbc7361f.pdf), [DMS dossier guidance](https://cdn.euroncap.com/cars/assets/sd_201_driver_monitoring_dossier_guidance_v11_4fbc6a9531.pdf), [first 2026 ratings](https://www.euroncap.com/press-media/a-new-benchmark-for-vehicle-safety-bmw-and-zeekr-secure-five-stars-under-euro-ncap-s-new-tests/) |
| **China GB 47955-2026** | The mandatory national standard takes effect on 1 January 2027 for M- and N-category vehicles fitted with defined combined driver-assistance systems. MIIT states that it includes detailed driver-state detection requirements, test scenarios, test procedures and pass criteria. MIIT also reports 2026 new-passenger-vehicle penetration above 70% for combined driver assistance and above 30% for NOA. | A China compliance pack, driver-state test coverage, versioned pass criteria and auditable results. The penetration figures are a scale signal for the affected engineering base. | **Prepare now** | [SAMR standard record](https://openstd.samr.gov.cn/bzgk/std/newGbInfo?hcno=A606486C4B8AFC2BE009FE3705E31B2E&refer=outter), [MIIT explanation](https://www.miit.gov.cn/jgsj/zbys/gzdt/art/2026/art_597aed2718264440a0caa19e883f8d74.html) |
| **C-NCAP 2027** | From 1 July 2027, C-NCAP adds DMS intervention and false-response scenarios and adds occupant-posture monitoring. | A separate China protocol pack, localized evidence output and reusable scenario-to-KPI mapping. | **Prepare now** | [C-NCAP 2027 release](https://www.c-ncap.org.cn/article-detail/2051922917171687426?type=2) |
| **ASAM VOMS** | An active industry project targets a platform-independent VOMS API and a VOMS-QA data model for validation. Release is planned for November 2026. Participants include Bosch, ITK, KPIT, Luxoft, Anyverse and other simulation and validation organizations. | Standard interfaces, vendor-neutral integration and portable test evidence. | **Design watch** | [ASAM project](https://www.asam.net/project-detail/p-2024-08-asam-voms-concept/), [active-project list](https://www.asam.net/active-projects/projects/) |
| **US NCAP** | NHTSA's roadmap places distracted and drowsy DMS research in 2023-2027, a request-for-comments phase in 2028, a final decision in 2029 and potential implementation in 2031. | Keep US requirements configurable, but do not make the US the first regulatory sales case. | **Watchlist** | [NHTSA NCAP roadmap](https://www.nhtsa.gov/sites/nhtsa.gov/files/2024-11/NCAP-Final-Decision-Notice-Advanced-Driver-Assistance-Systems-Roadmap-11182024-web.pdf) |

The MIIT penetration figures are official policy statements, not an audited market study. Do not convert vehicle penetration directly into platform revenue or TAM.

### Product consequence

The external offer should not promise certification. It should produce an auditable evidence package that an OEM and an authorized Technical Service can review. The product backlog should therefore prioritize:

1. immutable links between raw data, labels, SUT version, configuration, KPI version and result;
2. a complete record of exclusions, failures and reruns;
3. versioned EU and Euro NCAP KPI packages;
4. reproducible report and dossier export;
5. a vendor-neutral execution contract for non-Aptiv software;
6. customer-specific data isolation, retention and deletion;
7. later alignment with the ASAM VOMS API and QA data model.

## 1. Evidence rules

This report does not treat every press release as a sale.

| Grade | Required public evidence | Interpretation |
|---|---|---|
| **A** | The buyer or an independent program owner confirms operational use, selection or deployment of the named product. | Strong adoption evidence. Price can still be confidential. |
| **B** | The supplier names the buyer and the exact product or delivered capability. The announcement describes use or delivery. | Strong supplier-side evidence. Buyer confirmation or commercial terms are missing. |
| **C** | A named pilot, proof of value, co-development, channel agreement, consortium or technical partnership is confirmed. | Real relationship. A purchase or production deployment is not proven. |
| **D** | Anonymous customer, demo, launch, expression of interest, vendor claim, investment or an adjacent product design win. | Market signal only. Do not call it a customer sale for the product in scope. |

Two other labels are used:

- **Direct** means that the bought or used item is specific to DMS, OMS or in-cabin validation.
- **Adjacent** means that the item is a general ADAS/AD, HIL, simulation, data or engineering offer that can replace part of the proposed workflow.

## 2. Strongest named direct or near-direct business evidence

| Supplier | Named buyer or user | What the source confirms | Date | Public value or scale | Grade | Boundary | Source |
|---|---|---|---|---|---:|---|---|
| **SKY ENGINE AI** | **Renault Group** | SKY ENGINE AI says that Renault selected it to deliver Synthetic Data Cloud for DMS software. The announcement calls it a deal and states that the scope can grow with added DMS features. | 5 Dec 2023 | Not disclosed | **B** | This is DMS synthetic-data delivery. It is not proof of real-data replay, a KPI platform or a regulatory dossier. A Renault confirmation was not found. | [Supplier announcement](https://www.skyengine.ai/blog/sky-engine-ai-announces-synthetic-data-cloud-for-driver-monitoring-win-with-renault-group) |
| **Anyverse** | **Sony Depthsensing Solutions** | Sony identifies Anyverse as its synthetic-data partner. Sony integrates Anyverse data with its sensor models for the development and validation of driver-state, occupant and child-presence monitoring. | 1 Sep 2025 | Not disclosed | **A** | The evidence covers synthetic datasets and virtual testing. It does not show execution of Sony software inside Anyverse or a complete evidence dossier. | [Sony confirmation](https://www.sony-depthsensing.com/a-new-partnership-with-anyverse-as-synthetic-data-partner/), [Anyverse announcement](https://anyverse.ai/anyverse-sony-in-cabin-monitoring-collaboration/) |
| **Anyverse** | **GMV** | GMV confirms that it integrates Anyverse synthetic-data capabilities into its in-cabin validation workflow. GMV systems use Anyverse InCabin data for early Euro NCAP validation. | 3 Dec 2025 | Not disclosed | **A** | The companies call this a strategic collaboration. The public source does not state a license value or paid order. It is synthetic validation, not real-recording replay. | [GMV confirmation](https://www.gmv.com/en/communication/news/gmv-anyverse-join-forces-fast-track-future-safety-comfort-automotive-sector), [Anyverse announcement](https://anyverse.ai/gmv-anyverse-in-cabin-monitoring/) |
| **Anyverse** | **Tech Mahindra** | Tech Mahindra confirms a joint offer that uses the Anyverse platform to generate synthetic data for automotive clients. The scope includes ADAS, in-cabin systems and autonomous vehicles. | 17 Aug 2023 | Claimed 30-40% shorter development time; contract value not disclosed | **C** | This is a technology and delivery-channel partnership. The effect is a partner claim, not an audited customer result. No end OEM is named. | [Tech Mahindra announcement](https://www.techmahindra.com/insights/press-releases/tech-mahindra-and-anyverse-partner-accelerate-ai-adoption-automotive-industry/), [Anyverse announcement](https://anyverse.ai/tech-mahindra-anyverse-partner-accelerate-ai-adoption-automotive-industry/) |
| **IVEX** | **Euro NCAP** | IVEX states that its NCAP Evaluator will be used for data processing and score calculation under the 2026-2028 protocols. The platform includes manual verification and report processing for Driver Engagement and Occupant Monitoring. | 6 May 2026 | Not disclosed | **B** | This is strong program-owner adoption. The public DMS/OMS scope is report and score processing. It is not customer-SUT replay. | [IVEX selection announcement](https://ivex.ai/2026/05/06/ivex-delivers-new-software-to-support-euro-ncaps-2026-2028-safety-testing/), [product scope](https://ivex.ai/euro-ncap-evaluator/) |
| **Optalert** | **Unnamed leading European OEM** | Optalert says that its JDS drowsiness algorithm entered mass production in an OEM vehicle. | 17 Apr 2026 | Buyer and value not disclosed | **D** | This is production proof for a DMS algorithm. It is not a named buyer and it does not prove purchase of the separate validation service. | [Optalert production announcement](https://www.optalert.com/the-false-alert-epidemic-is-over-optalerts-medical-grade-impairment-detection-hits-the-road/) |
| **Devant** | **Seeing Machines** | Seeing Machines confirms use of Devant synthetic data for DMS/OMS development, training and future validation. The companies also develop an NCAP Validation Service together. | 20 Jun 2023 | Not disclosed | **A** | This proves use by a DMS supplier. It does not prove that an OEM or Tier 1 bought the joint validation service. | [Seeing Machines announcement](https://seeingmachines.com/wp-content/uploads/2023/06/PR-Seeing-Machines-and-Devant-FINAL-20.06.23.pdf), [Devant announcement](https://www.devant.ai/news/devant-and-seeing-machines-join-forces-to-enhance-transport-safety) |
| **Innov+** | **UTAC** | Innov+ and UTAC confirm a partnership for DMS development, testing and approval support. The offer combines Innov+ tools with simulator, track and real-driver work. | 2024 | Not disclosed | **C** | This is a delivery partnership. No named OEM purchase of Trusty was found. | [Innov+ OEM page and UTAC partnership](https://innov-plus.com/customer-oem/) |
| **Anyverse** | **Euro NCAP and VAIP members** | Anyverse manages a three-year Virtual Assessment Implementation Program. Public partner logos include Aisin, Applus+ IDIADA, Aptiv, emotion3D, Ficosa, GMV, IAV, IBV, LG Electronics, Mitsubishi Electric, Seeing Machines, Smart Eye and Sony. | Jun 2026 | Membership is free | **C** | This is an industry program, not sales revenue. Members can receive a preferred rate for additional Anyverse data. | [VAIP program](https://anyverse.ai/virtual-assessment-implementation-program/) |

### Direct business conclusion

Only a small number of public cases name the user and the exact in-cabin validation input. The best disclosed commercial pattern is a narrow product that is easy to buy:

1. synthetic datasets or a data application;
2. a physical test or ground-truth tool;
3. regulatory score-processing software;
4. a managed validation campaign.

No reviewed public case gives a contract value for a complete DMS/OMS validation platform.

## 3. Named adjacent deployments that prove buyer budgets

These relationships do not prove a DMS/OMS product sale. They prove that OEMs and Tier 1 suppliers buy replay, validation and software-development infrastructure.

| Supplier | Named buyer or user | What was selected or used | Date | Public value or scale | Grade | Relevance and boundary | Source |
|---|---|---|---|---|---:|---|---|
| **Xylon** | **ZF** | ZF chose logiRECORDER HIL Video Logger for Smart Camera 6 validation. ZF also states that the solution was already proven in many global projects for Smart Camera 4.8. | 26 Nov 2024 | Value not disclosed; multiple global prior projects | **A** | Strong proof that a Tier 1 buys record-and-replay HIL equipment. The named program is a forward-facing ADAS camera, not DMS/OMS or ARTIEYE. | [Xylon and ZF announcement](https://xylon-lab.com/2024/11/25/xylon-delivers-hil-data-loggers-to-zf/) |
| **Xylon** | **Qualcomm** | Qualcomm uses logiRECORDER and XYLON QUATTRO HIL stations for Snapdragon Ride Vision. Jenkins schedules datasets and KPI checks across the stations. | Current case page | Value not disclosed | **B** | Strong operational HIL proof. The case is ADAS/AD, not in-cabin monitoring. | [Qualcomm HIL case](https://xylon-lab.com/product-features/hil-qualcomm-use-case/) |
| **AWS and Qualcomm** | **BMW Group** | BMW chose AWS for its next-generation ADAS platform. The implemented environment covers data ingestion and quality, automatic labeling, annotations and references, visualization, simulation, reprocessing and KPI calculation. It uses reusable infrastructure-as-code modules and self-service environments. A BMW architect states that the initial platform was built in eight weeks. | 2023-2024 | Eight-week initial build; contract value not disclosed | **A** | This is the closest named horizontal architecture case. It is a custom BMW ADAS platform, not an off-the-shelf DMS/OMS product and not proof that eight weeks is a normal customer delivery time. | [Architecture and use](https://aws.amazon.com/blogs/industries/how-bmw-group-and-qualcomm-built-an-automated-driving-platform/), [BMW buyer quote](https://aws.amazon.com/solutions/case-studies/bmw-reinvent-2023-qualcomm/) |
| **Microsoft Azure** | **BMW Group** | BMW's Measurement Data Reprocessing platform has supported vehicle development since 2020. The customer story reports 3,500 development vehicles, more than 10,000 signals per vehicle and 10-times-faster data delivery and analysis. | 28 Jan 2025 | 3,500 vehicles; more than 10,000 signals per vehicle; reported 10x improvement | **B** | Strong buyer-scale evidence for cloud test-data processing. It is telemetry and analysis, not a complete replay-to-DMS-KPI workflow. The 10x value is not comparable with Aptiv's 50% runtime result. | [BMW and Microsoft customer story](https://www.microsoft.com/en/customers/story/19769-bmw-ag-azure-app-service) |
| **Applied Intuition** | **Porsche** | Porsche uses an off-board platform and an end-to-end validation toolset across SIL, HIL and vehicle tests. Porsche calls Applied Intuition an important software partner. | 27 Mar 2024 | Value not disclosed | **A**
