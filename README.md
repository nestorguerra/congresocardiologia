# CardioAgudos26 · El cardiólogo vs la IA

Landing de la sesión "El cardiólogo de críticos contra la IA" en la 23ª Reunión Anual de Cardiopatía Isquémica y Cuidados Agudos Cardiovasculares (Parador de Alcalá de Henares, 7-8 mayo 2026).

Contiene los 3 casos de la sesión con sus prompts listos para copiar y mostrar en directo en GPT‑5.5 Pro.

## Cómo desplegar en GitHub Pages

1. Crea un repo nuevo en GitHub (público o privado, da igual).
2. Sube todos los archivos de esta carpeta a la raíz del repo (incluido `.nojekyll`):
   - `index.html`
   - `README.md`
   - `.nojekyll`
   - carpeta `img/`
3. En el repo: **Settings → Pages**.
4. En "Source" elige **Deploy from a branch**.
5. En "Branch" elige `main` (o `master`) y carpeta `/ (root)`. Guarda.
6. Espera 1-2 minutos. La URL será `https://<tu-usuario>.github.io/<nombre-del-repo>/`.

## Subida rápida desde terminal

```bash
cd CardioAgudos26
git init
git add .
git commit -m "Landing CardioAgudos26"
git branch -M main
git remote add origin https://github.com/<tu-usuario>/<nombre-repo>.git
git push -u origin main
```

Luego activa Pages desde Settings.

## Estructura

```
CardioAgudos26/
├── index.html          ← la landing
├── .nojekyll           ← evita procesado de GitHub Pages
├── README.md
└── img/
    ├── ecg/            ← 22 imágenes de los ECGs
    ├── caso1/          ← (opcional) páginas del PDF caso 1
    └── caso2/          ← (opcional) páginas del PDF caso 2
```

## Notas

- Los prompts están preparados para GPT‑5.5 Pro.
- El botón "COPIAR" en cada bloque pone el prompt en el portapapeles.
- Las pestañas internas del Caso 3 permiten saltar entre los 10 ECGs.

— Néstor Guerra · NCompany
