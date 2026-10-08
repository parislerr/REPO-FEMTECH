# Care Journal

A mobile-first React, TypeScript, and Vite prototype based on the CDE5311 Figma design. Includes Home, Prepare, Summary, and a three-step entry form. Entries are saved locally in the browser. Today is centered in the date picker; the next three days are visible but disabled.

## Setup and run

Install Node.js 22.12+ and pnpm, then run:

```sh
pnpm install --frozen-lockfile
pnpm dev
```

Open the local address printed by Vite (usually http://127.0.0.1:5173).

```sh
pnpm build    # Type-check and create the production build
pnpm preview  # Serve the production build locally
```

## Browser checks

With Google Chrome installed and the dev server running:

```sh
node checks/verify.mjs
```

Checks cover the six screens, asset loading, entry creation and persistence, and responsive widths. Generated screenshots are ignored by Git.

## Prototype scope

Fonts and SVG assets are bundled locally. Appointment and assistant interactions are demos; no backend or API keys are required. The Profile screen was not supplied, so it displays an explanatory dialog. Some Figma placeholder text is retained. Browser entries are not committed to Git.
