# Nick Sorin — Personal Platform Demo

A portable, employer-agnostic personal site for Nicholas “Nick” Sorin: retired U.S. Army Special Operations officer, VA mortgage strategist, team builder, and educator.

## Design direction

The site uses the visual language of a modern command dossier—graphite, field green, parchment, signal red, and brass—with an original crescent-and-aviation mark as a restrained homage to Nick’s Night Stalker service. It does **not** reproduce an official military insignia or imply U.S. Army/DoD endorsement.

## Run locally

```bash
npm install
npm run dev
```

## Production build

```bash
npm run build
npm run preview
```

## Deployment

The repository includes `netlify.toml`. Netlify should use:

- Build command: `npm run build`
- Publish directory: `dist`
- Node: 22

The contact form uses Netlify Forms with a honeypot. Enable form detection for the Netlify project and configure submission notifications in the Netlify dashboard.

## Easy-to-update current affiliation

Employer-dependent information appears only in the “Current professional assignment,” direct contact, footer compliance text, and structured-data block. Nick’s core positioning, service history, capabilities, and personal identity remain independent.

## Public-source notes

- [The Task Force](https://www.tftaskforce.com/)
- [LinkedIn profile](https://www.linkedin.com/in/nicholas-shumpis)
- [U.S. Army Special Operations Command — 160th SOAR overview](https://www.army.mil/usasoc)
- [Special Operators Transition Foundation](https://sotf.org/)

Research and profile content were reviewed August 6, 2026. Public professional details should be reconfirmed before a permanent custom-domain launch.
