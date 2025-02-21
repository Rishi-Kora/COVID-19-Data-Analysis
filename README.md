# COVID-19-Data-Analysis
Exploratory Data Analysis - COVID-19<br>
This project analyzes COVID-19 data obtained from UCI. The following steps were performed:<br>

1. Data Loading and Initial Exploration:<br>

The dataset covid_19_clean_complete.csv was loaded into a Pandas DataFrame.<br>
Initial exploration was conducted using head(), tail(), info(), and describe() functions to understand the data structure and basic statistics.<br>

2. Data Cleaning and Preprocessing:<br>

The 'Province/State' column was removed due to a significant number of missing values (NaN).<br>
Duplicate rows were identified and removed to ensure data integrity.<br>
Numerical features were standardized using StandardScaler for better performance in potential machine learning tasks.<br>

3. Data Visualization:<br>

The trend of confirmed, death, and recovered cases over time was visualized using a line chart created with Plotly Express.<br>
The top 10 countries with the highest confirmed cases on the latest date were identified and visualized using a bar chart.<br>

4. Streamlit Dashboard<br>

The key insights and visualizations were integrated into a Streamlit dashboard for interactive exploration and data presentation. The dashboard includes:<br>
Dataset Information<br>
Summary statistics<br>
Global Trend visualization<br>
Top 10 Countries<br>

Feel free to download the code and data.
