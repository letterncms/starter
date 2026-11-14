---
id: 01m7bf0hepk9ytgapy7acd9y01
title: 'Story, Side by Side'
status: published
published_at: '2026-11-13T22:03:54+00:00'
position: 5
description: 'The title and facts in a column that stays in view, the cover and the story beside it.'
collections:
  - posts
---

::: component {"id":"ps-header","props":{"ref":"header"}}
:::

::: box {"id":"ps-main","props":{"tag":"main"},"label":"Main","anchor":"main"}
:::: box {"id":"ps-article","props":{"tag":"article"},"class":"mx-auto grid max-w-wide grid-cols-12 gap-x-columns gap-y-10 px-gutter pt-[clamp(2.5rem,6vw,6rem)] pb-section"}
::::: box {"id":"ps-side","props":{"tag":"header"},"class":"sticky top-26 col-span-4 col-start-1 flex flex-col gap-6 self-start max-lg:static max-lg:col-span-full"}
:::::: box {"id":"ps-meta","class":"meta flex gap-3"}
::::::: paragraph {"id":"ps-topic","props":{"tag":"span"},"class":"text-foreground","bind":{"text":"entry.topic","visible":"entry.topic"}}
:::::::

::::::: paragraph {"id":"ps-date","props":{"tag":"time"},"bind":{"text":"entry.date|date:F j, Y"}}
:::::::
::::::

:::::: heading {"id":"ps-title","props":{"level":"1"},"class":"text-4xl","bind":{"text":"entry.title"}}
::::::

:::::: paragraph {"id":"ps-summary","props":{"tag":"p"},"class":"text-lg leading-[1.5] text-muted","bind":{"text":"entry.summary","visible":"entry.summary"}}
::::::

:::::: button {"id":"ps-back","props":{"label":"All stories","url":"entry:01m7bf0hdtbd9d9d33m5gp91et","variant":"secondary","size":"sm","icon":"arrow-left","icon_position":"start"}}
::::::
:::::

::::: box {"id":"ps-body","class":"col-start-6 -col-end-1 flex flex-col gap-blocks max-lg:col-span-full"}
:::::: image {"id":"ps-cover","props":{"aspect":"4/3","priority":true,"sizes":"(min-width: 64rem) 58vw, 100vw"},"bind":{"image":"entry.cover","visible":"entry.cover"}}
::::::

:::::: outlet {"id":"ps-content","props":{"wrap":true,"prose":true},"class":"max-w-(--container-prose)"}
::::::
:::::
::::
:::

::: component {"id":"ps-footer","props":{"ref":"footer"}}
:::
