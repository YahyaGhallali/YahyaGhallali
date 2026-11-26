<h1 align="center">Yahya Ghallali</h1>

<p align="center">
  <strong>Data Engineering · Machine Learning · LLM Evaluation</strong><br/>
  Building reliable data pipelines and measurable AI systems.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat&logo=apachespark&logoColor=white" alt="Spark"/>
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=flat&logo=databricks&logoColor=white" alt="Databricks"/>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white" alt="PyTorch"/>
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat&logo=springboot&logoColor=white" alt="Spring Boot"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" alt="Docker"/>
</p>

---

## About

I am a data and AI engineering student looking for an **end-of-studies internship (PFE)**. My work sits where data engineering meets applied machine learning: I design pipelines with clear layers and validation, and I evaluate models with methods that can be reproduced and checked.

- Lakehouse and ETL/ELT pipelines with PySpark and Databricks
- Evaluation of LLM outputs, including hallucination detection with an LLM-as-a-Judge
- Time series modeling, reinforcement learning, computer vision and speech
- Backend services with Spring Boot and REST APIs

**Languages:** Arabic · English · French

---

## Featured Projects

### [Medallion E-Commerce Pipeline](https://github.com/YahyaGhallali/Medallion-ecommerce)
End-to-end lakehouse pipeline on the Olist Brazilian e-commerce dataset (9 source tables, about 100k orders).
- **Bronze / Silver / Gold** layers with explicit schemas, deduplication, type casting and integrity checks
- **Kimball star schema**: item-grain fact table, customer, product, seller and date dimensions
- **6 analytical KPI datasets** built with Spark window functions (MoM revenue growth, repeat-customer rate, seller delivery delay, and more)
- Gold tables published to **Databricks Unity Catalog Volumes** through the Databricks SDK
- Tuned shuffle partitions and broadcast joins, with a CLI runner (`--stage bronze|silver|gold|all`)

`PySpark` `Databricks` `Parquet` `Unity Catalog` `uv`

### [Project Veracity: LLM Hallucination Evaluation](https://github.com/YahyaGhallali/Hallucination-Project)
Reproducible pipeline that audits a small target model against the HaluEval benchmark.
- Independent **LLM-as-a-Judge** with three-way NLI-style verdicts and Pydantic-enforced JSON output
- **Self-consistency voting**, calibration against known hallucinations, and a perturbed out-of-distribution set to detect benchmark leakage
- Resilient inference: token-bucket rate limiter, exponential backoff and a retry queue for failures
- *Roadmap:* advanced RAG mitigation and internal-state probing (planned, not yet implemented)

`Python` `OpenAI SDK` `Pydantic` `HaluEval`

### [MS: Spring Boot Microservices](https://github.com/YahyaGhallali/MS)
Two independent services, a product catalog and an order service, communicating over REST.
- Stock validation with structured `404` / `400` error responses
- API documentation with OpenAPI and Swagger UI
- Maven multi-module build with JPA persistence

`Java` `Spring Boot` `REST` `OpenAPI`

### Also on my profile
- [NYC Taxi on Databricks](https://github.com/YahyaGhallali/nyc_taxi-DB-DE): data engineering project deployed as a Databricks Asset Bundle
- [Academic Orientation Agentic AI](https://github.com/YahyaGhallali/Academic-Orientation-AgenticAI): agentic AI application for academic orientation

---

## Technical Skills

| Area | Tools and concepts |
|---|---|
| **Data Engineering** | PySpark, Spark SQL, Databricks, Asset Bundles, Medallion architecture, dimensional modeling, Parquet, data quality validation |
| **Machine Learning** | PyTorch, scikit-learn, time series econometrics (GARCH), reinforcement learning (DQN/DDQN), Statsmodels, SciPy |
| **LLM / GenAI** | LLM-as-a-Judge, hallucination evaluation, self-consistency, structured outputs, Whisper and Llama fine-tuning |
| **Computer Vision** | YOLOv8, OpenCV, OCR pipelines |
| **Backend and DevOps** | Java, Spring Boot, PostgreSQL, Docker, CI/CD, Jenkins, AWS, Angular |
| **Tooling** | Git, GitHub, uv, Jupyter |

---

## Education and Experience

- **INSEA**: Master-level studies in data science
- **ENSET**: coursework in cryptography, blockchain and network security
- **INTELCIA**: software engineering internship (Spring Boot, PostgreSQL, Docker)
- **Freelance**: computer vision and AI projects

---

## GitHub Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=YahyaGhallali&show_icons=true&hide_border=true&theme=default" alt="GitHub stats"/>
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=YahyaGhallali&layout=compact&hide_border=true" alt="Top languages"/>
</p>

---

## Contact

Open to PFE and internship opportunities in data engineering, machine learning and LLM evaluation.
Reach me through [GitHub](https://github.com/YahyaGhallali).
