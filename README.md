# 🌍 Satellite Data Analysis (Jupyter Notebook)

This repository contains a **Jupyter Notebook** showcasing workflows for exploring and visualizing geospatial data using Python.  
It demonstrates how to load, process, and plot raster and vector data in a reproducible way.  

---

## ⚡ Features
- Handle **raster and vector geospatial data**  
- Work with common formats: **GeoTIFF, NetCDF, GeoJSON, Shapefiles**  
- Visualize results using **Matplotlib**  
- Reproducible analysis inside a single **Jupyter Notebook**  

---

## 📦 Dependencies

This project requires the following Python packages:

- numpy  
- rasterio  
  - rasterio.transform  
  - rasterio.enums (optional)  
  - rasterio.plot (optional)  
- rioxarray  
- netCDF4  
- geojson  
- pandas  
- geopandas  
- affine  
- matplotlib  
  - matplotlib.pyplot  
  - matplotlib.ticker  

---

## 🛠️ Installation

Create and activate a virtual environment (recommended with [conda](https://docs.conda.io/)):

```bash
conda create -n sat-env python=3.10
conda activate sat-env
pip install numpy rasterio rioxarray netCDF4 geojson pandas geopandas affine matplotlib

git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
