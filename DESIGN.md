# Eric Ayeh Bonsrah Portfolio Design System

## Intent

This is a light, evidence-led technical editorial portfolio for recruiters and
collaborators. It should make Eric's practical software work easy to scan while
keeping professional employment, independent projects, learning and project
status clearly distinct.

The visual system is deliberately restrained. Authentic project evidence earns
attention; interface decoration does not.

## Color roles

- **Paper** (`#f3f6fa`): the cool, light page background.
- **Surface** (`#ffffff`): cards, hero and contained information.
- **Ink** (`#0e1a2b`): headings and primary reading text.
- **Muted ink** (`#46566b`): supporting copy and metadata.
- **Blue** (`#0b57a8`): the only interactive brand accent. Use for primary
  actions, links, focus, selected emphasis and the lead-project rule.
- **Amber** (`#d18d00` with its light tint): status and disclaimer treatment
  only. It must not decorate non-status content.

Use hairline neutral borders before introducing more color or elevation.

## Typography

- Use the system sans stack for reading, UI, metadata and controls.
- Use the existing serif display stack for the name and editorial headings.
- Headlines are sentence case, compactly tracked and balanced; do not use
  all-caps display headings.
- Eyebrows and technical-highlight labels may use modest uppercase tracking.
- Keep body copy comfortable and concise. Do not compress factual disclaimers.

## Spacing and layout

- Work from a 4px rhythm with practical steps of 8, 12, 16, 24, 32, 48 and
  64px.
- Sections use generous responsive vertical rhythm; individual cards use
  tighter internal spacing.
- The primary content measure remains readable rather than full-width.
- Desktop layouts may use two columns for comparison. Mobile stacks in source
  order, with evidence before secondary detail where a project has media.

## Surfaces, borders and elevation

- Page bands alternate between paper and white only when this improves scan
  rhythm.
- Cards use white surfaces, 1px neutral borders and restrained radius.
- Prefer a hairline and spacing over nested cards or strong shadows.
- Use only the small shared shadow token when a surface otherwise loses its
  boundary; never use a large floating shadow.

## CTA hierarchy

1. **Primary**: blue-filled action for the next meaningful recruiter action.
2. **Secondary**: outlined, neutral-surface action for a useful alternative,
   such as downloading the CV.
3. **Tertiary**: text link for a lower-emphasis action, such as contact from
   the hero.

Every action stays keyboard-focusable and meets the 44px minimum touch target.

## Project presentation and media

- Every project remains accurate about its status and scope.
- The first project may have a subtle blue lead rule; it must not imply a
  production service.
- Status labels and disclaimers use amber only when a real caveat is required.
- Technical highlights are a clearly labelled, scannable list rather than a
  visually competing nested card.
- Authentic screenshots use `figure.project-media`, meaningful alt text,
  explicit intrinsic width and height, a calm hairline frame and a concise
  caption.
- Images below the initial viewport use `loading="lazy"`.
- Never add generated screenshots, stock imagery, private data, credentials,
  customer data or simulated production evidence.

## Responsive and accessibility principles

- Navigation collapses to the existing labelled Menu button below desktop.
- The menu must retain its Escape-to-close and focus-return behavior.
- Preserve the skip link, semantic landmarks, heading order, visible
  `:focus-visible` treatment, reduced-motion support and anchor offsets below
  the sticky header.
- Avoid horizontal overflow at every supported viewport.
- Keep tap feedback intentional and use semantic links for navigation.

## Do / don't

**Do:** preserve clarity, use one blue interactive accent, let authentic work
be the proof, and keep enough whitespace for rapid recruiter scanning.

**Don't:** add dark mode, gradients, generic dashboard decoration, fake
metrics, visual noise, copied company branding, or claims beyond the public
project evidence.
