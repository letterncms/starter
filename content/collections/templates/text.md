---
id: 01m7bf0hepk9ytgapy7acd9xzz
title: 'Text Page'
status: published
published_at: '2026-11-13T22:03:54+00:00'
position: 3
description: 'A title and long-form text in a comfortable reading column, for terms, a privacy notice or a plain page.'
collections:
  - pages
---

::: component {"id":"tx-header","props":{"ref":"header"}}
:::

::: box {"id":"tx-main","props":{"tag":"main"},"label":"Main","class":"px-gutter pt-[clamp(3rem,8vw,8rem)] pb-section","anchor":"main"}
:::: box {"id":"tx-head","props":{"tag":"header"},"class":"mx-auto mb-12 flex max-w-(--container-prose) flex-col gap-5"}
::::: heading {"id":"tx-title","props":{"level":"1"},"bind":{"text":"entry.title"}}
:::::

::::: paragraph {"id":"tx-summary","props":{"tag":"p"},"class":"lede text-muted","bind":{"text":"entry.summary","visible":"entry.summary"}}
:::::
::::

:::: outlet {"id":"tx-body","props":{"wrap":true,"prose":true},"class":"mx-auto max-w-(--container-prose)"}
::::
:::

::: component {"id":"tx-footer","props":{"ref":"footer"}}
:::
