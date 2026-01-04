# 📄 Carpeta de CV

## Instrucciones rápidas

1) Copia tu archivo PDF a esta carpeta (`cv/`).
2) Opción A (sin cambiar nada): nómbralo exactamente `Mario_Canadas_CV.pdf` y listo.
3) Opción B (mantén tu nombre de archivo): edita el `href` del botón en las páginas que muestran el CV para que apunte a tu PDF:

- `index.html` → enlace con id `download-cv`
- `sobre-mi.html` → enlace con id `download-cv`

Ejemplo de enlace:

```html
<a href="cv/TU_NOMBRE_DE_CV.pdf" target="_blank" rel="noopener" download id="download-cv">📄 Descargar CV</a>
```

## ¿Cómo funciona?

- El botón usa el `href` del enlace para abrir/descargar el PDF.
- Si el PDF no existe o hay un error al cargarlo (solo cuando se sirve por HTTP/HTTPS), se descargará un CV de ejemplo en `.txt` como fallback.
- Si abres la web directamente como archivo local (file://), el enlace abrirá el PDF sin interferencias de JavaScript.

## Formatos y tamaño

- Formato recomendado: PDF
- Tamaño máximo sugerido: 5 MB

## Consejos

- Mantén tu CV actualizado regularmente.
- Usa un diseño profesional y limpio.
- Incluye palabras clave relevantes a tu sector.
- Revisa la ortografía antes de subirlo.

---

💡 Tip: También puedes usar un enlace externo (Drive, Dropbox) en el `href`. Asegúrate de que el enlace sea directo al archivo y con permisos de visualización.
