---
title: "Inside ACR Artifact Cache: Pull-Through Caching at Scale"
url: "https://techcommunity.microsoft.com/t5/apps-on-azure-blog/inside-acr-artifact-cache-pull-through-caching-at-scale/ba-p/4524949"
date: "2026-06-02"
author: "akashsinghal"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=AppsonAzureBlog"
---
By: Akash Singhal , Luis Dieguez , Kiran Challa, Nathan Anderson , Tony Vargas , Caroline Barker , Ren Shao , Mabel Egba , Toddy Mladenov , Johnson Shi Introduction For many customers, Azure Container Registry (ACR) is the only registry their workloads can trust, even when images and artifacts originate from a different registry such as Docker Hub, Microsoft Artifact Registry, GitHub Container Registry, Quay, another ACR, or a private registry. ACR Artifact Cache makes this many-to-one model practical by letting a platform team map a downstream ACR repository path to an upstream source reposit
