---
title: "Batch pipeline with GCP, dbt and Airflow"
date: 2024-09-20T17:10:36-06:00
draft: false
language: en
featured_image: ../assets/images/featured/batch-gcp.png
summary: At Fintual, I took care of the design of the warehouse and mantainance of a Batch Pipeline using proven tools for testing and scalability.
description: I researched and built an scalable streaming pipeline using Quix Streams and InfluxDB
author: Francisco Sanhueza Matamala
authorimage: ../assets/images/pages/Panchito_drawing.png
categories: ["Featured", "Portfolio"]
tags: Projects
---

I had a year and a half of work as a Data Engineer at [Fintual](https://fintual.cl/), top fintech in Chile. There I had the following roles:

- I mantained a full pipeline with a state-of-the-art technology stack to copy data from several sources to Bigquery with an ETL flow: Extraction using Airflow jobs and Kubernetes, Transforming data using dbt and Load using a data lake in Google Cloud Platform.
- I worked along with several teams including product, growth and bizops teams developing new tables in the warehouse to ease the reporting of quarterly metrics, conducting meetings between teams in Chile and México in order to be aware of the neccesities of the analytics teams and helping to standardize metrics. Moreover, I designed and implemented the whole Mexico Warehouse and helped design visualizations in Grafana.
- I wrote and made available for the whole company the documentation of the warehouse using dbt docs and Github pages, promoting autonomy in the company to look the documentation, therefore reducing significantly the amount of time my team invested to attending requests.
- I was the link between the software engineers and the data team during a large refactor of the production database, conducting several meetings to all the teams involved in the refactor, designing the necessary changes to the warehouse and documenting the changes in a website.
- Reduced processing time of tables by 95% by creating it in a incremental way using dbt.
- Provide mentorship to new hires.

# Technologies

* GCP
  * GCS
  * Bigquery
  * Composer
* Apache Airflow
* Docker
* Kubernetes
* dbt
* Grafana
* Github Actions