<h1 align="center">Hi, I'm Lance Gonsalves 👋</h1>

<p align="center">
  <b>Data Engineer / Data Scientist</b><br>
  I build reliable data pipelines and turn the data they produce into answers.
</p>

<p align="center">
  <a href="https://github.com/LanceGonsalves?tab=repositories"><img src="https://img.shields.io/badge/Focus-Data%20Engineering%20%2B%20Data%20Science-4C6EF5?style=flat-square"></a>
  <img src="https://img.shields.io/badge/Cloud-AWS-232F3E?style=flat-square&logo=amazonaws">
  <img src="https://img.shields.io/badge/IaC-Terraform-7B42BC?style=flat-square&logo=terraform">
  <img src="https://img.shields.io/badge/Warehousing-Star%20Schema-1D9BF0?style=flat-square">
</p>

---

### 👨‍💻 About me

I design **event-driven, infrastructure-as-code data platforms** and **dimensional analytics warehouses**, then use SQL and Python to pull insight out of them. I care about the things that make data work trustworthy in production: **idempotent pipelines, data-quality gates, tested code, and reproducible infrastructure**. Everything I build runs end-to-end and is verified with automated tests before it ships.

- 🔭 Currently deepening my work across the **data engineering ↔ data science** boundary
- 🛠️ Comfortable from **Terraform + AWS** all the way to **star-schema SQL and analytics**
- ✅ Big on **testing, CI, and data quality** — pipelines that fail loudly, not silently
- 📫 Reach me: **[LinkedIn](https://www.linkedin.com/in/lance-gonsalves/)** · **lancegonsalves009@gmail.com**

---

### 🧰 Tech stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-CC2927?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

**Data Engineering**

![Airflow-style ETL](https://img.shields.io/badge/ETL%20%2F%20ELT-Pipelines-2C3E50?style=for-the-badge)
![Parquet](https://img.shields.io/badge/Apache%20Parquet-50ABF1?style=for-the-badge&logo=apacheparquet&logoColor=white)
![Dimensional Modeling](https://img.shields.io/badge/Dimensional%20Modeling-Star%20Schema-8E44AD?style=for-the-badge)
![Data Quality](https://img.shields.io/badge/Data%20Quality-Gates-27AE60?style=for-the-badge)

**Cloud & Infra**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Lambda](https://img.shields.io/badge/AWS%20Lambda-FF9900?style=for-the-badge&logo=awslambda&logoColor=white)
![S3](https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white)
![Athena](https://img.shields.io/badge/Athena-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Glue](https://img.shields.io/badge/AWS%20Glue-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

**Databases & Warehouses**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=for-the-badge&logo=duckdb&logoColor=black)
![Glue Catalog](https://img.shields.io/badge/Glue%20Data%20Catalog-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)

**Data Science & Analysis**

![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![PyArrow](https://img.shields.io/badge/PyArrow-4C4C4C?style=for-the-badge&logo=apache&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)

---

### 🚀 Featured projects

#### 🌊 [aws-serverless-data-lake](https://github.com/LanceGonsalves/aws-serverless-data-lake)

![Top language](https://img.shields.io/github/languages/top/LanceGonsalves/aws-serverless-data-lake?style=flat-square&color=4C6EF5)
![Last commit](https://img.shields.io/github/last-commit/LanceGonsalves/aws-serverless-data-lake?style=flat-square)
![Repo size](https://img.shields.io/github/repo-size/LanceGonsalves/aws-serverless-data-lake?style=flat-square)
![Stars](https://img.shields.io/github/stars/LanceGonsalves/aws-serverless-data-lake?style=flat-square)

An event-driven data lake on AWS, fully provisioned with **Terraform**. S3 events trigger a **serverless ETL Lambda** that validates and flattens order events into **partitioned Parquet**, queried in place with **Athena**. Runs on real AWS *or* free/offline via LocalStack, and the core pipeline is proven end-to-end with a `moto` + `pytest` suite.<br>
`Terraform` · `S3` · `Lambda` · `Glue` · `Athena` · `IAM` · `Parquet` · `CI`

#### 🚕 [nyc-taxi-pipeline](https://github.com/LanceGonsalves/nyc-taxi-pipeline)

![Top language](https://img.shields.io/github/languages/top/LanceGonsalves/nyc-taxi-pipeline?style=flat-square&color=4C6EF5)
![Last commit](https://img.shields.io/github/last-commit/LanceGonsalves/nyc-taxi-pipeline?style=flat-square)
![Repo size](https://img.shields.io/github/repo-size/LanceGonsalves/nyc-taxi-pipeline?style=flat-square)
![Stars](https://img.shields.io/github/stars/LanceGonsalves/nyc-taxi-pipeline?style=flat-square)

A batch ETL pipeline that models NYC Yellow Taxi trips into an analytics-ready **star schema**. **Idempotent and incremental per month**, with a **6-check data-quality gate** that stops bad data before analytics. The same Python + SQL runs zero-setup on **DuckDB** or production-like on **PostgreSQL** via Docker.<br>
`Python` · `SQL` · `DuckDB` · `PostgreSQL` · `dimensional modeling` · `data quality`

---

### 📊 GitHub stats

<p align="center">
  <img src="https://img.shields.io/github/followers/LanceGonsalves?style=for-the-badge&logo=github&labelColor=1F2430&color=4C6EF5">
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=LanceGonsalves&style=for-the-badge&color=4C6EF5&label=PROFILE+VIEWS">
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=LanceGonsalves&hide_border=true&theme=tokyonight">
</p>

<p align="center"><sub>📈 My full contribution graph shows natively just below this README on my profile.</sub></p>

---

### 🤝 Connect

<p align="center">
  <a href="https://www.linkedin.com/in/lance-gonsalves/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:lancegonsalves009@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://github.com/LanceGonsalves"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"></a>
</p>

---

<p align="center"><i>Pipelines that fail loudly, data you can trust, and code that's tested before it ships.</i></p>
