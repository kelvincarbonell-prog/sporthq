# SportHQ

Estructura optimizada para despliegue estático en Vercel.

## Estructura

- `index.html`: entrada de producción (apunta a la versión estable actual).
- `versions/`: histórico versionado de entregas (`v6`, `v7`, `v8`, ...).
- `docs/`: notas operativas y guía rápida.
- `vercel.json`: configuración de despliegue y enrutado.

## Flujo recomendado

1. Editar una nueva versión en `versions/indexcodexhqsport (vN).html`.
2. Copiar esa versión a `index.html` para publicarla.
3. Hacer `git add`, `git commit`, `git push`.
4. Vercel desplegará automáticamente desde `main`.
