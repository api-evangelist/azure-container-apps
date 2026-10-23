---
title: "Qwen3.8-Flash-Next on two H100s in an Azure Spot VM"
url: "https://techcommunity.microsoft.com/t5/apps-on-azure-blog/qwen3-8-flash-next-on-two-h100s-in-an-azure-spot-vm/ba-p/4563893"
date: "2026-10-12"
author: "Wuyi_Weng"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=AppsonAzureBlog"
---
With 150,000 tokens of context, one request to Qwen3.8-Flash-Next decoded at about 200 tokens a second, and its first token arrived in under a second, because 95% of the prompt came from the cache. That held while the agents kept up to five requests running at once. At seven, one request in twenty waited 23 seconds or more for its first token.
