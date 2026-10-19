---
name: research-figures
description: Create reproducible publication figures from supplied mechanics and lubrication data, or clearly labeled conceptual schematics, with English labels and Word-ready exports.
---

# Research Figures

1. Read workspace instructions and domain checklist. Identify data provenance,
   units, axes, comparisons, journal dimensions and requested figure type.
2. For quantitative figures, use supplied data and reproducible Python scripts.
   Never fabricate measurements, simulation fields, error bars or significance.
   Label demonstration data as synthetic in the figure and caption.
3. Preserve raw data. Record transformations, normalization, filtering, interpolation,
   uncertainty definitions and exclusions. Check shapes, units and missing values.
4. Choose the plot for the comparison; use legible English labels, units, consistent
   symbols, accessible colors and line styles. Avoid misleading axes and 3D effects.
5. Save a script under `figures/`, export vector PDF/SVG and a 300-dpi-or-higher PNG
   for Word, and supply an English caption plus provenance/processing notes.
6. Use matplotlib for data plots and precise scientific diagrams. If an available
   image-generation tool is requested for conceptual illustration, use it and clearly
   label the output schematic; it cannot establish quantitative results or exact geometry.
7. Execute the script and inspect the outputs using available image tools. Check labels,
   cropping, legends and units. Report if visual inspection is unavailable. Keep vector
   masters even when a Word-compatible raster copy is required.
