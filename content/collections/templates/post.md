---
id: 01m7bf0hepk9ytgapy7acd9y00
title: Story
status: published
published_at: '2026-11-13T22:03:54+00:00'
position: 4
description: 'A centred title, a wide cover photo, the story in a reading column, then the next stories.'
collections:
  - posts
---

::: component {"id":"po-header","props":{"ref":"header"}}
:::

::: box {"id":"po-main","props":{"tag":"main"},"label":"Main","anchor":"main"}
:::: box {"id":"po-article","props":{"tag":"article"},"label":"Story"}
::::: box {"id":"po-band","label":"Title band","bind":{"state:clay":"entry.topic|is:Making","state:tide":"entry.topic|is:Places","state:sun":"entry.topic|is:People","state:mist":"entry.topic|is:Notes"}}
:::::: box {"id":"po-head","props":{"tag":"header"},"label":"Title","class":"mx-auto flex max-w-4xl flex-col items-center gap-6 px-gutter pt-[clamp(3rem,7vw,7rem)] pb-[calc(clamp(3rem,8vw,7rem)+3rem)] text-center"}
::::::: box {"id":"po-meta","class":"meta flex items-center gap-3"}
:::::::: paragraph {"id":"po-topic","props":{"tag":"span"},"class":"font-semibold text-foreground","bind":{"text":"entry.topic","visible":"entry.topic"}}
::::::::

:::::::: paragraph {"id":"po-dot","props":{"text":"·","tag":"span"},"attrs":{"aria-hidden":"true"},"bind":{"visible":"entry.topic"}}
::::::::

:::::::: paragraph {"id":"po-date","props":{"tag":"time"},"bind":{"text":"entry.date|date:F j, Y"}}
::::::::
:::::::

::::::: heading {"id":"po-title","props":{"level":"1"},"class":"text-6xl leading-display","bind":{"text":"entry.title"}}
:::::::

::::::: paragraph {"id":"po-summary","props":{"tag":"p"},"class":"lede max-w-[34em] text-xl text-muted","bind":{"text":"entry.summary","visible":"entry.summary"}}
:::::::
::::::
:::::

::::: image {"id":"po-cover","props":{"aspect":"16/9","priority":true,"sizes":"(min-width: 100rem) 100rem, 100vw"},"class":"relative mx-auto -mt-[clamp(3rem,8vw,7rem)] max-w-wide px-gutter max-md:px-0","bind":{"image":"entry.cover","visible":"entry.cover"}}
:::::

::::: outlet {"id":"po-body","props":{"wrap":true,"prose":true},"class":"mx-auto max-w-[calc(var(--container-prose)+2*var(--spacing-gutter))] px-gutter pt-blocks pb-12"}
:::::

::::: repeat {"id":"po-tags","props":{"source":"list","path":"entry.tags","tag":"ul"},"label":"Tags","class":"mx-auto flex max-w-[calc(var(--container-prose)+2*var(--spacing-gutter))] flex-wrap gap-2 px-gutter"}
:::::: paragraph {"id":"po-tag","props":{"tag":"li"},"class":"rounded-full border border-border px-3 py-[0.3rem] text-sm text-muted","bind":{"text":"{item}"}}
::::::
:::::
::::

:::: section {"id":"po-more","props":{"width":"wide","tag":"aside"},"label":"More stories","class":"mt-blocks border-t border-border pt-blocks"}
::::: box {"id":"po-more-head","class":"flex items-baseline justify-between gap-4"}
:::::: heading {"id":"po-more-title","props":{"text":"More from the journal","level":"2"},"class":"text-2xl"}
::::::

:::::: button {"id":"po-more-all","props":{"label":"All stories","url":"entry:01m7bf0hdtbd9d9d33m5gp91et","variant":"secondary","size":"sm","icon":"arrow-right","icon_position":"end"}}
::::::
:::::

::::: repeat {"id":"po-more-list","props":{"source":"entries","collection":"posts","sort":"-published_at","limit":3,"skipCurrent":true},"class":"mt-8 grid grid-cols-3 gap-columns max-lg:grid-cols-2 max-lg:gap-y-12 max-md:grid-cols-1"}
:::::: component {"id":"po-more-card","props":{"ref":"story-card"},"bind":{"values.title":"item.title","values.image":"item.cover","values.link":"item.url","values.date":"item.date|date:F j, Y","values.topic":"item.topic"}}
::::::
:::::
::::
:::

::: component {"id":"po-footer","props":{"ref":"footer"}}
:::
