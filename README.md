# 🌍 Satellite Pollution Monitoring using AI

## 📌 Project Overview
This project is developed as part of the **AICTE Edunet GreenAI Skills Internship**.  
The objective is to use **AI and satellite imagery (Sentinel-2, Landsat, MODIS)** to monitor environmental pollution indicators such as:

- **Water Pollution** (turbidity, algal blooms, contamination)  
- **Land Pollution** (deforestation, illegal landfills, urban expansion)  
- **Air Pollution Proxies** (urban heat islands, industrial smoke zones)

The system leverages **Computer Vision (CNN/U-Net/Transformers)** for automated detection and generates **pollution maps** to support monitoring and decision-making.

---

## 🎯 Project Objectives
- Collect and preprocess satellite imagery for chosen regions.  
- Apply **AI models** to classify and segment polluted vs. clean areas.  
- Visualize results with heatmaps and pollution trend graphs.  
- Build an interactive **dashboard/web app** for end users.  
- Deliver an end-to-end pipeline from **data → AI model → insights**.  

---

## 📂 Dataset Sources
We are using open-source datasets:

- **Sentinel-2 (ESA Copernicus)** → high-resolution multispectral imagery  
  🔗 https://scihub.copernicus.eu/  
- **Landsat (NASA/USGS)** → long-term earth observation  
  🔗 https://earthexplorer.usgs.gov/  
- **MODIS (NASA)** → daily global monitoring  
  🔗 https://ladsweb.modaps.eosdis.nasa.gov/  
- **Validation Data**: [OpenAQ](https://openaq.org/), [Global Forest Watch](https://www.globalforestwatch.org/)  

---

## 🛠️ Tech Stack
- **Programming Language**: Python  
- **Libraries**:  
  - Data & Geospatial: `rasterio`, `geopandas`, `earthengine-api`, `gdal`  
  - AI/ML: `tensorflow` / `pytorch`, `scikit-learn`, `opencv`  
  - Visualization: `matplotlib`, `seaborn`, `folium`, `streamlit`  
- **Platforms**: Google Earth Engine, Jupyter Notebook / Google Colab  

---

## 🚀 Project Milestones

### ✅ Week 1 (30% Completion)
- Defined project scope & problem statement.  
- Collected sample Sentinel-2/Landsat images.  
- Preprocessed images (cloud masking, RGB composites).  
- Computed **NDVI** (vegetation index) and **NDWI** (water index).  
- Produced initial pollution indicator visualizations.  

### 🟡 Week 2 (60% Completion)
- Implemented AI model: CNN / U-Net for classification and segmentation.  
- Improved preprocessing pipeline (band selection, normalization).  
- Generated pollution heatmaps for selected region.  
- Validated results against external datasets (OpenAQ, GFW).  

### 🔴 Final Submission (100% Completion)
- Full AI pipeline for pollution monitoring completed.  
- Built **interactive dashboard** (Streamlit / Folium maps).  
- Prepared **Final Project PPT** (in official internship template).  
- Uploaded final source code and documentation to GitHub.  

---

## 📊 Expected Results
- Heatmaps showing polluted vs. clean regions.  
- Time-series plots of vegetation loss & water quality decline.  
- AI model accuracy metrics (precision, recall, IoU).  
- Dashboard for user-friendly interaction.  

*(Final graphs, screenshots, and accuracy results will be updated in this section once training is complete.)*

---



