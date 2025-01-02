# [Real Estate Dashboard Project in R](https://github.com/Igusee/Project-3-Real-Estate)

## About my data:
* Dataset features apartment listings in Wrocław, Poland.
* Key variables include:
  * **Cena**: Apartment price in PLN.
  * **Lata użytkowania**: Age of the building in years.
  * **Odległość od centrum**: Distance from the city center in kilometers.
  * **Metraż**: Apartment size in square meters.
* Data source: Extracted from local property listings platform **Otodom**.
* Preprocessed to ensure consistent data structure and completeness.

## R and Flexdashboard Workflow:
* Designed an interactive dashboard using the **flexdashboard** package.
* Processed the dataset and created meaningful visualizations, combining multiple R libraries for an engaging presentation:
  * **ggplot2**: For aesthetic and flexible visualizations.
  * **plotly**: For interactive charts.
  * **corrplot**: To display correlation matrices.
  * **threejs** and **plot3D**: For 3D visualizations.

## Dashboard Pages and Visualizations:

### **Page 1**:
1. **Scatterplots**:  
   * Apartment price vs. building age.  
   * Apartment price vs. distance from the city center, with a regression line added.
2. **Correlation Matrix**:  
   * Displayed relationships between all variables using `corrplot`.
3. **Quantile-Quantile Plot (QQ Plot)**:  
   * Assessed normality of residuals for the regression model.
4. **Heatmap**:  
   * Highlighted correlations between dataset variables.

### **Page 2**:
1. **Interactive Scatterplots**:  
   * Created using **ggplot2** and enhanced with **plotly**.
   * Visualized relationships between apartment price, building age, and distance.
   * Added linear regression lines and smoothed fit curves.
2. **2D Density Plot**:  
   * Combined scatterplots with density contours for deeper insights.

### **Page 3**:
1. **Data Table**:  
   * Displayed apartment listings with pagination for easy browsing using the **DT** package.
2. **3D Scatterplot**:  
   * Visualized price, building age, and distance in a three-dimensional space using the **threejs** library.

### **Page 4**:
1. **3D Scatterplot**:  
   * Created using the **scatterplot3d** package for another perspective.
2. **3D Histogram**:  
   * Generated a 3D price vs. distance histogram with kernel density estimation using **plot3D**.

## Files:
* **R Markdown Code**: Embedded in the repository for reproducibility and customization.
* **Dashboard Outputs**: Interactive visuals included as part of the hosted dashboard.

## This is the end of this project, I hope you enjoyed it as much as I did!
