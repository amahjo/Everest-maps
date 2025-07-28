# 🌍 World Population Density Map

This project visualizes the **population density (people per km²)** of countries across the world using R.

It uses open-source data and tools to compute and display the density on a world map.

---

## 📦 Packages Used

- **sf**: for handling spatial features (simple features)
- **ggplot2**: for plotting the map
- **rnaturalearth** and **rnaturalearthdata**: for fetching global shapefiles
- **dplyr**: for data manipulation
- **units**: to assign area units (km²)

---

## 📊 Output

The map color codes countries by their **population density** on a logarithmic scale using a viridis color palette. Countries with higher densities appear darker.

⚠️ Note: Countries with zero or missing area estimates may appear blank or throw warnings.

---

## 🖼️ Map

Below is the generated map image.

![World Population Density Map](world_density_map.png)

---

## 📁 Files Included

- `world_map_density.html`: web enabled script of the map
- `world_map_density.Rmd`: R script that generates the map
- `world_population_density.png`: the map image
- `README.md`: this file

---

## 🔗 Data Sources

- Country geometries and population estimates: via [Natural Earth](https://www.naturalearthdata.com/)

---

## 💬 Notes

- Log scale helps reveal population differences between countries.
- Learning geography is fun in Everest School, Bodija, Ibadan, Nigeria.

---
