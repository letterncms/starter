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

::: box {"id":"sc","props":{"tag":"article"},"style":{"base":{"position":"relative","display":"flex","flexDirection":"column","gap":"token:space.5","padding":"token:space.4","paddingBottom":"token:space.6","borderRadius":"token:radius.lg","textDecorationLine":"none","transition":"transform 500ms cubic-bezier(.2,.8,.2,1)"},"group-hover":{"transform":"translateY(-4px)"}},"bind":{"link":"props.link","state:clay":"props.topic|is:Making","state:tide":"props.topic|is:Places","state:sun":"props.topic|is:People","state:mist":"props.topic|is:Notes"},"logic":{"behaviors":{"group":true}},"label":"Story card"}
:::: box {"id":"sc-media","style":{"base":{"overflow":"clip","borderRadius":"token:radius.md","aspectRatio":"4/3"}}}
::::: image {"id":"sc-image","props":{"aspect":"4/3","sizes":"(min-width: 64rem) 30vw, (min-width: 48rem) 46vw, 100vw"},"style":{"base":{"transition":"transform 900ms cubic-bezier(.2,.8,.2,1)"},"group-hover":{"transform":"scale(1.03)"}},"bind":{"image":"props.image","visible":"props.image"}}
:::::

::::

:::: box {"id":"sc-text","style":{"base":{"display":"flex","flexDirection":"column","gap":"token:space.3","paddingInline":"token:space.2"}}}
::::: box {"id":"sc-meta","class":"meta","style":{"base":{"display":"flex","gap":"token:space.3"}}}
:::::: paragraph {"id":"sc-topic","props":{"text":"","tag":"span"},"style":{"base":{"fontWeight":"token:weight.medium"}},"bind":{"text":"props.topic","visible":"props.topic"}}
::::::

:::::: paragraph {"id":"sc-date","props":{"text":"","tag":"span"},"style":{"base":{"color":"token:color.muted"}},"bind":{"text":"props.date","visible":"props.date"}}
::::::

:::::

::::: heading {"id":"sc-title","props":{"level":"3"},"style":{"base":{"fontFamily":"token:font.display","fontSize":"token:text.2xl","lineHeight":"1.05","letterSpacing":"token:tracking.tight","fontWeight":"token:weight.regular"}},"bind":{"text":"props.title"}}
:::::

::::

:::
