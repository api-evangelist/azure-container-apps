---
title: "MCP Just Went Stateless — What the 2026 Spec Changes About Scaling on App Service"
url: "https://techcommunity.microsoft.com/t5/apps-on-azure-blog/mcp-just-went-stateless-what-the-2026-spec-changes-about-scaling/ba-p/4530222"
date: "2026-06-23"
author: "jordanselig"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=AppsonAzureBlog"
---
A couple of months ago I wrote about scaling MCP servers behind App Service's built-in load balancer . The trick back then was to lean on stateless HTTP transport so any instance could serve any request — and to make sure you turned off ARR affinity so the load balancer was actually free to spread traffic around. That post still works.
