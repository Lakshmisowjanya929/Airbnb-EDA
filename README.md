# 🏠 New York Airbnb Data Analysis & EDA

An **Exploratory Data Analysis (EDA)** project on the **New York City Airbnb dataset**. The project analyzes Airbnb listings to understand pricing, availability, room types, neighborhood trends, and other factors that influence Airbnb listings across New York City.

## 📌 Project Overview

The goal of this project is to explore and analyze Airbnb listing data from New York City and identify meaningful patterns and insights.

The analysis focuses on understanding:

* 💰 Airbnb pricing patterns
* 🏘️ Distribution of listings across neighborhoods
* 🛏️ Different room types
* ⭐ Popular areas and listings
* 📅 Availability of properties
* 📊 Relationships between different features
* 🔍 Outliers and unusual observations

## 🎯 Objectives

* Understand the structure and characteristics of the Airbnb dataset.
* Perform data cleaning and preprocessing.
* Identify missing values and duplicate records.
* Analyze Airbnb prices across different areas.
* Compare different room types.
* Identify neighborhoods with the highest number of listings.
* Analyze availability and minimum-night requirements.
* Visualize important patterns and relationships in the data.
* Extract useful insights from the dataset.

## 🛠️ Technologies & Tools

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook** – Development and analysis environment

## 📂 Dataset

The dataset contains information about Airbnb listings in New York City.

Some important features include:

| Feature               | Description                       |
| --------------------- | --------------------------------- |
| `id`                  | Unique listing ID                 |
| `name`                | Name of the Airbnb listing        |
| `host_id`             | Unique host ID                    |
| `host_name`           | Name of the host                  |
| `neighbourhood_group` | NYC borough                       |
| `neighbourhood`       | Specific neighborhood             |
| `latitude`            | Geographic latitude               |
| `longitude`           | Geographic longitude              |
| `room_type`           | Type of accommodation             |
| `price`               | Price per night                   |
| `minimum_nights`      | Minimum number of nights          |
| `number_of_reviews`   | Number of reviews                 |
| `reviews_per_month`   | Average monthly reviews           |
| `availability_365`    | Number of available days per year |

## 🔎 Exploratory Data Analysis

The following analysis was performed:

### 1. Data Understanding

* Examined the number of rows and columns.
* Checked data types.
* Generated descriptive statistics.
* Identified unique values.

### 2. Data Cleaning

* Checked for missing values.
* Handled missing data where required.
* Checked for duplicate records.
* Identified and analyzed outliers.
* Prepared the dataset for analysis.

### 3. Univariate Analysis

Analyzed individual variables such as:

* Price
* Room type
* Neighborhood
* Number of reviews
* Minimum nights
* Availability

### 4. Bivariate Analysis

Explored relationships such as:

* Price vs. Room Type
* Price vs. Neighborhood
* Reviews vs. Availability
* Minimum Nights vs. Price
* Neighborhood vs. Room Type

### 5. Data Visualization

Created visualizations using **Matplotlib** and **Seaborn**, including:

* Bar charts
* Histograms
* Box plots
* Count plots
* Scatter plots
* Heatmaps

## 📊 Key Insights

Some important insights identified from the analysis include:

* Airbnb listings are distributed unevenly across New York City boroughs.
* Different room types show significant differences in pricing.
* Some neighborhoods have considerably more Airbnb listings than others.
* Price distributions contain high-value outliers.
* Entire homes/apartments generally have higher prices than private or shared rooms.
* Availability varies significantly among listings.
* Review activity differs across neighborhoods and room types.

> **Note:** The exact insights and values depend on the dataset and analysis performed in the notebook.

## 📁 Project Structure

```text
New-York-Airbnb-EDA/
│
├── New_York_Airbnb_EDA.ipynb
├── AB_NYC_2019.csv
├── README.md
└── images/
    └── visualizations/
```

## ▶️ How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/new-york-airbnb-eda.git
```

### 2. Navigate to the project folder

```bash
cd new-york-airbnb-eda
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Open Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
New_York_Airbnb_EDA.ipynb
```

Run the notebook cells to reproduce the analysis.

## 📈 Sample Visualizations

You can add screenshots of your EDA visualizations here.

```markdown
![Price Distribution](images/price_distribution.png)

![Room Type Distribution](images/room_type.png)

![Neighborhood Analysis](images/neighborhood_analysis.png)
```

## 💡 Skills Demonstrated

This project demonstrates practical skills in:

* Python Programming
* Data Cleaning
* Exploratory Data Analysis
* Data Preprocessing
* Statistical Analysis
* Data Visualization
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook
* Data Interpretation

## 🔮 Future Improvements

Possible improvements include:

* Building a machine learning model to predict Airbnb prices.
* Creating an interactive dashboard using **Power BI** or **Tableau**.
* Using geographic maps to visualize listing locations.
* Performing advanced statistical analysis.
* Developing a price prediction model.
* Comparing Airbnb trends across different years.

## 👩‍💻 Author

**Lakshmi Sowjanya**

B.Tech – Artificial Intelligence and Data Science

### 🔗 GitHub

https://github.com/Lakshmisowjanya929



⭐ If you found this project useful, consider giving the repository a star!
