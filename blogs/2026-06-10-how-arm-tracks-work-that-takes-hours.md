---
title: "How ARM Tracks Work That Takes Hours"
url: "https://techcommunity.microsoft.com/t5/apps-on-azure-blog/how-arm-tracks-work-that-takes-hours/ba-p/4526930"
date: "2026-06-10"
author: "aravgoyal"
feed_url: "https://techcommunity.microsoft.com/t5/s/gxcuf89792/rss/board?board.id=AppsonAzureBlog"
---
By Arav Goyal , Joy Shah , Michael Cheng , Manik Sikka , Jenny Hunter , Johnson Shi Introduction When a user creates, updates, or deletes a resource in Azure, the request flows through Azure Resource Manager (ARM) before reaching the service that actually owns the resource. For operations that complete in milliseconds, the request and response fit cleanly into a single synchronous HTTP exchange. For operations that take seconds, minutes, or hours, this is not possible: HTTP connections cannot be held open that long, and the user's client needs a way to track the work asynchronously.
