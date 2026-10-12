<h1 align="center">Hi there 👋, I'm Michael Edidem</h1>

<p align="center"><strong>Geospatial AI · Scientific machine learning · Environmental systems</strong><br>PhD Researcher @ Southern Illinois University Carbondale · Expected graduation <strong>2027</strong></p>


[🌍 Portfolio](https://mikedidem.github.io/medidem/) · [📄 CV](https://mikedidem.github.io/medidem/cv/Michael_Edidem_CV.pdf) · [📚 Publications](https://mikedidem.github.io/medidem/publications/) · [📫 Email](mailto:edidemichael@gmail.com)

## 🌟 About me

**If we could observe every place on Earth, every day, what could we learn about how our planet changes—and how it shapes us?**

I develop geospatial AI and scientific machine-learning methods to turn imagery, terrain and simulation data into useful knowledge about infrastructure and environmental systems. My research explores how we can learn from sparse, heterogeneous observations and build predictions we can trust.

With a background in geomatics, I bring a spatial perspective to machine learning, connecting terrain, remote sensing and environmental modeling in my research.

- 🔭 Currently exploring **multimodal geospatial representation learning** and **neural surrogates**, with a focus on geospatial foundation (GF) models, multimodal feature extraction and learning from sparse, heterogeneous geospatial data.
- 💬 Ask me about **LiDAR/DEM analysis, drainage crossings, groundwater surrogates**, or making models easier to evaluate.
- 📚 M.S., Geography & Environmental Resources (Geospatial AI), SIUC, **2024** · B.S., Geoinformatics & Surveying, University of Uyo, **2019**.

✨ **My guiding idea:** “Learning from Earth’s complexity to build models we can trust and knowledge we can act on.”

---

<!-- 🌐 Research Framework -->
<p align="center">
  <img src="assets/research-framework.svg"
       alt="Geospatial AI connects multimodal representation learning, scientific machine learning, remote sensing and computer vision, and environmental decision support" width="900"/>
</p>


## 🐍 Contribution Activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)"
            srcset="https://raw.githubusercontent.com/mikedidem/mikedidem/output/github-contribution-grid-snake-dark.svg" />
    <img alt="GitHub Contribution Snake"
         src="https://raw.githubusercontent.com/mikedidem/mikedidem/output/github-contribution-grid-snake.svg"
         width="100%" />
  </picture>
</p>


---

## 📝 Selected projects

### 💧 Groundwater surrogates: accuracy and conservation

[**gw_surrogate_evaluation**](https://github.com/mikedidem/gw_surrogate_evaluation) · Lead author & developer · Manuscript under review

A surrogate can reproduce hydraulic head at **R² > 0.999** and still fail to conserve water. I built a diagnostic framework comparing CNN, ConvLSTM and PINN surrogates against MODFLOW-2005 on two synthetic aquifers, measuring predictive error, governing-equation residuals, boundary behavior and mass balance together.

The repository includes reproducible evaluators, benchmark configurations and tests. [Case study](https://mikedidem.github.io/medidem/projects/groundwater-surrogates/)

### 🌊 CHIRRP: groundwater scenarios in plain language

[**chirrp**](https://github.com/mikedidem/chirrp) · Co-author & repository maintainer · Manuscript under review

A deployed research application connecting natural-language scenario requests to a physics-informed groundwater surrogate, with regulation retrieval and an on-demand MODFLOW cross-check. Its CPU surrogate evaluation is approximately **238× faster than MODFLOW** in the reported benchmark; this is distinct from end-to-end interaction time.

**PyTorch · FastAPI · Angular · Docker · RAG**<br>
[Live demo](https://morule-hydro.hf.space) · [Case study](https://mikedidem.github.io/medidem/projects/chirrp/)

### 🛰️ Drainage crossings: finding what terrain hides

[**Detection code**](https://github.com/GeoFewLab/Drainage_CrossingDet) · [**Classification code**](https://github.com/GeoFewLab/Drainge_CrossingClassification) · First author of two 2025 papers

Culverts and bridges are often missing from elevation-derived stream networks. My research uses high-resolution LiDAR DEMs and terrain derivatives to classify and locate drainage crossings, with Grad-CAM to examine the features driving predictions. The best classification configuration reached **97.9% accuracy within the study watershed**; geographic transfer is a separate research question.

[Detection paper](https://doi.org/10.1016/j.envsoft.2025.106338) · [Classification paper](https://doi.org/10.3389/frai.2025.1561281) · [Case study](https://mikedidem.github.io/medidem/projects/drainage-crossing-detection/)

### 🌱 Soil Swin-UNet

[**soil**](https://github.com/mikedidem/soil) · Earlier work within GeoFewLab

Swin-UNet experiments for drought forecasting across remote-sensing drought indices—part of my broader work with Earth-observation data and spatial deep learning.

---

## 📚 Publications

- **Edidem, M.**, Xu, B., Li, R., Wu, D., Rekabdar, B., Wang, G. (2025). *[Identification of Drainage Crossings on High-Resolution Digital Elevation Models Using Explanatory Deep Learning Approaches](https://doi.org/10.3389/frai.2025.1561281)*. **Frontiers in Artificial Intelligence**
- **Edidem, M.**, Li, R., Wu, D., Rekabdar, B., Wang, G. (2025). *[GeoAI-based Drainage Crossing Detection for Elevation-derived Hydrographic Mapping](https://doi.org/10.1016/j.envsoft.2025.106338)*. **Environmental Modelling & Software**
- Nazeri, A., Godwin, D.W., Panteleaki, A.M., Anagnostopoulos, I., **Edidem, M.**, Li, R., Shu, T. (2025). *[Exploration of TPU Architectures for the Optimized Transformer in Drainage Crossing Detection](https://doi.org/10.1109/BigData62323.2024.10826077)*. Proceedings of 2024 IEEE International Conference on Big Data
- Wu, D., Li, R., **Edidem, M.**, Wang, G. (2024). *[Enhancing Hydrologic LiDAR Digital Elevation Models: Bridging Hydrographic Gaps at Fine Scales](https://doi.org/10.1111/1752-1688.13239)*. **JAWRA – Journal of the American Water Resources Association**
- Wu, D., Li, R., Talbert, C., **Edidem, M.**, Rekabdar, B., Wang, G. (2023). *[Classification of Drainage Crossings on High-resolution Digital Elevation Models: A Deep Learning Approach](https://doi.org/10.1080/15481603.2023.2230706)*. **GIScience & Remote Sensing**, 60:1


[All publications and conference talks →](https://mikedidem.github.io/medidem/publications/)

---

## 🔬 Current research

- **Multimodal geospatial representation learning:** investigating how geospatial foundation models and multimodal feature extraction can support learning from sparse, heterogeneous data, including infrastructure mapping across regions.
- **Neural groundwater surrogates:** investigating finite-volume, physics-informed neural operators and tradeoffs between accuracy, physical consistency and computational cost.

## 🛠️ Tools & tech stack

**Programming & notebooks**
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![R](https://img.shields.io/badge/-R-276DC3?style=flat-square&logo=r&logoColor=white)
![SQL](https://img.shields.io/badge/-SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![Jupyter](https://img.shields.io/badge/-Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

**Machine learning**
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Transformers](https://img.shields.io/badge/-Transformers-FFD43B?style=flat-square&logo=huggingface&logoColor=black)
![TensorBoard](https://img.shields.io/badge/-TensorBoard-FFA500?style=flat-square&logo=tensorflow&logoColor=white)

**Maps, imagery & spatial data**
![GeoPandas](https://img.shields.io/badge/-GeoPandas-139C5A?style=flat-square&logo=pandas&logoColor=white)
![Rasterio](https://img.shields.io/badge/-Rasterio-2E7D32?style=flat-square)
![GDAL](https://img.shields.io/badge/-GDAL-2E7D32?style=flat-square)
![ArcGIS Pro](https://img.shields.io/badge/-ArcGIS%20Pro-4479A1?style=flat-square&logo=esri&logoColor=white)
![QGIS](https://img.shields.io/badge/-QGIS-589632?style=flat-square&logo=qgis&logoColor=white)
![ERDAS Imagine](https://img.shields.io/badge/-ERDAS%20Imagine-6B4C9A?style=flat-square)
![Google Earth Engine](https://img.shields.io/badge/-Earth%20Engine-34A853?style=flat-square&logo=googleearth&logoColor=white)
![Leaflet](https://img.shields.io/badge/-Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white)
![OpenStreetMap](https://img.shields.io/badge/-OpenStreetMap-7EBC6F?style=flat-square&logo=openstreetmap&logoColor=white)
![PostGIS](https://img.shields.io/badge/-PostGIS-336791?style=flat-square&logo=postgresql&logoColor=white)

**Cloud geospatial workflows**
![xarray](https://img.shields.io/badge/-xarray-1F6B75?style=flat-square)
![Dask](https://img.shields.io/badge/-Dask-FC6E6B?style=flat-square&logo=dask&logoColor=white)
![Zarr](https://img.shields.io/badge/-Zarr-2D8C72?style=flat-square)
![STAC](https://img.shields.io/badge/-STAC-4C7D99?style=flat-square)

**Geospatial foundation models**
![TorchGeo](https://img.shields.io/badge/-TorchGeo-3B7A57?style=flat-square)
![TerraTorch](https://img.shields.io/badge/-TerraTorch-5D4C9B?style=flat-square)

**Research software & deployment**
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![pytest](https://img.shields.io/badge/-pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Environmental modeling**
![MODFLOW](https://img.shields.io/badge/-MODFLOW-00639C?style=flat-square)
![FloPy](https://img.shields.io/badge/-FloPy-00639C?style=flat-square)

**Development & compute**
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Colab](https://img.shields.io/badge/-Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=black)
![VS Code](https://img.shields.io/badge/-VSCode-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/-GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

### Where the tools show up

| Area | Tools and methods I use |
| :--- | :--- |
| Scientific ML | PyTorch, CNNs, ConvLSTMs, PINNs, PDE and mass-balance diagnostics |
| Geospatial data | GeoPandas, Rasterio, GDAL, PostGIS, Google Earth Engine, ArcGIS Pro |
| Environmental modeling | MODFLOW-2005, FloPy, terrain derivatives, hydrographic analysis |
| Research software | Git, pytest, reproducible experiment pipelines, FastAPI, Docker |

My earlier work includes enterprise GIS and UAV inspection at a power utility, and a 2025 CDM Smith internship involving AI-based wetland delineation and Bayesian PFAS modeling. My M.S. thesis received SIUC’s university-wide Outstanding Thesis Award for 2025–2026.

## 🌐 Let’s connect

I’m interested in research roles and collaborations in **GeoAI, scientific ML and Earth observation**.

- 🌍 [Explore my portfolio](https://mikedidem.github.io/medidem/)
- 📄 [Download my CV](https://mikedidem.github.io/medidem/cv/Michael_Edidem_CV.pdf)
- 📫 [edidemichael@gmail.com](mailto:edidemichael@gmail.com)