# 🇨🇦 Femicide in Canada

This project explores femicide trends in Canada and globally using cleaned homicide data and data visualizations. It is part of Milestone 2 for the BSAD 482 – Decision Intelligence course at St. Francis Xavier University.

The visualizations were created using Tableau, based on data from various international and national sources.

---

## 🗂️ Repository Structure

| Folder/File         | Description                                                  |
|---------------------|--------------------------------------------------------------|
| `/data/`            | Raw and cleaned dataset used for analysis                    |
| `/visualizations/`  | PNG exports of charts created in Tableau                     |
| `/src/`             | Wrangling steps and optional code logic                      |
| `Milestone2.pdf`    | Full milestone write-up and narrative                        |
| `README.md`         | This file                                                    |

---

## 📊 Visualizations

### Insight 1 – Femicide Trends by Region and Year
![Insight 1](visualizations/Insight%201.png)

### Insight 2 – Regional Comparison (Stacked Bars)
![Insight 2a](visualizations/Insight%202a.png)

### Insight 3 – Bubble Chart of Global Femicide Counts
![Insight 3](visualizations/Insight%203.png)

### Insight 4 – Country-Level Breakdown (Canada Highlighted)
![Insight 4](visualizations/Insight%204.png)

> For interpretation and commentary, see [Milestone2.pdf](Milestone2.pdf)

---

## 🧹 Data Wrangling (in `/src/`)

The dataset was cleaned using Tableau Prep and Excel.

Key steps included:
- Filtering records by gender (Female)
- Grouping by region and year
- Removing nulls and standardizing region names
- Creating calculated fields for trend analysis

See: [`wrangling.md`](src/wrangling.md)

---

## 🔧 Tools Used

- Tableau (for visualization)
- Excel (for initial cleaning)
- GitHub (for version control and submission)
