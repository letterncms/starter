---
id: 01m7bf0hdp581k5svex4atn8dw
title: Header
status: published
published_at: '2026-11-13T22:03:53+00:00'
position: 1
category: Site
description: 'The site name, the main menu, sign in once the site has public accounts, and a full-screen menu on phones.'
---

::: box {"id":"hd","props":{"tag":"header"},"label":"Header","class":"sticky top-0 z-50 bg-background/0 transition-[background-color,box-shadow,translate] duration-[300ms,300ms,400ms] ease-[ease,ease,var(--ease-out)] data-hidden:-translate-y-full data-open:bg-background data-scrolled:shadow-[0_1px_0] data-scrolled:shadow-foreground/8 data-scrolled:backdrop-blur-lg data-scrolled:backdrop-saturate-140 data-scrolled:not-data-open:bg-background/88","logic":{"data":{"open":false},"on":[{"event":"keydown","mods":["window"],"key":"escape","actions":[{"do":"set","var":"open","value":"false"},{"do":"lock","on":true}]}],"states":{"open":"open"},"behaviors":{"scroll":{"threshold":24,"hide":true}}}}
:::: box {"id":"hd-bar","label":"Bar","class":"mx-auto grid h-18 max-w-wide grid-cols-[1fr_auto] items-center gap-8 px-gutter max-md:h-16"}
::::: link {"id":"hd-name","props":{"url":"/"},"label":"Site name","class":"quiet-link justify-self-start text-[1.0625rem] font-semibold tracking-[-0.02em]","bind":{"label":"site.name"}}
:::::

::::: box {"id":"hd-nav","props":{"tag":"nav"},"label":"Main menu","class":"flex items-center gap-8 max-md:hidden","attrs":{"aria-label":"Main"}}
:::::: repeat {"id":"hd-links","props":{"source":"menu","menu":"main","tag":"ul"},"class":"flex items-center gap-8 text-[0.9375rem]"}
::::::: box {"id":"hd-item","props":{"tag":"li"}}
:::::::: link {"id":"hd-link","class":"relative inline-block py-1 text-muted transition-colors duration-150 ease-[ease] after:absolute after:inset-x-0 after:-bottom-0.5 after:h-px after:origin-left after:scale-x-0 after:bg-current after:transition-transform after:duration-300 after:ease-out hover:text-foreground data-active:text-foreground","bind":{"label":"item.label","url":"item.url","state:active":"item.active"}}
::::::::
:::::::
::::::

:::::: box {"id":"hd-account","label":"Account","class":"flex items-center text-[0.9375rem]","bind":{"visible":"accounts"}}
::::::: link {"id":"hd-sign-in","class":"text-muted hover:text-foreground","bind":{"label":"accounts.sign_in.label","url":"accounts.sign_in.url","hidden":"account"}}
:::::::

::::::: link {"id":"hd-my-account","class":"text-muted hover:text-foreground","bind":{"label":"accounts.account.label","url":"accounts.account.url","visible":"account"}}
:::::::
::::::
:::::

::::: box {"id":"hd-toggle","props":{"tag":"button"},"label":"Menu button","class":"-mr-2 hidden h-10 items-center gap-2 rounded-full px-2 text-[0.9375rem] font-medium max-md:inline-flex","attrs":{"aria-label":"Menu","aria-controls":"site-menu"},"logic":{"on":[{"event":"click","actions":[{"do":"toggle","var":"open"},{"do":"lock","on":true},{"do":"if","test":"open","then":[{"do":"play","node":"hd-sheet-links","motion":"open","mode":"restart"}],"else":[]}]}],"attrs":{"aria-expanded":"open"}}}
:::::: paragraph {"id":"hd-toggle-menu","props":{"text":"Menu","tag":"span"},"logic":{"show":"!open"}}
::::::

:::::: paragraph {"id":"hd-toggle-close","props":{"text":"Close","tag":"span"},"logic":{"show":"open"}}
::::::
:::::
::::

:::: box {"id":"hd-sheet","props":{"tag":"nav"},"label":"Phone menu","class":"hidden max-md:flex max-md:h-[calc(100dvh-4rem)] max-md:flex-col max-md:justify-between max-md:bg-background max-md:px-gutter max-md:pb-10","attrs":{"aria-label":"Main"},"logic":{"show":"open","transition":"fade"},"anchor":"site-menu"}
::::: repeat {"id":"hd-sheet-links","props":{"source":"menu","menu":"main","tag":"ul"},"class":"flex flex-col gap-1 pt-8","motion":[{"id":"open","trigger":{"type":"event"},"steps":[{"target":"children","from":{"opacity":0,"y":16},"duration":0.5,"ease":"power3.out","stagger":0.05}]}]}
:::::: box {"id":"hd-sheet-item","props":{"tag":"li"}}
::::::: link {"id":"hd-sheet-link","class":"block py-1 text-4xl leading-[1.1] font-medium tracking-tight data-active:text-muted","bind":{"label":"item.label","url":"item.url","state:active":"item.active"}}
:::::::
::::::
:::::

::::: box {"id":"hd-sheet-foot","class":"flex flex-col gap-2 text-sm text-muted"}
:::::: link {"id":"hd-sheet-sign-in","class":"text-lg text-foreground","bind":{"label":"accounts.sign_in.label","url":"accounts.sign_in.url","hidden":"account","visible":"accounts"}}
::::::

:::::: link {"id":"hd-sheet-my-account","class":"text-lg text-foreground","bind":{"label":"accounts.account.label","url":"accounts.account.url","visible":"account"}}
::::::

:::::: paragraph {"id":"hd-sheet-email","props":{"tag":"p"},"bind":{"text":"globals.studio.email"}}
::::::

:::::: paragraph {"id":"hd-sheet-hours","props":{"tag":"p"},"bind":{"text":"globals.studio.hours"},"class":"whitespace-pre-line"}
::::::
:::::
::::
:::
