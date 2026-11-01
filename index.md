<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Berliana Fadlilatur Rahmah</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:opsz,wght,SOFT@9..144,300..500,0..100&family=Figtree:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{--bg:#eef4f5;--ink:#17313b;--mute:#5d7580;--tide:#4f8f9f;--line:rgba(23,49,59,.14);--ease:cubic-bezier(.22,.8,.26,1)}
*{box-sizing:border-box}
html,body{height:100%;margin:0;background:var(--bg);color:var(--ink);font:400 1rem/1.7 Figtree,system-ui,sans-serif;overflow:hidden}
a{color:inherit}
h1,h2,h3,.brand{font-family:Fraunces,Georgia,serif;font-weight:300;font-variation-settings:"SOFT" 100;letter-spacing:-.02em}
.bg{position:fixed;inset:0;z-index:0;overflow:hidden}
.bg i{position:absolute;border-radius:50%;filter:blur(70px);opacity:.75;animation:drift 24s ease-in-out infinite alternate}
.bg i:nth-child(1){width:46vmax;height:46vmax;background:#cde3e8;left:-12vmax;top:-12vmax}
.bg i:nth-child(2){width:38vmax;height:38vmax;background:#ddd8f3;right:-10vmax;top:22vh;animation-delay:-8s}
.bg i:nth-child(3){width:34vmax;height:34vmax;background:#f6e4de;left:28vw;bottom:-18vmax;animation-delay:-15s}
@keyframes drift{to{transform:translate(6vmax,-4vmax) scale(1.12)}}
nav{position:fixed;top:0;left:0;right:0;z-index:5;display:flex;align-items:center;justify-content:space-between;gap:1rem;padding:1rem 1.5rem;background:linear-gradient(var(--bg),rgba(238,244,245,0));transition:transform .7s var(--ease),opacity .7s}
body.intro nav{transform:translateY(-100%);opacity:0;pointer-events:none}
.brand{font-size:1.25rem;text-decoration:none;white-space:nowrap}
.links{position:relative;display:flex;gap:1.4rem;overflow-x:auto;scrollbar-width:none;padding-bottom:.5rem}
.links a{text-decoration:none;font-size:.9rem;color:var(--mute);white-space:nowrap;transition:color .3s}
.links a.on,.links a:hover{color:var(--ink)}
#ink{position:absolute;left:0;bottom:0;height:2px;width:0;border-radius:2px;background:var(--tide);transition:transform .6s var(--ease),width .6s var(--ease),opacity .3s}
.stage{position:fixed;inset:0;z-index:1}
.page{position:absolute;inset:0;overflow-y:auto;display:none}
.wrap{max-width:46rem;margin:0 auto;padding:6rem 1.5rem 4rem}
#p-welcome{display:flex;align-items:center}
#p-welcome .wrap{padding:2rem 1.5rem}
.pic{width:84px;height:84px;border-radius:50%;object-fit:cover;margin-bottom:1.4rem}
h1{font-size:clamp(2.6rem,7vw,4.6rem);line-height:1.05;margin:0 0 1rem}
h2{font-size:2rem;margin:0 0 1.5rem}
.lead{font-size:1.15rem;color:var(--mute);max-width:32rem;margin:0 0 2rem}
.btn{display:inline-block;padding:.85rem 1.8rem;border-radius:999px;background:var(--ink);color:var(--bg);text-decoration:none;font-weight:500;transition:transform .4s var(--ease),background .3s}
.btn:hover{background:var(--tide);transform:translateY(-2px)}
.wave{position:absolute;left:0;right:0;bottom:0;width:100%;height:28vh;pointer-events:none}
.contact{display:flex;gap:1rem;margin:0 0 2rem;font-size:clamp(.62rem,1.9vw,.85rem)}
.contact a{text-decoration:none;white-space:nowrap;color:var(--mute)}
.contact a::after{content:"\2197";margin-left:.3rem}
.contact a:hover{color:var(--ink);text-decoration:underline}
.sk p{margin:.6rem 0}
.sk b{font-weight:600}
details{border-top:1px solid var(--line)}
details:last-of-type{border-bottom:1px solid var(--line)}
summary{cursor:pointer;list-style:none;display:flex;justify-content:space-between;align-items:center;gap:1rem;padding:1rem 0;font-weight:500}
summary::-webkit-details-marker{display:none}
summary::after{content:"";flex:none;width:.5rem;height:.5rem;border:solid currentColor;border-width:0 2px 2px 0;transform:rotate(45deg);transition:transform .35s var(--ease)}
details[open]>summary::after{transform:rotate(-135deg)}
summary small{display:block;font-weight:400;color:var(--mute)}
details ul{margin:0 0 1.2rem;padding-left:1.1rem}
details li{margin:.35rem 0}
.card{display:block;padding:1.5rem;border-radius:24px;background:rgba(255,255,255,.55);border:1px solid var(--line);backdrop-filter:blur(8px);text-decoration:none;transition:transform .4s var(--ease),border-color .3s}
.card:hover{transform:translateY(-4px);border-color:var(--tide)}
.card h3{font-size:1.4rem;margin:0 0 .4rem}
.card p{margin:.3rem 0;color:var(--mute)}
.back{display:inline-block;margin-bottom:1.5rem;color:var(--mute);text-decoration:none}
.back:hover{color:var(--ink)}
h3.s{font-size:1.25rem;margin:1.6rem 0 .3rem}
@media(prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}}
</style>
</head>
<body class="intro">
<div class="bg"><i></i><i></i><i></i></div>

<nav>
  <a class="brand" href="#/home">Berliana</a>
  <div class="links">
    <a href="#/home" data-n="home">Home</a>
    <a href="#/experience" data-n="experience">Experience</a>
    <a href="#/projects" data-n="projects">Projects</a>
    <a href="#/research" data-n="research">Research</a>
    <a href="#/education" data-n="education">Education</a>
    <a href="#/certifications" data-n="certifications">Certifications</a>
    <span id="ink"></span>
  </div>
</nav>

<main class="stage">

<section class="page" id="p-welcome">
  <svg class="wave" viewBox="0 0 1440 300" preserveAspectRatio="none" aria-hidden="true">
    <path d="M0 160C240 60 420 260 720 170S1200 70 1440 150V300H0Z" fill="#cde3e8" opacity=".55"/>
    <path d="M0 220C260 140 500 290 780 215S1220 150 1440 230V300H0Z" fill="#ddd8f3" opacity=".6"/>
  </svg>
  <div class="wrap" style="position:relative">
    <img class="pic" src="assets/img/profpic.png" alt="" onerror="this.remove()">
    <h1>Hi, I'm Berliana.</h1>
    <p class="lead">I work with election, logistics, and risk data, and build tools that turn it into decisions.</p>
    <a class="btn" href="#/home">Get to know me</a>
  </div>
</section>

<section class="page" id="p-home"><div class="wrap">
  <h1>Data Analyst, Machine Learning, Operations &amp; Risk Analytics</h1>
  <div class="contact">
    <a href="mailto:berlianafr@gmail.com">berlianafr@gmail.com</a>
    <a href="https://www.linkedin.com/in/berlianafr9" target="_blank" rel="noopener">linkedin.com/in/berlianafr9</a>
    <a href="https://github.com/berlianafr" target="_blank" rel="noopener">github.com/berlianafr</a>
  </div>
  <p>Data-driven professional with 4+ years of experience at Indonesia's General Election Commission (KPU), spanning internal audit, procurement, logistics, and election analytics. I build data-driven tools, automate reporting, analyze operational risks, and apply machine learning to real-world business problems.</p>
  <p>I combine Python, SQL, and data analytics with practical experience in operations, supply chain, procurement, and regulatory compliance.</p>
  <h2 style="margin-top:2.5rem">Technical Skills</h2>
  <div class="sk">
    <p><b>Data Analytics &amp; Machine Learning:</b> Python, SQL, Microsoft Excel, Google Sheets, Google Colab, Scikit-learn, XGBoost, LightGBM, SHAP, Google Apps Script</p>
    <p><b>Data Processing &amp; Automation:</b> Data Cleaning, Data Validation, Data Analysis, Workflow Automation, Reporting Automation</p>
    <p><b>Operations &amp; Supply Chain:</b> Logistics Monitoring, Supply Chain Risk Management, Procurement Planning, Budget Estimation, Cost Analysis, Vendor Evaluation</p>
    <p><b>Audit &amp; Risk Management:</b> Internal Control Assessment, Risk Assessment, Regulatory Compliance, Financial Reconciliation, Transaction Vouching, Audit Documentation</p>
    <p><b>Systems Analysis &amp; Design:</b> UML Modeling, Business Requirements Analysis, Workflow and Process Modeling</p>
  </div>
</div></section>

<section class="page" id="p-experience"><div class="wrap">
  <h2>Experience</h2>
  <details open><summary><span>Election Technical Affairs Officer, KPU East Java<small>April 2026 to present</small></span></summary><ul>
    <li>Analyzed East Java voter data to determine electoral district (dapil) requirements and support district design simulations.</li>
    <li>Developed a dynamic seat-allocation tool using the Sainte-Laguë method for 18 political parties across 11 DPR and 14 provincial DPRD districts, cutting processing time from days to hours.</li>
    <li>Administered legislative replacement (PAW) processes for the East Java Provincial DPRD and monitored progress across 38 regencies/cities.</li>
    <li>Facilitated electoral discussions with administrators, academics, and other stakeholders.</li></ul></details>
  <details><summary><span>Logistics Monitoring and Evaluation Officer, KPU Logistics Bureau, Jakarta<small>July 2024 to April 2026</small></span></summary><ul>
    <li>Compiled and analyzed logistics data from 552 work units (38 provinces and 514 regencies/cities) for nationwide consolidated reporting.</li>
    <li>Designed a centralized logistics monitoring system with standardized formats and input validation, replacing inconsistent manual Excel files.</li>
    <li>Mapped supply chain risks across 5 zones and 20 risk categories, identifying the top 4 risks per zone and nationally with zone-specific mitigation recommendations.</li>
    <li>Contributed to the initial 2029 Election Logistics Roadmap by defining business processes, outputs, steps, and deadlines.</li></ul></details>
  <details><summary><span>Procurement Officer, KPU Logistics Bureau, Jakarta<small>July 2023 to July 2024</small></span></summary><ul>
    <li>Planned nationwide logistics procurement for the 2024 General Election: 204.8 million registered voters, 820,161 polling stations, 10 logistics categories.</li>
    <li>Contributed to regional zoning and centralized procurement with LKPP, supporting efficiency of approximately Rp381 billion.</li>
    <li>Conducted nationwide market price surveys and prepared Estimated Costs (HPS) for designated zones.</li>
    <li>Monitored production of approximately 1.2 billion ballot sheets for compliance with specifications and quality requirements.</li></ul></details>
  <details><summary><span>Internal Auditor, KPU, Jakarta<small>January 2022 to July 2023</small></span></summary><ul>
    <li>Reviewed semiannual financial statements and reconciled cash balances and imprest funds.</li>
    <li>Advised regional work units on financial management, regulatory compliance, and internal controls.</li>
    <li>Supported development of risk management regulation PKPU No. 8 of 2023 through research, stakeholder discussions, and socialization materials.</li></ul></details>
  <details><summary><span>Audit Intern, AR Utomo Public Accounting Firms, Surabaya<small>September 2021</small></span></summary><ul>
    <li>Prepared audit working papers and performed transaction vouching and reconciliation to identify discrepancies.</li></ul></details>
  <details><summary><span>Student Intern, Directorate General of Taxes<small>March to June 2021</small></span></summary><ul>
    <li>Supported tax audits by reviewing financial records, preparing working papers, and reconciling ledger and bank data in Excel.</li>
    <li>Evaluated audit quality assurance procedures against SOPs and recommended process improvements.</li></ul></details>
</div></section>

<section class="page" id="p-projects"><div class="wrap">
  <h2>Projects</h2>
  <a class="card" href="#/seat">
    <h3>SEAT: Seat Allocation &amp; Electoral Candidate Selection</h3>
    <p>Google Apps Script, Google Sheets, Gemini API</p>
    <p>Turns scanned election result forms into seat allocations and elected-candidate lists. AI extracts, humans verify, the system calculates.</p>
  </a>
</div></section>

<section class="page" id="p-seat"><div class="wrap">
  <a class="back" href="#/projects">Back to projects</a>
  <h2>SEAT: Seat Allocation &amp; Electoral Candidate Selection</h2>
  <p>Personal project, ongoing. Google Apps Script, Google Sheets, Gemini API.</p>
  <h3 class="s">Problem</h3>
  <p>Seat allocation from scanned election result forms (Formulir D Hasil) was slow, manual work.</p>
  <h3 class="s">Solution</h3>
  <p>An end-to-end tool that turns the scanned PDFs into parliamentary seat allocations and elected-candidate lists. The Gemini API extracts vote counts, users verify them, then the Sainte-Laguë method and candidate selection run automatically.</p>
  <h3 class="s">Outcome</h3>
  <p>Processing time dropped from days to hours, with centralized Google Drive exports and per-user calculation history.</p>
  <details style="margin-top:1.5rem"><summary>How I built it</summary><ul>
    <li>Human-in-the-loop workflow: users verify extracted data before any calculation.</li>
    <li>Three rounds of testing added API error handling, retry, and a manual data-entry fallback.</li></ul></details>
</div></section>

<section class="page" id="p-research"><div class="wrap">
  <h2>Research &amp; Publications</h2>
  <h3 class="s" style="margin-top:0">Comparative Study of Predictive Models for Non-Performing Loan Prediction in a P2P Lending Company</h3>
  <p>The 2nd International Conference on Artificial Intelligence for Learning and Optimization (ICoAILO 2026), October 2026, paper presenter. To be published in Scopus-indexed conference proceedings.</p>
  <ul>
    <li>Compared Logistic Regression, Decision Tree, Random Forest, XGBoost, and LightGBM on 578 corporate loan records with 17 scorecard features and an NPL rate of 8.7%.</li>
    <li>Handled class imbalance with stratified 5-fold cross-validation, class weights, and threshold tuning.</li>
    <li>Selected the model by misclassification cost, since a missed bad loan costs about 4.5 times more than a false alarm. XGBoost performed best.</li>
    <li>SHAP showed year-over-year revenue growth, payor type, and past-due receivables as top risk drivers. Financial factors made up 53% of model importance despite 20% of the original scorecard weight.</li>
  </ul>
  <p><a href="https://zenodo.org/records/23138626" target="_blank" rel="noopener">Code and processed dataset on Zenodo</a></p>
</div></section>

<section class="page" id="p-education"><div class="wrap">
  <h2>Education</h2>
  <details open><summary><span>Bina Nusantara University (BINUS), B.Comp.Sc. Information Systems<small>August 2024 to October 2026, RPL (Diploma-to-Bachelor) program</small></span></summary><ul>
    <li>Focus: data analytics and machine learning, systems analysis and design, UML modeling, business requirements analysis, project management.</li>
    <li>Thesis: Non-Performing Loan (NPL) prediction using machine learning, comparing five models on real corporate loan data and selecting the best by misclassification cost.</li></ul></details>
  <details><summary><span>Polytechnic of State Finance STAN, A.Md.Ak. Accounting<small>September 2018 to October 2021</small></span></summary><ul>
    <li>Focus: financial accounting, government accounting and compliance, cost accounting, product pricing, auditing.</li>
    <li>Final project: cost of production analysis at a bakery, applying process costing and recommending improvements to cost classification, recordkeeping, and pricing.</li></ul></details>
</div></section>

<section class="page" id="p-certifications"><div class="wrap">
  <h2>Licenses &amp; Certifications</h2>
  <ul>
    <li><b>Supervised Machine Learning: Regression and Classification</b>, DeepLearning.AI, Stanford University (February 2026)</li>
    <li><b>Certified Skilled Auditor</b>, BPKP (June 2024)</li>
    <li><b>Government Procurement Certification</b>, LKPP (April 2024)</li>
    <li><b>Certified Associate in Python Programming (PCAP)</b>, Python Institute (November 2021)</li>
  </ul>
</div></section>

</main>

<script>
const order=['home','experience','projects','seat','research','education','certifications'];
const reduce=matchMedia('(prefers-reduced-motion: reduce)').matches;
let cur=null;
const $=s=>document.querySelector(s);
function ink(){
  const a=$('.links a.on'),i=$('#ink');
  if(!a){i.style.opacity=0;return}
  i.style.opacity=1;i.style.width=a.offsetWidth+'px';i.style.transform='translateX('+a.offsetLeft+'px)';
  a.scrollIntoView({inline:'center',block:'nearest'});
}
function go(id){
  if(id===cur)return;
  const el=$('#p-'+id),old=cur&&$('#p-'+cur),prev=cur;
  const vertical=id==='welcome'||prev==='welcome';
  const d=prev===null?0:vertical?(id==='welcome'?-1:1):Math.sign(order.indexOf(id)-order.indexOf(prev));
  const t=v=>vertical?'translateY('+v*60+'px)':'translateX('+v*80+'px)';
  document.body.classList.toggle('intro',id==='welcome');
  el.style.display=id==='welcome'?'flex':'block';el.scrollTop=0;
  const o={duration:reduce?0:750,easing:'cubic-bezier(.22,.8,.26,1)'};
  if(old){
    if(!reduce){
      el.animate([{opacity:0,transform:t(d)},{opacity:1,transform:'none'}],o);
      old.animate([{opacity:1,transform:'none'},{opacity:0,transform:t(-d)}],o).onfinish=()=>{if(cur!==prev)old.style.display='none'};
    }else old.style.display='none';
  }
  cur=id;
  const n=id==='seat'?'projects':id;
  document.querySelectorAll('.links a').forEach(a=>a.classList.toggle('on',a.dataset.n===n));
  ink();
}
function route(){
  const id=location.hash.replace(/^#\/?/,'')||'welcome';
  go(document.getElementById('p-'+id)?id:'welcome');
}
addEventListener('hashchange',route);
addEventListener('resize',ink);
document.fonts&&document.fonts.ready.then(ink);
route();
</script>
</body>
</html>
