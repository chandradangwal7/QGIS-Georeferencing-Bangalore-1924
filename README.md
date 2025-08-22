# QGIS – Georeferencing Historical Map of Bangalore (1924)

This project demonstrates how to georeference a **scanned historical map of Bangalore (1924)** using **QGIS** and overlay it on a modern **OpenStreetMap basemap**.  
The aim is to visualize how the city has evolved over time by aligning past and present maps.

---

## 📌 Project Overview
- **Software Used:** QGIS (with Georeferencer tool)  
- **Dataset:**  
  - Scanned Bangalore Map (1924) → `Bangalore_1924.png`  
  - Georeferenced output GeoTIFF → `Bangalore_1924_modified.tif`  
  - QGIS Project File → `.qgz`  
- **Basemap:** OpenStreetMap (EPSG:3857)  

---

## ⚙️ Steps Followed
1. Loaded the scanned 1924 Bangalore map into **QGIS Georeferencer**.  
2. Collected **Ground Control Points (GCPs)** by matching intersections, roads, and landmarks visible in both maps.  
3. Applied a **Polynomial 2 Transformation** with **EPSG:3857 projection**.  
4. Exported the **GeoTIFF overlay** (`Bangalore_1924_modified.tif`).  
5. Created a **Print Layout** in QGIS to visualize the georeferenced historical map over the OpenStreetMap basemap.  

---

## 🎯 Key Learning
- Understanding the use of **Georeferencing** in GIS.  
- Importance of **Ground Control Points (GCPs)** in aligning historical maps.  
- Visualizing **urban growth and historical geography** by comparing maps across time.  

---

## Final Output
Below is the georeferenced Bangalore 1924 map aligned with the present-day OpenStreetMap:

![Georeferenced Bangalore Map](geographic%20bangalore%20map%20analysis.png)

---

## 🙏 Credits
- Tutorial Reference: [Ujaval Gandhi – Spatial Thoughts](https://spatialthoughts.com)  
- Software: [QGIS](https://qgis.org)  

---

## 📂 Repository Structure

├── Bangalore_1924_modified.tif # Georeferenced raster output
├── Bangalore Lakes mapping from 1927 to present.png # Final layout image
├── Layout 1.pdf # Print layout PDF
└── README.md # Project documentation
