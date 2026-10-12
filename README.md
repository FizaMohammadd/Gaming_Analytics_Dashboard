# 🎮 Gaming Analytics Dashboard Using Excel

---

**💡 Project Focus:** Excel-based data analysis, gameplay engagement, transaction trends, and dashboard reporting.

## 📌 Project Overview

Gaming platforms generate data about player activity, gameplay sessions, and in-game purchases. Analyzing this data can help businesses understand player engagement, compare platform performance, monitor transactions, and identify activity that may need further investigation.

In this project, I used **Microsoft Excel** to analyze gameplay and transaction data from an Indian gaming platform. I organized the data into useful summaries and built a dashboard to compare gameplay trends across regions, platforms, and session statuses.

The main goal was to make the data easier to understand and help answer business questions through visual analysis.

## 🎯 Business Objectives

- Analyze gameplay activity across regions and over time.
- Compare session activity across Mobile, PC, and Console.
- Understand in-game purchase patterns.
- Track completed, crashed, exited-early, and incomplete sessions.
- Review sessions flagged as potentially suspicious.
- Present the findings through an Excel dashboard.

## 📂 Dataset

**Dataset:** [Indian Gaming Platform Data](https://docs.google.com/spreadsheets/d/1xi2lii3oHm7wkwm9a3x9mE9yDTL_hqAF/edit?usp=sharing)

The dataset contains 500 gameplay-session records, with fields covering players, games, platforms, regions, dates, session duration, purchases, and session outcomes.

### Key Columns

| Column | Description |
|---|---|
| Session ID | Unique identifier for a gameplay session |
| Player ID | Identifier for a player |
| Game Name | Name of the game played |
| Platform | Mobile, PC, or Console |
| Region | Region associated with the session |
| Session Date | Date of gameplay |
| Session Duration (min) | Duration of the session in minutes |
| In-Game Purchase ($) | Purchase amount associated with the session |
| Purchase Type | Type of in-game purchase |
| Session Status | Outcome of the gameplay session |
| Player Type | Free or Paid |
| Level Reached | Level reached during the session |
| Is Suspicious | Flag indicating potentially irregular activity |

## 🔄 Project Workflow

### 1️⃣ Data Understanding

Reviewed the dataset and identified the fields relevant to gameplay activity, transactions, player categories, dates, and session outcomes.

### 2️⃣ Data Preparation

Prepared the data for analysis by reviewing session identifiers, date and numeric fields, category values, and the available session and suspicious-activity flags.

### 3️⃣ Data Transformation

Worked with date-related fields and analysis columns, including Year-Month, ARPU, SuccessFlag, and Suspicious Flag, to support the required summaries.

### 4️⃣ Data Analysis

Used PivotTable summaries to compare gameplay volume, purchase activity, session outcomes, and suspicious-session flags across relevant categories.

### 5️⃣ Dashboard Development

Created an Excel dashboard with charts that bring the main findings together and make comparisons easier to understand.

## 📊 Dashboard Highlights

The dashboard contains five visualizations:

| Visualization | Purpose |
|---|---|
| Regional Gameplay Volume | Compares gameplay session counts across regions |
| Monthly Sessions & Purchases | Shows monthly trends in sessions and purchases |
| Platform Usage | Compares session distribution across Mobile, PC, and Console |
| Suspicious Sessions by Region | Compares sessions flagged as suspicious across regions |
| Session Status | Shows the distribution of session outcomes |

The workbook is organized into three sheets:

- **Dataset:** Session-level data and analysis fields.
- **Pivot Table:** Summaries used for analysis.
- **Dashboard:** Visual presentation of the key comparisons.

## 🛠️ Tools & Techniques

- Microsoft Excel
- Data preparation and transformation
- PivotTables
- Charts and dashboard design
- KPI and category-based analysis

## 🚀 How to Use

1. Clone or download this repository.
2. Open `Gaming_Dashboard.xlsx` in Microsoft Excel.
3. Visit the **Dashboard** sheet to explore the visual summaries.
4. Check the **Pivot Table** sheet to review the supporting calculations.
5. Explore the **Dataset** sheet to understand the fields used in the analysis.

## ⚠️ Limitations

- The analysis is based on 500 records and should not be generalized to the entire Indian gaming industry.
- A suspicious-activity flag indicates a record for further review; it does not independently prove fraud or bot activity.
- The project examines gameplay and transaction patterns. Player retention or fraud detection would require additional definitions and validation.

## 📁 Project File

`Gaming_Dashboard.xlsx` — Excel workbook containing the dataset, PivotTable summaries, and dashboard.

---

**Project Focus:** Excel-based data analysis, gameplay engagement, transaction trends, and dashboard reporting.
