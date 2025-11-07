# 🌾 Land Use / Land Cover (LULC) Maps — 2025

This section contains **LULC classification maps** developed for Gokarneshwar Municipality and surrounding regions using **Sentinel-2 imagery** and GIS-based classification.


## 🗺️ Map Preview
![LULC Map Preview](LULC_Gokarneshwar_2025.jpg)


## 📊 Project Overview
- **Area:** Gokarneshwar Municipality, Kathmandu  
- **Purpose:** To assess built-up expansion and green-space distribution in the context of SDG 11 (Sustainable Cities & Communities).  
- **Resolution:** 10 m (Sentinel-2 MSI)  
- **Coordinate System:** WGS 84 / UTM Zone 45N  

---

## 🧭 Methodology Summary

| Step | Process | Description |
|------|----------|-------------|
| 1 | **Data Acquisition** | Sentinel-2 Level-1C imagery (ESA Open Data Hub) |
| 2 | **Preprocessing** | Cloud masking, mosaicking, and clipping to study area boundary |
| 3 | **Classification** | Supervised Maximum Likelihood Classification (6 land classes) |
| 4 | **Post-Processing** | Smoothing and reclassification using majority filter |
| 5 | **Map Layout** | Cartographic design with legend, scale bar, north arrow |

---

## 🗂️ Repository Contents
| File | Description |
|------|--------------|
| `LULC_Gokarneshwar_2025.jpg` | Final map layout (JPEG) |
| `LULC_Gokarneshwar_2025.pdf` | Printable map (optional) |
| `README.md` | Project documentation |

---

## 🧩 Land Classes
| Code | Class | Color |
|------|--------|--------|
| 1 | Built-up | 🔴 Red |
| 2 | Cropland | 🟨 Yellow |
| 3 | Forest | 🟩 Green |
| 4 | Grassland | 🟩 Light Green |
| 5 | OWL (Other Woodland) | 🟫 Brown |
| 6 | Riverbed | 🟦 Blue |

---

## 🧰 Software & Skills
- ArcGIS / QGIS  
- Raster classification & analysis  
- Map layout & design  
- SDG 11 spatial indicators interpretation  

---

## 👨‍💻 Author
Chanakya Banjara**  
*B.Sc. Environmental Science, Tribhuvan University*  
📍 Kathmandu, Nepal  
chanakyabanjaralinkedin@gmail.com
