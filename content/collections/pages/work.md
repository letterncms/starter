---
id: 01m7bf0hdtbd9d9d33m5gp91es
title: Work
status: published
published_at: '2026-11-13T22:03:53+00:00'
position: 1
summary: 'Rooms, furniture, ceramics and the odd book, made for people along the coast and a few further away.'
---

::: section {"id":"wk-list","props":{"width":"wide"},"class":"pt-0"}
:::: list-filter {"id":"wk-filter"}
::::: filter-choice {"id":"wk-choice","props":{"look":"chips","facet":"discipline","label":"Discipline","all_label":"All work"},"class":"border-t border-border py-6"}
:::::

::::: repeat {"id":"wk-items","props":{"sort":"position","source":"entries","filter_by":"item.discipline","collection":"work"},"class":"mt-8 grid grid-cols-2 gap-x-columns gap-y-blocks max-md:grid-cols-1"}
:::::: box {"id":"wk-item","class":"even:pt-[clamp(0rem,12vw,12rem)] max-md:even:pt-0"}
::::::: component {"id":"wk-card","props":{"ref":"project-card","values":{"aspect":"4/5"}},"bind":{"values.link":"item.url","values.year":"item.year","values.image":"item.cover","values.title":"item.title","values.discipline":"item.discipline","values.colour":"item.colour"}}
:::::::
::::::
:::::

::::: filter-empty {"id":"wk-empty"}
:::::: paragraph {"id":"wk-empty-text","props":{"tag":"p","text":"Nothing here yet."},"class":"meta"}
::::::
:::::
::::
:::
