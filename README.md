# 4E4A1k3 watershed 3D viewer

**Live website: https://anantrajj7-sketch.github.io/watershed-4E4A1k3/**

Interactive 3D model of watershed 4E4A1k3 (2,363 ha, Pathardi and Ashti talukas, Maharashtra). It works on desktop and on phones, and the page is about 34 MB, so give it a moment to load.

## How the page works
Scroll, hold the arrow keys, or press PageDown/PageUp (or Space) to glide to the next or previous view (Home/End jump to the ends) to zoom from Earth to India, Maharashtra and the watershed. The map then cross-fades into the interactive 3D model, which rotates slowly until you take control: drag to rotate (the wheel keeps scrolling the page). Scrolling on, a satellite sweeps over the watershed and a scan line reveals the data collected (imagery, elevation, land cover, soil, groundwater), then the model moves to the top-left and a grid of rotating 3D icons appears for the soil and groundwater layers (depth, texture, pH, EC, CaCO3, N, P, K, groundwater); the maps themselves are still to be added. The dots on the right jump between stages and Replay returns to the start. The intro map streams Esri World Imagery tiles and needs an internet connection; the India, Maharashtra, district and taluka outlines come from the supplied administrative boundary shapefiles (state, district and taluka layers; source and date not stated in the files), simplified for display.

## Data and credits
- Field parcels: Fields of The World (FTW Global, Taylor Geospatial; PRUE model on Sentinel-2, 2024 run), CC-BY, https://source.coop/ftw/global-data. 10 m pixel-based; boundaries were refined against Esri imagery.
- Buildings: GlobalBuildingAtlas (Zhu et al. 2025, ESSD 17, 6647), CC BY-NC 4.0, non-commercial use only.
- Imagery: Esri World Imagery. Source: Esri, Vantor, Earthstar Geographics, and the GIS User Community.
- Terrain: GEDTM30 30 m.
- Wells and groundwater levels: MRSAC and CGWB.
- Fields, trees and water are automatic estimates from imagery and have not been field-checked.
