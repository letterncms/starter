---
id: 01m7bf0hdtbd9d9d33m5gp91er
title: Home
status: published
published_at: '2026-11-13T22:03:53+00:00'
position: 0
summary: 'A studio for furniture, ceramics and rooms, made slowly by the sea.'
template: default
---

::: section {"id":"h-hero","props":{"width":"full","tag":"header"},"class":"tide","style":{"base":{"paddingTop":"clamp(3rem, 8vw, 8rem)","paddingBottom":"0"}},"label":"Hero"}
:::: box {"id":"h-hero-in","style":{"base":{"maxWidth":"token:container.wide","marginInline":"auto","paddingInline":"token:space.gutter","display":"grid","gridTemplateColumns":"repeat(12,minmax(0,1fr))","columnGap":"token:space.grid"}}}
::::: heading {"id":"h-hero-title","props":{"text":"Things made slowly, to be used for a long time.","level":"1"},"class":"display","style":{"base":{"gridColumn":"1 / span 9","maxWidth":"10em"},"tablet":{"gridColumn":"1 / -1"}},"motion":[{"id":"h-rise","trigger":{"type":"load"},"steps":[{"target":"words","mask":true,"from":{"y":"110%"},"duration":1,"ease":"power4.out","stagger":0.045}]}]}
:::::

::::: box {"id":"h-hero-side","style":{"base":{"gridColumn":"10 / -1","alignSelf":"end","display":"flex","flexDirection":"column","alignItems":"flex-start","gap":"token:space.6","paddingBottom":"0.75rem"},"tablet":{"gridColumn":"1 / -1","marginTop":"token:space.10"}}}
:::::: paragraph {"id":"h-hero-p","props":{"text":"We design and make furniture, ceramics and rooms in an old net loft by the harbour.","tag":"p"},"style":{"base":{"fontSize":"token:text.lg","lineHeight":"1.5","maxWidth":"22rem"}}}
::::::

:::::: button {"id":"h-hero-b","props":{"label":"See our work","url":"entry:01m7bf0hdtbd9d9d33m5gp91es","variant":"primary","size":"lg","icon":"arrow-right","icon_position":"end"}}
::::::

:::::

::::

:::: box {"id":"h-film-frame","style":{"base":{"maxWidth":"token:container.wide","marginInline":"auto","paddingInline":"token:space.gutter","marginTop":"clamp(3rem, 7vw, 6rem)"}}}
::::: video {"id":"h-film-video","props":{"file":["01m7ba38vd2byrj19ycky7ny47"],"poster":["01m7ba38vcsxdm1sqta31gsm3h"],"autoplay":true,"loop":true,"controls":false,"fit":"cover"},"style":{"base":{"aspectRatio":"21/9","overflow":"clip","borderRadius":"token:radius.lg"},"tablet":{"aspectRatio":"16/10"},"mobile":{"aspectRatio":"4/5"}}}
:::::

::::: box {"id":"h-film-caption","style":{"base":{"display":"flex","justifyContent":"space-between","gap":"token:space.4","paddingBlock":"token:space.5"}}}
:::::: paragraph {"id":"h-film-caption-text","props":{"text":"Centering clay for a set of table bowls, in the workshop on Harbour Road.","tag":"p"},"class":"meta","style":{"base":{"color":"token:color.muted"}}}
::::::

:::::: motion-toggle {"id":"h-film-pause","props":{"pause_label":"Pause motion","play_label":"Play motion"},"class":"meta","style":{"base":{"flexShrink":"0","padding":"0","border":"0","background":"none","color":"token:color.foreground","textDecorationLine":"underline","textUnderlineOffset":"0.2em","cursor":"pointer"}}}
::::::

:::::

::::

:::

::: section {"id":"h-intro","props":{"width":"wide"},"label":"Introduction"}
:::: box {"id":"h-intro-grid","style":{"base":{"display":"grid","gridTemplateColumns":"repeat(12,minmax(0,1fr))","columnGap":"token:space.grid","rowGap":"token:space.6"}}}
::::: paragraph {"id":"h-intro-label","props":{"text":"The studio","tag":"p"},"class":"eyebrow","style":{"base":{"gridColumn":"1 / span 3","paddingTop":"0.6rem","color":"token:color.muted"},"tablet":{"gridColumn":"1 / -1","paddingTop":"0"}}}
:::::

::::: box {"id":"h-intro-text","style":{"base":{"gridColumn":"4 / -1","display":"flex","flexDirection":"column","alignItems":"flex-start","gap":"token:space.8"},"tablet":{"gridColumn":"1 / -1"}}}
:::::: paragraph {"id":"h-intro-lede","props":{"text":"Five makers in an old net loft by the harbour. We design and build furniture, throw tableware and fit out rooms, for people who would rather have fewer, better things.","tag":"p"},"class":"lede","style":{"base":{"fontSize":"token:text.3xl","lineHeight":"1.2","letterSpacing":"-0.015em","maxWidth":"22em"}}}
::::::

:::::: button {"id":"h-intro-more","props":{"label":"About the studio","url":"entry:01m7bf0hdtbd9d9d33m5gp91ev","variant":"secondary","icon":"arrow-right","icon_position":"end"}}
::::::

:::::

::::

:::

::: section {"id":"h-work","props":{"width":"wide"},"style":{"base":{"paddingTop":"0"}},"label":"Selected work"}
:::: box {"id":"h-work-head","style":{"base":{"display":"flex","justifyContent":"space-between","alignItems":"end","gap":"token:space.6","marginBottom":"token:space.12"}}}
::::: heading {"id":"h-work-head-t","props":{"text":"Selected work","level":"2"}}
:::::

::::: button {"id":"h-work-head-b","props":{"label":"All work","url":"entry:01m7bf0hdtbd9d9d33m5gp91es","variant":"secondary","size":"sm","icon":"arrow-right","icon_position":"end"}}
:::::

::::

:::: repeat {"id":"h-work-list","props":{"source":"entries","collection":"work","sort":"position","limit":4},"style":{"base":{"display":"grid","gridTemplateColumns":"repeat(2,minmax(0,1fr))","gap":"token:space.grid"},"mobile":{"gridTemplateColumns":"minmax(0,1fr)"}}}
::::: box {"id":"h-work-item","style":{"even":{"marginTop":"clamp(0rem, 8vw, 8rem)"},"mobile:even":{"marginTop":"0"}},"motion":[{"id":"h-work-in","trigger":{"type":"appear"},"steps":[{"target":"self","from":{"opacity":0,"y":40},"duration":1,"ease":"power3.out"}]}]}
:::::: component {"id":"h-work-card","props":{"ref":"project-card","values":{"aspect":"4/3"}},"bind":{"values.title":"item.title","values.image":"item.cover","values.link":"item.url","values.discipline":"item.discipline","values.year":"item.year","values.colour":"item.colour"}}
::::::

:::::

::::

:::

::: section {"id":"h-make","props":{"width":"wide"},"class":"clay","label":"What we make"}
:::: box {"id":"h-make-head","style":{"base":{"display":"grid","gridTemplateColumns":"repeat(12,minmax(0,1fr))","columnGap":"token:space.grid","rowGap":"token:space.4","marginBottom":"token:space.16"}}}
::::: paragraph {"id":"h-make-label","props":{"text":"What we make","tag":"p"},"class":"eyebrow","style":{"base":{"gridColumn":"1 / span 3","paddingTop":"0.75rem"},"tablet":{"gridColumn":"1 / -1","paddingTop":"0"}}}
:::::

::::: heading {"id":"h-make-title","props":{"text":"Three crafts under one roof, so a room can be made as a whole.","level":"2"},"style":{"base":{"gridColumn":"4 / -1","maxWidth":"14em"},"tablet":{"gridColumn":"1 / -1"}}}
:::::

::::

:::: box {"id":"h-make-grid","style":{"base":{"display":"grid","gridTemplateColumns":"repeat(3,minmax(0,1fr))","gap":"token:space.grid"},"tablet":{"gridTemplateColumns":"minmax(0,1fr)","gap":"token:space.12"}}}
::::: box {"id":"h-make-1","props":{"tag":"article"},"style":{"base":{"display":"flex","flexDirection":"column","gap":"token:space.3","paddingTop":"0"},"tablet":{"paddingTop":"0"}}}
:::::: image {"id":"h-make-1-img","props":{"image":"01m7ba38tbnnp5x3srt37wanq2","alt":"Hands marking a line on an oak board with a pencil.","aspect":"4/5","sizes":"(min-width: 64rem) 32vw, 100vw"},"style":{"base":{"borderRadius":"token:radius.md","overflow":"hidden"}}}
::::::

:::::: box {"id":"h-make-1-row","style":{"base":{"display":"flex","alignItems":"baseline","gap":"token:space.4","marginTop":"token:space.3"}}}
::::::: paragraph {"id":"h-make-1-n","props":{"text":"01","tag":"p"},"style":{"base":{"fontFamily":"token:font.display","fontSize":"token:text.2xl","lineHeight":"1"}}}
:::::::

::::::: heading {"id":"h-make-1-t","props":{"text":"Furniture","level":"3"}}
:::::::

::::::

:::::: paragraph {"id":"h-make-1-p","props":{"text":"Tables, benches and chairs in oak, ash and walnut from trees felled within a day’s drive, joined by hand and finished with oil.","tag":"p"},"style":{"base":{"color":"token:color.muted","maxWidth":"26em"}}}
::::::

:::::

::::: box {"id":"h-make-2","props":{"tag":"article"},"style":{"base":{"display":"flex","flexDirection":"column","gap":"token:space.3","paddingTop":"token:space.16"},"tablet":{"paddingTop":"0"}}}
:::::: image {"id":"h-make-2-img","props":{"image":"01m7ba38te6wbdn2r5xh441w5w","alt":"Wet hands shaping a bowl on a spinning wheel.","aspect":"4/5","sizes":"(min-width: 64rem) 32vw, 100vw"},"style":{"base":{"borderRadius":"token:radius.md","overflow":"hidden"}}}
::::::

:::::: box {"id":"h-make-2-row","style":{"base":{"display":"flex","alignItems":"baseline","gap":"token:space.4","marginTop":"token:space.3"}}}
::::::: paragraph {"id":"h-make-2-n","props":{"text":"02","tag":"p"},"style":{"base":{"fontFamily":"token:font.display","fontSize":"token:text.2xl","lineHeight":"1"}}}
:::::::

::::::: heading {"id":"h-make-2-t","props":{"text":"Ceramics","level":"3"}}
:::::::

::::::

:::::: paragraph {"id":"h-make-2-p","props":{"text":"Plates, bowls and jugs thrown on the wheel from local stoneware, glazed in the colours of the coast and fired twice.","tag":"p"},"style":{"base":{"color":"token:color.muted","maxWidth":"26em"}}}
::::::

:::::

::::: box {"id":"h-make-3","props":{"tag":"article"},"style":{"base":{"display":"flex","flexDirection":"column","gap":"token:space.3","paddingTop":"token:space.32"},"tablet":{"paddingTop":"0"}}}
:::::: image {"id":"h-make-3-img","props":{"image":"01m7ba38tj3beebgr7h3v7n7w8","alt":"A low wooden table and straw cushions in a quiet room with a round window.","aspect":"4/5","sizes":"(min-width: 64rem) 32vw, 100vw"},"style":{"base":{"borderRadius":"token:radius.md","overflow":"hidden"}}}
::::::

:::::: box {"id":"h-make-3-row","style":{"base":{"display":"flex","alignItems":"baseline","gap":"token:space.4","marginTop":"token:space.3"}}}
::::::: paragraph {"id":"h-make-3-n","props":{"text":"03","tag":"p"},"style":{"base":{"fontFamily":"token:font.display","fontSize":"token:text.2xl","lineHeight":"1"}}}
:::::::

::::::: heading {"id":"h-make-3-t","props":{"text":"Rooms","level":"3"}}
:::::::

::::::

:::::: paragraph {"id":"h-make-3-p","props":{"text":"Kitchens, cafés and quiet places to read, drawn and built from the floor up, with the furniture made for them.","tag":"p"},"style":{"base":{"color":"token:color.muted","maxWidth":"26em"}}}
::::::

:::::

::::

:::

::: section {"id":"h-quote","props":{"width":"content"},"class":"sun","label":"Quote"}
:::: box {"id":"h-quote-in","props":{"tag":"figure"},"style":{"base":{"maxWidth":"64rem","marginInline":"auto","display":"flex","flexDirection":"column","alignItems":"center","gap":"token:space.12","textAlign":"center"}}}
::::: paragraph {"id":"h-quote-text","props":{"text":"“We would rather make one table that lasts a lifetime than ten that last a season.”","tag":"blockquote"},"style":{"base":{"fontFamily":"token:font.display","fontSize":"token:text.6xl","lineHeight":"0.95","letterSpacing":"-0.015em","textWrap":"balance"}}}
:::::

::::: box {"id":"h-quote-who","props":{"tag":"figcaption"},"style":{"base":{"display":"flex","alignItems":"center","gap":"token:space.4","textAlign":"left"}}}
:::::: image {"id":"h-quote-face","props":{"image":"01m7ba38v3qs0vjhnt6s4p215b","alt":"","aspect":"1/1","sizes":"4rem"},"style":{"base":{"width":"3.5rem","borderRadius":"token:radius.full","overflow":"hidden","flexShrink":"0"}}}
::::::

:::::: box {"id":"h-quote-name"}
::::::: paragraph {"id":"h-quote-n","props":{"text":"Ines Varga","tag":"p"},"style":{"base":{"fontWeight":"token:weight.semibold"}}}
:::::::

::::::: paragraph {"id":"h-quote-r","props":{"text":"Founder and furniture maker","tag":"p"},"class":"meta","style":{"base":{"color":"token:color.muted"}}}
:::::::

::::::

:::::

::::

:::

::: section {"id":"h-pause","props":{"width":"full"},"style":{"base":{"paddingBlock":"0","overflow":"clip"}},"label":"Photograph"}
:::: image {"id":"h-pause-img","props":{"image":"01m7ba38txhavpcp1xkh6rt6p1","alt":"Two people walking side by side along the shore.","sizes":"100vw"},"style":{"base":{"aspectRatio":"21/9","overflow":"clip"},"mobile":{"aspectRatio":"4/3"}},"motion":[{"id":"h-pause-drift","trigger":{"type":"scroll","start":"top bottom","end":"bottom top"},"steps":[{"target":"self","from":{"scale":1.08},"to":{"scale":1}}]}]}
::::

:::

::: section {"id":"h-numbers","props":{"width":"wide"},"class":"mist","label":"In numbers"}
:::: box {"id":"h-numbers-grid","props":{"tag":"dl"},"style":{"base":{"display":"grid","gridTemplateColumns":"repeat(4,minmax(0,1fr))","gap":"token:space.grid"},"tablet":{"gridTemplateColumns":"repeat(2,minmax(0,1fr))","rowGap":"token:space.12"}}}
::::: box {"id":"h-num-1","style":{"base":{"display":"flex","flexDirection":"column-reverse","gap":"token:space.4","paddingTop":"token:space.5","borderTop":"1px solid token:color.foreground"}}}
:::::: paragraph {"id":"h-num-1-k","props":{"text":"years at the harbour","tag":"dt"},"class":"meta","style":{"base":{"color":"token:color.muted"}}}
::::::

:::::: paragraph {"id":"h-num-1-v","props":{"text":"38","tag":"dd"},"style":{"base":{"fontFamily":"token:font.display","fontSize":"token:text.display","lineHeight":"0.85","letterSpacing":"-0.02em"}}}
::::::

:::::

::::: box {"id":"h-num-2","style":{"base":{"display":"flex","flexDirection":"column-reverse","gap":"token:space.4","paddingTop":"token:space.5","borderTop":"1px solid token:color.foreground"}}}
:::::: paragraph {"id":"h-num-2-k","props":{"text":"makers in the loft","tag":"dt"},"class":"meta","style":{"base":{"color":"token:color.muted"}}}
::::::

:::::: paragraph {"id":"h-num-2-v","props":{"text":"5","tag":"dd"},"style":{"base":{"fontFamily":"token:font.display","fontSize":"token:text.display","lineHeight":"0.85","letterSpacing":"-0.02em"}}}
::::::

:::::

::::: box {"id":"h-num-3","style":{"base":{"display":"flex","flexDirection":"column-reverse","gap":"token:space.4","paddingTop":"token:space.5","borderTop":"1px solid token:color.foreground"}}}
:::::: paragraph {"id":"h-num-3-k","props":{"text":"pieces leave the workshop each year","tag":"dt"},"class":"meta","style":{"base":{"color":"token:color.muted"}}}
::::::

:::::: paragraph {"id":"h-num-3-v","props":{"text":"240","tag":"dd"},"style":{"base":{"fontFamily":"token:font.display","fontSize":"token:text.display","lineHeight":"0.85","letterSpacing":"-0.02em"}}}
::::::

:::::

::::: box {"id":"h-num-4","style":{"base":{"display":"flex","flexDirection":"column-reverse","gap":"token:space.4","paddingTop":"token:space.5","borderTop":"1px solid token:color.foreground"}}}
:::::: paragraph {"id":"h-num-4-k","props":{"text":"kilometres to the nearest sawmill","tag":"dt"},"class":"meta","style":{"base":{"color":"token:color.muted"}}}
::::::

:::::: paragraph {"id":"h-num-4-v","props":{"text":"60","tag":"dd"},"style":{"base":{"fontFamily":"token:font.display","fontSize":"token:text.display","lineHeight":"0.85","letterSpacing":"-0.02em"}}}
::::::

:::::

::::

:::

::: section {"id":"h-journal","props":{"width":"wide"},"label":"Journal"}
:::: box {"id":"h-journal-head","style":{"base":{"display":"flex","justifyContent":"space-between","alignItems":"end","gap":"token:space.6","marginBottom":"token:space.12"}}}
::::: heading {"id":"h-journal-head-t","props":{"text":"From the journal","level":"2"}}
:::::

::::: button {"id":"h-journal-head-b","props":{"label":"All stories","url":"entry:01m7bf0hdtbd9d9d33m5gp91et","variant":"secondary","size":"sm","icon":"arrow-right","icon_position":"end"}}
:::::

::::

:::: repeat {"id":"h-journal-list","props":{"source":"entries","collection":"posts","sort":"-published_at","limit":3},"style":{"base":{"display":"grid","gridTemplateColumns":"repeat(3,minmax(0,1fr))","gap":"token:space.grid"},"tablet":{"gridTemplateColumns":"repeat(2,minmax(0,1fr))"},"mobile":{"gridTemplateColumns":"minmax(0,1fr)"}}}
::::: component {"id":"h-journal-card","props":{"ref":"story-card"},"bind":{"values.title":"item.title","values.image":"item.cover","values.link":"item.url","values.date":"item.date|date:F j, Y","values.topic":"item.topic"}}
:::::

::::

:::
