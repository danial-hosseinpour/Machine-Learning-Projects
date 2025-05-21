### Clustering Museums Based on Geographic Proximity built with:
- **Python** for backend logic and data processing  
- **Pandas** & **NumPy** for efficient data manipulation  
- **Matplotlib** & **Seaborn** for data visualization  
- **Geopandas** for handling geographical data  
- **Contextily** for basemap overlay  
- **DBSCAN** & **HDBSCAN** for clustering museum locations  

---

## Museum Location Clustering Using DBSCAN & HDBSCAN

This project applies **DBSCAN and HDBSCAN clustering algorithms** to segment museums based on their geographical coordinates. By grouping museums based on **latitude and longitude**, it provides insights into museum density across Canada and identifies potential outlier locations.  

## Key Insights:
- DBSCAN successfully clustered 701 museums in the largest group, while **HDBSCAN assigned fewer points to clusters** due to its hierarchical approach.  
- HDBSCAN detected significantly more noise (462 points) compared to DBSCAN (79 points), making it more conservative in clustering.  
- Museums tend to be concentrated in certain cities, with rural areas showing scattered or isolated points.  
- Scaling coordinates impacts clustering performance, requiring adjustments to parameters (`eps`, `min_samples`).  
- Mapped clusters help visualize museum locations dynamically, enhancing geographic exploration.  

---

## Visualization

- DBSCAN Museum Clustering Map
- HDBSCAN Museum Clustering Map 

---

## Dependencies  

```bash
pip install pandas numpy matplotlib seaborn geopandas contextily hdbscan scikit-learn
```

---

## License

This project is licensed under the MIT License.


