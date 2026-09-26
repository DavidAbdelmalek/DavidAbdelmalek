<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:29B5E8&height=200&section=header&text=David%20Abdelmalek&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Senior%20Data%20Engineer%20%E2%80%A2%20Snowflake%20%E2%80%A2%20dbt%20%E2%80%A2%20Azure&descAlignY=58&descSize=18&animation=fadeIn" alt="David Abdelmalek" />
</p>

<p align="center">
  <a href="https://david-abdelmalek.pages.dev">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=900&color=29B5E8&center=true&vCenter=true&width=640&lines=Data+Vault+2.0+warehouses+on+Snowflake;1000%2B+dbt+models+in+production;One+JSON+file+%E2%86%92+a+full+ingestion+stack;LangGraph+text-to-SQL+agents+over+dbt;MSc+Data+Science+%40+RWTH+Aachen" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://david-abdelmalek.pages.dev"><img src="https://img.shields.io/badge/Portfolio-Ask%20DoDo-29B5E8?style=for-the-badge&logo=cloudflare&logoColor=white" /></a>
  <a href="https://linkedin.com/in/davidabdelmalek/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://medium.com/@davidonsy123"><img src="https://img.shields.io/badge/Medium-000000?style=for-the-badge&logo=medium&logoColor=white" /></a>
  <a href="mailto:davidonsy123@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <img src="https://komarev.com/ghpvc/?username=DavidAbdelmalek&style=for-the-badge&color=203A43&label=VISITORS" />
</p>

---

### `SELECT * FROM david;`

```sql
-- models/marts/dim_engineer.sql
select
    'David Abdelmalek'                                   as name,
    'Senior Data Management & AI Consultant'             as role,
    'INFORM DataLab'                                     as company,
    'Essen, Germany (CET)'                               as location,
    array_construct('Snowflake', 'dbt', 'Azure', 'Python', 'Terraform')
                                                         as daily_driver,
    array_construct('Data Vault 2.0', 'Kimball')         as modeling,
    array_construct('Pharma', 'Banking', 'Energy', 'Retail')
                                                         as industries,
    'MSc Data Science, RWTH Aachen'                      as education,
    array_construct('EN', 'DE', 'AR')                    as languages,
    true                                                 as open_to_freelance
from {{ ref('real_experience') }}  -- nothing invented, all tested
```

## 💼 EXPERIENCE

### Senior Data Management & AI Consultant @ INFORM DataLab
*Jun 2023 – Present · Aachen, Germany*
- **Pharma SAP integration:** Snowflake Data Vault 2.0 warehouse for a DACH pharma group. SAP ECC and S/4 ingested via Fivetran, 1000+ dbt models, P&L and sales-order marts served to Power BI.
- **Banking ingestion framework:** config-driven staging for a regulated DACH bank. One JSON file provisions the full Snowflake stack (Snowpipe, Streams, Tasks) through Terraform and a Python CLI. 200+ entities, zero custom code per source.
- **Energy trading analytics:** led 4 engineers on a 2+ TB Azure + Snowflake platform (Azure Data Factory, dbt). SAP and Oracle via SAP OData, deployments automated with GitLab CI/CD.
- **Magazine demand forecasting:** production architecture for a large POS network. ML on Azure Batch, forecasts served from Snowflake with row-level security per publisher, scheduled retraining, sub-minute serving.
- **HubSpot CRM analytics:** Snowflake + dbt pipeline into Qlik Sense, extended with Cortex ML (lead scoring, funnel forecasting, anomaly detection) and Cortex LLM tagging of notes by sentiment and intent.

### Cloud Data & MLOps Engineer @ Bosch
*Feb 2022 – Feb 2023 · Stuttgart, Germany*
- Kubernetes-based ingestion pipelines migrating sensor data from Hadoop to Azure Data Lake.
- Scalable sensor-data workflows on Azure Databricks with a layered data lake design.

### AI Researcher (Master Thesis) @ Fraunhofer IPT
*May 2022 – Dec 2022 · Aachen, Germany*
- Reinforcement-learning scheduling for CAR-T therapy patients using Graph Neural Networks in PyTorch.

### Data Scientist / AI Engineer @ BMW
*Feb 2021 – Jul 2021 · Munich, Germany*
- Migrated statistical workflows from R to Python on AWS/Azure, infrastructure provisioned with Terraform.
- PySpark pipelines over German after-sales data, feeding BI dashboards used in sales strategy.

### Data Scientist @ Henkel
*Jan 2020 – Jun 2020 · Düsseldorf, Germany*
- AI price-tracking platform (TensorFlow + PySpark) forecasting raw-material costs for procurement planning.

### What I build

| | |
|---|---|
| ❄️ **Snowflake + dbt warehouses** | Data Vault 2.0 and star-schema models, tested and documented, shipped through Azure DevOps and GitLab CI/CD across dev → test → prod. |
| ⚙️ **Config-driven ingestion** | One JSON file provisions a full Snowflake ingestion stack (Snowpipe, Streams, Tasks) via Terraform and a Python CLI. 200+ entities onboarded, zero custom code per source. |
| ☁️ **Cloud data platforms** | 2+ TB Azure + Snowflake platform on Azure Data Factory and dbt; Kubernetes ingestion from Hadoop into Azure Data Lake. |
| 🔐 **Governance for regulated clients** | RBAC, data masking, row-level security, data contracts, Data Mesh. |
| 🤖 **AI on top of the warehouse** | Snowflake Cortex, LangGraph text-to-SQL agents, RAG, FastAPI in Docker. |

### Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,postgres,azure,gcp,aws,terraform,docker,kubernetes,githubactions,gitlab,fastapi,cloudflare&perline=12" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Snowflake-29B5E8?style=flat-square&logo=snowflake&logoColor=white" />
  <img src="https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white" />
  <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white" />
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure%20Data%20Factory-0078D4?style=flat-square&logo=microsoftazure&logoColor=white" />
  <img src="https://img.shields.io/badge/Fivetran-0073FF?style=flat-square&logo=fivetran&logoColor=white" />
  <img src="https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black" />
  <img src="https://img.shields.io/badge/Qlik%20Sense-009848?style=flat-square&logo=qlik&logoColor=white" />
</p>

### Featured projects

- **[Ask DoDo](https://david-abdelmalek.pages.dev)** — RAG assistant on my portfolio. Ask it about me in English or German; answers come only from my real CV. Snowflake Cortex behind a Cloudflare Worker.
- **[Agentic Text-to-SQL](https://github.com/DavidAbdelmalek/agentic-text-to-sql)** — plain-English questions answered with safely generated, read-only SQL over a dbt star schema. LangGraph, FastAPI, Docker.
- **[Ontology vs Semantic Layer](https://github.com/DavidAbdelmalek/hubspot-ontology-snowflake)** — two AI agents on identical HubSpot data in Snowflake. On a multi-hop question the ontology agent found the full set in one pass; the typed-table agent missed connections. [Write-up on Medium →](https://medium.com/@davidonsy123/ontology-vs-a-plain-semantic-layer-testing-ai-agents-on-hubspot-in-snowflake-5245cf7c5a46)

## 🏅 CERTIFICATIONS

- **Microsoft Certified: Azure Solutions Architect Expert (AZ-305)** — [credential](https://learn.microsoft.com/api/credentials/share/en-us/DavidAbdelmalek-9866/EBFD9A660D6CA148?sharingId=DE2BC44C85601C1F)
- **Microsoft Certified: Azure Data Engineer Associate (DP-203)**
- **Microsoft Certified: Azure Administrator Associate (AZ-104)** — [credential](https://learn.microsoft.com/en-us/users/davidabdelmalek-9866/credentials/9a01048d318f1a79)
- **Microsoft Certified: Azure Fundamentals (AZ-900)** — [credential](https://www.credly.com/badges/3fa3064d-cad8-4b62-97a5-dda86aefa22f/public_url)

### Activity

<p align="center">
  <img src="https://raw.githubusercontent.com/DavidAbdelmalek/DavidAbdelmalek/main/profile-summary-card-output/tokyonight/0-profile-details.svg" width="100%" />
</p>
<p align="center">
  <img src="https://raw.githubusercontent.com/DavidAbdelmalek/DavidAbdelmalek/main/profile-summary-card-output/tokyonight/1-repos-per-language.svg" height="165" />
  <img src="https://raw.githubusercontent.com/DavidAbdelmalek/DavidAbdelmalek/main/profile-summary-card-output/tokyonight/3-stats.svg" height="165" />
  <img src="https://streak-stats.demolab.com?user=DavidAbdelmalek&theme=tokyonight&hide_border=true" height="165" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/DavidAbdelmalek/DavidAbdelmalek/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/DavidAbdelmalek/DavidAbdelmalek/output/github-snake.svg" />
    <img alt="snake eating my contributions" src="https://raw.githubusercontent.com/DavidAbdelmalek/DavidAbdelmalek/output/github-snake.svg" />
  </picture>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:29B5E8,50:203A43,100:0F2027&height=110&section=footer" />
</p>
