---
id: 01m7k2edg0mp6yhsq3fctjqp98
title: 'Topic or Tag'
status: published
published_at: '2026-11-13T22:03:54+00:00'
position: 8
description: 'A topic or a tag: its name in a band of its colour, then the stories filed under it.'
collections:
  - topics
  - tags
---

::: component {"id":"tm-header","props":{"ref":"header"}}
:::

::: box {"id":"tm-main","props":{"tag":"main"},"label":"Main","anchor":"main"}
:::: box {"id":"tm-band","class":"data-tide:scheme-tide data-clay:scheme-clay data-sun:scheme-sun data-mist:scheme-mist","label":"Title band","bind":{"state:clay":"entry.colour|is:clay","state:tide":"entry.colour|is:tide","state:sun":"entry.colour|is:sun","state:mist":"entry.colour|is:mist"}}
::::: box {"id":"tm-head","props":{"tag":"header"},"label":"Title","class":"mx-auto grid max-w-wide grid-cols-12 items-end gap-x-columns gap-y-6 px-gutter pt-[clamp(3rem,9vw,9rem)] pb-[clamp(3rem,6vw,6rem)]"}
:::::: heading {"id":"tm-title","props":{"level":"1"},"class":"col-span-8 col-start-1 text-6xl leading-headline tracking-headline max-lg:col-span-full","bind":{"text":"entry.title"}}
::::::

:::::: paragraph {"id":"tm-summary","props":{"tag":"p"},"class":"lede col-start-9 -col-end-1 text-xl text-muted max-lg:col-span-10 max-lg:col-start-1 max-md:col-span-full","bind":{"text":"entry.summary","visible":"entry.summary"}}
::::::
:::::
::::

:::: section {"id":"tm-stories","props":{"width":"wide"},"label":"Stories","class":"pt-12 max-md:pt-8"}
::::: repeat {"id":"tm-list","props":{"source":"archive","sort":"-published_at","limit":12,"paginate":true},"class":"grid grid-cols-3 gap-x-columns gap-y-16 max-lg:grid-cols-2 max-md:grid-cols-1 max-md:gap-y-12"}
:::::: component {"id":"tm-card","props":{"ref":"story-card"},"bind":{"values.title":"item.title","values.image":"item.cover","values.link":"item.url","values.date":"item.date|date:F j, Y","values.topic":"item.topic","values.colour":"item.topic.colour"}}
::::::
:::::

::::: box {"id":"tm-pages","label":"Pages","class":"flex items-center justify-between gap-4 empty:hidden"}
:::::: link {"id":"tm-prev","props":{"label":"Newer stories"},"class":"quiet-link","bind":{"url":"pagination.prev","visible":"pagination.prev"}}
::::::

:::::: link {"id":"tm-next","props":{"label":"Older stories"},"class":"quiet-link ml-auto","bind":{"url":"pagination.next","visible":"pagination.next"}}
::::::
:::::

::::: button {"id":"tm-all","props":{"label":"All stories","url":"entry:01m7bf0hdtbd9d9d33m5gp91et","variant":"secondary","size":"sm","icon":"arrow-right","icon_position":"end"},"class":"mt-16"}
:::::
::::
:::

::: component {"id":"tm-footer","props":{"ref":"footer"}}
:::
