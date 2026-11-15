# Starter

A complete site to make your own, and the site a new Lettern site starts from unless you choose another. It is a small studio by the sea, with a home page, work, a journal, about and contact pages and a library of ready-made patterns to build more pages from, set on a bright, editorial design: large serif headings, sections in five colours, a twelve-column grid, and photographs, a film and a sound recording throughout. Replace the words and pictures, and keep the rest.

## Install

```bash
composer require letterncms/starter
php cms site:apply starter --dry-run
php cms site:apply starter
```

Or choose **Starter** when you install (`php cms install --start-from=starter`, or in the browser; it is the default), or under Settings → Sites.

## What it brings

- **Pages**: Home, Work, Journal, About and Contact, each built from the admin’s own blocks.
- **Collections**: Work, four projects with a cover, client, place, year and colour; Journal, five stories with a cover, topic and tags, that filter and search on the page.
- **Templates**: Blank, Page, Text Page, Story, Story Side by Side, Project and 404.
- **Components**: the header with a full-screen menu on phones, the footer, and cards for stories and projects.
- **Patterns**: 29 sections to insert and edit freely, from heroes with a photograph or a film to galleries, carousels, a sound recording, numbers, a team, prices, an agenda, questions and calls to action, and four whole pages (a landing page, an about page, an event page and a photo story) to start a new page from.
- **Globals and menus**: the Studio’s tagline, address, hours, email and phone, used in the footer and on Contact, and a main and a footer menu.
- **The styling**: a Tailwind CSS theme with colours for light and dark, Inter and Instrument Serif, buttons, form fields, and colour schemes for sections and cards (`scheme-tide`, `scheme-clay`, `scheme-sun`, `scheme-mist`, `scheme-band`, and `scheme-photo` for words over a photograph). Every block is styled with Tailwind classes.
- **Media**: 33 photographs, a ten-second film and a sound recording, with their alt text.

## Needs

Lettern 0.37 or later. No plugins. The fonts, photographs, film and sound keep their own licences: see `NOTICE.md`.

---

This repository is published from [letterncms/sites-public](https://github.com/letterncms/sites-public/tree/main/starter). Open issues and pull requests there.
