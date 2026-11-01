---
layout: default
title: Berliana Fadlilatur Rahmah
---

<style>
  /* ---------- Dropdown sections ---------- */
  details.section {
    border-top: 1px solid #d8d8d8;
    padding: 0.4rem 0;
  }
  details.section:last-of-type { border-bottom: 1px solid #d8d8d8; }

  details.section > summary {
    cursor: pointer;
    list-style: none;
    font-size: 1.35rem;
    font-weight: 600;
    padding: 0.6rem 0;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  details.section > summary::-webkit-details-marker { display: none; }
  details.section > summary::after {
    content: "";
    width: 0.55rem;
    height: 0.55rem;
    border-right: 2px solid currentColor;
    border-bottom: 2px solid currentColor;
    transform: rotate(45deg);          /* points down when closed */
    margin-right: 0.3rem;
    transition: transform 0.2s ease;
  }
  details.section[open] > summary::after { transform: rotate(-135deg); }  /* flips up when open */
  details.section > summary:focus-visible { outline: 2px solid #2b5fd9; outline-offset: 2px; }
  .section-body { padding: 0.5rem 0 1.2rem; }


  /* ---------- Profile picture + contact ---------- */
  .profile { text-align: center; max-width: 220px; margin: 0 0 1.5rem; }
  .profile-pic {
    width: 180px; height: 180px;
    border-radius: 50%;
    object-fit: cover;
    display: block;
    margin: 0 auto 0.8rem;
  }
  .contact-links { list-style: none; margin: 0; padding: 0; }
  .contact-links li { margin: 0.3rem 0; }
  .contact-links a { text-decoration: none; }
  .contact-links a:hover, .contact-links a:focus-visible { text-decoration: underline; }

  /* ---------- Project cards ---------- */
  .card-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 1rem;
  }
  a.project-card {
    display: block;
    padding: 1.1rem 1.2rem;
    border: 1px solid #d8d8d8;
    border-radius: 10px;
    text-decoration: none;
    color: inherit;
    transition: border-color 0.15s ease, transform 0.15s ease;
  }
  a.project-card:hover,
  a.project-card:focus-visible {
    border-color: #2b5fd9;
    transform: translateY(-2px);
  }
  .project-card h3 { margin: 0 0 0.3rem; font-size: 1.1rem; }
  .project-card .meta { font-size: 0.85rem; color: #666; margin: 0 0 0.6rem; }
  .project-card p { margin: 0; font-size: 0.95rem; }

  @media (prefers-reduced-motion: reduce) {
    details.section > summary::after,
    a.project-card { transition: none; }
  }
</style>

<div class="profile">
  <img class="profile-pic" src="{{ '/assets/images/profile.jpg' | relative_url }}" alt="Berliana Fadlilatur Rahmah">
  <ul class="contact-links">
    <li><a href="mailto:berlianafr@gmail.com">Email</a></li>
    <li><a href="https://www.linkedin.com/in/berlianafr9" target="_blank" rel="noopener">LinkedIn</a></li>
    <li><a href="https://github.com/berlianafr" target="_blank" rel="noopener">GitHub</a></li>
  </ul>
</div>

# Data Analyst | Machine Learning | Operations & Risk Analytics

Data-driven professional with 4+ years of experience at Indonesia's General Election Commission (KPU), spanning internal audit, procurement, logistics, and election analytics. Experienced in building data-driven tools, automating reporting processes, analyzing operational risks, and applying machine learning to real-world business problems.

Combines technical capabilities in Python, SQL, and data analytics with practical experience in operations, supply chain, procurement, and regulatory compliance.

---

## Technical Skills

**Data Analytics & Machine Learning:** Python, SQL, Microsoft Excel, Google Sheets, Google Colab, Scikit-learn, XGBoost, LightGBM, SHAP, Google Apps Script

**Data Processing & Automation:** Data Cleaning, Data Validation, Data Analysis, Workflow Automation, Reporting Automation

**Operations & Supply Chain:** Logistics Monitoring, Supply Chain Risk Management, Procurement Planning, Budget Estimation, Cost Analysis, Vendor Evaluation

**Audit & Risk Management:** Internal Control Assessment, Risk Assessment, Regulatory Compliance, Financial Reconciliation, Transaction Vouching, Audit Documentation

**Systems Analysis & Design:** UML Modeling, Business Requirements Analysis, Workflow and Process Modeling

---

<!-- NOTE: markdown="1" is required so kramdown renders markdown inside HTML blocks -->

<details class="section" markdown="1">
<summary>Professional Experience</summary>
<div class="section-body" markdown="1">

**Election Technical Affairs Officer @ General Election Commission (KPU), East Java Province**
_April 2026 – Present_

- Analyzed East Java voter data to determine electoral district (dapil) requirements and support legislative election district design simulations.
- Developed a dynamic seat-allocation tool using the Sainte-Laguë method to simulate 18 political parties across 11 DPR and 14 provincial DPRD electoral districts, reducing processing time from days to hours.
- Facilitated electoral discussions involving election administrators, academics, and other stakeholders.
- Administered legislative replacement (PAW) processes for the East Java Provincial DPRD and monitored progress across 38 regencies/cities.
- Verified periodic political party data updates and prepared supporting administrative documentation.

**Logistics Monitoring and Evaluation Officer @ General Election Commission (KPU)**
_Logistics Bureau, Jakarta, Indonesia \| July 2024 – April 2026_

- Compiled and analyzed election logistics data from 552 work units (38 provinces and 514 regencies/cities) to support nationwide consolidated reporting.
- Designed and maintained a centralized logistics monitoring system with standardized formats and input validation, replacing inconsistent manual Excel files and improving data consolidation and reporting.
- Evaluated operational challenges reported by regional work units and monitored 38 provincial procurement teams during regional election logistics procurement.
- Mapped supply chain risks across 5 geographic zones and 20 risk categories, identifying the top 4 risks per zone and nationally and developing zone-specific mitigation recommendations.
- Supported operational risk monitoring and mitigation planning within the Logistics Bureau.
- Contributed to the initial development of the 2029 Election Logistics Roadmap by defining business processes, expected outputs, implementation steps, and estimated deadlines.

**Procurement Officer @ General Election Commission (KPU)**
_Logistics Bureau, Jakarta, Indonesia \| July 2023 – July 2024_

- Planned nationwide logistics procurement for the 2024 General Election, covering 204.8 million registered voters and 820,161 polling stations across 10 logistics categories.
- Forecasted procurement quantities, estimated budgets, and established procurement timelines across two procurement phases.
- Contributed to nationwide procurement strategies through regional zoning and centralized procurement with LKPP, supporting procurement efficiency of approximately Rp381 billion.
- Conducted nationwide market price surveys and prepared Estimated Costs (HPS) for designated procurement zones.
- Processed tender data, evaluated bids, and verified vendor documentation and qualifications against procurement regulations.
- Monitored the production of approximately 1.2 billion ballot sheets to ensure compliance with procurement specifications and quality requirements.
- Prepared procurement documentation for internal audit reviews, including HPS reviews and procurement probity audits.

**Internal Auditor @ General Election Commission (KPU)**
_Jakarta, Indonesia \| January 2022 – July 2023_

- Reviewed semiannual financial statements and reconciled cash balances and imprest funds to ensure financial accuracy and accountability.
- Provided advisory support to regional government work units on financial management, regulatory compliance, and internal controls.
- Supported the development of risk management regulation (PKPU No. 8 of 2023) through stakeholder discussions, regulatory research, and preparation of socialization materials.
- Monitored risk management and internal control implementation across government work units nationwide.
- Reviewed corrective actions in response to previous audit findings and recommendations.
- Conducted compliance clarifications related to special-purpose audit findings (PDTT).

**Audit Intern @ AR Utomo Public Accounting Firms**
_Surabaya, Indonesia \| September 2021_

- Prepared audit working papers by entering information from auditee-provided source documents.
- Performed transaction vouching and reconciliation to identify discrepancies and inconsistencies.

**Student Intern @ Directorate General of Taxes, Ministry of Finance**
_Audit, Collection, Intelligence & Investigation Division \| March 2021 – June 2021_

- Analyzed tax collection and bankruptcy cases involving outstanding tax liabilities and potential compliance risks.
- Supported tax audits by reviewing financial records, preparing audit working papers, and reconciling ledger and bank transaction data using Excel.
- Evaluated tax audit Quality Assurance (QA) procedures, identified gaps between implementation and established SOPs, and recommended process improvements.
- Prepared tax-related correspondence and archived official documents and audit reports.

</div>
</details>

<details class="section" markdown="1">
<summary>Projects</summary>
<div class="section-body" markdown="0">

<div class="card-grid">

  <a class="project-card" href="{{ '/projects/seat/' | relative_url }}">
    <h3>SEAT: Seat Allocation &amp; Electoral Candidate Selection</h3>
    <p class="meta">Personal project, ongoing &middot; Google Apps Script, Google Sheets, Gemini API</p>
    <p>Turns scanned election result forms (Formulir D Hasil) into seat allocations and elected-candidate lists. AI extracts, humans verify, the system calculates.</p>
  </a>

  <!-- Add more cards by copying the block above and changing href, title, and text -->

</div>

</div>
</details>

<details class="section" markdown="1">
<summary>Research &amp; Publications</summary>
<div class="section-body" markdown="1">

### Comparative Study of Predictive Models for Non-Performing Loan Prediction in a P2P Lending Company

**The 2nd International Conference on Artificial Intelligence for Learning and Optimization (ICoAILO 2026)**
_October 2026 \| Paper Presenter_

Presented research investigating machine learning approaches for predicting non-performing loans (NPL) using real corporate loan data from an Indonesian peer-to-peer lending company.

- Compared five machine learning models: Logistic Regression, Decision Tree, Random Forest, XGBoost, and LightGBM.
- Analyzed 578 corporate loan records with 17 scorecard features, including an NPL rate of 8.7%.
- Addressed class imbalance using stratified 5-fold cross-validation, class weights, and threshold tuning.
- Selected the best-performing model using misclassification cost, considering that a missed bad loan costs approximately 4.5 times more than a false alarm.
- Identified XGBoost as the best-performing model.
- Applied SHAP for model interpretability, identifying year-over-year revenue growth, payor type, and past-due receivables as the top risk drivers.
- Found that financial factors contributed 53% of model importance despite accounting for only 20% of the original scorecard weight.

**Publication:** To be published in Scopus-indexed conference proceedings.

**Reproducibility:** [Code and Processed Dataset – Zenodo](https://zenodo.org/records/23138626)

</div>
</details>

<details class="section" markdown="1">
<summary>Education</summary>
<div class="section-body" markdown="1">

**Bina Nusantara University (BINUS)**
_Bachelor of Computer Science (S.Kom.) in Information Systems \| August 2024 – October 2026_

RPL Program (Diploma-to-Bachelor pathway).

Specialized in:
- Data Analytics and Machine Learning
- Systems Analysis and Design
- UML Modeling and Business Requirements Analysis
- Project Management

**Undergraduate Thesis:** Non-Performing Loan (NPL) Prediction Using Machine Learning.

Compared five machine learning models using real corporate loan data, selecting the best model based on misclassification cost.

**Polytechnic of State Finance STAN (PKN STAN)**
_Associate Degree in Accounting (A.Md.Ak.) \| September 2018 – October 2021_

Specialized in:
- Financial Accounting
- Government Accounting and Compliance
- Cost Accounting
- Product Pricing
- Auditing

**Final Project:** Cost of Production Analysis at Bakery.

Applied process costing to analyze production costs and evaluate cost accounting practices, recommending improvements to cost classification, financial recordkeeping, and product pricing.

</div>
</details>

<details class="section" markdown="1">
<summary>Licenses &amp; Certifications</summary>
<div class="section-body" markdown="1">

- **Supervised Machine Learning: Regression and Classification** – DeepLearning.AI, Stanford University (February 2026)
- **Certified Skilled Auditor** – Financial and Development Supervisory Agency (BPKP) (June 2024)
- **Government Procurement Certification** – National Public Procurement Agency (LKPP) (April 2024)
- **Certified Associate in Python Programming (PCAP)** – Python Institute (November 2021)

</div>
</details>  .section-body { padding: 0.5rem 0 1.2rem; }

  /* ---------- Project cards ---------- */
  .card-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
    gap: 1rem;
  }
  a.project-card {
    display: block;
    padding: 1.1rem 1.2rem;
    border: 1px solid #d8d8d8;
    border-radius: 10px;
    text-decoration: none;
    color: inherit;
    transition: border-color 0.15s ease, transform 0.15s ease;
  }
  a.project-card:hover,
  a.project-card:focus-visible {
    border-color: #2b5fd9;
    transform: translateY(-2px);
  }
  .project-card h3 { margin: 0 0 0.3rem; font-size: 1.1rem; }
  .project-card .meta { font-size: 0.85rem; color: #666; margin: 0 0 0.6rem; }
  .project-card p { margin: 0; font-size: 0.95rem; }

  @media (prefers-reduced-motion: reduce) {
    details.section > summary::after,
    a.project-card { transition: none; }
  }
</style>

# Data Analyst | Machine Learning | Operations & Risk Analytics

Data-driven professional with 4+ years of experience at Indonesia's General Election Commission (KPU), spanning internal audit, procurement, logistics, and election analytics. Experienced in building data-driven tools, automating reporting processes, analyzing operational risks, and applying machine learning to real-world business problems.

Combines technical capabilities in Python, SQL, and data analytics with practical experience in operations, supply chain, procurement, and regulatory compliance.

[LinkedIn](https://www.linkedin.com/in/berlianafr9) | [Email](mailto:berlianafr@gmail.com)

---

## Technical Skills

**Data Analytics & Machine Learning:** Python, SQL, Microsoft Excel, Google Sheets, Google Colab, Scikit-learn, XGBoost, LightGBM, SHAP, Google Apps Script

**Data Processing & Automation:** Data Cleaning, Data Validation, Data Analysis, Workflow Automation, Reporting Automation

**Operations & Supply Chain:** Logistics Monitoring, Supply Chain Risk Management, Procurement Planning, Budget Estimation, Cost Analysis, Vendor Evaluation

**Audit & Risk Management:** Internal Control Assessment, Risk Assessment, Regulatory Compliance, Financial Reconciliation, Transaction Vouching, Audit Documentation

**Systems Analysis & Design:** UML Modeling, Business Requirements Analysis, Workflow and Process Modeling

---

<!-- NOTE: markdown="1" is required so kramdown renders markdown inside HTML blocks -->

<details class="section" markdown="1">
<summary>Professional Experience</summary>
<div class="section-body" markdown="1">

**Election Technical Affairs Officer @ General Election Commission (KPU), East Java Province**
_April 2026 – Present_

- Analyzed East Java voter data to determine electoral district (dapil) requirements and support legislative election district design simulations.
- Developed a dynamic seat-allocation tool using the Sainte-Laguë method to simulate 18 political parties across 11 DPR and 14 provincial DPRD electoral districts, reducing processing time from days to hours.
- Facilitated electoral discussions involving election administrators, academics, and other stakeholders.
- Administered legislative replacement (PAW) processes for the East Java Provincial DPRD and monitored progress across 38 regencies/cities.
- Verified periodic political party data updates and prepared supporting administrative documentation.

**Logistics Monitoring and Evaluation Officer @ General Election Commission (KPU)**
_Logistics Bureau, Jakarta, Indonesia \| July 2024 – April 2026_

- Compiled and analyzed election logistics data from 552 work units (38 provinces and 514 regencies/cities) to support nationwide consolidated reporting.
- Designed and maintained a centralized logistics monitoring system with standardized formats and input validation, replacing inconsistent manual Excel files and improving data consolidation and reporting.
- Evaluated operational challenges reported by regional work units and monitored 38 provincial procurement teams during regional election logistics procurement.
- Mapped supply chain risks across 5 geographic zones and 20 risk categories, identifying the top 4 risks per zone and nationally and developing zone-specific mitigation recommendations.
- Supported operational risk monitoring and mitigation planning within the Logistics Bureau.
- Contributed to the initial development of the 2029 Election Logistics Roadmap by defining business processes, expected outputs, implementation steps, and estimated deadlines.

**Procurement Officer @ General Election Commission (KPU)**
_Logistics Bureau, Jakarta, Indonesia \| July 2023 – July 2024_

- Planned nationwide logistics procurement for the 2024 General Election, covering 204.8 million registered voters and 820,161 polling stations across 10 logistics categories.
- Forecasted procurement quantities, estimated budgets, and established procurement timelines across two procurement phases.
- Contributed to nationwide procurement strategies through regional zoning and centralized procurement with LKPP, supporting procurement efficiency of approximately Rp381 billion.
- Conducted nationwide market price surveys and prepared Estimated Costs (HPS) for designated procurement zones.
- Processed tender data, evaluated bids, and verified vendor documentation and qualifications against procurement regulations.
- Monitored the production of approximately 1.2 billion ballot sheets to ensure compliance with procurement specifications and quality requirements.
- Prepared procurement documentation for internal audit reviews, including HPS reviews and procurement probity audits.

**Internal Auditor @ General Election Commission (KPU)**
_Jakarta, Indonesia \| January 2022 – July 2023_

- Reviewed semiannual financial statements and reconciled cash balances and imprest funds to ensure financial accuracy and accountability.
- Provided advisory support to regional government work units on financial management, regulatory compliance, and internal controls.
- Supported the development of risk management regulation (PKPU No. 8 of 2023) through stakeholder discussions, regulatory research, and preparation of socialization materials.
- Monitored risk management and internal control implementation across government work units nationwide.
- Reviewed corrective actions in response to previous audit findings and recommendations.
- Conducted compliance clarifications related to special-purpose audit findings (PDTT).

**Audit Intern @ AR Utomo Public Accounting Firms**
_Surabaya, Indonesia \| September 2021_

- Prepared audit working papers by entering information from auditee-provided source documents.
- Performed transaction vouching and reconciliation to identify discrepancies and inconsistencies.

**Student Intern @ Directorate General of Taxes, Ministry of Finance**
_Audit, Collection, Intelligence & Investigation Division \| March 2021 – June 2021_

- Analyzed tax collection and bankruptcy cases involving outstanding tax liabilities and potential compliance risks.
- Supported tax audits by reviewing financial records, preparing audit working papers, and reconciling ledger and bank transaction data using Excel.
- Evaluated tax audit Quality Assurance (QA) procedures, identified gaps between implementation and established SOPs, and recommended process improvements.
- Prepared tax-related correspondence and archived official documents and audit reports.

</div>
</details>

<details class="section" markdown="1">
<summary>Projects</summary>
<div class="section-body" markdown="0">

<div class="card-grid">

  <a class="project-card" href="{{ '/projects/seat/' | relative_url }}">
    <h3>SEAT: Seat Allocation &amp; Electoral Candidate Selection</h3>
    <p class="meta">Personal project, ongoing &middot; Google Apps Script, Google Sheets, Gemini API</p>
    <p>Turns scanned election result forms (Formulir D Hasil) into seat allocations and elected-candidate lists. AI extracts, humans verify, the system calculates.</p>
  </a>

  <!-- Add more cards by copying the block above and changing href, title, and text -->

</div>

</div>
</details>

<details class="section" markdown="1">
<summary>Research &amp; Publications</summary>
<div class="section-body" markdown="1">

### Comparative Study of Predictive Models for Non-Performing Loan Prediction in a P2P Lending Company

**The 2nd International Conference on Artificial Intelligence for Learning and Optimization (ICoAILO 2026)**
_October 2026 \| Paper Presenter_

Presented research investigating machine learning approaches for predicting non-performing loans (NPL) using real corporate loan data from an Indonesian peer-to-peer lending company.

- Compared five machine learning models: Logistic Regression, Decision Tree, Random Forest, XGBoost, and LightGBM.
- Analyzed 578 corporate loan records with 17 scorecard features, including an NPL rate of 8.7%.
- Addressed class imbalance using stratified 5-fold cross-validation, class weights, and threshold tuning.
- Selected the best-performing model using misclassification cost, considering that a missed bad loan costs approximately 4.5 times more than a false alarm.
- Identified XGBoost as the best-performing model.
- Applied SHAP for model interpretability, identifying year-over-year revenue growth, payor type, and past-due receivables as the top risk drivers.
- Found that financial factors contributed 53% of model importance despite accounting for only 20% of the original scorecard weight.

**Publication:** To be published in Scopus-indexed conference proceedings.

**Reproducibility:** [Code and Processed Dataset – Zenodo](https://zenodo.org/records/23138626)

</div>
</details>

<details class="section" markdown="1">
<summary>Education</summary>
<div class="section-body" markdown="1">

**Bina Nusantara University (BINUS)**
_Bachelor of Computer Science (S.Kom.) in Information Systems \| August 2024 – October 2026_

RPL Program (Diploma-to-Bachelor pathway).

Specialized in:
- Data Analytics and Machine Learning
- Systems Analysis and Design
- UML Modeling and Business Requirements Analysis
- Project Management

**Undergraduate Thesis:** Non-Performing Loan (NPL) Prediction Using Machine Learning.

Compared five machine learning models using real corporate loan data, selecting the best model based on misclassification cost.

**Polytechnic of State Finance STAN (PKN STAN)**
_Associate Degree in Accounting (A.Md.Ak.) \| September 2018 – October 2021_

Specialized in:
- Financial Accounting
- Government Accounting and Compliance
- Cost Accounting
- Product Pricing
- Auditing

**Final Project:** Cost of Production Analysis at Bakery.

Applied process costing to analyze production costs and evaluate cost accounting practices, recommending improvements to cost classification, financial recordkeeping, and product pricing.

</div>
</details>

<details class="section" markdown="1">
<summary>Licenses &amp; Certifications</summary>
<div class="section-body" markdown="1">

- **Supervised Machine Learning: Regression and Classification** – DeepLearning.AI, Stanford University (February 2026)
- **Certified Skilled Auditor** – Financial and Development Supervisory Agency (BPKP) (June 2024)
- **Government Procurement Certification** – National Public Procurement Agency (LKPP) (April 2024)
- **Certified Associate in Python Programming (PCAP)** – Python Institute (November 2021)

</div>
</details>

<details class="section" markdown="1">
<summary>Contact</summary>
<div class="section-body" markdown="1">

**Berliana Fadlilatur Rahmah**

Surabaya, Indonesia

- Email: [berlianafr@gmail.com](mailto:berlianafr@gmail.com)
- LinkedIn: [linkedin.com/in/berlianafr9](https://www.linkedin.com/in/berlianafr9)
- GitHub: [github.com/berlianafr](https://github.com/berlianafr)

</div>
</details>
