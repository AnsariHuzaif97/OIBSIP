# 🏡 Airbnb NYC 2019 Data Analysis

This project explores and analyzes the Airbnb listings dataset from New York City (2019) to identify insights, clean data, and prepare it for machine learning modeling. It includes comprehensive data preprocessing, outlier detection, and visual analysis to understand the behavior of features and relationships.

# 📁 Dataset Description

The dataset contains information about Airbnb listings in NYC, with over 48,000 entries and the following key features:

name, host_name, neighbourhood_group, neighbourhood

latitude, longitude, room_type, price

minimum_nights, number_of_reviews, reviews_per_month

availability_365, and more

# 🛠️ Project Workflow

# 1. Loading & Initial Exploration

Reading CSV and inspecting structure.

Understanding column types and null values.

# 2. Data Cleaning

Handling missing values (reviews_per_month, last_review).

Removing irrelevant or duplicate entries.

Type conversions where necessary.

# 3. Outlier Detection & Handling

Using IQR method to detect outliers in numerical columns like price, minimum_nights, etc.

Created outlier_<column> flags for transparency.

Compared results before and after cleaning.

# 4. Data Visualization

Histograms, and Heatmaps to show:

Distribution of key features

Outlier spread

Correlation between variables (before and after cleaning)

# 5. Insights and Conclusions

Identified high-price outliers affecting price distribution.

Strong correlation observed between reviews and availability.

Location-based analysis reveals key pricing zones.

# 📊 Key Visuals

Distribution plots of prices

Heatmaps of correlation before vs. after outlier removal

Bar plots of room types and their average pricing

# 💡 Potential Extensions

Build regression models to predict Airbnb prices.

Cluster listings by location and price.

Time-series analysis on review dates (if timestamp cleaned).

Geo-spatial mapping of listings using folium.

# 🔧 Technologies Used
Python (Pandas, NumPy, Matplotlib, Seaborn, SciPy)

Jupyter Notebook

CSV Dataset (Kaggle)

# 📂 How to Run

# 1. Clone the repo or download files
# 2. Install dependencies

pip install pandas numpy matplotlib seaborn

# 3. Run the notebook

jupyter notebook file_name.ipynb

📌 Author

MD HUZAIFA ANSARI
(https://www.linkedin.com/in/huzaifa-ansari-830988148) | (https://github.com/AnsariHuzaif97)


