# Rajasthan Pincode Clustering Analysis

## Project Overview
This project clusters pincodes in Rajasthan, India using k-means on geographic coordinates. Key steps include:
- Data cleaning of coordinates
- Spatial filtering using shapefiles
- K-means clustering implementation from scratch
- Visualization of clusters on a map


## Installation
1. Clone this repository:
git clone https://github.com/AtulBoyal/EpochSpringCamp2024-2025.git

2. Install dependencies:
pip install -r requirements.txt


## Usage
1. Place `clustering_data.csv` in the `data/` folder
2. Download [Natural Earth Admin 1 States shapefile](https://www.naturalearthdata.com/downloads/10m-cultural-vectors/) and extract to `data/ne_10m_admin_1_states_provinces/`
3. Run Jupyter notebook:   
jupyter notebook notebooks/rajasthan_clustering.ipynb


## Project Structure
data/ - Raw/processed data
notebooks/ - Jupyter notebooks
requirements.txt - Python dependencies


## Results
- Identified 4 distinct geographic clusters in Rajasthan
- Visualization showing cluster distribution and centroids
- Elbow method plot for optimal k-value selection
