# Sneaker Brand Comparison: Nike vs Adidas  

This project conducts a comparative analysis of sneakers from Nike and Adidas based on key performance indicators, including price (INR), durability, and comfort. It also integrates geospatial data to visualize the headquarters of both brands.  

---

## Project Overview  

This study aims to analyze and visualize critical factors influencing consumer preferences for Nike and Adidas sneakers. The primary areas of focus include:  

- **Price Analysis (INR):** Evaluating the cost differences between the two brands.  
- **Durability Assessment:** Analyzing which brand demonstrates greater longevity.  
- **Comfort Evaluation:** Comparing comfort levels based on available data.  
- **Geospatial Visualization:** Mapping the headquarters of Nike and Adidas.  

---

## Dataset  

The dataset consists of sneaker models from both brands with the following attributes:  

| Brand  | Model        | Price (INR) | Durability | Comfort |
|--------|-------------|-------------|------------|---------|
| Nike   | Air Max     | 12,450      | 8          | 9       |
| Nike   | Air Force 1 | 9,960       | 9          | 8       |
| Nike   | React       | 10,790      | 7          | 9       |
| Adidas | Ultraboost  | 14,940      | 9          | 8       |
| Adidas | Superstar   | 8,300       | 8          | 9       |
| Adidas | NMD         | 11,620      | 8          | 8       |

The pricing data has been converted from USD to INR based on the latest exchange rate.  

---

## Data Analysis and Visualization  

The following visualizations are included in the study:  

- **Bar Chart:** Comparative pricing analysis between Nike and Adidas.  
- **Box Plot:** Durability distribution across both brands.  
- **Scatter Plot:** Relationship between price and comfort.  
- **Geospatial Mapping:** Headquarters of Nike and Adidas represented on an interactive map.

Install Required Libraries
This project utilizes the following Python libraries:
- pandas (data manipulation)
- matplotlib and seaborn (data visualization)
- folium (geospatial mapping)

Install dependencies if necessary:
**pip install pandas matplotlib seaborn folium**
Execute the Jupyter Notebook (sneaker_comparison.ipynb) in Google Colab or a local Jupyter environment.
