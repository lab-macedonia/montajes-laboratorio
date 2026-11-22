# Montajes de laboratorio

Editor web para dibujar montajes de material de vidrio de laboratorio de química, con revisión automática en "modo actividad", pictogramas SGA oficiales, animación y exportación (SVG/PNG/GIF), informes para docentes y modo evaluación.

Es una sola página (`index.html`), sin dependencias ni servidor: HTML, CSS y JavaScript puros, con las fuentes incrustadas. Funciona sin conexión. Incluye animaciones de los procesos (reflujo, destilación, filtración, electrólisis, pila Daniell, rotavapor, cromatografía, etc.).

**Uso (español):** https://lab-macedonia.github.io/montajes-laboratorio/

**Use (English):** https://lab-macedonia.github.io/montajes-laboratorio/en/

La versión en inglés se genera a partir de la española; ambas comparten el mismo código y los mismos datos guardados en el navegador.

## Notas

- Vínculo curricular: cada actividad puede llevar curso, OA y habilidades de investigación (campos editables en «Configurar actividad»). Las actividades de separación de mezclas y valoración traen una sugerencia (7.º básico OA 14; 2.º medio OA 15) que el docente debe validar y cuya vigencia debe verificar en curriculumnacional.cl. El informe del docente y el CSV incluyen estos campos y un resumen de logro por OA.
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

- Curriculum link: each activity can carry a grade, a learning objective (OA) and inquiry skills (editable fields under “Configure activity”). The mixture-separation and titration activities ship with a suggestion (grade 7 OA 14; grade 10 OA 15) that the teacher must validate against the current Chilean curriculum (curriculumnacional.cl). The teacher report and the CSV include these fields and a summary of achievement by OA.
- Hazard classifications of the reagents are for reference only (cross-checked against safety data sheets from several suppliers). Always confirm with your supplier's SDS.
- The chemical thresholds used by the automatic checks (electrolysis voltages, sublimation criteria, pH meter tolerances) are pending expert validation.
- GHS pictograms: `@ghs-hazard-pictograms/assets` package (MIT), artwork by UNECE/Wikimedia. Fonts: IBM Plex (SIL OFL).

## License

MIT. MACEDONIA Laboratory, UMCE (Universidad Metropolitana de Ciencias de la Educación, Chile).
