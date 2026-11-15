---
id: 01m7bf0hdp581k5svex4atn8dz
title: 'Project Card'
status: published
published_at: '2026-11-13T22:03:53+00:00'
position: 4
category: Cards
description: 'A project in a list: a tile in the project’s colour, with its photo, title, discipline and year, linked to the project.'
props:
  -
    handle: title
    type: text
    label: Title
    default: 'House in the dunes'
  -
    handle: image
    type: media
    label: Image
    max: 1
  -
    handle: link
    type: url
    label: Link
  -
    handle: discipline
    type: text
    label: Discipline
    default: Rooms
  -
    handle: year
    type: text
    label: Year
    default: '2026'
  -
    handle: colour
    type: select
    label: Colour
    options:
      tide: Tide
      clay: Clay
      sun: Sun
      mist: Mist
    default: tide
  -
    handle: aspect
    type: select
    label: Shape
    options:
      4/5: Portrait
      4/3: Landscape
      1/1: Square
      16/9: Wide
    default: 4/3
---

::: box {"id":"pc","props":{"tag":"article"},"class":"relative flex flex-col gap-5 rounded-lg p-4 pb-6 transition-transform duration-500 ease-out group-hover:-translate-y-1 data-tide:scheme-tide data-clay:scheme-clay data-sun:scheme-sun data-mist:scheme-mist","bind":{"link":"props.link","state:tide":"props.colour|is:tide","state:clay":"props.colour|is:clay","state:sun":"props.colour|is:sun","state:mist":"props.colour|is:mist"},"logic":{"behaviors":{"group":true}},"label":"Project card"}
:::: box {"id":"pc-media","class":"overflow-clip rounded-md"}
::::: image {"id":"pc-image","props":{"sizes":"(min-width: 64rem) 46vw, 100vw"},"class":"transition-transform duration-900 ease-out group-hover:scale-103","bind":{"image":"props.image","aspect":"props.aspect","visible":"props.image"}}
:::::

::::

:::: box {"id":"pc-text","class":"flex items-baseline justify-between gap-4 px-2"}
::::: heading {"id":"pc-title","props":{"level":"3"},"class":"font-display text-3xl leading-none font-normal tracking-tight","bind":{"text":"props.title"}}
:::::

::::: box {"id":"pc-meta","class":"meta flex shrink-0 gap-3"}
:::::: paragraph {"id":"pc-discipline","props":{"text":"","tag":"span"},"bind":{"text":"props.discipline","visible":"props.discipline"}}
::::::

:::::: paragraph {"id":"pc-year","props":{"text":"","tag":"span"},"bind":{"text":"props.year","visible":"props.year"}}
::::::

:::::

::::

:::
