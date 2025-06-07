Project Overview

This project uses unsupervised machine learning (KMeans clustering) to analyze and optimize public transport stop locations in Nairobi, Kenya. The goal is aligned with UN Sustainable Development Goal 11 (Sustainable Cities and Communities) — specifically enhancing accessibility and efficiency of public transport systems.

📊 Dataset

We used GTFS data (General Transit Feed Specification) for Nairobi, which includes:

Stop names

Latitude and longitude

Parent station info

🔍 Methodology

Data Cleaning: We filtered out stops without valid lat/lon coordinates.

Clustering: Applied KMeans with 5 clusters to group stops based on geographic proximity.

Visualization: Leveraged Folium to plot each cluster on an interactive map with color-coded markers.

🗺️ Results

Clustered stops into 5 logical zones across Nairobi.

Map shows spatial groupings, useful for route planning and service optimization.

🧠 Tech Stack

Python

Pandas

Scikit-learn

Folium

Geopy

📷 Screenshots

Add your screenshots here (e.g., cluster map, elbow plot, sample stop table)

🌍 Why It Matters

Reduces commute time.

Aids urban planners in reallocating or introducing routes.

Promotes sustainable and inclusive public transportation for all.

📁 Files in This Repo

transport_clustering.ipynb: Main notebook for clustering logic.

gtfs.zip: Raw GTFS data (if small).

README.md: You’re reading it!

🏁 Next Steps

Try DBSCAN or HDBSCAN for density-based clustering.

Integrate real-time traffic data.

Add route optimization using TSP or Nearest Neighbor algorithms.

Made with ❤️ by Evans

