**Fault Zone Mapping using Unsupervised Spatial Analysis (Synthetic Data)**

This project simulates geospatial data and applies **DBSCAN clustering** to identify potential fault zones based on synthetic topographic features such as elevation, slope, and aspect.

📌 **Features**

Generates 1000 synthetic spatial data points
Calculates synthetic elevation, slope, and aspect
Applies **DBSCAN** (Density-Based Spatial Clustering) for unsupervised analysis
Saves results with cluster labels in a downloadable Excel file

🧪 **Technologies Used**

Python
NumPy
Pandas
scikit-learn
Matplotlib
seaborn

📁 **Output**

The final output is a file named:  
synthetic_fault_zone_clusters.xlsx

This file contains:

| X     | Y     | Elevation | Slope | Aspect | Cluster |
|-------|-------|-----------|-------|--------|---------|
| ...   | ...   | ...       | ...   | ...    | ...     |

Cluster `-1` indicates noise points as detected by DBSCAN.

🚀 How to Run

1. Clone this repository or run the code in a Python environment.
2. Ensure required libraries are installed:
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn
Run the Python script.

Find the output Excel file in the working directory.

🗺️ Notes
This example uses synthetic data. For real applications, you can substitute spatial features derived from GIS datasets or remote sensing (e.g., DEMs).

DBSCAN is well-suited for spatial data because it handles noise and non-linear cluster shapes effectively.

📧 Contact
Tarinabo williamtarinabo@gmail.com
