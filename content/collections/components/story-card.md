---
id: 01m7bf0hdp581k5svex4atn8dy
title: 'Story Card'
status: published
published_at: '2026-11-13T22:03:53+00:00'
position: 3
category: Cards
description: 'A story in a list: a tile in its topic’s colour, with its cover, topic, date and title, linked to the story.'
props:
  -
    handle: title
    type: text
    label: Title
    default: 'A week in the workshop'
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
    handle: date
    type: text
    label: Date
    default: 'October 2, 2026'
  -
    handle: topic
    type: text
    label: Topic
    default: Making
---

::: box {"id":"sc","props":{"tag":"article"},"class":"relative flex flex-col gap-5 rounded-lg p-4 pb-6 transition-transform duration-500 ease-out group-hover:-translate-y-1 data-tide:scheme-tide data-clay:scheme-clay data-sun:scheme-sun data-mist:scheme-mist","bind":{"link":"props.link","state:clay":"props.topic|is:Making","state:tide":"props.topic|is:Places","state:sun":"props.topic|is:People","state:mist":"props.topic|is:Notes"},"logic":{"behaviors":{"group":true}},"label":"Story card"}
:::: box {"id":"sc-media","class":"aspect-4/3 overflow-clip rounded-md"}
::::: image {"id":"sc-image","props":{"aspect":"4/3","sizes":"(min-width: 64rem) 30vw, (min-width: 48rem) 46vw, 100vw"},"class":"transition-transform duration-900 ease-out group-hover:scale-103","bind":{"image":"props.image","visible":"props.image"}}
:::::

::::

:::: box {"id":"sc-text","class":"flex flex-col gap-3 px-2"}
::::: box {"id":"sc-meta","class":"meta flex gap-3"}
:::::: paragraph {"id":"sc-topic","props":{"text":"","tag":"span"},"class":"font-medium","bind":{"text":"props.topic","visible":"props.topic"}}
::::::

:::::: paragraph {"id":"sc-date","props":{"text":"","tag":"span"},"class":"text-muted","bind":{"text":"props.date","visible":"props.date"}}
::::::

:::::

::::: heading {"id":"sc-title","props":{"level":"3"},"class":"font-display text-2xl leading-[1.05] font-normal tracking-tight","bind":{"text":"props.title"}}
:::::

::::

:::
