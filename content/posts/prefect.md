---
title: "Automate ETL flows using Prefect and AWS"
date: 2024-09-20T17:10:36-06:00
draft: false
language: en
featured_image: ../assets/images/featured/prefect.png
summary: Build scalable pipelines using tools like Prefect, S3,  Docker and Kubernetes
description: I researched and built an scalable streaming pipeline using Quix Streams and InfluxDB
author: Francisco Sanhueza Matamala
authorimage: ../assets/images/pages/Panchito_drawing.png
categories: ["Featured", "Portfolio"]
tags: Projects
---

For a two-month project at Coysu Consulting, I created prefect flows and tasks to automate scripts that were executed manually for ingestion of data from csv files located in S3 buckets to a MYSQL database. Moreover, I implemented integration tests to verify the flows were working correctly using sample data provided by the client, and build an initial local setup using Docker and a Kubernetes cluster simulated using kind to emulate a MinIO server, a MYSQL server and a Prefect server.

# Technologies

* Python
* Prefect
* Docker
* Kubernetes
* Kind
* S3
* MinIO
* EKS
* Github