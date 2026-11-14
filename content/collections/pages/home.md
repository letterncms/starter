---
id: 01m7bf0hdtbd9d9d33m5gp91er
title: Home
status: published
published_at: '2026-11-13T22:03:53+00:00'
position: 0
summary: 'A studio for furniture, ceramics and rooms, made slowly by the sea.'
template: default
---

::: section {"id":"h-hero","props":{"width":"full","tag":"header"},"class":"tide pt-[clamp(3rem,8vw,8rem)] pb-0","label":"Hero"}
:::: box {"id":"h-hero-in","class":"mx-auto grid max-w-wide grid-cols-12 gap-x-columns px-gutter"}
::::: heading {"id":"h-hero-title","props":{"text":"Things made slowly, to be used for a long time.","level":"1"},"class":"display col-span-9 col-start-1 max-w-[10em] max-lg:col-span-full","motion":[{"id":"h-rise","trigger":{"type":"load"},"steps":[{"target":"words","mask":true,"from":{"y":"110%"},"duration":1,"ease":"power4.out","stagger":0.045}]}]}
:::::

::::: box {"id":"h-hero-side","class":"col-start-10 -col-end-1 flex flex-col items-start gap-6 self-end pb-3 max-lg:col-span-full max-lg:mt-10"}
:::::: paragraph {"id":"h-hero-p","props":{"text":"We design and make furniture, ceramics and rooms in an old net loft by the harbour.","tag":"p"},"class":"max-w-88 text-lg leading-[1.5]"}
::::::

:::::: button {"id":"h-hero-b","props":{"label":"See our work","url":"entry:01m7bf0hdtbd9d9d33m5gp91es","variant":"primary","size":"lg","icon":"arrow-right","icon_position":"end"}}
::::::

:::::

::::

:::: box {"id":"h-film-frame","class":"mx-auto mt-[clamp(3rem,7vw,6rem)] max-w-wide px-gutter"}
::::: video {"id":"h-film-video","props":{"file":["01m7ba38vd2byrj19ycky7ny47"],"poster":["01m7ba38vcsxdm1sqta31gsm3h"],"autoplay":true,"loop":true,"controls":false,"fit":"cover"},"class":"aspect-21/9 overflow-clip rounded-lg max-lg:aspect-16/10 max-md:aspect-4/5"}
:::::

::::: box {"id":"h-film-caption","class":"flex justify-between gap-4 py-5"}
:::::: paragraph {"id":"h-film-caption-text","props":{"text":"Centering clay for a set of table bowls, in the workshop on Harbour Road.","tag":"p"},"class":"meta"}
::::::

:::::: motion-toggle {"id":"h-film-pause","props":{"pause_label":"Pause motion","play_label":"Play motion"},"class":"meta shrink-0 cursor-pointer border-0 bg-transparent p-0 text-foreground underline-offset-[0.2em]"}
::::::

:::::

::::

:::

::: section {"id":"h-intro","props":{"width":"wide"},"label":"Introduction"}
:::: box {"id":"h-intro-grid","class":"grid grid-cols-12 gap-x-columns gap-y-6"}
::::: paragraph {"id":"h-intro-label","props":{"text":"The studio","tag":"p"},"class":"eyebrow col-span-3 col-start-1 pt-[0.6rem] text-muted max-lg:col-span-full max-lg:pt-0"}
:::::

::::: box {"id":"h-intro-text","class":"col-start-4 -col-end-1 flex flex-col items-start gap-8 max-lg:col-span-full"}
:::::: paragraph {"id":"h-intro-lede","props":{"text":"Five makers in an old net loft by the harbour. We design and build furniture, throw tableware and fit out rooms, for people who would rather have fewer, better things.","tag":"p"},"class":"lede max-w-[22em] text-3xl leading-[1.2] tracking-[-0.015em]"}
::::::

:::::: button {"id":"h-intro-more","props":{"label":"About the studio","url":"entry:01m7bf0hdtbd9d9d33m5gp91ev","variant":"secondary","icon":"arrow-right","icon_position":"end"}}
::::::

:::::

::::

:::

::: section {"id":"h-work","props":{"width":"wide"},"class":"pt-0","label":"Selected work"}
:::: box {"id":"h-work-head","class":"mb-12 flex items-end justify-between gap-6"}
::::: heading {"id":"h-work-head-t","props":{"text":"Selected work","level":"2"}}
:::::

::::: button {"id":"h-work-head-b","props":{"label":"All work","url":"entry:01m7bf0hdtbd9d9d33m5gp91es","variant":"secondary","size":"sm","icon":"arrow-right","icon_position":"end"}}
:::::

::::

:::: repeat {"id":"h-work-list","props":{"source":"entries","collection":"work","sort":"position","limit":4},"class":"grid grid-cols-2 gap-columns max-md:grid-cols-1"}
::::: box {"id":"h-work-item","class":"even:mt-[clamp(0rem,8vw,8rem)] max-md:even:mt-0","motion":[{"id":"h-work-in","trigger":{"type":"appear"},"steps":[{"target":"self","from":{"opacity":0,"y":40},"duration":1,"ease":"power3.out"}]}]}
:::::: component {"id":"h-work-card","props":{"ref":"project-card","values":{"aspect":"4/3"}},"bind":{"values.title":"item.title","values.image":"item.cover","values.link":"item.url","values.discipline":"item.discipline","values.year":"item.year","values.colour":"item.colour"}}
::::::

:::::

::::

:::

::: section {"id":"h-make","props":{"width":"wide"},"class":"clay","label":"What we make"}
:::: box {"id":"h-make-head","class":"mb-16 grid grid-cols-12 gap-x-columns gap-y-4"}
::::: paragraph {"id":"h-make-label","props":{"text":"What we make","tag":"p"},"class":"eyebrow col-span-3 col-start-1 pt-3 max-lg:col-span-full max-lg:pt-0"}
:::::

::::: heading {"id":"h-make-title","props":{"text":"Three crafts under one roof, so a room can be made as a whole.","level":"2"},"class":"col-start-4 -col-end-1 max-w-[14em] max-lg:col-span-full"}
:::::

::::

:::: box {"id":"h-make-grid","class":"grid grid-cols-3 gap-columns max-lg:grid-cols-1 max-lg:gap-12"}
::::: box {"id":"h-make-1","props":{"tag":"article"},"class":"flex flex-col gap-3 pt-0 max-lg:pt-0"}
:::::: image {"id":"h-make-1-img","props":{"image":"01m7ba38tbnnp5x3srt37wanq2","alt":"Hands marking a line on an oak board with a pencil.","aspect":"4/5","sizes":"(min-width: 64rem) 32vw, 100vw"},"class":"overflow-hidden rounded-md"}
::::::

:::::: box {"id":"h-make-1-row","class":"mt-3 flex items-baseline gap-4"}
::::::: paragraph {"id":"h-make-1-n","props":{"text":"01","tag":"p"},"class":"font-display text-2xl leading-none"}
:::::::

::::::: heading {"id":"h-make-1-t","props":{"text":"Furniture","level":"3"}}
:::::::

::::::

:::::: paragraph {"id":"h-make-1-p","props":{"text":"Tables, benches and chairs in oak, ash and walnut from trees felled within a day’s drive, joined by hand and finished with oil.","tag":"p"},"class":"max-w-[26em] text-muted"}
::::::

:::::

::::: box {"id":"h-make-2","props":{"tag":"article"},"class":"flex flex-col gap-3 pt-16 max-lg:pt-0"}
:::::: image {"id":"h-make-2-img","props":{"image":"01m7ba38te6wbdn2r5xh441w5w","alt":"Wet hands shaping a bowl on a spinning wheel.","aspect":"4/5","sizes":"(min-width: 64rem) 32vw, 100vw"},"class":"overflow-hidden rounded-md"}
::::::

:::::: box {"id":"h-make-2-row","class":"mt-3 flex items-baseline gap-4"}
::::::: paragraph {"id":"h-make-2-n","props":{"text":"02","tag":"p"},"class":"font-display text-2xl leading-none"}
:::::::

::::::: heading {"id":"h-make-2-t","props":{"text":"Ceramics","level":"3"}}
:::::::

::::::

:::::: paragraph {"id":"h-make-2-p","props":{"text":"Plates, bowls and jugs thrown on the wheel from local stoneware, glazed in the colours of the coast and fired twice.","tag":"p"},"class":"max-w-[26em] text-muted"}
::::::

:::::

::::: box {"id":"h-make-3","props":{"tag":"article"},"class":"flex flex-col gap-3 pt-32 max-lg:pt-0"}
:::::: image {"id":"h-make-3-img","props":{"image":"01m7ba38tj3beebgr7h3v7n7w8","alt":"A low wooden table and straw cushions in a quiet room with a round window.","aspect":"4/5","sizes":"(min-width: 64rem) 32vw, 100vw"},"class":"overflow-hidden rounded-md"}
::::::

:::::: box {"id":"h-make-3-row","class":"mt-3 flex items-baseline gap-4"}
::::::: paragraph {"id":"h-make-3-n","props":{"text":"03","tag":"p"},"class":"font-display text-2xl leading-none"}
:::::::

::::::: heading {"id":"h-make-3-t","props":{"text":"Rooms","level":"3"}}
:::::::

::::::

:::::: paragraph {"id":"h-make-3-p","props":{"text":"Kitchens, cafés and quiet places to read, drawn and built from the floor up, with the furniture made for them.","tag":"p"},"class":"max-w-[26em] text-muted"}
::::::

:::::

::::

:::

::: section {"id":"h-quote","props":{"width":"content"},"class":"sun","label":"Quote"}
:::: box {"id":"h-quote-in","props":{"tag":"figure"},"class":"mx-auto flex max-w-5xl flex-col items-center gap-12 text-center"}
::::: paragraph {"id":"h-quote-text","props":{"text":"“We would rather make one table that lasts a lifetime than ten that last a season.”","tag":"blockquote"},"class":"font-display text-6xl leading-[0.95] tracking-[-0.015em] text-balance"}
:::::

::::: box {"id":"h-quote-who","props":{"tag":"figcaption"},"class":"flex items-center gap-4 text-left"}
:::::: image {"id":"h-quote-face","props":{"image":"01m7ba38v3qs0vjhnt6s4p215b","alt":"","aspect":"1/1","sizes":"4rem"},"class":"w-14 shrink-0 overflow-hidden rounded-full"}
::::::

:::::: box {"id":"h-quote-name"}
::::::: paragraph {"id":"h-quote-n","props":{"text":"Ines Varga","tag":"p"},"class":"font-semibold"}
:::::::

::::::: paragraph {"id":"h-quote-r","props":{"text":"Founder and furniture maker","tag":"p"},"class":"meta"}
:::::::

::::::

:::::

::::

:::

::: section {"id":"h-pause","props":{"width":"full"},"class":"overflow-clip py-0","label":"Photograph"}
:::: image {"id":"h-pause-img","props":{"image":"01m7ba38txhavpcp1xkh6rt6p1","alt":"Two people walking side by side along the shore.","sizes":"100vw"},"class":"aspect-21/9 overflow-clip max-md:aspect-4/3","motion":[{"id":"h-pause-drift","trigger":{"type":"scroll","start":"top bottom","end":"bottom top"},"steps":[{"target":"self","from":{"scale":1.08},"to":{"scale":1}}]}]}
::::

:::

::: section {"id":"h-numbers","props":{"width":"wide"},"class":"mist","label":"In numbers"}
:::: box {"id":"h-numbers-grid","props":{"tag":"dl"},"class":"grid grid-cols-4 gap-columns max-lg:grid-cols-2 max-lg:gap-y-12"}
::::: box {"id":"h-num-1","class":"flex flex-col-reverse gap-4 border-t border-foreground pt-5"}
:::::: paragraph {"id":"h-num-1-k","props":{"text":"years at the harbour","tag":"dt"},"class":"meta"}
::::::

:::::: paragraph {"id":"h-num-1-v","props":{"text":"38","tag":"dd"},"class":"font-display text-display leading-[0.85] tracking-[-0.02em]"}
::::::

:::::

::::: box {"id":"h-num-2","class":"flex flex-col-reverse gap-4 border-t border-foreground pt-5"}
:::::: paragraph {"id":"h-num-2-k","props":{"text":"makers in the loft","tag":"dt"},"class":"meta"}
::::::

:::::: paragraph {"id":"h-num-2-v","props":{"text":"5","tag":"dd"},"class":"font-display text-display leading-[0.85] tracking-[-0.02em]"}
::::::

:::::

::::: box {"id":"h-num-3","class":"flex flex-col-reverse gap-4 border-t border-foreground pt-5"}
:::::: paragraph {"id":"h-num-3-k","props":{"text":"pieces leave the workshop each year","tag":"dt"},"class":"meta"}
::::::

:::::: paragraph {"id":"h-num-3-v","props":{"text":"240","tag":"dd"},"class":"font-display text-display leading-[0.85] tracking-[-0.02em]"}
::::::

:::::

::::: box {"id":"h-num-4","class":"flex flex-col-reverse gap-4 border-t border-foreground pt-5"}
:::::: paragraph {"id":"h-num-4-k","props":{"text":"kilometres to the nearest sawmill","tag":"dt"},"class":"meta"}
::::::

:::::: paragraph {"id":"h-num-4-v","props":{"text":"60","tag":"dd"},"class":"font-display text-display leading-[0.85] tracking-[-0.02em]"}
::::::

:::::

::::

:::

::: section {"id":"h-journal","props":{"width":"wide"},"label":"Journal"}
:::: box {"id":"h-journal-head","class":"mb-12 flex items-end justify-between gap-6"}
::::: heading {"id":"h-journal-head-t","props":{"text":"From the journal","level":"2"}}
:::::

::::: button {"id":"h-journal-head-b","props":{"label":"All stories","url":"entry:01m7bf0hdtbd9d9d33m5gp91et","variant":"secondary","size":"sm","icon":"arrow-right","icon_position":"end"}}
:::::

::::

:::: repeat {"id":"h-journal-list","props":{"source":"entries","collection":"posts","sort":"-published_at","limit":3},"class":"grid grid-cols-3 gap-columns max-lg:grid-cols-2 max-md:grid-cols-1"}
::::: component {"id":"h-journal-card","props":{"ref":"story-card"},"bind":{"values.title":"item.title","values.image":"item.cover","values.link":"item.url","values.date":"item.date|date:F j, Y","values.topic":"item.topic"}}
:::::

::::

:::
