# Nameless Mountain Website

Clean rebuild of https://www.namelessmountain.org/ (originally built on Squarespace).

## Purpose

Provide an editable, minimal HTML/CSS/JS version of the Nameless Mountain website
that can be hosted anywhere without Squarespace dependencies.

## Pages

- **Home** (`index.html`): Hero with mountain painting, tagline, and "Join Us" CTA
- **About** (`about.html`): Mission, vision, leadership team
- **Join** (`join.html`): Hero with painting background, three membership cards (Donate, Volunteer, Stay In Touch)
- **Calendar** (`calendar.html`): Hero, upcoming events list
- **Contact** (`contact.html`): Contact form, ethics/violation buttons, painting

## Design System

- **Colors**: Cream (#fff5d9), Blue-Gray (#7b949c), Steel Blue (#536c7c), Burgundy (#4f2122), Navy (#182241)
- **Fonts**: Marcellus (headings), PT Serif (body) via Google Fonts
- **Layout**: Max-width 1400px, 4vw gutters (6vw mobile), responsive at 799px breakpoint
- **Buttons**: 10px border-radius, PT Serif font, primary (steel blue) and secondary (outlined)

## Structure

All pages share a common header (logo + nav) and footer (links + logo + mailing list signup).
CSS is in a single `style.css`. No build tools required. Images in `images/`.
