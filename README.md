# el-salvador-health-clustering
Interactive clustering analysis of healthcare service points in El Salvador using DBSCAN and Folium. This project explores spatial patterns in clinics, health centers, and laboratories using open geolocation data for educational purposes.

What is clustering, and why does it matter in public health?
Clustering is a technique used in spatial and data analysis to identify natural groupings within a dataset based on proximity, similarity, or behavior. In healthcare, clustering allows us to analyze how services are distributed geographically and assess potential areas of under- or over-concentration.

🗺️ In this exploratory exercise, I analyzed the spatial distribution of primary health service units across El Salvador using publicly available geolocation data. The dataset includes clinics, medical centers, and laboratories collected through open geographic sources.

📊 The methodology involved:

Aggregating a national dataset of public and private health points of interest.

Applying DBSCAN (Density-Based Spatial Clustering of Applications with Noise) to group nearby facilities within a 1,000-meter radius.

Mapping all points using folium to create an interactive visualization.

Categorizing facilities by type: Medical Clinic, Laboratory, or Health Center.

✅ What insights emerged?

Several municipalities show high-density clusters, particularly in urban areas where health access is already concentrated.

A significant number of facilities fall outside any cluster, suggesting geographically isolated service points.

Clustering helps visualize patterns that are not always obvious in tabular data — offering an intuitive way to explore accessibility and saturation.

⚠️ Disclaimer:
This analysis is intended for educational and exploratory purposes only. It is not exhaustive, nor should it be used to inform health policy or investment decisions without further validation.

🧪 I conducted this as part of a personal project to practice spatial clustering and geodata visualization in Python. Feedback and collaboration from fellow data professionals and public health experts are welcome.
