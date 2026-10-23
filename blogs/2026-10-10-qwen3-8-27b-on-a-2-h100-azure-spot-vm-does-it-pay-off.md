---
title: "Qwen3.8-27B on a $2 H100 Azure Spot VM: does it pay off?"
url: "https://techcommunity.microsoft.com/t5/apps-on-azure-blog/qwen3-8-27b-on-a-2-h100-azure-spot-vm-does-it-pay-off/ba-p/4563387"
date: "2026-10-10"
author: "Wuyi_Weng"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=AppsonAzureBlog"
---
For three hours on the morning of October 9, a single H100 in Azure served 1,434 requests to Qwen3.8-27B: 168.7 million input tokens in, 1.27 million output tokens out. At a public list price for this model that day ($0.425 per million input tokens, $0.085 per million cached input tokens and $2.55 per million output tokens), those tokens are worth $24.35. The three hours of VM time cost $4.65 at that region's Spot price; the dashboard below counts them at a round $2 an hour.
