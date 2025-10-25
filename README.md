## Crop Recommendation System – EDA, Visualization & Multivariate Analysis

This project focuses on performing **Exploratory Data Analysis (EDA)**, insightful **visualizations**, and **multivariate analysis** to explore the relationships between environmental factors and crop types. The goal is to understand how variables such as temperature, humidity, pH, rainfall, and soil nutrients (N, P, K) interact and influence crop suitability — forming a solid foundation for a future crop recommendation model.


## Project Description

Agricultural decision-making can benefit greatly from data-driven insights. This project analyzes a crop dataset to uncover hidden patterns and relationships between climate, soil conditions, and crop types. Through **univariate**, **bivariate**, and **multivariate** analysis, we aim to gain a holistic understanding of the data and prepare for building an effective recommendation system.

## Objectives

- Load and explore the crop dataset.
- Clean and preprocess data for analysis.
- Perform univariate analysis (distributions of individual features).
- Conduct bivariate and **multivariate analysis** to explore inter-feature relationships.
- Visualize crop-specific environmental needs using boxplots and scatter plots.
- Summarize insights to support model development and decision-making.


## Key Findings

### Univariate & Bivariate Analysis

- **Nutrients (N, P, K)**: Most crops prefer moderate levels. Potassium shows a right-skewed distribution with an unusual spike at high values.
- **Temperature**: Normally distributed, peaking around **24–28°C**, ideal for many tropical crops.
- **Humidity**: Bimodal, suggesting crops span both arid and humid climate zones.
- **pH**: Most crops favor a **slightly acidic to neutral** range (pH 6–6.5).
- **Rainfall**: Varies widely, supporting diverse crop types.

### Multivariate Analysis

- Explored the combined impact of **rainfall and humidity** on different crop types.
- Identified **distinct clusters of crops** that share similar climate needs.
- Found that some crops (e.g., **rice, jute, coconut**) thrive in both **high rainfall and high humidity**, while others (e.g., **grapes, kidneybeans**) are more suited to **drier conditions**.
- Multivariate patterns help identify **climate-based crop groupings**, which are useful for regional recommendations.

### Temperature Distribution by Crop

- Most crops fall in the **20–30°C** range.
- **Mango, papaya, orange** tolerate higher temperatures, while **apple, chickpea, kidneybeans** prefer cooler climates.

### Rainfall vs. Humidity by Crop Type

- Clear clustering observed:
  - **High humidity + high rainfall**: Rice, jute, mungbean
  - **Moderate conditions**: Maize, mango, pigeonpeas
  - **Low humidity**: Grapes, kidneybeans
  - **Moderate zones**: Apple, coffee, orange


## Tech Stack

- **Python**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Visualization
- **Jupyter Notebook** – Interactive analysis


