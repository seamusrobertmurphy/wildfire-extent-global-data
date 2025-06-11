# Wildfire Delineation (Task 5 – 06 Feb 2025)

This notebook performs burned-area delineation for Ecuador over a reference and a crediting period, using MODIS FireCCI51 data and Google Earth Engine in Google Colab.

---

## Table of Contents

1. [Prerequisites](#prerequisites)  
2. [Setup & Authentication](#setup--authentication)  
3. [Environment Check](#environment-check)  
4. [Data Ingestion](#data-ingestion)  
5. [Visualization](#visualization)  
   - [Map Jurisdiction Boundary](#map-jurisdiction-boundary)  
   - [Map Burned Area – Reference Period](#map-burned-area--reference-period)  
   - [Map Burned Area – Crediting Period](#map-burned-area--crediting-period)  
6. [Export Rasters](#export-rasters)  
7. [Cleanup](#cleanup)  
8. [Author & License](#author--license)

---

## Prerequisites

- **Google Account** with access to [Google Earth Engine](https://earthengine.google.com/)  
- **Google Colab** runtime (standard or GPU)  
- Python packages:  
  ```bash
  pip install leafmap geemap==0.16.4 geopandas numpy session_info
