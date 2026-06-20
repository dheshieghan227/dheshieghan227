<h1 align="center">Hi 👋, I'm Dheshieghan</h1>
<h3 align="center">Data Engineering Undergraduate @ UTM · Azure · Spark · Power BI</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/dheshieghan-saravana-moorthy-5855011b8"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:dheshieghan@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://dheshieghan227.github.io/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=githubpages&logoColor=white"/></a>
  <a href="https://github.com/dheshieghan227"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/></a>
</p>

---

## 👨‍💻 About Me

🎓 Final-year **Computer Science (Data Engineering)** student at **Universiti Teknologi Malaysia (UTM)** · CGPA **3.83**  
☁️ Building end-to-end cloud data pipelines on **Azure** with hands-on experience in Medallion Architecture and PySpark  
🚀 Actively seeking a **Data Engineering internship** (September 2026 – June 2027, 10 months)  
🏢 Founder of **AscendX** — a digital marketing & aerial content studio  
📍 Based in Puchong, Selangor, Malaysia

---

## 🛠️ Tech Stack

### ☁️ Cloud & Data Platforms
![Azure Data Factory](https://img.shields.io/badge/Azure_Data_Factory-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Azure Databricks](https://img.shields.io/badge/Azure_Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white)
![Azure Synapse](https://img.shields.io/badge/Azure_Synapse-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![ADLS Gen2](https://img.shields.io/badge/ADLS_Gen2-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)

### ⚙️ Big Data & Processing
![Apache Spark](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white)
![Apache Flink](https://img.shields.io/badge/Apache_Flink-E6526F?style=for-the-badge&logo=apacheflink&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta_Lake-003366?style=for-the-badge&logo=databricks&logoColor=white)

### 💻 Languages & Databases
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)

### 📊 Analytics & Tools
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Alteryx](https://img.shields.io/badge/Alteryx-0078C0?style=for-the-badge&logo=alteryx&logoColor=white)

---

## 🚀 Featured Projects

### ☁️ [End-to-End Azure Data Engineering Medallion Pipeline](https://github.com/dheshieghan227/azure_end-end_data_engineering_pipeline)
> **Azure Data Factory · Azure Databricks · ADLS Gen2 · PySpark · Delta Lake · Synapse Analytics · Power BI**

Enterprise-grade ETL pipeline ingesting transactional data through a full Bronze → Silver → Gold Medallion Architecture on Azure.
- ADF orchestrates parallel `Copy Data` activities via `ForEach` loop into ADLS Gen2 Bronze layer
- Databricks PySpark notebooks clean, cast, and normalize data into Delta Lake Silver tables
- Gold layer performs Star Schema dimensional modeling; Synapse + Power BI serve executive dashboards
- Full cloud governance with Azure Key Vault, Entra ID RBAC, and ARM template infrastructure-as-code

---

### ⚡ [Spark Censo Escolar ETL Pipeline — Brazilian School Data](https://github.com/dheshieghan227/spark_etl_project_brazillian_school_data)
> **Apache Spark · PySpark · PostgreSQL · Docker · Metabase · Star Schema**

High-performance PySpark ETL pipeline processing ~2.79M rows of Brazilian School Census microdata (2010–2021).
- Dynamic delimiter detection + latin1 decoding converting raw CSVs to optimized partitioned Parquet
- Builds a full Star Schema (fact + 6 dimension tables) loaded via PySpark JDBC into PostgreSQL
- Multi-container Docker Compose stack (PostgreSQL, Adminer, Metabase) for full local reproducibility
- Metabase dashboards expose enrollment trends, top cities, and school infrastructure stats over time

---

### 📊 [High Performance Data Processing (HPDP) Portfolio](https://github.com/dheshieghan227/HPDP_myPROJECTS)
> **Python · Pandas · Dask · Polars · PyArrow · concurrent.futures · Jupyter**

Two-part portfolio benchmarking big data processing strategies and high-performance web crawling at scale.
- **Assignment 2**: Benchmarked 6 strategies (chunking, sampling, type optimization, Dask, Polars) on a 2M-row × 109-col airline dataset (841 MB) — Polars achieved **1.56s** vs Pandas baseline of **23.54s**
- **Project 1**: Concurrently scraped 100,000+ book records from BookXcess using 40-worker `ThreadPoolExecutor` with `curl_cffi` Chrome impersonation; benchmarked Pandas vs Polars vs PyArrow across 6 operations

---

### 📦 PPG Industries — Inventory Management Analytics Pipeline
> **Azure Databricks · ADLS Gen2 · PySpark · Azure Synapse · Power BI**

3-layer Medallion Architecture pipeline solving real-world inventory problems (expiry risk, dead stock, recoverable assets, stockout warnings) for PPG Industries.
- Ingested and validated 6 synthetic CSV sources with null detection, type validation, and deduplication
- Applied complex PySpark business logic in Silver layer to classify inventory risk categories
- Interactive Power BI dashboard connected to Azure Synapse Serverless SQL for business analytics

---

### 🤖 [Tutorial 4 — AI & Data Engineering](https://github.com/dheshieghan227/Tutorial4_AI)
> **Python · AI/ML · Data Engineering**

AI-assisted data processing tutorial work covering data quality management and intelligent pipeline workflows.

---

### 🖼️ [Image Classification CNN](https://github.com/dheshieghan227/image_classification_cnn)
> **Python · TensorFlow/Keras · Convolutional Neural Networks**

Deep learning image classification project implementing a CNN model for visual recognition tasks.

---

## 📚 Academic Course Repositories

These repositories document coursework, assignments, and lab work across my Computer Science degree at UTM.

| Repository | Course | Description |
|---|---|---|
| [Business-Intelligence](https://github.com/dheshieghan227/Business-Intelligence) | Business Intelligence | BI tools, dashboards, reporting, and OLAP concepts |
| [data-mining](https://github.com/dheshieghan227/data-mining) | Data Mining | Classification, clustering, association rules, and data preprocessing |
| [dap](https://github.com/dheshieghan227/dap) | Data Analytics & Programming | Analytics workflows and Python data programming |
| [ai](https://github.com/dheshieghan227/ai) | Artificial Intelligence | AI algorithms, search, and intelligent systems |
| [Database](https://github.com/dheshieghan227/Database) | Database Systems | Relational DB design, SQL, normalization |
| [database-programming](https://github.com/dheshieghan227/database-programming) | Database Programming | Stored procedures, triggers, advanced SQL |
| [dsa](https://github.com/dheshieghan227/dsa) | Data Structures & Algorithms | Core DSA implementations and problem-solving |
| [Software-Engineering](https://github.com/dheshieghan227/Software-Engineering) | Software Engineering | SDLC, design patterns, UML, and project management |
| [Enterprise](https://github.com/dheshieghan227/Enterprise) | Enterprise Systems | ERP, enterprise architecture, and system integration |
| [operating-system](https://github.com/dheshieghan227/operating-system) | Operating Systems | Process management, memory, scheduling, concurrency |
| [network-and-communications](https://github.com/dheshieghan227/network-and-communications) | Network & Communications | TCP/IP, protocols, and network architecture |
| [coa](https://github.com/dheshieghan227/coa) | Computer Organization & Architecture | CPU design, instruction sets, memory hierarchy |
| [probability-and-statistics](https://github.com/dheshieghan227/probability-and-statistics) | Probability & Statistics | Statistical methods, distributions, and data analysis |
| [OOP-Project](https://github.com/dheshieghan227/OOP-Project) | Object-Oriented Programming | OOP principles, design, and Java/C++ projects |
| [OOP-Section3-2425-2](https://github.com/dheshieghan227/OOP-Section3-2425-2) | OOP (Section 3) | Group OOP assignments and lab submissions |
| [Programming-technique](https://github.com/dheshieghan227/Programming-technique) | Programming Techniques | Foundational C++ programming and algorithms |
| [Discreet-structure](https://github.com/dheshieghan227/Discreet-structure) | Discrete Structure | Logic, sets, graphs, and combinatorics |
| [Digital-logic](https://github.com/dheshieghan227/Digital-logic) | Digital Logic | Boolean algebra, gates, circuits, and Karnaugh maps |
| [Technology-and-Information-System](https://github.com/dheshieghan227/Technology-and-Information-System) | Technology & Information System | IS concepts, IT infrastructure, and systems thinking |

---

## 🏗️ Other Projects

| Repository | Description |
|---|---|
| [BioFlora](https://github.com/dheshieghan227/BioFlora) | Plant/biodiversity information system |
| [KADA-system](https://github.com/dheshieghan227/KADA-system) | Cooperative management system (web app) |
| [Interview-Simulation](https://github.com/dheshieghan227/Interview-Simulation) | AI-powered interview simulation tool |
| [mvc_basic_pdo_php](https://github.com/dheshieghan227/mvc_basic_pdo_php) | PHP MVC architecture with PDO database layer |
| [project_ad_zeroOne_geniusaqil_os](https://github.com/dheshieghan227/project_ad_zeroOne_geniusaqil_os) | OS-related group project |
| [pt2-group-project-s03_snakemaster](https://github.com/dheshieghan227/pt2-group-project-s03_snakemaster) | Programming Technique 2 group project — Snake game |
| [Certifications](https://github.com/dheshieghan227/Certifications) | Collection of professional certification badges and credentials |

---

## 🏅 Certifications

| Certification | Issuer | Year |
|---|---|---|
| AWS Academy — Cloud Data Pipeline Builder | Amazon Web Services | 2026 |
| AWS Academy — Cloud Developing | Amazon Web Services | May 2026 |
| AWS Academy — Cloud Foundations | Amazon Web Services | Apr 2026 |
| Microsoft Certified: Azure Data Fundamentals (DP-900) | Microsoft | Feb 2026 |
| Alteryx Designer Core Certification | Alteryx | Apr 2026 |

---

## 💼 Experience

### 🚀 AscendX — Founder & Analytics Lead *(2026 – Present)*
Founded a digital marketing & aerial content studio supporting businesses with SEO, website development, content strategy, and analytics-driven campaign execution.
- Built and maintain **4 client business websites**: ascendxlab.com, greatpathsolutions.com, nutriche.com.my, aurixdigitals.com
- Developed structured KPI reporting workflows covering reach, leads, conversions, and campaign performance

---

## 🏆 Achievements

- 🥈 **2nd Place** — PROTON x UTM Business Case Study Challenge 2024
- 🥇 **1st Place** — Malaya Tigers Championship 2024
- 🎓 **CGPA 4.00** — Kolej Matrikulasi Melaka (Pre-University)
- 👑 **President** — Peer Guidance Club / Pembimbing Rakan Sebaya (2021–2022)
- 👤 **Student Council Leader** — Kolej Matrikulasi Melaka

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=dheshieghan227&show_icons=true&theme=tokyonight&hide_border=true" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=dheshieghan227&layout=compact&theme=tokyonight&hide_border=true" height="165"/>
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=dheshieghan227&theme=tokyonight&hide_border=true"/>
</p>

---

<p align="center">
  <i>"Always learning, always building."</i>
</p>
