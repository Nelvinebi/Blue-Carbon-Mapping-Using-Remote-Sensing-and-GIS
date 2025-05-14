# Blue Carbon Ecosystem Mapping and Carbon Stock Estimation

This project simulates the classification of coastal blue carbon habitats—**mangroves**, **seagrass**, and **salt marshes**—based on synthetic spectral indices (NDVI and NDWI), and estimates associated carbon stocks using simplified assumptions.

---

## 🌍 Objective

To demonstrate how remote sensing data (e.g., NDVI/NDWI) can be used to classify blue carbon ecosystems and estimate carbon storage spatially using synthetic raster inputs.

---

## 🧰 Features

- Generates synthetic NDVI and NDWI raster data
- Classifies habitats based on index thresholds:
  - **Mangroves (1)**: High NDVI & high NDWI
  - **Seagrass (2)**: Moderate NDVI & lower NDWI
  - **Salt Marsh (3)**: Low NDVI
- Estimates carbon stock (tons/ha):
  - Mangroves: 200
  - Seagrass: 150
  - Salt Marsh: 100
- Saves the classified habitat map as a **GeoTIFF**
- Visualizes classification and carbon stock
- Exports data in Excel format for tabular analysis

---

## 📁 Project Structure

blue-carbon-mapping/
├── synthetic_blue_carbon_data.xlsx # Flattened dataset for Excel export
├── blue_carbon_map.tif # GeoTIFF of classified habitats
├── blue_carbon_mapping.py # Main script
└── README.md

yaml
Copy
Edit

---

## 📦 Requirements

Install dependencies using pip:

```bash
pip install numpy rasterio matplotlib pandas openpyxl
🚀 How to Run
bash
Copy
Edit
python blue_carbon_mapping.py
This will:

Generate synthetic NDVI/NDWI data

Classify blue carbon habitats

Estimate carbon stock

Save a GeoTIFF and Excel dataset

Display visualization of results

📊 Output
GeoTIFF: blue_carbon_map.tif

Excel: synthetic_blue_carbon_data.xlsx

Visuals: Habitat classification & carbon stock heatmap

✍️ Author
Agbozu Ebingiye Nelvin
Environmental Data Scientist
GitHub: @Nelvinebi
