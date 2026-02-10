# Ley de Ohm — Calculadora (react-vite-tailwind)

Proyecto: "Ley de Omhs" — calculadora sencilla implementada con React + Vite + TypeScript + Tailwind.

Requisitos
- Node.js 20+ (recomendado)
- npm v9+ (o usa `npm ci` con lockfile)

Instalación y desarrollo
```
# desde la raíz del repositorio
npm ci
npm run dev
# abrir http://localhost:5173 (Vite te mostrará la URL)
```

Build de producción
```
npm run build
# previsualizar
npm run preview
```

Docker (ejemplo)
```
# build
docker build -t ley-de-ohm-app .
# run
docker run -p 8080:80 ley-de-ohm-app
# luego abrir http://localhost:8080
```

CI (GitHub Actions)
- Incluye un workflow básico para instalar dependencias y ejecutar `npm run build`.

Archivos clave
- `vite.config.ts` — configuración Vite (ya presente).
- `src/` — código TypeScript/React (ya presente).
- `tailwind.config.cjs` y `postcss.config.cjs` — configuración Tailwind/PostCSS (añadidos aquí).
- `Dockerfile` — para construir imagen estática con nginx.

Notas
- Si quieres que haga push directo a una rama (crear PR), dímelo y lo creo automáticamente.
- También puedo añadir GitHub Pages / Netlify / Vercel config si prefieres un despliegue específico.
