---
title: "Designing for High Availability: The Operational Reference for Running a Geo-Replicated ACR"
url: "https://techcommunity.microsoft.com/t5/apps-on-azure-blog/designing-for-high-availability-the-operational-reference-for/ba-p/4526465"
date: "2026-06-08"
author: "johnsonshi_msft"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=AppsonAzureBlog"
---
By Johnson Shi , Zoey (Zhuyu) Li , Huangli Wu Introduction Three of the most common questions we hear from enterprise teams running geo-replicated Azure Container Registries (ACR) are: "How do I control which region serves my traffic?" — When my AKS clusters are spread across regions, can I pin each one to its co-located replica, or am I stuck with however the global endpoint routes? "What happens during a regional incident — is failover automatic or do I have to act?" — If the registry in one region degrades, does the global endpoint reroute on its own, or do I need to manually disable the af
