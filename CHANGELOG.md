# Changelog

## Unreleased

## 0.6.0 (2026-11-16)

### Added

- **Topics and tags are taxonomies.** A story's topic is one of four categories, *Making*, *Places*, *People* and *Notes*, each with a summary and the colour its stories' tiles and title bands take: change a topic's colour and its stories follow. Tags are made as you type them into a story. Every topic and tag has a page listing its stories (`/journal/topics/making`, `/journal/tags/coast`), and a story links to its topic and its tags.
- The template *Topic or Tag* designs those pages.

### Changed

- **Breaking.** Needs Lettern 0.49 or later.
- **Patterns are components that are not synced.** The 29 sections and four whole pages are under Components, each inserted as a copy to change freely, and a new page starts from one of the whole pages.

## 0.5.0 (2026-11-15)

### Changed

- **Section colours are schemes**: *Tide*, *Clay*, *Sun*, *Mist* and *Band*, and *Photo* for words over a photograph. Each is a background and a text colour you change under **Styling → Colors**, and a block takes one under **Add Style**.
- The large headline style is called *Headline* (it was *display*), with its size, line height and letter spacing.
- Long-form text is styled under **Styling → Styles → Articles**, and the site has no custom CSS left.

## 0.4.0 (2026-11-15)

### Changed

- The stylesheet is tidier: a link's hover is part of the link's style, and dark mode follows the colors without a line of its own.

## 0.3.0 (2026-11-14)

### Changed

- **Built with Tailwind CSS.** Every block is styled with Tailwind classes, and the site's colours, type, spacing and buttons are a Tailwind theme, one stylesheet you can read and change under Styling. The pages look as they did.
- The space between columns and between blocks is `gap-columns` and `py-blocks` in classes (it was the tokens `grid` and `block`).

## 0.2.0 (2026-11-14)

### Changed

- **A new look, in colour.** Headings are set large in Instrument Serif, text in Inter, on white. Sections take one of five colours: deep sea green, terracotta, yellow, pale blue or near black, with their text, lines and buttons to match, in light and dark.
- Projects and stories show as coloured tiles. A project's colour is a field on the project; a story takes the colour of its topic, on its card and behind its title.
- One typeface to a line: headings and paragraphs no longer mix the serif into a sentence.
- The home page opens with its headline, without the lines above it.
- **All work** and **All stories** are buttons.
- Opening hours have their own lines, in the footer, the phone menu and on Contact, at the size of the address.
- The numbers of **How we work** sit beside their titles, and **Along the way** is set at the size of the rest of the page.

### Removed

- The Patterns page: the patterns are in the admin, under Design → Patterns, with pictures of each.

## 0.1.0 (2026-11-13)

### Added

- **Starter, the site a new Lettern site starts from.** A small studio by the sea, to make your own: a home page with a film, Work with four projects, a Journal with five stories that filter by topic and search, About, Contact, and 33 patterns: 29 sections, shown together on a Patterns page, and four whole pages to start a new page from. Photographs, a film and a sound recording throughout, a calm editorial design in light and dark, and templates for pages, text pages, stories and projects. It replaces Minimal.
