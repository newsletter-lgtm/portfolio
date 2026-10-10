# Design brief

Source: screenshot of a Stitch design
Mood: passion, experience, friendly. A StageTech dark developer aesthetic: monospace metadata and terminal precision set against a high-contrast dark palette, balanced by clean typography and generous whitespace.

## Style

- Style: Technical, with a Modern touch: lots of whitespace and borderless lists.
- Feel: passion, experience, friendly.
- Personal detail: a subtle chef knife divider detail inspired by cooking.
- Motion: crisp and functional: state changes, subtle glowing hover accents. When the visitor prefers reduced motion, nothing moves.

## Colours

| Token | Light | Dark | Used for |
|---|---|---|---|
| background | #f6f7f9 | #081425 | page background: cool white in light mode, deep obsidian blue in dark mode |
| surface | #eef2f6 | #111c26 | cards, badges, terminal headers |
| text | #161b22 | #e6edf3 | headings and body text |
| muted | #57606a | #8ba2b9 | headline under the name, dates, metadata labels, borders |
| accent | #0969da | #00d8ff | links, focus ring, interactive highlights: syntax blue / electric cyan |
| on-accent | #ffffff | #081425 | text on an accent-coloured button or badge |

## Type

| Role | Font | Size | Weight |
|---|---|---|---|
| headings | "JetBrains Mono", ui-monospace, Menlo, Consolas, monospace | name 2rem, section 1.125rem, item 1rem | 600 |
| body | "IBM Plex Sans", system-ui, sans-serif | 1rem, line height 1.6 | 400 |
| details | "JetBrains Mono", ui-monospace, Menlo, Consolas, monospace | dates, status badge, metadata labels 0.875rem | 400 |

## Shapes

- Corner radius: square corners (0) or subtle 2px rounding on badges and terminal containers; small square photo frame.
- Borders: 1px subtle border in the muted/surface colour, with glowing accent highlights on active elements.
- Shadows: subtle dark glow on accent borders, no heavy drop shadows.

## Layout

- One column, at most 48rem wide, centred, with 1.25rem padding at the sides on phones; faint dot grid backdrop.
- 3.5rem between sections, 1.25rem between items in a list.
- Talks and experience: structured chronological list with dates aligned, metadata tags, and action links.

## Components

- Links: accent colour, underlined or styled as terminal-style bracketed links ([view], [slides]); keyboard focus shows a 2px accent ring.
- Talks & events: clean chronological rows with date, city, session title, and talk type badge.
- Skills: monospace tag cloud / array style with subtle borders and high-contrast hover states.
- Section headings: monospace font with numbered index or terminal comment style (e.g. "// 01. SPEAKING & TALKS").
- Availability badge: glowing status pill ("status: available for speaking") next to the role.

## Signature

- Move: Other cards step back on hover and focus
- Guide: guides/css/child-state-based-styling.md
- Where: the talks and events list: while one item is hovered or focused, the others step back slightly to focus the reader's attention.

## Sections

1. `bio`: name, headline, pitch, availability status badge, and bio.
2. `events`: speaking is the primary goal, so talks and workshops lead.
3. `cv`: experience, lecturer roles, education, and skills.
4. `links`: Sessionize, GDE, GitHub, LinkedIn, Speed Kit, and email contact channel.
