## Data Collection

Samples of sea water and sand were collected from three distinct sites for 10 consecutive weeks. The following parameters were measured:

### Bacterial Varieties:
- **Enterococcus**  
- **Fecal coliform**  
- **E.coli**  
*(Counts were recorded separately for sea water and sand)*  

### Physical Parameters:
- pH  
- Conductivity  
- Salinity  
- Temperature  
*(Measured in sea water and sand samples)*  

### Environmental Parameters:
- Rainfall  
- Wind speed  
*(Recorded over the 10-week period)*  

## Analysis Process

The collected data was processed and analyzed using Python libraries (`pandas`, `numpy`, `statsmodels`, `scipy`, `scikit-learn`, `matplotlib`, `seaborn`) through a multi-stage pipeline:

### 1. Descriptive Analysis
- Calculated key statistics (mean, median, range, standard deviation) for bacterial counts and physical parameters for both sea water and sand at each site.
- Determined total bacterial counts (using mean values) separately for sea water and sand.
- Generated graphs visualizing individual bacterial variety counts per site (sea water and sand separately) and total bacterial counts per variety across sea water and sand.

### 2. Temporal Analysis
- Analyzed the trends of bacterial counts over the 10 weeks for sea water and sand (Time series analysis).
- Analyzed the trends of environmental parameters (Rainfall, Wind speed) over the 10 weeks.
- Created graphical representations of these temporal trends.

### 3. Correlation Analysis
- Investigated the relationships between bacterial counts (sea water and sand separately) and physical and environmental parameters.
- Used Spearman's correlation coefficient to measure these relationships.
- Visualized correlations using heatmaps.

### 4. Comparative Analysis
- Applied the non-parametric Mann-Whitney U test to compare the total count of each bacterial variety between sea water and sand to determine significant differences.
- Used the Kruskal-Wallis test to compare the total counts of each bacterial variety across the three sites (sea water and sand separately).
- Utilized boxplots and bar charts to visually compare bacterial levels across sites.

### 5. Regression Analysis
- Determined the variance of each bacterial variety's count with Rainfall and Wind speed over the 10 weeks (sea water and sand separately).
- Identified linear relationships between each other.
- Generated graphs illustrating these relationships.

### 6. Analysis with Standard Water Quality Guidelines
- Compared total bacterial counts in sea water (for each variety) against established standards from the Blue Flag criteria, US EPA guidelines, and WHO guidelines.
- Provided graphical outputs to show how the measured bacterial levels compare to these guideline thresholds and categories.
