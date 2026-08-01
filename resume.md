# Chenyu Wu — Data Engineer

> 来源：Chenyu_Wu_CV_09.docx 完整转录（2026-07-24），供 JD 匹配用，未做精简或润色。

- 电话：07536 953 620
- 邮箱：chenyu.wu.dev@gmail.com
- 所在地：Coventry
- LinkedIn: http://www.linkedin.com/in/chenyu-wu-data-engineer
- GitHub: https://github.com/Shyqwq5
- Portfolio: https://portfolio.chenyuwu.tech/

## SUMMARY

Data Engineer with a strong foundation in software engineering and applied data science, backed by an MRes from Imperial College London. Experienced in building AWS-based ETL/ELT pipelines with Python, SQL, PySpark, Terraform and Apache Airflow, and in engineering CI/CD quality frameworks for shared data engineering codebases. Passionate about scalable, well-tested cloud data platforms that support analytics and AI-driven systems.

## SKILLS

- **Programming/Code**: Python, PySpark, Java, JavaScript
- **AWS**: Glue, Redshift, S3, EC2, Lambda, RDS, CloudWatch, IAM, Step Functions
- **DevOps**: Terraform, Apache Airflow, CI/CD (GitHub Actions), Docker, SonarQube
- **Data**: intermediate/advanced SQL, Postgres, normalisation, warehouse design
- **Design patterns**: Star Schema Warehouse, data lake, Lakehouse
- **Methodology**: Agile/Scrum, GitHub Projects (Kanban), Jira
- **Testing**: Test Driven Development (TDD), Pytest
- **Machine Learning**: Scikit-learn, OpenAI SDK, LangChain/LangGraph, LLM integration

## EXPERIENCE

### Data Engineer | Coventry Building Society, Coventry | March 2026 – Current

**Core Data Platform (Primary Responsibility)**

- Developed AWS Glue (PySpark/SQL) ETL jobs to transform mortgage data from Silver to Gold layer in a Medallion Architecture, staging in S3 and loading curated outputs into Redshift for high-performance analytics
- Orchestrated daily ETL/ELT workflows using Apache Airflow, integrating automated data quality checks, error handling and alerting to ensure SLA-compliant, dependable pipelines
- Optimised Gold layer data models for the mortgage domain, improving query performance and enabling reliable reporting for downstream analytics and risk assessment teams
- Partnered with Data Architects, Data Scientists and business stakeholders to translate reporting requirements into SQL transformations, productionising them as Glue jobs

**CI/CD Initiative (Side Project)**

- Engineered a centralised CI/CD and quality-control framework for a shared common-utils repository, raising code reliability for reusable AWS Glue/Airflow utilities used across multiple data engineering teams
- Implemented local pre-commit hooks (linting, formatting, static analysis) to enforce coding standards and prevent breaking changes to shared modules
- Built containerised test workflows in GitHub Actions with SonarQube integration, automating regression testing in reproducible Docker environments and blocking merges that fail code-coverage thresholds

### Trainee Data Engineer | Northcoders, London | September 2025 – March 2026

- Designed and orchestrated AWS-based ETL pipelines using Lambda and Pyspark to ingest external API data, transform datasets, and model them into a star-schema data warehouse with monitoring and logging
- Loaded and queried datasets in S3 and local PostgreSQL using SQL-based analytics
- Provisioned and managed AWS infrastructure reproducibly using Terraform
- Maintained data pipeline quality through Git-based workflows and CI/CD practices
- Applied software engineering best practices, including TDD, modular function-oriented design and object-oriented programming
- Developed an understanding of machine learning and LLM-driven systems with a focus on data requirements and pipeline design

### Data Scientist Intern | Lifya, London | November 2024 – February 2025

- Built quantitative models assessing environmental factors (carbon emissions, water usage, chemical inputs) from raw data, producing sustainability indicators
- Cleaned, structured and validated datasets to ensure robust analytical conclusions

### Software Developer Intern | Lifya, London | July 2024 – November 2024

- Built a full-stack e-commerce dashboard with Next.js/React, integrating Shopify APIs to ingest and process business data
- Deployed dashboards with performance metrics to support data-driven decisions

## PROJECTS

### Cloud-Based Data Engineering Platform

GitHub: https://github.com/Shyqwq5/Data-engineering-mini-platform

- Implemented an AWS Lambda function to pull JSON data from external APIs, validate, clean and transform responses, and store processed data in Amazon S3
- Implemented analytical SQL queries for business-style insights
- Developed and tested a FastAPI REST service using Pytest (TDD)
- Provisioned AWS infrastructure with Terraform (Lambda, S3, IAM, EventBridge)
- Implemented CI/CD with GitHub Actions for automated testing and deployment

### AI News Title Classification and conversational system

GitHub: https://github.com/Shyqwq5/natural-language-classifier

- Integrated a small LLM to extract titles from user input and another LLM to generate friendly explanations based on model-predicted topics
- Trained multiple scikit-learn models (Naive Bayes, Logistic Regression, Random Forest), tuned hyperparameters, and saved the best-performing classifier
- Implemented automated testing using pytest
- Built a pipeline to classify news and generate user-friendly explanations

## EDUCATION

### MRes. Nanomaterials | Imperial College London | 2023 – 2024

- Applied machine learning to address complex NFA molecular design challenges, advancing next-generation organic solar cells (OSCs)

### BSc. Chemistry | University of Nottingham | 2019 – 2023

- Developed strong problem-solving skills through hypothesis-driven experimentation
