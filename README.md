# Real-Estate-Project

A data-driven exploration of residential property trends in Belmont North (NSW) using Python, Pandas, and Folium. This notebook analyzes pricing, land size, bedrooms, bathrooms, and other property attributes from a real-estate API sandbox to uncover insights about the suburb’s housing market.
🔍 Key Features
	•	Data Cleaning & Preparation – Normalized nested JSON from API responses into a flat Pandas DataFrame.
	•	Exploratory Data Analysis (EDA) – Summary statistics, price distribution, correlation checks, and trend visualization.
	•	Interactive Charts – Histograms, scatterplots, and regression plots built with Seaborn and Matplotlib.
	•	Geospatial Visualization – Folium map showing each property’s location, price, and features.
	•	Market Insights – Derived metrics such as average price per bedroom and land price per m².

🧰 Tech Stack
	•	Python 3 | Pandas | NumPy | Matplotlib | Seaborn | Folium | Jupyter Notebook

📊 Insights Summary
	•	Average property price ≈ $1.23 M
	•	Median price ≈ $1.15 M
	•	Market composition ≈ 78 % Houses / 22 % Units
	•	Moderate price variance (Std ≈ $411 K) → diverse housing stock
	•	Interactive map visualizes Belmont North’s property distribution and value clusters

🚀 How to Use
	1.	Clone the repo
	2.	Install dependencies from requirements.txt
	3.	Run project.ipynb to reproduce the full analysis
	4.	Open belmont_map.html to explore the interactive property map

