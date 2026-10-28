# Then and now: sitio de estudio

Sitio estático (un solo `index.html`, sin build ni dependencias).

## Subir a Vercel
**Opción A, sin terminal:** entra en vercel.com/new, arrastra esta carpeta (o súbela a GitHub e impórtala). En "Framework Preset" deja **Other**; no pongas Build Command ni Output Directory.

**Opción B, con terminal:**
```
cd vercel-site
npx vercel --prod
```

## Notas
- Se adapta solo: barra inferior en móvil, navegación superior y cuadrícula de 4 columnas en escritorio.
- Los enlaces tipo `/#past` o `/#practice` abren cada pestaña directamente.
- Las fuentes vienen de Google Fonts; si falla la conexión, usa fuentes del sistema.

## Funciones
Progreso con XP, niveles y racha (se guarda en el navegador), audio de pronunciación, tema claro/oscuro, juegos (unir opuestos, ordenar frases), práctica de verbos regulares e irregulares, repaso de fallos, diario de 5 frases al día y modo sin conexión (PWA: `sw.js`, `manifest.json`, `icon.svg`).
