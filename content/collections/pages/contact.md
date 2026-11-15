---
id: 01m7bf0hdtbd9d9d33m5gp91ew
title: Contact
status: published
published_at: '2026-11-13T22:03:53+00:00'
position: 4
summary: 'Write, call or come by. The workshop is open Thursday to Saturday, and the kettle is usually on.'
---

::: section {"id":"ct-main","props":{"width":"wide"},"label":"Details","class":"pt-0"}
:::: box {"id":"ct-grid","class":"grid grid-cols-12 gap-x-columns gap-y-12 border-t border-border pt-10"}
::::: box {"id":"ct-details","props":{"tag":"address"},"class":"col-span-5 col-start-1 flex flex-col gap-10 not-italic max-lg:col-span-full"}
:::::: box {"id":"ct-write","class":"flex flex-col gap-2"}
::::::: paragraph {"id":"ct-write-label","props":{"tag":"p","text":"Write"},"class":"eyebrow"}
:::::::

::::::: link {"id":"ct-email","class":"text-3xl leading-[1.2] tracking-snug","bind":{"url":"mailto:{globals.studio.email}","label":"globals.studio.email"}}
:::::::
::::::

:::::: box {"id":"ct-call","class":"flex flex-col gap-2"}
::::::: paragraph {"id":"ct-call-label","props":{"tag":"p","text":"Call"},"class":"eyebrow"}
:::::::

::::::: paragraph {"id":"ct-phone","props":{"tag":"p"},"class":"text-3xl leading-[1.2] tracking-snug","bind":{"text":"globals.studio.phone"}}
:::::::
::::::

:::::: box {"id":"ct-visit","class":"flex flex-col gap-2"}
::::::: paragraph {"id":"ct-visit-label","props":{"tag":"p","text":"Visit"},"class":"eyebrow"}
:::::::

::::::: paragraph {"id":"ct-address","props":{"tag":"p"},"class":"text-xl leading-[1.45] whitespace-pre-line","bind":{"text":"globals.studio.address"}}
:::::::

::::::

:::::: box {"id":"ct-open","class":"flex flex-col gap-2"}
::::::: paragraph {"id":"ct-open-label","props":{"tag":"p","text":"Open"},"class":"eyebrow"}
:::::::

::::::: paragraph {"id":"ct-hours","props":{"tag":"p"},"class":"text-xl leading-[1.45] whitespace-pre-line","bind":{"text":"globals.studio.hours"}}
:::::::
::::::

:::::: buttons {"id":"ct-actions"}
::::::: button {"id":"ct-mail","props":{"icon":"envelope-simple","size":"lg","label":"Write to us","variant":"primary","icon_position":"start"},"bind":{"url":"mailto:{globals.studio.email}"}}
:::::::

::::::: button {"id":"ct-insta","props":{"size":"lg","label":"Instagram","new_tab":true,"variant":"secondary"},"bind":{"url":"globals.studio.instagram","visible":"globals.studio.instagram"}}
:::::::
::::::
:::::

::::: image {"id":"ct-image","props":{"alt":"Two people on a grass lane between trees that leads to the sea.","image":["01m7ba38tzva6369gacpp7mqw9"],"sizes":"(min-width: 64rem) 50vw, 100vw","aspect":"4/5","caption":"The lane from the car park to the workshop. Follow it to the end."},"class":"col-start-7 -col-end-1 max-lg:col-span-full"}
:::::
::::
:::

::: section {"id":"ct-getting-here","props":{"width":"wide"},"label":"Getting here","class":"scheme-mist"}
:::: columns {"id":"ct-gh-cols","props":{"gap":"6","layout":"1-1-1"}}
::::: column {"id":"ct-gh-1"}
:::::: heading {"id":"ct-gh-1-t","props":{"text":"By train","level":"3"},"class":"mb-3 text-2xl"}
::::::

:::::: paragraph {"id":"ct-gh-1-p","props":{"tag":"p","text":"Trains run every half hour to the harbour station. From there it is a ten-minute walk along the quay, past the fish auction."},"class":"text-muted"}
::::::
:::::

::::: column {"id":"ct-gh-2"}
:::::: heading {"id":"ct-gh-2-t","props":{"text":"By bike","level":"3"},"class":"mb-3 text-2xl"}
::::::

:::::: paragraph {"id":"ct-gh-2-p","props":{"tag":"p","text":"The coast path passes the back of the yard. Leave your bike against the timber stack; nobody will move it."},"class":"text-muted"}
::::::
:::::

::::: column {"id":"ct-gh-3"}
:::::: heading {"id":"ct-gh-3-t","props":{"text":"By car","level":"3"},"class":"mb-3 text-2xl"}
::::::

:::::: paragraph {"id":"ct-gh-3-p","props":{"tag":"p","text":"Park at the dune car park and take the grass lane to the sea. For a delivery or a collection, drive right up to the loft door."},"class":"text-muted"}
::::::
:::::
::::
:::
