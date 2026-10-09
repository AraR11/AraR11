# Hi, I'm Aramis Ramirez Lopez

**AI Engineer at TekDatum** 

I build the data pipelines behind ML systems. My pipelines turn raw web pages, documents and databases into validated, model-ready training data. Before data engineering I spent two years in QA automation, and it shows in how I work: my pipelines check their own output, and a record isn't done until it's verified.

**[LinkedIn](https://www.linkedin.com/in/araramirez19/)** · **[Email](mailto:aramisramirez19@gmail.com)**

Open to Data Engineer and ML Data Engineer roles.

## What I've built

- **Self-correcting data-labeling pipeline:** Multi-agent system built with LangChain, LangGraph and Gemini. One agent writes code from natural-language questions. A second runs the reference SQL, compares DataFrame outputs and sends mismatches back until each label is verified.
- **Schema and metadata extraction:** Generates metadata graphs schemas automatically from raw SQLite databases, so the agents work from the real schema.
- **Text-to-SQL pipeline:** Runs the pipeline end to end with four generation strategies (LATS, ReAct agents) and an LLM-as-judge stage. I used the curated labels to LoRA fine-tune Qwen3 generator and judge models, served with vLLM on H100s.
- **Production ETL/ELT and curation pipelines:** Built in Python and SQL with Pandas and Polars over CSV, JSON and Parquet data in AWS S3. Instrumented with OpenTelemetry, Arize Phoenix and MLflow.
- **Web corpus and RAG pipeline:** Scrapy ingestion from manufacturer sites, Google Custom Search and arXiv, running on AWS EC2/S3 and Modal. A production Agentic RAG pipeline serves it behind a Django REST API.

## Skills

- **Languages:** Python, SQL, Bash, TypeScript
- **Data engineering:** ETL/ELT, data ingestion, data modeling, data quality, schema extraction, web scraping (Scrapy)
- **Data tools:** Pandas, Polars, SQLServer, Parquet, PostgreSQL, MySQL, SQLite
- **Cloud and infrastructure:** AWS, Vertex AI, Docker, GitHub Actions, Linux
- **ML and LLM data:** RAG, LangChain, LangGraph, DSPy, vLLM, LoRA/PEFT, MLflow, OpenTelemetry

## Currently learning

<p>
  <img src="https://cdn.simpleicons.org/databricks/FF3621" height="40" alt="Databricks" title="Databricks" />
  &nbsp;
  <img src="https://cdn.simpleicons.org/snowflake/29B5E8" height="40" alt="Snowflake" title="Snowflake" />
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apachespark/apachespark-original.svg" height="40" alt="Apache Spark" title="Apache Spark" />
</p>

<details>
  <summary>Education and certifications</summary>

- B.Sc. Information Systems Engineering, Universidad Nacional de Costa Rica
- AWS Certified Cloud Practitioner
- Scrum Fundamentals Certified (SCRUMstudy)
- Postman API Fundamentals Student Expert
- Spanish (native) · English (professional)

</details>

