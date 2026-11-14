---
id: 01m7bf0hdp581k5svex4atn8dx
title: Footer
status: published
published_at: '2026-11-13T22:03:53+00:00'
position: 2
category: Site
description: 'An invitation, the studio’s address, how to get in touch, the footer menu and the small print, on a dark band.'
---

::: box {"id":"ft","props":{"tag":"footer"},"label":"Footer","class":"band pt-section pb-8"}
:::: box {"id":"ft-in","class":"mx-auto flex max-w-wide flex-col gap-blocks px-gutter"}
::::: box {"id":"ft-top","label":"Invitation","class":"grid grid-cols-[minmax(0,8fr)_minmax(0,4fr)] items-end gap-8 max-lg:grid-cols-1"}
:::::: heading {"id":"ft-title","props":{"text":"Come and see the workshop.","level":"2"},"class":"max-w-[12em] text-6xl leading-display tracking-[-0.015em] text-sun"}
::::::

:::::: buttons {"id":"ft-actions","props":{"justify":"end"},"class":"max-lg:justify-start"}
::::::: button {"id":"ft-visit","props":{"label":"Plan a visit","url":"entry:01m7bf0hdtbd9d9d33m5gp91ew","variant":"primary","size":"lg","icon":"arrow-right","icon_position":"end"}}
:::::::
::::::
:::::

::::: box {"id":"ft-grid","label":"Details","class":"grid grid-cols-4 gap-8 border-t border-border pt-10 text-[0.9375rem] leading-[1.6] max-lg:grid-cols-2 max-md:grid-cols-1"}
:::::: box {"id":"ft-about","class":"flex flex-col gap-2"}
::::::: link {"id":"ft-name","props":{"url":"/"},"class":"text-[1.0625rem] font-semibold tracking-[-0.02em] text-inherit","bind":{"label":"site.name"}}
:::::::

::::::: paragraph {"id":"ft-tagline","props":{"tag":"p"},"class":"max-w-72 text-muted","bind":{"text":"globals.studio.tagline"}}
:::::::
::::::

:::::: box {"id":"ft-visit-us","class":"flex flex-col gap-2"}
::::::: paragraph {"id":"ft-visit-label","props":{"text":"Visit","tag":"p"},"class":"text-muted"}
:::::::

::::::: paragraph {"id":"ft-address","props":{"tag":"p"},"class":"whitespace-pre-line","bind":{"text":"globals.studio.address"}}
:::::::

::::::: paragraph {"id":"ft-open-label","props":{"text":"Open","tag":"p"},"class":"mt-4 text-muted"}
:::::::

::::::: paragraph {"id":"ft-hours","props":{"tag":"p"},"class":"whitespace-pre-line","bind":{"text":"globals.studio.hours"}}
:::::::
::::::

:::::: box {"id":"ft-contact","class":"flex flex-col gap-2"}
::::::: paragraph {"id":"ft-contact-label","props":{"text":"Get in touch","tag":"p"},"class":"text-muted"}
:::::::

::::::: link {"id":"ft-email","class":"text-inherit","bind":{"label":"globals.studio.email","url":"mailto:{globals.studio.email}"}}
:::::::

::::::: paragraph {"id":"ft-phone","props":{"tag":"p"},"bind":{"text":"globals.studio.phone"}}
:::::::

::::::: link {"id":"ft-instagram","props":{"label":"Instagram","new_tab":true},"class":"text-inherit","bind":{"url":"globals.studio.instagram","visible":"globals.studio.instagram"}}
:::::::
::::::

:::::: box {"id":"ft-menu","props":{"tag":"nav"},"class":"flex flex-col gap-2","attrs":{"aria-label":"Footer"}}
::::::: paragraph {"id":"ft-menu-label","props":{"text":"Explore","tag":"p"},"class":"text-muted"}
:::::::

::::::: repeat {"id":"ft-links","props":{"source":"menu","menu":"footer","tag":"ul"},"class":"flex flex-col gap-1"}
:::::::: box {"id":"ft-link-item","props":{"tag":"li"}}
::::::::: link {"id":"ft-link","class":"text-inherit","bind":{"label":"item.label","url":"item.url"}}
:::::::::
::::::::
:::::::
::::::
:::::

::::: box {"id":"ft-small","label":"Small print","class":"flex flex-wrap justify-between gap-4 text-sm text-muted"}
:::::: paragraph {"id":"ft-copy","props":{"tag":"p"},"bind":{"text":"© {site.year} {site.name}"}}
::::::

:::::: link {"id":"ft-made","props":{"label":"Made with Lettern","url":"https://lettern.org","new_tab":true},"class":"text-inherit hover:text-foreground"}
::::::
:::::
::::
:::
