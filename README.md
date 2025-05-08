
# 🚗 Used Car Analysis

This project presents an Exploratory Data Analysis (EDA) of a comprehensive dataset of used cars listed on Craigslist.org across the United States. The dataset includes a wide range of features such as price, condition, manufacturer, vehicle type, location data (latitude/longitude), and more.

## 📌 About the Dataset

- **Source**: [Craigslist.org](https://www.craigslist.org)
- **Author**: Collected via custom web scraper
- **Description**: The dataset aggregates thousands of used car listings from Craigslist, scraped every few months. It includes important variables for analysis like:
  - `price`
  - `condition`
  - `manufacturer`
  - `year`
  - `odometer`
  - `fuel`
  - `title_status`
  - `transmission`
  - `drive`
  - `size`, `type`, `paint_color`
  - `state`, `region`, `lat`, `long`
- **Rows**: Thousands of entries from across the U.S.

> Note: This dataset may not reflect real-time listings and is best used for analytical and learning purposes.

---

## 📊 Objectives of the Analysis

- Understand the distribution of used car prices.
- Examine the most common car manufacturers and models.
- Analyze the relationship between mileage, year, and price.
- Explore geographical trends using latitude and longitude.
- Identify common features of cars in different conditions (e.g., new, good, fair).
- Detect potential outliers or inconsistencies in the dataset.

---

## 🧪 Techniques Used

- Data Cleaning (handling nulls, duplicates, inconsistent entries)
- Feature Engineering (creating new variables such as car age)
- Data Visualization (histograms, box plots, scatter plots, heatmaps, maps)
- Statistical Analysis (descriptive statistics, correlations)

### 📚 Libraries Used

```python
pandas  
numpy  
matplotlib  
seaborn  
plotly (optional for interactive maps)
```

---

## 📈 Key Insights

- Cars from certain manufacturers like Toyota, Ford, and Chevrolet dominate the listings.
- Newer cars predictably tend to cost more, but outliers exist in luxury or collectible categories.
- High mileage significantly decreases price, especially in cars older than 10 years.
- States like California, Texas, and Florida show the highest number of listings.
- Transmission type and title status also play a role in pricing variability.

---

## 📁 Repository Structure

```
Used-Car-Analysis/
│
├── data/                    # Contains the original dataset
├── notebooks/               # Jupyter notebooks for EDA
├── images/                  # Plots and visuals
├── Used_Car_Analysis.ipynb  # Main notebook with analysis
└── README.md                # Project documentation
```

---

## 🚀 Future Improvements

- Build a price prediction model using regression.
- Apply clustering techniques to group similar car listings.
- Deploy interactive dashboards with Streamlit or Dash.
- Enhance geospatial analysis using Folium or Plotly Maps.

---

## 📬 Contact

**Author**: Trijesh Kondapuram  
📧 [LinkedIn](https://www.linkedin.com/in/trijesh-kondapuram)  
🧠 Emerging Data Scientist 

---

## 📜 License

This project is for educational and research purposes only. The dataset is publicly available and originally sourced from Craigslist using a custom scraper.
