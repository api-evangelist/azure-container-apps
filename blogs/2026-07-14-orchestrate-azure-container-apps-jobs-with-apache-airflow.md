---
title: "Orchestrate Azure Container Apps Jobs with Apache Airflow"
url: "https://techcommunity.microsoft.com/t5/apps-on-azure-blog/orchestrate-azure-container-apps-jobs-with-apache-airflow/ba-p/4534607"
date: "2026-07-14"
author: "hetvip"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=AppsonAzureBlog"
---
Azure Container Apps (ACA) Jobs are a great way to run work that starts, does something, and finishes: nightly batch, data processing, ETL, ML scoring, report generation. They scale to zero, bill per execution, and run any container you give them. But the moment your "one job" becomes "a set of jobs that depend on each other," a gap appears: How do I run twenty jobs in parallel, wait for all of them, then run one more job only if they all succeeded — and retry just the one that failed?
