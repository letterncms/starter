---
id: 01m7bf0hdtbd9d9d33m5gp91et
title: Journal
status: published
published_at: '2026-11-13T22:03:53+00:00'
position: 2
summary: 'Notes from the workshop and the coast: how things are made, the people who make them, and the places in between.'
---

::: section {"id":"jn-latest","props":{"width":"wide"},"label":"Latest story","class":"pt-0"}
:::: repeat {"id":"jn-latest-list","props":{"sort":"-published_at","limit":1,"source":"entries","collection":"posts"}}
::::: box {"id":"jn-feature","props":{"tag":"article"},"class":"relative grid grid-cols-12 items-end gap-x-columns gap-y-6 text-inherit","bind":{"link":"item.url"},"logic":{"behaviors":{"group":true}}}
:::::: box {"id":"jn-feature-media","class":"col-span-8 col-start-1 overflow-clip max-lg:col-span-full"}
::::::: image {"id":"jn-feature-image","props":{"sizes":"(min-width: 64rem) 66vw, 100vw","aspect":"3/2","priority":true},"class":"transition-transform duration-900 ease-out group-hover:scale-102","bind":{"image":"item.cover"}}
:::::::
::::::

:::::: box {"id":"jn-feature-text","class":"col-start-9 -col-end-1 flex flex-col gap-5 pb-2 max-lg:col-span-full"}
::::::: box {"id":"jn-feature-meta","class":"meta flex gap-2"}
:::::::: paragraph {"id":"jn-feature-topic","props":{"tag":"span"},"class":"text-foreground","bind":{"text":"item.topic","visible":"item.topic"}}
::::::::

:::::::: paragraph {"id":"jn-feature-date","props":{"tag":"span"},"bind":{"text":"item.date|date:F j, Y"}}
::::::::
:::::::

::::::: heading {"id":"jn-feature-title","props":{"level":"2"},"class":"text-4xl","bind":{"text":"item.title"}}
:::::::

::::::: paragraph {"id":"jn-feature-summary","props":{"tag":"p"},"class":"text-lg leading-[1.5] text-muted","bind":{"text":"item.summary","visible":"item.summary"}}
:::::::
::::::
:::::
::::
:::

::: section {"id":"jn-all","props":{"width":"wide"},"label":"All stories","class":"pt-0"}
:::: list-filter {"id":"jn-filter"}
::::: box {"id":"jn-tools","class":"flex flex-wrap items-center justify-between gap-4 border-t border-border py-6"}
:::::: filter-choice {"id":"jn-topics","props":{"look":"chips","facet":"topic","label":"Topic","all_label":"All stories"}}
::::::

:::::: filter-search {"id":"jn-search","props":{"label":"Search the journal","show_label":false,"placeholder":"Search the journal"},"class":"w-72 max-w-full"}
::::::
:::::

::::: repeat {"id":"jn-list","props":{"sort":"-published_at","offset":1,"source":"entries","filter_by":"item.topic","search_in":"item.title, item.summary","collection":"posts"},"class":"mt-8 grid grid-cols-3 gap-x-columns gap-y-16 max-lg:grid-cols-2 max-md:grid-cols-1 max-md:gap-y-12"}
:::::: component {"id":"jn-card","props":{"ref":"story-card"},"bind":{"values.date":"item.date|date:F j, Y","values.link":"item.url","values.image":"item.cover","values.title":"item.title","values.topic":"item.topic","values.colour":"item.topic.colour"}}
::::::
:::::

::::: filter-empty {"id":"jn-empty"}
:::::: paragraph {"id":"jn-empty-text","props":{"tag":"p","text":"No stories match. Try another word or topic."},"class":"meta py-12"}
::::::
:::::
::::
:::
