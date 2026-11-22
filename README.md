<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0f2027,50:203a43,100:2c9fe0&height=260&section=header&text=Mouad%20Chouai&fontSize=64&fontColor=ffffff&animation=twinkling&fontAlignY=40&desc=Data%20Engineering%20%26%20Data%20Science&descSize=20&descAlignY=62" alt="header" width="100%"/>

<a href="https://github.com/justMouad">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=2C9FE0&center=true&vCenter=true&width=760&lines=%24+building+end-to-end+data+pipelines+%E2%9A%99%EF%B8%8F;%24+streaming+in+real+time+with+Kafka+%26+Spark+%E2%9A%A1;%24+capturing+changes+with+Debezium+CDC+%F0%9F%94%81;%24+turning+raw+data+into+insights+%F0%9F%93%8A" alt="Typing animation" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/moaudchaoui/)
[![Email](https://img.shields.io/badge/Email-Contact%20Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:chouaimouad42@gmail.com)
[![Location](https://img.shields.io/badge/Fès-Morocco-2C5364?style=for-the-badge&logo=googlemaps&logoColor=white)](#)
![Profile Views](https://komarev.com/ghpvc/?username=justMouad&label=Views&color=2c9fe0&style=for-the-badge)

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f2027,100:2c9fe0&height=2&section=header" width="100%"/>

## 👨‍💻 About Me

Master's student in **Data Engineering & Data Science** at **FSDM Fès**, on a **double degree with Université Sorbonne Paris Nord**. I build **scalable data systems** and turn raw data into insights, with hands-on experience on banking data and in data analysis.

> 🎯 **Goal:** become a skilled Data Engineer by shipping real-world, reliable and scalable data architectures.

<div align="center">

| 🔄 Pipelines | ⚡ Streaming | 🏛️ Modeling | 🔁 CDC | 🏅 Quality |
|:---:|:---:|:---:|:---:|:---:|
| ETL / ELT end to end | Kafka & Spark | Star schema | Debezium | Tests between layers |

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f2027,100:2c9fe0&height=2&section=header" width="100%"/>

## 🛠️ Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=py,scala,java,r,js,bash&theme=dark" alt="languages"/>

**Data Engineering & Streaming**

<img src="https://skillicons.dev/icons?i=kafka,spark,hadoop,postgres,mongodb,cassandra&theme=dark" alt="data engineering"/>

![dbt](https://img.shields.io/badge/dbt-FF694B?style=for-the-badge&logo=dbt&logoColor=white)
![Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=for-the-badge&logo=apacheairflow&logoColor=white)
![Debezium](https://img.shields.io/badge/Debezium-CDC-FF6F00?style=for-the-badge)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=for-the-badge&logo=delta&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=databricks&logoColor=white)

**ML & Analysis**

<img src="https://skillicons.dev/icons?i=pandas,numpy,sklearn,pytorch,tensorflow&theme=dark" alt="ml"/>

**DevOps & Tools**

<img src="https://skillicons.dev/icons?i=docker,linux,git,githubactions,fastapi,react&theme=dark" alt="devops"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f2027,100:2c9fe0&height=2&section=header" width="100%"/>

## 🐍 Contribution Snake

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/justMouad/justMouad/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/justMouad/justMouad/output/github-snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/justMouad/justMouad/output/github-snake-dark.svg" />
</picture>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=justMouad&theme=tokyonight&hide_border=true&ring=2C9FE0&fire=FF6F00&currStreakLabel=2C9FE0" alt="Streak" width="95%"/>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f2027,100:2c9fe0&height=2&section=header" width="100%"/>

## 📂 Featured Projects

### 🔁 Real-Time CDC Streaming Lakehouse Platform
`Debezium` `Kafka` `Spark Structured Streaming` `Delta Lake` `DuckDB` `dbt` `Airflow` `Docker` `Python`

Captures every row-level change from **PostgreSQL** with **Debezium**, streams it through **Kafka** into a **Delta Lake** lakehouse with **Spark Structured Streaming** (Bronze → Silver), then models it with **dbt** in **DuckDB**, orchestrated by **Airflow**. Analytical tables stay continuously and incrementally up to date with low latency.

```mermaid
flowchart LR
    A[(PostgreSQL)] --> B[Debezium]
    B --> C[Kafka]
    C --> D[Spark Streaming]
    D --> E[(Bronze)]
    E --> F[(Silver)]
    F --> G[(DuckDB)]
    G --> H[dbt]
    J{{Airflow}} -.-> D
    J -.-> H
```

[![Repo](https://img.shields.io/badge/View%20Repo-realtime--cdc--lakehouse-2C9FE0?style=for-the-badge&logo=github)](https://github.com/justMouad/realtime-cdc-lakehouse)

### 🏅 Data Platform with Medallion Architecture
`Python` `Spark` `Airflow` `dbt` `Docker`

End-to-end platform in **Bronze / Silver / Gold** layers: raw ingestion, cleansing and validation, then business-ready **star-schema** models. Orchestrated with **Airflow**, transformed with **dbt**, with data quality tests between layers.

```mermaid
flowchart LR
    A[Raw Sources] --> B[Bronze<br/>Ingestion]
    B --> C[Silver<br/>Cleansing & Validation]
    C --> D[Gold<br/>Star Schema]
    D --> E[Analytics]
```

### 🏗️ End-to-End Data Engineering Platform
`Python` `Kafka` `Airflow` `PostgreSQL` `Docker` `GitHub Actions`

Complete stack for ingestion, orchestration, transformation and serving of analytical data. Fully containerised with **Docker**, with **CI/CD via GitHub Actions** for automated testing and delivery.

<details>
<summary><b>➕ More projects</b></summary>
<br/>

**⚡ MASI Real-Time Market Data Pipeline** · `Spark` `Kafka` `Cassandra` `HDFS` `Python` `Scala`
Kafka and Spark Structured Streaming feeding Cassandra for low-latency queries on the MASI index, with HDFS archiving and parallelised ARIMA forecasting.

**⚽ Expected Goals (xG) Prediction Model** · `Python` `Scikit-learn` `StatsBomb`
Estimates shot quality from StatsBomb event data and matched the official benchmark across three classifiers.

**🧠 Federated Learning for Depression Detection** *(in progress)* · `Python` `PyTorch`
Privacy-preserving federated learning with CNNs, so no patient data is centralised.

**📈 ML-Driven Portfolio Optimisation** *(in progress)* · `Python` `LightGBM` `LSTM` `cvxpy`
Ensemble forecasting with walk-forward backtesting and mean-variance optimisation.

</details>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0f2027,100:2c9fe0&height=2&section=header" width="100%"/>

## 💼 Experience & 🎓 Education

| | | |
|:--|:--|:--|
| 💼 **AGH Data Agency Holding SA** | Data Analyst Intern | Summer 2026 |
| 💼 **CIH Bank** | Data Engineering Intern | Summer 2025 |
| 🎓 **Université Sorbonne Paris Nord** | Double-Degree Master's in Data Science | In progress |
| 🎓 **FSDM Fès** | Master's in Data Engineering & Data Science | Sep 2025 – present |
| 🎓 **FSDM Fès** | Licence in Mathematics & Computer Science | 2022 – 2025 |

**🤝 Leadership:** President of the Chess Club (FPT) · Teaching Member of the English and French Club (USMBA)

**🌍 Languages:** 🇲🇦 Arabic (Native) · 🇫🇷 French (C1) · 🇬🇧 English (C1)

<div align="center">

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-moaudchaoui-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/moaudchaoui/)
[![Gmail](https://img.shields.io/badge/Gmail-chouaimouad42%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:chouaimouad42@gmail.com)

*Open to internships, collaborations and conversations about data engineering.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=120&section=footer" alt="footer" width="100%"/>

</div>
