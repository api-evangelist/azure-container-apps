---
title: "How to build long-running MCP tools on Azure Functions"
url: "https://techcommunity.microsoft.com/t5/apps-on-azure-blog/how-to-build-long-running-mcp-tools-on-azure-functions/ba-p/4532653"
date: "2026-07-01"
author: ""
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=AppsonAzureBlog"
---
Addresses handling long-running MCP tool operations that exceed typical client timeout windows of 30-60 seconds using the emerging MCP Tasks extension for asynchronous workflows. Presents a pattern using Azure Durable Functions with two tools, start_mining and get_mining_result, to initiate and poll long-running tasks while client support for the Tasks extension is still developing.
