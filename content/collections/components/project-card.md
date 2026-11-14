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

::: box {"id":"pc","props":{"tag":"article"},"style":{"base":{"position":"relative","display":"flex","flexDirection":"column","gap":"token:space.5","padding":"token:space.4","paddingBottom":"token:space.6","borderRadius":"token:radius.lg","textDecorationLine":"none","transition":"transform 500ms cubic-bezier(.2,.8,.2,1)"},"group-hover":{"transform":"translateY(-4px)"}},"bind":{"link":"props.link","state:tide":"props.colour|is:tide","state:clay":"props.colour|is:clay","state:sun":"props.colour|is:sun","state:mist":"props.colour|is:mist"},"logic":{"behaviors":{"group":true}},"label":"Project card"}
:::: box {"id":"pc-media","style":{"base":{"overflow":"clip","borderRadius":"token:radius.md"}}}
::::: image {"id":"pc-image","props":{"sizes":"(min-width: 64rem) 46vw, 100vw"},"style":{"base":{"transition":"transform 900ms cubic-bezier(.2,.8,.2,1)"},"group-hover":{"transform":"scale(1.03)"}},"bind":{"image":"props.image","aspect":"props.aspect","visible":"props.image"}}
:::::

::::

:::: box {"id":"pc-text","style":{"base":{"display":"flex","justifyContent":"space-between","alignItems":"baseline","gap":"token:space.4","paddingInline":"token:space.2"}}}
::::: heading {"id":"pc-title","props":{"level":"3"},"style":{"base":{"fontFamily":"token:font.display","fontSize":"token:text.3xl","lineHeight":"1","letterSpacing":"token:tracking.tight","fontWeight":"token:weight.regular"}},"bind":{"text":"props.title"}}
:::::

::::: box {"id":"pc-meta","class":"meta","style":{"base":{"display":"flex","gap":"token:space.3","flexShrink":"0","color":"token:color.muted"}}}
:::::: paragraph {"id":"pc-discipline","props":{"text":"","tag":"span"},"bind":{"text":"props.discipline","visible":"props.discipline"}}
::::::

:::::: paragraph {"id":"pc-year","props":{"text":"","tag":"span"},"bind":{"text":"props.year","visible":"props.year"}}
::::::

:::::

::::

:::
