# Elite Noir — Digital Universe

Cinematic 3D landing hub for the Elite Noir ecosystem.

## Stack
- React + Vite
- Motion
- Three.js
- React Three Fiber + Drei
- Lucide icons
- CSS/WebGL visual system

## Configure portal URLs
Edit `src/sites.js`. Telecom is already pointed to the known production URL. Replace each `#configure-...-url` value with the exact production URL before launch.

## Run
```bash
npm install
npm run dev
npm run build
```

## cPanel
Build with `npm run build` and publish the generated `dist/` contents at the elite-noir.com document root. Existing applications in subdirectories remain independent.

The experience includes a reduced-motion accessibility fallback and touch/mobile layouts.
