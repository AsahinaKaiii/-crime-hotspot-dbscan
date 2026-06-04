# -Crime-Hotspot-DBSCAN
A machine learning project that identifies crime hotspots 
in Los Angeles using density-based clustering (DBSCAN).

## Results
- ✅ **58 crime hotspots** identified
- 📍 **30,000 crime incidents** analysed
- 🔴 Largest hotspot contained **20,303 crimes**
- 🔇 **322 isolated incidents** classified as noise (1.1%)

## How It Works
1. Load LA crime data (2020–Present)
2. Clean invalid GPS coordinates
3. Scale coordinates using StandardScaler
4. Run DBSCAN (eps=0.05, min_samples=5)
5. Visualise hotspots on an interactive map

## Tools Used
Tool and Purpose
## Python
- Programming language 
## Google Colab
- Development environment 
## scikit-learn
- DBSCAN algorithm 
## Pandas & NumPy
 - Data cleaning 
## Matplotlib
 - Plotting clusters 
## Folium
 - Interactive crime map 


## Dataset
Los Angeles Crime Data (2020 to Present)  
Download from: https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8

##  How to Run
1. Open the `.ipynb` file in Google Colab
2. Upload the crime dataset CSV when prompted
3. Run all cells in order
4. View the generated heatmap

## 📌 Top 10 Crime Hotspots Found
| Rank | Hotspot | Crimes |
|------|---------|--------|
| #1 | Hotspot 0 | 20,303 |
| #2 | Hotspot 1 | 5,367 |
| #3 | Hotspot 4 | 1,477 |
| #4 | Hotspot 5 | 1,233 |
| #5 | Hotspot 10 | 201 |
| #6 | Hotspot 8 | 199 |
| #7 | Hotspot 14 | 167 |
| #8 | Hotspot 6 | 55 |
| #9 | Hotspot 19 | 53 |
| #10 | Hotspot 3 | 46 |
