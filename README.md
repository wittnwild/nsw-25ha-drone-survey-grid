# NSW 25-ha Drone Survey Grid

This repository provides a 25-hectare resolution spatial grid for New South Wales. 

This grid layer was used to align systematic drone surveys and spatially structure binomial N-mixture models for estimating the abundance of koalas at the landscape-scale. It supports presence/absence and abundance frameworks and is suitable for use in large-scale ecological monitoring programs. 

The grid was used in the following study:

> **Ryan, S.A., Southwell, D.M., Beranek, C.T., Clulow, J., Jordan, N.R., Witt, R.R. (2025)**  
> *Estimating the landscape-scale abundance of an arboreal folivore using thermal imaging drones and binomial N-mixture modelling*  
> Biological Conservation. Manuscript ID: 111207 (accepted 2025). https://doi.org/10.1016/j.biocon.2025.111207

##Abstract

Estimating the abundance of wildlife populations at a landscape-scale is vital for conservation, but is often hampered
by survey costs, data processing and imperfect detection. In this study, we developed a framework that
combines a protocol for validating nocturnal thermal drone detections in real-time with N-mixture modelling to
estimate the landscape-scale abundance of arboreal folivores. As a case study, we estimated the abundance of
koalas (Phascolarctos cinereus) across seven reserves (673 km2) in New South Wales, Australia. We conducted
thermal drone surveys of 208, 25-ha sites stratified across vegetation type and fire history, on average, three
times over consecutive nights (range 1–12 repeats), between 18:00–04:00 h (May to September). All koala detections
were validated by field personnel or in real-time with drones equipped with a thermal camera and searchlight.
Koalas were detected on 245 occasions. We fitted N-mixture models to validated repeat count data to quantify
the effect of site and observation variables on abundance and detectability. Using our top set of competing
models, we estimated that 4357 koalas (95 % CI = 2319–8307) occupy the seven reserves, with a mean detection
probability of 0.22 (95 % CI = 0.15–0.31) over all survey occasions. We found detection probability decreased
with increases in relative humidity and temperature. Koala abundance was negatively associated with
fire severity, elevation, tree height and soil clay content, and positively associated with available water content,
forest cover and soil organic carbon. Our framework, which combines real-time field validated drone data while
accounting for imperfect detection, improves the accuracy of abundance estimates for arboreal folivores across
large-scales.

---

## 📂 Contents

- `Grid_Albers_00500m_NSW_Polys.shp` and associated files  
  A shapefile representing 25-ha (500 m × 500 m) grid cells across New South Wales.

---

## 🗺️ Spatial Details

- **CRS:** GDA94 / Australian Albers (EPSG:3577)  
- **Geometry Type:** Polygon  
- **Cell Size:** 500 m × 500 m (25 hectares)  
- **Total Features:** 3,222,693  
- **Attribute Fields:** `Id` (unique cell identifier)  
- **Bounding Box (minx, miny, maxx, maxy):**  
  (826250.0, –4212250.0, 2082750.0, –3181250.0)

---

## ✅ Intended Applications

- Thermal drone survey planning  
- Spatial alignment of repeatable wildlife monitoring  
- Koala and arboreal mammal detection  
- Binomial or Poisson N-mixture model design  
- Landscape-scale ecological stratification

---

## ⚠️ Data Use and Licensing

This grid layer is based on spatial data provided by the NSW Government and is published with permission as open-access supplementary material to support the following paper:

> **Ryan, S.A., Southwell, D.M., Beranek, C.T., Clulow, J., Jordan, N.R., Witt, R.R. (2025)**  
> *Estimating the landscape-scale abundance of an arboreal folivore using thermal imaging drones and binomial N-mixture modelling*  
> Biological Conservation. Manuscript ID: 111207 (accepted 2025). https://doi.org/10.1016/j.biocon.2025.111207

The dataset is made available to support open ecological research and systematic drone survey planning in New South Wales. The authors are not the original creators and do not assign an open license.

Users applying this grid for survey or monitoring purposes in NSW are encouraged to submit resulting species detection records to [NSW BioNet](https://www.bionet.nsw.gov.au/) to contribute to state-wide biodiversity data and conservation efforts.

---

## 📌 Citation

If using the grid for academic purposes, please cite:

> Ryan, S.A., Southwell, D.M., Beranek, C.T., Clulow, J., Jordan, N.R., Witt, R.R. (2025).  
> *Estimating the landscape-scale abundance of an arboreal folivore using thermal imaging drones and binomial N-mixture modelling.*  
> Manuscript 111207. Grid layer available via GitHub: https://github.com/wittnwild/nsw-25ha-drone-survey-grid/

