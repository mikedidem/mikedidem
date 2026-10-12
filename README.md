# Michael Edidem

**Geospatial AI · Scientific machine learning · Environmental systems**<br>
PhD researcher at Southern Illinois University Carbondale · Expected graduation **2027**

[Portfolio](https://mikedidem.github.io/medidem/) · [CV](https://mikedidem.github.io/medidem/cv/Michael_Edidem_CV.pdf) · [Publications](https://mikedidem.github.io/medidem/publications/) · [Email](mailto:edidemichael@gmail.com)

I build machine-learning methods for mapping infrastructure and modeling environmental systems. My work asks two connected questions: **what can we infer from geospatial data, and when can we trust a model’s predictions?**

I started in surveying and applied GIS before moving into research. That background informs how I work with terrain, imagery and simulation data: the geography and physics matter as much as the model.

## Selected work

### Groundwater surrogates: accuracy and conservation

[**gw_surrogate_evaluation**](https://github.com/mikedidem/gw_surrogate_evaluation) · Lead author & developer · Manuscript under review

A surrogate can reproduce hydraulic head at **R² > 0.999** and still fail to conserve water. I built a diagnostic framework comparing CNN, ConvLSTM and PINN surrogates against MODFLOW-2005 on two synthetic aquifers, measuring predictive error, governing-equation residuals, boundary behavior and mass balance together.

The repository includes reproducible evaluators, benchmark configurations and tests. [Case study](https://mikedidem.github.io/medidem/projects/groundwater-surrogates/)

### CHIRRP: groundwater scenarios in plain language

[**chirrp**](https://github.com/mikedidem/chirrp) · Co-author & repository maintainer · Manuscript under review

A deployed research application connecting natural-language scenario requests to a physics-informed groundwater surrogate, with regulation retrieval and an on-demand MODFLOW cross-check. Its CPU surrogate evaluation is approximately **238× faster than MODFLOW** in the reported benchmark; this is distinct from end-to-end interaction time.

**PyTorch · FastAPI · Angular · Docker · RAG**<br>
[Live demo](https://morule-hydro.hf.space) · [Case study](https://mikedidem.github.io/medidem/projects/chirrp/)

### Drainage crossings: finding what terrain hides

[**Detection code**](https://github.com/GeoFewLab/Drainage_CrossingDet) · [**Classification code**](https://github.com/GeoFewLab/Drainge_CrossingClassification) · First author of two 2025 papers

Culverts and bridges are often missing from elevation-derived stream networks. My research uses high-resolution LiDAR DEMs and terrain derivatives to classify and locate drainage crossings, with Grad-CAM to examine the features driving predictions. The best classification configuration reached **97.9% accuracy within the study watershed**; geographic transfer is a separate research question.

[Detection paper](https://doi.org/10.1016/j.envsoft.2025.106338) · [Classification paper](https://doi.org/10.3389/frai.2025.1561281) · [Case study](https://mikedidem.github.io/medidem/projects/drainage-crossing-detection/)

## Current research

- **Geospatial representation learning:** testing whether Earth foundation-model embeddings transfer infrastructure information across regions.
- **Neural groundwater surrogates:** investigating finite-volume, physics-informed neural operators and tradeoffs between accuracy, physical consistency and computational cost.

## Methods & tools

| Area | Tools and methods I use |
| :--- | :--- |
| Scientific ML | PyTorch, CNNs, ConvLSTMs, PINNs, PDE and mass-balance diagnostics |
| Geospatial data | GeoPandas, Rasterio, GDAL, PostGIS, Google Earth Engine, ArcGIS Pro |
| Environmental modeling | MODFLOW-2005, FloPy, terrain derivatives, hydrographic analysis |
| Research software | Git, pytest, reproducible experiment pipelines, FastAPI, Docker |

My earlier work includes enterprise GIS and UAV inspection at a power utility, and a 2025 CDM Smith internship involving AI-based wetland delineation and Bayesian PFAS modeling. My M.S. thesis received SIUC’s university-wide Outstanding Thesis Award for 2025–2026.

I’m interested in research roles and collaborations in **GeoAI, scientific ML and Earth observation** as I prepare to graduate in 2027. [Get in touch](mailto:edidemichael@gmail.com).