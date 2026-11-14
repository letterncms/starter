---
id: 01m7bf0hecpc4at7yn43gy5e4d
title: 'Latest Stories'
status: published
published_at: '2026-11-13T22:03:53+00:00'
position: 18
category: Lists
description: 'The three newest stories from the journal as coloured tiles, filled in by themselves.'
---

::: section {"id":"latest-stories-s","props":{"width":"wide"}}
:::: box {"id":"latest-stories-head","class":"flex items-end justify-between gap-6 border-t border-border pt-8"}
::::: heading {"id":"latest-stories-t","props":{"text":"From the journal","level":"2"}}
:::::

::::: button {"id":"latest-stories-l","props":{"label":"All stories","url":"entry:01m7bf0hdtbd9d9d33m5gp91et","variant":"secondary","size":"sm","icon":"arrow-right","icon_position":"end"}}
:::::
::::

:::: repeat {"id":"latest-stories-r","props":{"source":"entries","collection":"posts","sort":"-published_at","limit":3},"class":"mt-12 grid grid-cols-3 gap-columns max-lg:grid-cols-2 max-md:grid-cols-1 max-md:gap-y-12"}
::::: component {"id":"latest-stories-c","props":{"ref":"story-card"},"bind":{"values.title":"item.title","values.image":"item.cover","values.link":"item.url","values.date":"item.date|date:F j, Y","values.topic":"item.topic"}}
:::::
::::
:::
