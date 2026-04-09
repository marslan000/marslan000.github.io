<!-- PAGE FORMAT -->

<style>
  body {
    background-color: #0d1117;
    color: #e6edf3;
  }

  .section-container {
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:25px;
  }

  .category-card {
    background:#161b22;
    border-radius:12px;
    padding:18px;
    box-shadow:0 4px 12px rgba(0,0,0,0.4);
  }

  .project-item {
    margin-bottom:20px;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }

  .project-item:hover {
    transform: translateY(-4px);
  }

  .project-item img {
    width:100%;
    border-radius:8px;
    margin-top:6px;
    margin-bottom:6px;
    box-shadow:0 4px 10px rgba(0,0,0,0.3);
  }

  .project-link {
    color:#58a6ff;
    text-decoration:none;
    font-weight:bold;
  }

  .project-link:hover {
    text-decoration:underline;
  }

  .subtext {
    color:#8b949e;
    font-size:13px;
  }

  .fade-in {
    opacity:0;
    transform: translateY(20px);
    animation: fadeIn 0.6s ease forwards;
  }

  .fade-in:nth-child(2) { animation-delay:0.15s; }
  .fade-in:nth-child(3) { animation-delay:0.3s; }

  @keyframes fadeIn {
    to {
      opacity:1;
      transform: translateY(0);
    }
  }
</style>

<!-- HERO SECTION -->
[![CCBA Badge](https://img.shields.io/badge/CCBA-Certified-blue?style=for-the-badge)](https://badges.iiba.org/ee9bb5e6-0dde-4bae-97bc-f1bf6d6168f0#acc.yMVj8cTS)

### Sr. Data Modeling & BI Analyst | Aerospace & Manufacturing Systems
Over 10 years of experience designing and delivering data-driven solutions that optimize operations, costs, and strategic planning.

<!-- SKILL / TECH BADGES -->
## 🛠 Tech & Tools

### Programming & Analytics
![SQL](https://img.shields.io/badge/SQL-blue?style=for-the-badge&logo=Microsoft-SQL-Server)
![Python](https://img.shields.io/badge/Python-yellow?style=for-the-badge&logo=python)
![PySpark](https://img.shields.io/badge/PySpark-orange?style=for-the-badge&logo=apache-spark)
![MS Fabric](https://img.shields.io/badge/Microsoft-Fabric-lightgrey?style=for-the-badge)
![Power BI](https://img.shields.io/badge/Power%20BI-darkorange?style=for-the-badge&logo=power-bi)
![Excel](https://img.shields.io/badge/Excel-365-green?style=for-the-badge&logo=microsoft-excel)

### Automation & Workflow
![VBA](https://img.shields.io/badge/VBA-purple?style=for-the-badge)
![CRD](https://img.shields.io/badge/CRD-lightblue?style=for-the-badge&title=Automation%20Experience)
![Task Scheduler](https://img.shields.io/badge/Task%20Scheduler-orange?style=for-the-badge&title=Automation%20Experience)
![Data Pipelines](https://img.shields.io/badge/Data%20Pipelines-blueviolet?style=for-the-badge&title=MS%20Fabric%20Automation)
![Automation](https://img.shields.io/badge/Workflow-Automation-green?style=for-the-badge)

### ERP Systems
<!-- ERP Systems - Horizontal with hover years -->
<span>
  <img src="https://img.shields.io/badge/IFS-green?style=for-the-badge" title="2025 - Current" style="display:inline-block; margin-right:5px;" />
  <img src="https://img.shields.io/badge/Visual7-yellow?style=for-the-badge" title="2025" style="display:inline-block; margin-right:5px;" />
  <img src="https://img.shields.io/badge/Blaze-green?style=for-the-badge" title="2024-2025" style="display:inline-block; margin-right:5px;" />
  <img src="https://img.shields.io/badge/JDIS-yellow?style=for-the-badge" title="2021-2025" style="display:inline-block; margin-right:5px;" />
  <img src="https://img.shields.io/badge/Equip-yellow?style=for-the-badge" title="2021-2025" style="display:inline-block; margin-right:5px;" />
  <img src="https://img.shields.io/badge/SAP-green?style=for-the-badge&logo=sap&logoColor=white" title="2015-2019" style="display:inline-block; margin-right:5px;" />
</span>

<strong>Legend:</strong> 🟢 Cloud Based ERP | 🟡 Server Based ERP <br>
<strong>ERP Systems:</strong> Hover over each badge to see years of experience

<!-- CORE EXPERTISE -->
## 🛠 Core Expertise

- **Data Engineering & Analytics**: SQL, PySpark, Microsoft Fabric, data-driven modeling  
- **Supply Chain Modeling**: End-to-end supply chain mapping (**ERP-integrated cloud replication**)  
- **Cost & Pricing Modeling**: Aircraft cost traceability, pricing strategy, and standardization (**$22M revenue impact**)  
- **Inventory Optimization**: Fill rate improvement (**~1.5% increase on $300M multi-site inventory**)  
- **Automation**: Python, VBA, Power Automate, CRD, Task Scheduler, Data Pipelines, workflow optimization  
- **Visualization**: Power BI dashboards and reporting  


## 🚀 Featured Projects

<div class="section-container">

<!-- ================= LEFT ================= -->
<div class="category-card fade-in">
  
<b style="font-size:18px;">💼 Data-Driven Business</b>

<br><br>

<div class="project-item">
  <b>🔹 Supply Chain Mapping Engine</b><br>
  <div class="subtext" style="color: #f0f0f0;">End-to-end supply chain visibility & traceability</div>
  <a class="project-link" href="project-supply-chain.html">View Project →</a>
</div>

<div class="project-item">
<b>🔹 Aircraft Cost Modeling (Coming Soon)</b><br>
<img src="images/aircraft_cost.png" />
<div class="subtext">Full cost traceability from aircraft to raw material</div>
<a href="#">View Project →</a>
</div>

<div class="project-item">
<b>🔹 Global Pricing Standardization (Coming Soon)</b><br>
<img src="images/pricing.png" />
<div class="subtext">Standardized pricing across 100+ global locations</div>
<a href="#">View Project →</a>
</div>

</div>

<!-- ================= RIGHT ================= -->
<div class="category-card fade-in">
  
<b style="font-size:18px;">🏗 Data Architecture</b>

<br><br>

<div class="project-item">
  <b>🔹 Medallion Architecture</b><br>
  <div class="subtext">End-to-end layered data architecture (Bronze → Silver → Gold)</div>
  <a class="project-link" href="project-medallion-architecture.html">View Project →</a>
</div>

<div class="project-item">
  <b>🔹 Data Pipelines</b><br>
  <div class="subtext">Scalable ingestion & transformation pipelines</div>
  <a class="project-link" href="project-data-pipeline.html">View Project →</a>
</div>

<div class="project-item">
<b>🔹 Workflow Automation (Coming Soon)</b><br>
<img src="images/workflow.png" />
<div class="subtext">Automated pipelines reducing manual effort by 75%</div>
<a href="#">View Project →</a>
</div>

</div>

</div>


<!-- LINKS / CONTACT -->
## 🔗 Links

<div style="margin-top:15px; display:flex; gap:15px; flex-wrap:wrap;">

  <a href="https://www.linkedin.com/in/arslan-muhammad-ccba-meng-eit-94a21461/" 
     style="padding:10px 16px; background:#161b22; border-radius:8px; text-decoration:none; color:#58a6ff; font-weight:bold; box-shadow:0 4px 10px rgba(0,0,0,0.3); transition:0.2s;"
     onmouseover="this.style.transform='translateY(-2px)'"
     onmouseout="this.style.transform='translateY(0)'">
     💼 LinkedIn
  </a>
  
  <a href="https://github.com/marslan000" 
     style="padding:10px 16px; background:#161b22; border-radius:8px; text-decoration:none; color:#58a6ff; font-weight:bold; box-shadow:0 4px 10px rgba(0,0,0,0.3); transition:0.2s;"
     onmouseover="this.style.transform='translateY(-2px)'"
     onmouseout="this.style.transform='translateY(0)'">
     🐙 GitHub
  </a>

</div>

<br>

<p style="text-align:right; color:#8b949e; font-size:12px;">
  © Arslan Muhammad
</p>
