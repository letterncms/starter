---
id: 01m7bf0hepk9ytgapy7acd9y02
title: Project
status: published
published_at: '2026-11-13T22:03:54+00:00'
position: 6
description: 'A large title, the facts of the project, a full-width photo, the project’s own sections, then the next project.'
collections:
  - work
---

::: component {"id":"pj-header","props":{"ref":"header"}}
:::

::: box {"id":"pj-main","props":{"tag":"main"},"label":"Main","anchor":"main"}
:::: box {"id":"pj-band","label":"Title band","bind":{"state:tide":"entry.colour|is:tide","state:clay":"entry.colour|is:clay","state:sun":"entry.colour|is:sun","state:mist":"entry.colour|is:mist"},"class":"pb-[clamp(3rem,8vw,7rem)] data-tide:scheme-tide data-clay:scheme-clay data-sun:scheme-sun data-mist:scheme-mist"}
::::: box {"id":"pj-head","props":{"tag":"header"},"label":"Title","class":"mx-auto grid max-w-wide grid-cols-12 gap-x-columns gap-y-10 px-gutter pt-[clamp(3rem,9vw,9rem)] pb-12"}
:::::: link {"id":"pj-back","props":{"label":"Work","url":"entry:01m7bf0hdtbd9d9d33m5gp91es","icon":"arrow-left"},"class":"meta col-span-full justify-self-start hover:text-foreground"}
::::::

:::::: heading {"id":"pj-title","props":{"level":"1"},"class":"col-span-9 col-start-1 text-6xl leading-headline tracking-headline max-lg:col-span-full","bind":{"text":"entry.title"}}
::::::

:::::: paragraph {"id":"pj-summary","props":{"tag":"p"},"class":"lede col-span-7 col-start-1 max-lg:col-span-full","bind":{"text":"entry.summary","visible":"entry.summary"}}
::::::

:::::: box {"id":"pj-facts","props":{"tag":"dl"},"label":"Facts","class":"col-start-9 -col-end-1 grid grid-cols-2 gap-x-4 gap-y-5 self-end text-[0.9375rem] max-lg:col-span-full max-lg:grid-cols-4 max-md:grid-cols-2"}
::::::: box {"id":"pj-f-client","bind":{"visible":"entry.client"}}
:::::::: paragraph {"id":"pj-f-client-k","props":{"text":"Client","tag":"dt"},"class":"text-muted"}
::::::::

:::::::: paragraph {"id":"pj-f-client-v","props":{"tag":"dd"},"bind":{"text":"entry.client"}}
::::::::
:::::::

::::::: box {"id":"pj-f-place","bind":{"visible":"entry.place"}}
:::::::: paragraph {"id":"pj-f-place-k","props":{"text":"Place","tag":"dt"},"class":"text-muted"}
::::::::

:::::::: paragraph {"id":"pj-f-place-v","props":{"tag":"dd"},"bind":{"text":"entry.place"}}
::::::::
:::::::

::::::: box {"id":"pj-f-discipline","bind":{"visible":"entry.discipline"}}
:::::::: paragraph {"id":"pj-f-discipline-k","props":{"text":"Discipline","tag":"dt"},"class":"text-muted"}
::::::::

:::::::: paragraph {"id":"pj-f-discipline-v","props":{"tag":"dd"},"bind":{"text":"entry.discipline"}}
::::::::
:::::::

::::::: box {"id":"pj-f-year","bind":{"visible":"entry.year"}}
:::::::: paragraph {"id":"pj-f-year-k","props":{"text":"Year","tag":"dt"},"class":"text-muted"}
::::::::

:::::::: paragraph {"id":"pj-f-year-v","props":{"tag":"dd"},"bind":{"text":"entry.year"}}
::::::::
:::::::
::::::
:::::
::::

:::: image {"id":"pj-cover","props":{"priority":true,"sizes":"100vw"},"class":"relative mx-auto -mt-[clamp(3rem,8vw,7rem)] aspect-21/9 w-[calc(100%-2*var(--spacing-gutter))] max-w-wide overflow-clip rounded-lg max-md:aspect-4/3","bind":{"image":"entry.cover","visible":"entry.cover"}}
::::

:::: outlet {"id":"pj-content"}
::::

:::: repeat {"id":"pj-next","props":{"source":"neighbors","show":"next","wrap":true},"label":"Next project","class":"border-t border-border"}
::::: box {"id":"pj-next-link","class":"mx-auto grid max-w-wide grid-cols-2 items-center gap-columns px-gutter py-blocks max-md:grid-cols-1","bind":{"link":"item.url"},"logic":{"behaviors":{"group":true}}}
:::::: box {"id":"pj-next-text","class":"flex flex-col gap-4"}
::::::: paragraph {"id":"pj-next-label","props":{"text":"Next project","tag":"p"},"class":"meta"}
:::::::

::::::: paragraph {"id":"pj-next-title","props":{"tag":"p"},"class":"font-display text-6xl leading-headline font-normal tracking-tight transition-transform duration-500 ease-out group-hover:translate-x-1","bind":{"text":"item.title"}}
:::::::
::::::

:::::: box {"id":"pj-next-media","class":"overflow-clip"}
::::::: image {"id":"pj-next-image","props":{"aspect":"16/9","sizes":"(min-width: 48rem) 50vw, 100vw"},"class":"transition-transform duration-900 ease-out group-hover:scale-103","bind":{"image":"item.cover","visible":"item.cover"}}
:::::::
::::::
:::::
::::
:::

::: component {"id":"pj-footer","props":{"ref":"footer"}}
:::
