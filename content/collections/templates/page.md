---
id: 01m7bf0hepk9ytgapy7acd9xzy
title: Page
status: published
published_at: '2026-11-13T22:03:54+00:00'
position: 2
description: 'A large title and the page’s summary, then its sections.'
collections:
  - pages
---

::: component {"id":"pg-header","props":{"ref":"header"}}
:::

::: box {"id":"pg-main","props":{"tag":"main"},"label":"Main","anchor":"main"}
:::: box {"id":"pg-head","props":{"tag":"header"},"label":"Title","class":"mx-auto grid max-w-wide grid-cols-12 items-end gap-x-columns gap-y-6 px-gutter pt-[clamp(3rem,9vw,9rem)] pb-blocks"}
::::: heading {"id":"pg-title","props":{"level":"1"},"class":"col-span-8 col-start-1 text-6xl leading-headline tracking-headline max-lg:col-span-full","bind":{"text":"entry.title"}}
:::::

::::: paragraph {"id":"pg-summary","props":{"tag":"p"},"class":"lede col-start-9 -col-end-1 text-xl text-muted max-lg:col-span-10 max-lg:col-start-1 max-md:col-span-full","bind":{"text":"entry.summary","visible":"entry.summary"}}
:::::
::::

:::: outlet {"id":"pg-content"}
::::
:::

::: component {"id":"pg-footer","props":{"ref":"footer"}}
:::
