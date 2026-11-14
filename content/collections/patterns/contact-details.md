---
id: 01m7bf0hecpc4at7yn43gy5e3z
title: 'Contact Details'
status: published
published_at: '2026-11-13T22:03:53+00:00'
position: 4
category: 'Calls to Action'
description: 'Email, phone and address side by side, taken from the Studio settings.'
---

::: section {"id":"contact-details-s","props":{"width":"wide"}}
:::: box {"id":"contact-details-g","props":{"tag":"address"},"class":"grid grid-cols-3 gap-columns border-t border-border pt-8 not-italic max-lg:grid-cols-1 max-lg:gap-y-8"}
::::: box {"id":"contact-details-w","class":"flex flex-col gap-2"}
:::::: paragraph {"id":"contact-details-wl","props":{"text":"Write","tag":"p"},"class":"eyebrow"}
::::::

:::::: link {"id":"contact-details-we","class":"text-2xl","bind":{"label":"globals.studio.email","url":"mailto:{globals.studio.email}"}}
::::::
:::::

::::: box {"id":"contact-details-c","class":"flex flex-col gap-2"}
:::::: paragraph {"id":"contact-details-cl","props":{"text":"Call","tag":"p"},"class":"eyebrow"}
::::::

:::::: paragraph {"id":"contact-details-cp","props":{"tag":"p"},"class":"text-2xl","bind":{"text":"globals.studio.phone"}}
::::::
:::::

::::: box {"id":"contact-details-v","class":"flex flex-col gap-2"}
:::::: paragraph {"id":"contact-details-vl","props":{"text":"Visit","tag":"p"},"class":"eyebrow"}
::::::

:::::: paragraph {"id":"contact-details-va","props":{"tag":"p"},"class":"text-lg whitespace-pre-line","bind":{"text":"globals.studio.address"}}
::::::
:::::
::::
:::
