
# 🏠 RealEstate-Thesaloniki

A data-driven exploration of real estate listings in Thessaloniki, Greece.  
This project analyzes   residential property data with a focus on **price**, **area (m²)**, and **property type**.  
It also includes spatial data (latitude, longitude, distance to amenities) to support location-based insights.

---

## 📊 Dataset Overview

The dataset includes detailed information for each property listing with the following columns:

| Column                    | Description                                                |
|---------------------------|------------------------------------------------------------|
| `type`                   | Type of property (e.g. Διαμέρισμα, Στούντιο, Μονοκατοικία) |
| `code`                   | Unique internal reference code                             |
| `price`                  | Listing price in euros (€)                                 |
| `area`                   | Property size in square meters (m²)                        |
| `location`               | Area or neighborhood in Thessaloniki                       |
| `street`                 | Street name (if available)                                 |
| `floor`                  | Floor level of the property                                |
| `kitchen`, `bath`, `loft`| Room details                                               |
| `heating`                | Type of heating (central, autonomous, etc.)                |
| `energy_class`           | Energy efficiency rating                                   |
| `y_build`, `y_rebuild`   | Year built and year renovated (if any)                     |
| `sea_dist`               | Distance to the sea (in meters)                            |
| `ID`                     | Unique identifier                                          |
| `Latitude`, `Longitude`  | Geographic coordinates for mapping                         |
| `schools_within_1km`     | Number of schools within 1km                               |
| `dist_to_nearest_stop_m`| Distance to the nearest transit stop                        |
| `green_area_500m`        | Green space area (m²) within 500m                          |
| `green_area_percentage`  | % of green space within 500m radius                        |
| `distance_to_entertainment_m` | Distance to entertainment venues                     |
| `entertainment_within_1km`    | Count of entertainment venues within 1km            |

---

## 🎯 Project Goals

- Analyze and visualize price trends by **property type** and **area size**
- Generate **interactive maps** showing listing distribution using `folium`

---

## 🧰 Technologies Used

- **Python**
  - `pandas` for data wrangling
  - `folium` for interactive maps
- **Jupyter Notebook** for exploration

---

## 📌 Key Insights

- Price per square meter varies significantly by **property type** and **proximity to amenities**




