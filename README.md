Looking for Contributors!
Project Vision
I'm building an open-source tool for full IFRS 17 (Insurance Contracts) implementation, covering methodology, calculations, and financial reporting. The goal is to create a comprehensive, transparent, and accessible solution — especially for firms in emerging markets where commercial IFRS 17 software is prohibitively expensive.
Project Scope
The tool aims to automate the entire IFRS 17 workflow:
1. Measurement Models

General Measurement Model (GMM / Building Block Approach)
Premium Allocation Approach (PAA)
Variable Fee Approach (VFA)

2. Core Calculations

Fulfilment Cash Flows (FCF) — estimates of future cash flows
Risk Adjustment for non-financial risk
Discount rate curve construction and application
Contractual Service Margin (CSM) — initial recognition and subsequent measurement
Loss Component recognition and allocation
Experience adjustments

3. Transition Approaches

Full retrospective approach
Modified retrospective approach
Fair value approach

4. Reporting & Disclosures

Statement of Financial Position (insurance contract assets/liabilities)
Statement of Financial Performance (insurance revenue, insurance service expenses, insurance finance income/expenses)
Roll-forward reconciliation tables (as required by IFRS 17.98–132)
Automated disclosure notes generation

🛠️ Tech Stack (Open for Discussion)
I'm open to suggestions on the best technology choices. Current considerations:
OptionProsConsPythonRich actuarial/data science ecosystem (pandas, numpy, scipy), large communityMay need additional frameworks for UIRStrong actuarial community, excellent statistical packagesSmaller developer poolPython + ExcelPython backend + Excel interface for end usersComplexity of integration
Key question for contributors: What tech stack would maximize both technical capability and adoption by insurance/audit professionals?
 Who I'm Looking For

Actuaries with IFRS 17 implementation experience
Accountants/Auditors familiar with IFRS 17 reporting requirements
Developers interested in FinTech / InsurTech / RegTech
Data scientists for cash flow modeling and discount curve construction
Documentation writers for methodology guides and user manuals

Context
I lead an audit firm in Central Asia (Grant Thornton network) and work extensively with international auditing and financial reporting standards. There is a significant gap in affordable, transparent IFRS 17 tools for smaller insurance companies, audit firms, and regulators — particularly in developing economies. This project aims to fill that gap.
Roadmap (Proposed)
PhaseDescriptionTimelinePhase 1Core methodology documentation & data model designMonths 1–2Phase 2FCF calculation engine + discount rate moduleMonths 3–4Phase 3CSM calculation & measurement models (GMM, PAA, VFA)Months 5–6Phase 4Reporting engine & disclosure generationMonths 7–8Phase 5Testing, validation & user documentationMonths 9–10
Discussion Points

Tech stack preference? Python, R, or hybrid?
Priority measurement model? Should we start with PAA (simpler) or GMM (more comprehensive)?
Data format? What input data structure would work best for insurance companies?
Validation approach? How should we verify calculation accuracy against known benchmarks?
Licensing? MIT, Apache 2.0, or GPL?

How to Contribute

Star this repo if you're interested
Join the Discussion tab to share ideas
Open Issues for feature requests or methodology questions
Submit Pull Requests once development begins
Let's make IFRS 17 implementation accessible to everyone.
If you're an actuary, auditor, developer, or just passionate about open financial standards — I'd love to hear from you!
Contact: nematullaaka@gmail.com
