---
id: 01m7bf0hecpc4at7yn43gy5e4j
title: 'Selected Work'
status: published
published_at: '2026-11-13T22:03:54+00:00'
position: 23
category: Lists
description: 'Projects as coloured tiles in two staggered columns, filled in from Work. Each takes the colour set on its project.'
---

::: section {"id":"selected-work-s","props":{"width":"wide"}}
:::: box {"id":"selected-work-head","class":"flex items-end justify-between gap-6 border-t border-border pt-8"}
::::: heading {"id":"selected-work-t","props":{"text":"Selected work","level":"2"}}
:::::

::::: button {"id":"selected-work-l","props":{"label":"All work","url":"entry:01m7bf0hdtbd9d9d33m5gp91es","variant":"secondary","size":"sm","icon":"arrow-right","icon_position":"end"}}
:::::
::::

:::: repeat {"id":"selected-work-r","props":{"source":"entries","collection":"work","sort":"position","limit":4},"class":"mt-12 grid grid-cols-2 gap-x-columns gap-y-blocks max-md:grid-cols-1"}
::::: box {"id":"selected-work-i","class":"even:pt-[clamp(0rem,12vw,12rem)] max-md:even:pt-0"}
:::::: component {"id":"selected-work-c","props":{"ref":"project-card","values":{"aspect":"4/5"}},"bind":{"values.title":"item.title","values.image":"item.cover","values.link":"item.url","values.discipline":"item.discipline","values.colour":"item.colour","values.year":"item.year"}}
::::::
:::::
::::
:::
