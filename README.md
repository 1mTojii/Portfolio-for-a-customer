# HageSan — [Link-in-Bio](https://www.instagram.com/hagesanja/) Portfolio

A custom "link-in-bio" style landing page built for a client, designed to
sit at the center of their social presence — one clean, branded page that
routes visitors out to Instagram, YouTube, Facebook, TikTok, Snapchat, and
a direct collaboration contact.

Built as a single static HTML page — no frameworks, no build step, no
dependencies beyond two Google Fonts. Just clean, hand-written HTML/CSS/JS.

## Live Preview

Open `hagesan.html` directly in any browser — it's fully self-contained.

## What it includes

- **Animated hero portrait** — a circular profile photo framed by two
  procedurally-generated flower clusters, built with inline SVG and a small
  script that positions each petal using a golden-angle spiral (the same
  math behind natural petal/seed arrangements in real flowers) so the
  bloom looks organic rather than a fixed, repeated pattern.
- **Social link list** — a clean, icon-led list of outbound links,
  currently pointing to Instagram live, with YouTube, Facebook, TikTok,
  and Snapchat staged and ready to activate as those channels launch.
- **Collaboration contact** — a dedicated `mailto:` entry pre-filled with
  a subject line, so brand/collab inquiries land ready-to-answer instead
  of as a blank email.
- **Custom theming** — a warm, paper-and-hydrangea color palette defined
  entirely through CSS custom properties, making the whole site's look
  adjustable from one place at the top of the stylesheet.
- **Responsive layout** — scales down cleanly for small screens via media
  queries, since this is designed primarily to be opened from a mobile
  Instagram bio link.
- **Accessibility touches** — respects `prefers-reduced-motion` (disables
  the bloom animation for users who've asked for reduced motion),
  keyboard-focus styling on every link, and decorative SVGs marked
  `aria-hidden`.

## Tech stack

- Plain HTML5 + CSS3 + vanilla JavaScript (no libraries, no frameworks)
- Google Fonts: **Cormorant Garamond** (display serif) and **Mulish**
  (body sans-serif)
- Inline SVG, animated and positioned via a small self-contained script

## Project structure

```
hagesanja/
├── hagesan.html      # the entire site — markup, styles, and script in one file
└── images/
    └── IMG_5541.jpg  # profile portrait
```

## Notes for future updates

A few links are staged but not yet live (YouTube, Facebook, TikTok,
Snapchat) — each is marked with a `TODO` comment directly in the HTML at
the point where the real URL/handle needs to be dropped in once that
channel is public. The collaboration email is currently a placeholder
address and should be swapped for the client's real contact before launch.

## Why this exists

Freelance/client project — a single-page, no-dependency landing site built
to be lightweight, fast-loading, and easy for a non-technical client to
eventually hand off content updates for (swap a link, swap a photo) without
needing a CMS or hosting platform.

## License

MIT
