<div align="center">

  <h2>Fisheries Data Clustering Analysis</h2>

<p align="center">
  K-means clustering analysis of commercial groundfish fisheries data from NOAA Northeast Fisheries Science Center.
  <br />
  <a href="https://github.com/JonathanK556"><strong>GitHub</strong></a>
</p>

</div>

---

## About

This project analyzes commercial groundfish fisheries data collected through NOAA's At Sea Monitor observer program. The analysis uses unsupervised machine learning (K-means clustering) to identify patterns in species composition and fishing behavior across different temporal and spatial strata in the Northeast Atlantic.

## Features

- 🐟 **Species Composition Analysis**: Clustering based on proportion of live weight per species
- 📍 **Spatiotemporal Modeling**: Analysis across unique combinations of year, month, and QDSQ areas
- 🔬 **Unsupervised Learning**: K-means clustering to discover natural groupings in fishery data
- 📊 **Performance Evaluation**: Silhouette score analysis for cluster validation
- 🗂️ **Multi-year Data**: Comprehensive analysis spanning 1999-2025 fishery seasons

## Model Performance

- **Algorithm**: K-means Clustering
- **Optimal Clusters**: 8 clusters identified
- **Silhouette Score (Train)**: 0.277
- **Silhouette Score (Holdout)**: 0.254
- **Alternative Method**: Hierarchical clustering also evaluated with n_clusters=8

## Key Findings

- Eight distinct fishery patterns identified through species composition analysis
- Temporal and spatial strata show meaningful clustering based on catch composition
- Model demonstrates consistent performance across training and holdout datasets
- Clustering reveals seasonal and regional variations in groundfish fishing patterns

## Data Sources

- **Primary Source**: NOAA Northeast Fisheries Science Center At Sea Monitor program
- **Data Type**: Haul-by-haul catch data from federal permit commercial groundfish vessels
- **Coverage**: Northeast Atlantic commercial fishing operations
- **Time Period**: 1999-2025 (multi-decade analysis)

## Project Structure

```
Fisheries-Model/
├── Fisheries_Data_Wrangling.ipynb  # Data preprocessing and cleaning
├── Capstone_3_Final_Report.pdf     # Comprehensive analysis report
├── Capstone_3_model_metrics.txt    # Model performance metrics
├── QSDQ.png                        # Spatial reference data
└── statisticalareas-0.jpg          # Statistical area boundaries
```

## Contributors

<table align="center">
  <tr>
    <td align="center" valign="top">
      <a href="https://github.com/JonathanK556">
        <img src="https://github.com/JonathanK556.png?size=120" width="88" height="88" style="border-radius:50%" alt="JonathanK556" />
        <br/>
        <sub><b>JonathanK556</b></sub>
      </a>
    </td>
  </tr>
</table>