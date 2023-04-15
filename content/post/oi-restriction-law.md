---
author: maddy
date: 2023-02-17T10:05:28+05:30
lastmod: 2023-02-17T10:05:32+05:30
title: OI Restriction Law
description: 
tags:
- #NSE🏴
categories: 
- 🤹Options-Trading
draft: false
disableComments: false
---
- Total OTM you can buy should be equal to the Total options sold.
- Today I was confused why I couldn't buy hedge for options sold. ie I had sold 300 ce but bought only 250 ce hedge. But when i place +50 order it was showing you cannot buy OTM due to OI restriction.
- I was perplexed. I had bought 300, hedged only 250 then why can't I buy 50 more.
- The problem was that I had bought one extra hedge in PE.
- In PE I bought 250 hedge for 200 pe only.
- Hence OI restriction.
- So we have to calculate all pe & se sold = all otm hedges pe & ce.