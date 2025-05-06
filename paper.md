---
title: 'Interactive Visualization of CheMin Mineral Data from the Curiosity Rover: A Python Tool'
authors:
  - name: "Fatima-Ezzahra Jadid"
    affiliation: 1
  - name: "Hasnaa Chennaoui Aoudjehane"
    affiliation: 1
affiliations:
  - name: "Faculty of Sciences Ain Chock (FSAC), Hassan II University of Casablanca and ATTARIK Foundation"
    index: 1
date: 2025-05-06
bibliography: []
---

# Summary

This Python-based Dash application was developed as part of a Ph.D. thesis project in planetary science at the Faculty of Sciences Ain Chock (FSAC), Hassan II University of Casablanca. Supervised by Prof. Hasnaa Chennaoui Aoudjehane, the tool provides an interactive interface for visualizing mineralogical data from the CheMin instrument aboard NASA's Curiosity rover. By combining mineral abundance data with spatial information, the tool enables researchers to explore mineral diversity across different Martian sols. The interface includes a map-based viewer, a mineral abundance plot with uncertainty bars, and dropdown selection of sols.

# Statement of Need

Despite the importance of CheMin data for planetary science, there are limited tools for visualizing its outputs interactively. This tool fills that gap by enabling scientists, educators, and developers to explore mineralogical variations across the Curiosity mission, using a lightweight and open-source interface built with Dash and Plotly.

# Functionality

- Load and visualize mineral abundances with associated error values
- Map sol locations with elevation data on a Mars orthophoto basemap
- Easy integration with additional CSV datasets
- Requires only open-source Python packages (Dash, Plotly, Pandas, Leaflet)

# Example Use

Using `combined_chemin_data_all_sols.csv` and `combined_sol_data.csv`, users can launch the app and instantly visualize changes in clay, sulfate, or oxide content by Martian sol, along with geospatial context.

# References

- Blake et al., 2012. "Characterization and calibration of the CheMin mineralogical instrument on Mars Science Laboratory." *Space Science Reviews*, 170(1-4), 341–399.
- NASA PDS Analyst's Notebook. https://an.rsl.wustl.edu/msl
