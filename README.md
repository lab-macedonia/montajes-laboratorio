# Montajes de laboratorio

Editor web para dibujar montajes de material de vidrio de laboratorio de química, con revisión automática en "modo actividad", pictogramas SGA oficiales, animación y exportación (SVG/PNG/GIF), informes para docentes y modo evaluación.

Es una sola página (`index.html`), sin dependencias ni servidor: HTML, CSS y JavaScript puros, con las fuentes incrustadas. Funciona sin conexión. Incluye animaciones de los procesos (reflujo, destilación, filtración, electrólisis, pila Daniell, rotavapor, cromatografía, etc.).

**Uso (español):** https://lab-macedonia.github.io/montajes-laboratorio/

**Use (English):** https://lab-macedonia.github.io/montajes-laboratorio/en/

La versión en inglés se genera a partir de la española; ambas comparten el mismo código y los mismos datos guardados en el navegador.

## Notas

- Las clasificaciones de peligro de los reactivos son referenciales (contrastadas con HDS de varios proveedores). Confirma siempre con la HDS de tu proveedor.
- Los umbrales químicos de las revisiones automáticas (voltajes de electrólisis, criterios de sublimación, tolerancias del pH-metro) están pendientes de validación experta.
- Pictogramas SGA: paquete `@ghs-hazard-pictograms/assets` (MIT), arte de UNECE/Wikimedia. Fuentes: IBM Plex (SIL OFL).

## Licencia

MIT. Laboratorio MACEDONIA, UMCE.
