# Economía I · Unidad IV — Universidad William Osler

Artefacto educativo para Administración de Empresas y Contabilidad, basado en la guía de cuaderno de la Unidad IV: Control, Optimización y Análisis Operativo.

## Publicación en GitHub Pages
1. Sube `index.html` y `config.json` a la misma carpeta del repositorio (raíz o `unidad_IV/`).
2. En GitHub → Settings → Pages, activa la publicación desde la rama correspondiente.
3. Abre la URL publicada de esa carpeta. El HTML funciona sin compilación, Node ni dependencias externas.
4. Edita `config.json` para agregar URLs del video de YouTube, infografía y Classroom, además de la fecha límite. **Los cambios locales no aparecen para otros estudiantes hasta subir el archivo actualizado a GitHub.**

## Funcionamiento y límites
- Las pestañas, tarjetas, cálculos, dashboard, exportación CSV, prueba y notas funcionan con JavaScript local.
- Las notas se guardan únicamente en el navegador/dispositivo mediante `localStorage`. Descargar copia de seguridad; no es una entrega ni un registro institucional.
- El video solo aparece si se configura un enlace válido de YouTube. No se incluye un video ficticio.
- El dashboard usa supuestos didácticos; el indicador de consumo 45/50=90% no demuestra eficiencia de producción.
- La evaluación formal es el cuaderno entregado en PDF por Classroom y calificado con la rúbrica docente.
- `config.json` se carga en el sitio publicado; si abres `index.html` como archivo local puede bloquearse la lectura por seguridad del navegador. Para probar toda la configuración usa GitHub Pages o un servidor local.

## Evidencia
Cuatro fases: antes, durante y después del video, y análisis de infografía. Nombre del PDF: `U4_Apellido_Nombre_EconomiaI.pdf`.


## Lectura teórica y Google Drive
La ruta de estudio aparece **antes de las pestañas**. La teoría y los autores están integrados en la primera etapa, por lo que el estudiante puede estudiar sin salir de la plataforma. Para ofrecer la fuente ampliada en Google Drive, convierta el archivo `FUENTE_NOTEBOOKLM_UNIDAD_IV.md` a Google Docs (o suba un PDF), habilite acceso de lectura y pegue el enlace en `config.json` → `fuenteAcademica.driveUrl`. El botón solo aparece si hay una URL válida. **No usar el enlace de edición.**

### Nota didáctica sobre el caso
El ejemplo de la fábrica de galletas compara 50 kg planeados con 45 kg utilizados para 100 paquetes. El 90% es consumo relativo de harina, no eficiencia productiva. Los escenarios de calidad son hipotéticos. La lectura ampliada se recomienda mediante Google Drive; no se ofrece enlace directo al archivo Markdown desde la interfaz.
