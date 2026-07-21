# PuBlitec — Centro del proyecto (GitHub Pages)

Sitio estático que centraliza toda la información del proyecto PuBlitec para el equipo.
No requiere compilación ni dependencias: es un único `index.html` autocontenido más la carpeta `docs/` con los entregables.

## Cómo publicarlo en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `publitec-hub`).
2. Sube **todo el contenido de esta carpeta** al repositorio: `index.html`, la carpeta `docs/` (con los .docx y .pptx), el archivo `.nojekyll` y este `README.md`.
3. En el repositorio ve a **Settings → Pages**.
4. En **Source**, elige **Deploy from a branch**, rama `main` (o `master`), carpeta `/ (root)`, y pulsa **Save**.
5. Espera ~1 minuto. Tu sitio quedará publicado en:
   `https://<tu-usuario>.github.io/<nombre-del-repo>/`

## Cómo actualizar un documento

Reemplaza el archivo dentro de `docs/` conservando **el mismo nombre**. El enlace de descarga del sitio seguirá funcionando y el equipo siempre verá la última versión.

## Aviso de privacidad

GitHub Pages en un repositorio **público** hace el sitio visible para cualquiera en internet.
Este sitio incluye la cara pública del proyecto (qué es, producto, mercado, fases, entregables, equipo).
No publiques aquí material interno sensible (hallazgos de errores del producto, estrategia de puntaje, cartas sin firmar).
Si necesitas que todo sea privado, usa un repositorio privado con GitHub Pages (requiere plan GitHub Team/Enterprise).

## Estructura

```
/
├── index.html          ← el sitio (edítalo para cambiar textos)
├── .nojekyll           ← evita el procesamiento Jekyll
├── README.md
└── docs/               ← los entregables descargables
    ├── PuBlitec_Documento_Maestro.docx
    ├── PuBlitec_Pitch_v2.pptx
    ├── Fase2_Descubrimiento_y_Validacion.docx
    ├── Fase3_De_Investigacion_a_Innovacion.docx
    ├── Fase4_Herramientas_Desarrollo_Negocios.docx
    ├── PuBlitec_PESTEL.docx
    ├── PuBlitec_Bitacora_Validaciones.docx
    └── PuBlitec_Informe_Validacion.docx
```
