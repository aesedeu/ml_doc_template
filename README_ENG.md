<div  style="border-radius: 10px; box-shadow: 2px 2px 2px; border: 1px solid; padding: 10px ">

**Date of documentation writing:**

**Current documentation version:** 1.0

**Document author:**

> *The author is not responsible for any copies, forks, re-uploads made by other users, or anything else related to this repository. This is the author's only account and repository.*

</div>

# Содержание
- [List of developers](#list-of-developers)
- [Glossary](#glossary)

1. [Statement of the problem](#1-statement-of-the-problem)
    - 1.1. [General description of the problem and statement of the business problem](#11-general-description-of-the-problem-and-statement-of-the-business-problem)
    - 1.2. [General statement of the mathematical problem](#12-general-statement-of-the-mathematical-problem)
        - 1.2.1. [Mathematical formulation](#121-mathematical-formulation)
        - 1.2.2. [Hypotheses and formal statement](#122-hypotheses-and-formal-statement)
        - 1.2.3. [Acceptance criteria and requirements for the accuracy of the final solution](#123-acceptance-criteria-and-requirements-for-the-accuracy-of-the-final-solution)
        - 1.2.4. [MVP](#124-mvp)
    - 1.3. [Cold start](#13-cold-start)
    - 1.4. [Proof of concept (POC)](#14-proof-of-concept-poc)
2. [Project architecture](#2-project-architecture)
    - 2.1. [Technical requirements for VM](#21-technical-requirements-for-vm)
    - 2.2. [Applicable software](#22-applicable-software)
    - 2.3. [Diagram of processes on a VM](#23-diagram-of-processes-on-a-vm)
3. [Analysis of initial data](#3-analysis-of-initial-data)
    - 3.1. [Data sources](#31-data-sources)
    - 3.2. [Analysis of data completeness and quality](#32-analysis-of-data-completeness-and-quality)
    - 3.3. [Analysis of statistical outliers and anomalies](#33-analysis-of-statistical-outliers-and-anomalies)
    - 3.4. [Description of the final dataset](#34-description-of-the-final-dataset)
4. [Description of the ML pipeline](#4-description-of-the-ml-pipeline)
    - 4.1. [ETL processes](#41-etl-processes)
        - 4.1.1. [Data extraction](#411-data-extraction)
        - 4.1.2. [Data transformation](#412-data-transformation)
    - 4.2. [Model architecture](#42-model-architecture)
    - 4.3. [Generating Model Recommendations](#43-generating-model-recommendations)
    - 4.4. [Description of Airflow DAGs](#44-description-of-airflow-dags)
        - 4.4.1. [pipeline.py](#441-pipelinepy)
        - 4.4.2. [short_pipeline.py](#442-short_pipelinepy)
5. [Build the project](#5-build-the-project)
    - 5.1. [Repository structure](#51-repository-structure)
    - 5.2. [Environment Variables](#52-environment-variables)
    - 5.3. [Project assembly algorithm and container characteristics](#53-project-assembly-algorithm-and-container-characteristics)
    - 5.4. [Ensuring fault tolerance](#54-ensuring-fault-tolerance)
6. [Endpoint](#6-endpoint)
7. [Security](#7-security)
    - 7.1. [Data confidentiality](#71-data-confidentiality)
    - 7.2. [Availability of services](#72-availability-of-services)
8. [Conclusion](#8-conclusion)
    - 8.1. [Main conclusions](#81-main-conclusions)
    - 8.2. [Recommendations](#82-recommendations)
    - 8.3. [Further development of the project](#83)

---
### List of developers


---
### Glossary

- `ETL` - Extract-Transform-Load, процесс извлечения, трансформации и загрузки данных из источниклв
- `ML` - Machine Learning
- `POC` - Prove of Conception
- `MVP` - Minimal Viable Product
- `DAG` - Directed Acyclic Graph
- `.parquet` - columnar data storage format (originally created for storing files in HDFS). Allows you to compactly store data and quickly read it.
- `AOV` - Average Order Value
- `OPAC` - Orders per Active Customer
- `ARPPU` - Average Revenue per Paying User
---
# 1. Statement of the problem

## 1.1. General description of the problem and statement of the business problem

## 1.2. General statement of the mathematical problem
### 1.2.1. Mathematical formulation

### 1.2.2. Hypotheses and formal statement

### 1.2.3. Acceptance criteria and requirements for the accuracy of the final solution

### 1.2.4. MVP

## 1.3. Cold start

## 1.4. Proof of concept (POC)

---
# 2. Project architecture

## 2.1. Technical requirements for VM

**Minimum Requirements:**


**Recommended requirements:**


## 2.2. Applicable software

- python3.11
- Airflow (2.8.1);
- Docker;
- Prometheus;
- Grafana;
- Postgres (16.2);
- Nginx;

## 2.3. Diagram of processes on a VM

---
# 3. Analysis of initial data
## 3.1. Data sources

| IP-адрес           	| База данных      	| Схема  	| Таблица 	| Атрибут      	| Описание                   	|
|--------------------	|------------------	|--------	|---------	|--------------	|----------------------------	|

## 3.2. Analysis of data completeness and quality

## 3.3. Analysis of statistical outliers and anomalies

## 3.4. Description of the final dataset

|  xxx 	|    xxx 	| xxx 	|        xxx 	| xxx 	| xxx 	|        xxx 	| xxx 	| xxx 	| xxx 	| xxx 	|
|---------:	|-----------:	|-------:	|-----------:	|---------------:	|-------------------:	|-----------:	|--------------------:	|-------------------:	|-------------:	|--------:	|


Data types:

| xxx 	| xxx 	|  xxx 	|    xxx 	| xxx 	| xxx 	|     xxx 	| xxx 	| xxx 	| xxx 	| xxx 	|
|--------:	|--------:	|--------:	|-------:	|---------------:	|-------------------:	|--------:	|--------------------:	|-------------------:	|-------------:	|--------:	|
|   int64 	|  object 	| float32 	| object 	|          int64 	|             object 	| float64 	|              object 	|              int64 	|        int64 	|  object 	|


---
# 4. Description of the ML pipeline
## 4.1. ETL processes
### 4.1.1. Data extraction


### 4.1.2. Data transformation

## 4.2. Model architecture


## 4.3. Generating Model Recommendations


## 4.4. Description of Airflow DAGs
### 4.4.1. pipeline.py

### 4.4.2. short_pipeline.py

---
# 5. Build the project
## 5.1. Repository structure

## 5.2. Environment Variables

## 5.3. Project assembly algorithm and container characteristics

## 5.4. Ensuring fault tolerance

---
# 6. Endpoint

---
# 7. Security
## 7.1 Data confidentiality

## 7.2. Availability of services

---
# 8. Conclusion
## 8.1. Main conclusions

## 8.2. Recommendations

## 8.3. Further development of the project
