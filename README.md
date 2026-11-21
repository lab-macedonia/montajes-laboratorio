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

---

# Lab Setups (English)

A web editor for drawing chemistry laboratory glassware setups, with automatic checking in "activity mode", official GHS pictograms, animations, export (SVG/PNG/GIF), teacher reports and an assessment mode.

It is a single page (`index.html`) with no dependencies and no server: plain HTML, CSS and JavaScript with embedded fonts. It works offline. It includes animations of the processes (reflux, distillation, filtration, electrolysis, Daniell cell, rotary evaporator, chromatography, etc.).

**Use (English):** https://lab-macedonia.github.io/montajes-laboratorio/en/

**Uso (español):** https://lab-macedonia.github.io/montajes-laboratorio/

The English version is generated from the Spanish one; both share the same code and the same data saved in the browser.

## Notes

- Hazard classifications of the reagents are for reference only (cross-checked against safety data sheets from several suppliers). Always confirm with your supplier's SDS.
- The chemical thresholds used by the automatic checks (electrolysis voltages, sublimation criteria, pH meter tolerances) are pending expert validation.
- GHS pictograms: `@ghs-hazard-pictograms/assets` package (MIT), artwork by UNECE/Wikimedia. Fonts: IBM Plex (SIL OFL).

## License

MIT. MACEDONIA Laboratory, UMCE (Universidad Metropolitana de Ciencias de la Educación, Chile).
