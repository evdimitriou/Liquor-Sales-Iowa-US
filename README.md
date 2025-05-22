# 📊 Liquor Sales in Iowa, US — Retail Analytics & Insights

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## 🧾 Project Overview

This project explores publicly available liquor sales data from the Iowa Alcoholic Beverages Division (ABD), spanning from **2012 to 2020**, with a focused analysis between **2016 and 2019**.

As a **Business Intelligence Analyst** hypothetically contracted by ABD, the aim is to extract strategic insights from retail sales to assist in:

- Understanding local and statewide **alcohol consumption patterns**
- **Optimizing store-level performance** and marketing strategies
- Informing **regulatory audits and policy-making**
- Supporting **private vendor expansion planning** and competitive benchmarking

---

## 🎯 Objectives

The key questions addressed for the years 2016–2019 are:

1. **Which item is the most popular (by volume) in each zip code?**
2. **What is the percentage of total sales (in USD) per store?**

To answer these, we perform:

- 📦 **Data Extraction & Cleaning**: Handling missing values, fixing types, filtering by date
- 📊 **Data Analysis**: Using Python (Pandas, NumPy) and/or SQL for in-depth slicing
- 📈 **Visualization**: Communicating insights using `matplotlib`, `seaborn`, `plotly`, or BI tools like Power BI, Tableau, Looker Studio

---

## 🔁 Workflow

| Step                          | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| 1️⃣ Data Preparation           | Clean, format, and filter dataset (2016–2019)                               |
| 2️⃣ Exploratory Data Analysis | Understand distribution, correlations, and outliers                        |
| 3️⃣ Feature Engineering       | Extract `year`, aggregate sales, identify top items per zip code           |
| 4️⃣ Insight Generation        | Identify item popularity and store revenue shares                          |
| 5️⃣ Visualization & Reporting | Create informative plots and summary tables                                |

---

## 💡 Business Value of Key Questions

| Analysis Goal                             | Strategic Impact                                                                 |
|------------------------------------------|----------------------------------------------------------------------------------|
| 🔎 Most Popular Item per Zip Code         | Enables **hyper-local inventory management**, regional promotions, demand planning |
| 💰 Store Sales % Contribution             | Supports **resource allocation**, **incentive planning**, and **performance benchmarking** |

Together, these insights fuel:

- Region-specific marketing campaigns  
- Real-time price promotions  
- Smarter stocking decisions  
- Vendor negotiation strategies  
- Data-informed regulatory oversight  

---

## 📂 Dataset Fields & Context

The dataset contains over 24 fields. Here's a concise breakdown:

| Column                  | Description                                              |
|-------------------------|----------------------------------------------------------|
| `date`                  | Date of sale                                             |
| `store_number`          | Unique store ID                                          |
| `store_name`            | Retail outlet name                                       |
| `zip_code`              | Zip code for location-based segmentation                 |
| `category_name`         | Product category (e.g., Vodka, Rum)                      |
| `item_description`      | Specific product name and details                        |
| `bottles_sold`          | Number of units sold                                     |
| `sale_dollars`          | Revenue from the sale                                    |
| `state_bottle_cost`     | Wholesale cost per bottle                                |
| `state_bottle_retail`   | Retail price per bottle                                  |
| `lat`, `lon`            | Store coordinates (for geospatial analysis)              |
| `year`                  | Extracted year from the transaction date                 |

(Full schema in [columns.md](#) or see dataset reference above.)

---

## 📌 Key Insights

### 1. Most Popular Item by Zip Code (Volume-Based)

- **Zip Code 52314** stands out, with *"Juarez Gold Dss"* accounting for **40%** of top-10 zip code volume.
- **Item preferences are highly regionalized**, indicating local demand and cultural preferences.
- Strategic recommendation: **Targeted promotions** and **supply chain alignment** in top zip codes.

### 2. Most Popular Item by Revenue per Zip Code (Revenue-Based)

- High-value items differ from top-volume ones.  
- **Zip 51106** ranks high for *"Kahlua Coffee Liqueur"* by revenue—suggesting premium preference.  
- Strategic recommendation: **Upsell opportunities** and **premium positioning** in affluent regions.

### 3. Store-Level Sales % Contribution

- **Wilkie Liquors** alone contributes **20.5%** of total sales.
- The **top 5 stores generate over 60%** of revenue.
- Strategic recommendation: **Channel key resources** (e.g., marketing, inventory) to top-performing stores.

---

## 📊 Visualizations & Tools

- 📍 Pie Charts: Item sales by volume and revenue across zip codes
- 📉 Bar Charts: Store-wise revenue contributions
- 🗺️ (Optional) Geo Heatmaps: Using latitude and longitude fields
- 📈 Tool Options: `matplotlib`, `plotly`, and/or export to Tableau / Power BI dashboards

---

## 📎 License

This project is licensed under the **MIT License**. Feel free to reuse or adapt with attribution.

---

## 👤 Author

**Evangelos Dimitriou**  
Business Intelligence Analyst | Data Storyteller
📧 [vagdimi6@gmail.com]  
🔗 [LinkedIn Profile](https://linkedin.com/in/evdimitriou) · [Check out the Tableau Visuals for this!](https://public.tableau.com/app/profile/evangelos.dimitriou/viz/MappingIowasLiquorLandsape/BottlesBucksandBordersMappingIowasLiquorLandscape?publish=yes)

---


## 🙌 Contributions

Contributions, forks, or feedback are welcome! Please open an issue or submit a pull request.

