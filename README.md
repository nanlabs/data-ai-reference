<!--lint disable double-link awesome-heading awesome-git-repo-age awesome-toc-->
<!-- markdownlint-disable MD013 -->
<!-- jscpd:ignore-start -->

<div align="center">
<p>
    <img
        style="width: 200px"
        width="200"
        src="https://avatars.githubusercontent.com/u/4426989?s=200&v=4"
    >
</p>
<h1>Data & AI Reference</h1>

[Changelog](#) |
[Contributing](./CONTRIBUTING.md)

</div>
<div align="center">

[![Awesome](https://awesome.re/mentioned-badge.svg)](https://github.com/nanlabs/awesome-nan)
[![Continious Integration][cibadge]][ciurl]
[![License: MIT][licensebadge]][licenseurl]

</div>

This repository contains different Data & AI related resources like applications, examples, libraries,
tools and more!

## Contents

- [Architecture](#architecture)
- [Case Study](#case-study)
- [AI Agents](#ai-agents)
- [Decision Framework](#decision-framework)
- [Apps and Boilerplates](#apps-and-boilerplates)
- [Examples](#examples)
  - [Data Science and Machine Learning](#data-science-and-machine-learning)
    - [Geospatial Analysis](#geospatial-analysis)
  - [DevOps](#devops)
    - [Containers, Orchestration and Serverless](#containers-orchestration-and-serverless)
      - [Containers and Compositions (Docker, Docker Compose, Buildpacks and more)](#containers-and-compositions-docker-docker-compose-buildpacks-and-more)
      - [Development and Cloud Environments](#development-and-cloud-environments)
    - [Infrastructure as Code](#infrastructure-as-code)
      - [Serverless Framework, SAM and CloudFormation](#serverless-framework-sam-and-cloudformation)
    - [A/B Testing](#ab-testing)
  - [Backend](#backend)
    - [FastAPI](#fastapi)

- [Contributing](#contributing)
- [Contributors](#contributors)

## Architecture

| Name                                                                                                                                                                            | Description                                                                                                                                                                                                                                                                                                                                              | Keywords                                                                                                                                                                                                                                                                   |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Dagster AI Orchestration Framework - Case Study & Architecture Evaluation](https://github.com/nanlabs/data-ai-reference/tree/main/examples/dagster-ai-orchestration-framework) | Comprehensive architectural evaluation of POC-Dagster data orchestration project, examining suitability for evolution into a 4-layer AI Agent platform. Includes gap analysis (18% completeness), production-ready code templates for all 5 layers (Frontend/Orchestration/Runtime/Data/Validation), and decision framework for archival vs fresh start. | _Dagster_, _Data Orchestration_, _LangGraph_, _AI Agents_, _Architecture Evaluation_, _4-Layer Stack_, _Vercel AI SDK_, _Okta_, _Cedar_, _MCP_, _Embeddings_, _FastAPI_, _Next.js_, _TypeScript_, _Python_, _Prompt Evals_, _Decision Framework_, _Reference Architecture_ |

## Case Study

| Name                                                                                                                                                                            | Description                                                                                                                                                                                                                                                                                                                                              | Keywords                                                                                                                                                                                                                                                                   |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Dagster AI Orchestration Framework - Case Study & Architecture Evaluation](https://github.com/nanlabs/data-ai-reference/tree/main/examples/dagster-ai-orchestration-framework) | Comprehensive architectural evaluation of POC-Dagster data orchestration project, examining suitability for evolution into a 4-layer AI Agent platform. Includes gap analysis (18% completeness), production-ready code templates for all 5 layers (Frontend/Orchestration/Runtime/Data/Validation), and decision framework for archival vs fresh start. | _Dagster_, _Data Orchestration_, _LangGraph_, _AI Agents_, _Architecture Evaluation_, _4-Layer Stack_, _Vercel AI SDK_, _Okta_, _Cedar_, _MCP_, _Embeddings_, _FastAPI_, _Next.js_, _TypeScript_, _Python_, _Prompt Evals_, _Decision Framework_, _Reference Architecture_ |

## AI Agents

| Name                                                                                                                                                                            | Description                                                                                                                                                                                                                                                                                                                                              | Keywords                                                                                                                                                                                                                                                                   |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Dagster AI Orchestration Framework - Case Study & Architecture Evaluation](https://github.com/nanlabs/data-ai-reference/tree/main/examples/dagster-ai-orchestration-framework) | Comprehensive architectural evaluation of POC-Dagster data orchestration project, examining suitability for evolution into a 4-layer AI Agent platform. Includes gap analysis (18% completeness), production-ready code templates for all 5 layers (Frontend/Orchestration/Runtime/Data/Validation), and decision framework for archival vs fresh start. | _Dagster_, _Data Orchestration_, _LangGraph_, _AI Agents_, _Architecture Evaluation_, _4-Layer Stack_, _Vercel AI SDK_, _Okta_, _Cedar_, _MCP_, _Embeddings_, _FastAPI_, _Next.js_, _TypeScript_, _Python_, _Prompt Evals_, _Decision Framework_, _Reference Architecture_ |

## Decision Framework

| Name                                                                                                                                                                            | Description                                                                                                                                                                                                                                                                                                                                              | Keywords                                                                                                                                                                                                                                                                   |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Dagster AI Orchestration Framework - Case Study & Architecture Evaluation](https://github.com/nanlabs/data-ai-reference/tree/main/examples/dagster-ai-orchestration-framework) | Comprehensive architectural evaluation of POC-Dagster data orchestration project, examining suitability for evolution into a 4-layer AI Agent platform. Includes gap analysis (18% completeness), production-ready code templates for all 5 layers (Frontend/Orchestration/Runtime/Data/Validation), and decision framework for archival vs fresh start. | _Dagster_, _Data Orchestration_, _LangGraph_, _AI Agents_, _Architecture Evaluation_, _4-Layer Stack_, _Vercel AI SDK_, _Okta_, _Cedar_, _MCP_, _Embeddings_, _FastAPI_, _Next.js_, _TypeScript_, _Python_, _Prompt Evals_, _Decision Framework_, _Reference Architecture_ |

## Apps and Boilerplates

| Name                                                                                                                                                           | Description                                                                                                                                                                                                                                                                                                                  | Keywords                                                                                                                                                                                                      |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Basic AWS Glue ETL example app](https://github.com/nanlabs/data-ai-reference/tree/main/examples/serverless-glue-full-boilerplate/)                            | A simplified yet practical example of an AWS Glue application. It uses the Serverless Framework for infrastructure deployment and supports local development with DevContainers or Docker Compose.                                                                                                                           | _AWS Glue_, _ETL_, _Python_, _PySpark_, _Serverless Framework_, _DevContainers_, _Docker Compose_, _Jupyter Notebook_                                                                                         |
| [Geospatial Python Urban Analysis with PostGIS](https://github.com/nanlabs/data-ai-reference/tree/main/examples/geospatial-python-urban-analysis-with-postgis) | A comprehensive geospatial data analysis project for urban environments, featuring analysis of pedestrian zones, transportation networks, census data, and geographic boundaries. Built with PostgreSQL/PostGIS, Docker, and GeoPandas for efficient spatial queries, ETL pipelines, and geospatial machine learning models. | _Python3_, _GeoPandas_, _PostGIS_, _PostgreSQL_, _Docker_, _Geospatial Analysis_, _Urban Planning_, _ETL_, _Machine Learning_, _Jupyter Notebooks_, _Folium_, _Matplotlib_, _Scikit-learn_, _Rasterio_, _GIS_ |
| [LangGraph SLS FastAPI RAG](https://github.com/nanlabs/data-ai-reference/tree/main/examples/langgraph-sls-fastapi-rag)                                         | A Proof of Concept (POC) for a Retrieval Augmented Generation (RAG) system using LangGraph, deployed with the Serverless Framework on AWS Lambda. It integrates FastAPI for API development and DynamoDB for state management.                                                                                               | _Python3_, _FastAPI_, _LangGraph_, _Serverless Framework_, _AWS Lambda_, _DynamoDB_, _Docker_, _RAG_, _Retrieval Augmented Generation_                                                                        |

## Examples

### Data Science and Machine Learning

#### Geospatial Analysis

| Name                                                                                                                                                           | Description                                                                                                                                                                                                                                                                                                                  | Keywords                                                                                                                                                                                                      |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Geospatial Python Urban Analysis with PostGIS](https://github.com/nanlabs/data-ai-reference/tree/main/examples/geospatial-python-urban-analysis-with-postgis) | A comprehensive geospatial data analysis project for urban environments, featuring analysis of pedestrian zones, transportation networks, census data, and geographic boundaries. Built with PostgreSQL/PostGIS, Docker, and GeoPandas for efficient spatial queries, ETL pipelines, and geospatial machine learning models. | _Python3_, _GeoPandas_, _PostGIS_, _PostgreSQL_, _Docker_, _Geospatial Analysis_, _Urban Planning_, _ETL_, _Machine Learning_, _Jupyter Notebooks_, _Folium_, _Matplotlib_, _Scikit-learn_, _Rasterio_, _GIS_ |

### DevOps

#### Containers, Orchestration and Serverless

##### Containers and Compositions (Docker, Docker Compose, Buildpacks and more)

| Name                                                                                                                                                           | Description                                                                                                                                                                                                                                                                                                                  | Keywords                                                                                                                                                                                                      |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Airflow and Spark environment using Docker and Docker Compose](https://github.com/nanlabs/data-ai-reference/tree/main/examples/compose-airflow-spark/)        | Dockerfile and compose.yml to run Airflow locally with initialization scripts.                                                                                                                                                                                                                                               | _Docker_, _Docker Compose_, _Airflow_, _Spark_                                                                                                                                                                |
| [AWS Glue using Docker and Docker Compose](https://github.com/nanlabs/data-ai-reference/tree/main/examples/compose-glue/)                                      | Dockerfile and compose.yml for AWS Glue development with AWS Glue Libs, Spark, Jupyter Notebook, AWS CLI among other tools.                                                                                                                                                                                                  | _Docker_, _Docker Compose_, _AWS Glue_, _Spark_, _Jupyter Notebook_, _AWS CLI_                                                                                                                                |
| [Geospatial Python Urban Analysis with PostGIS](https://github.com/nanlabs/data-ai-reference/tree/main/examples/geospatial-python-urban-analysis-with-postgis) | A comprehensive geospatial data analysis project for urban environments, featuring analysis of pedestrian zones, transportation networks, census data, and geographic boundaries. Built with PostgreSQL/PostGIS, Docker, and GeoPandas for efficient spatial queries, ETL pipelines, and geospatial machine learning models. | _Python3_, _GeoPandas_, _PostGIS_, _PostgreSQL_, _Docker_, _Geospatial Analysis_, _Urban Planning_, _ETL_, _Machine Learning_, _Jupyter Notebooks_, _Folium_, _Matplotlib_, _Scikit-learn_, _Rasterio_, _GIS_ |

##### Development and Cloud Environments

| Name                                                                                          | Description                                                                                                                                                                                                                         | Keywords                                                                                                                                   |
| --------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| [AWS Glue](https://github.com/nanlabs/data-ai-reference/tree/main/examples/devcontainer-glue) | DevContainer for AWS Glue development. Uses `docker-compose` to run VSCode attached to a container with all the necessary tools to develop AWS Glue jobs such us AWS Glue Libs, Spark, Jupyter Notebook, AWS CLI among other tools. | _Docker_, _Docker Compose_, _DevContainer_, _VSCode DevContainer_, _GitHub Codespaces_, _AWS Glue_, _Spark_, _Jupyter Notebook_, _AWS CLI_ |

#### Infrastructure as Code

##### Serverless Framework, SAM and CloudFormation

| Name                                                                                                                                       | Description                                                                                                                                                                                                                    | Keywords                                                                                                                               |
| ------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------- |
| [AWS Glue with Python Shell and PySpark Jobs](https://github.com/nanlabs/data-ai-reference/tree/main/examples/serverless-glue-deployment/) | Serverless Framework example to deploy an AWS Glue job using Python Shell and PySpark.                                                                                                                                         | _Serverless Framework_, _AWS Glue_, _Python Shell_, _PySpark_                                                                          |
| [LangGraph SLS FastAPI RAG](https://github.com/nanlabs/data-ai-reference/tree/main/examples/langgraph-sls-fastapi-rag)                     | A Proof of Concept (POC) for a Retrieval Augmented Generation (RAG) system using LangGraph, deployed with the Serverless Framework on AWS Lambda. It integrates FastAPI for API development and DynamoDB for state management. | _Python3_, _FastAPI_, _LangGraph_, _Serverless Framework_, _AWS Lambda_, _DynamoDB_, _Docker_, _RAG_, _Retrieval Augmented Generation_ |

#### A/B Testing

| Name                                                                                                                  | Description                                                                                                                                                               | Keywords                                                                            |
| --------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------- |
| [AWS CloudWatch Evidently](https://github.com/nanlabs/data-ai-reference/tree/main/examples/aws-cloudwatch-evidently/) | An in-depth analysis and proof of concept demonstrating how to integrate AWS CloudWatch Evidently with a Node.js application for A/B testing and feature flag management. | _AWS CloudWatch_, _CloudWatch Evidently_, _A/B Testing_, _Feature Flags_, _Node.js_ |

### Backend

#### FastAPI

| Name                                                                                                                   | Description                                                                                                                                                                                                                    | Keywords                                                                                                                               |
| ---------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------------------------- |
| [LangGraph SLS FastAPI RAG](https://github.com/nanlabs/data-ai-reference/tree/main/examples/langgraph-sls-fastapi-rag) | A Proof of Concept (POC) for a Retrieval Augmented Generation (RAG) system using LangGraph, deployed with the Serverless Framework on AWS Lambda. It integrates FastAPI for API development and DynamoDB for state management. | _Python3_, _FastAPI_, _LangGraph_, _Serverless Framework_, _AWS Lambda_, _DynamoDB_, _Docker_, _RAG_, _Retrieval Augmented Generation_ |

## Contributing

- Contributions make the open source community such an amazing place to learn, inspire, and create.
- Any contributions you make are **truly appreciated**.
- Check out our [contribution guidelines](./CONTRIBUTING.md) for more information.

## Contributors

<a href="https://github.com/nanlabs/data-ai-reference/contributors">
  <img src="https://contrib.rocks/image?repo=nanlabs/data-ai-reference" alt="Contributors"/>
</a>

Made with [contributors-img](https://contrib.rocks).

[cibadge]: https://github.com/nanlabs/data-ai-reference/actions/workflows/ci.yml/badge.svg
[licensebadge]: https://img.shields.io/badge/License-MIT-blue.svg
[ciurl]: https://github.com/nanlabs/data-ai-reference/actions/workflows/ci.yml
[licenseurl]: https://github.com/nanlabs/data-ai-reference/blob/main/LICENSE
