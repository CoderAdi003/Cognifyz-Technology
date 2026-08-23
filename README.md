# Cognifyz Technologies Internship

Exploratory Data Analysis (EDA) project completed as part of the Data Science Internship at **Cognifyz Technologies**. The project analyzes a client restaurant chain complex dataset to uncover insights around cuisines, cities, pricing, delivery, ratings, and restaurant chains, using Python for data manipulation, visualization, and basic geospatial mapping.

## 📁 Project Structure

| File | Description |
|---|---|
| `Level_1.ipynb` | Foundational EDA tasks — cuisine trends, city-wise analysis, price range distribution, and online delivery insights |
| `Level_2.ipynb` | Deeper analysis — rating distribution, cuisine combinations, geographic/heatmap visualization, and restaurant chain analysis |

## 🎯 Objectives

### Level 1
- **Top Cuisines**: Identify the top 3 most common cuisines and their market share (% of restaurants serving each)
- **City Analysis**: Find the city with the most restaurants, average rating per city, and the highest-rated city
- **Price Range Distribution**: Visualize how restaurants are distributed across price categories
- **Online Delivery**: Determine what percentage of restaurants offer online delivery and compare average ratings for restaurants with vs. without it

### Level 2
- **Restaurant Ratings**: Analyze the distribution of aggregate ratings and average votes received
- **Cuisine Combinations**: Identify cuisine combinations associated with the highest ratings
- **Geographic Analysis**: Plot restaurant locations on a map and visualize density clusters using a heatmap
- **Restaurant Chains**: Detect restaurant chains (multiple outlets), and compare their ratings and popularity (votes)

## 🛠️ Tech Stack

- **Language**: Python
- **Libraries**: `pandas`, `numpy`, `matplotlib` for data handling and visualization
- **Geospatial**: `geopandas`, `geodatasets`, `folium` (with `HeatMap` plugin) for mapping restaurant locations
- **Environment**: Google Colab (dataset loaded from Google Drive)

## 📊 Dataset

A restaurant dataset (`Dataset.csv`) containing fields such as Restaurant Name, Cuisines, City, Aggregate Rating, Votes, Price Range, Online Delivery availability, and Latitude/Longitude coordinates.

> Note: The dataset is loaded from Google Drive in the notebooks (`/content/drive/MyDrive/...`). To run these notebooks yourself, update the `path` variable to point to your local copy of the dataset.

## 🚀 How to Run

1. Clone this repository
2. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib geopandas geodatasets folium
   ```
3. Open `Level_1.ipynb` and `Level_2.ipynb` in Jupyter Notebook, JupyterLab, or Google Colab
4. Update the dataset path to your local file location
5. Run the cells sequentially

## 🔑 Key Insights

- Identified the most popular cuisines and their market share across restaurants
- Found which cities have the highest restaurant density and highest average ratings
- Showed that restaurants offering online delivery tend to have different average ratings compared to those that don't
- Mapped restaurant locations geographically and visualized areas of high restaurant density
- Surfaced top restaurant chains by outlet count, rating, and total votes

## 🙏 Acknowledgment

This project was completed as part of the **Cognifyz Technologies Internship Program**.

## 📄 License

This project is intended for educational and portfolio purposes.
