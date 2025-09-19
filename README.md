# ✈️ Airlines Data Analysis Project

## 📌 Project Objective
The objective of this project is to analyze airline data to uncover trends in passenger behavior, flight performance, delays, and other operational insights.  
The analysis covers **data cleaning, exploratory data analysis (EDA), and visualization**, providing actionable findings for airlines and travelers.

---

## 📂 Dataset
- **Source**: Airlines dataset (from Kaggle / provided in project resources).  
- **Format**: CSV files processed via Jupyter Notebook (`Airlines.ipynb`).  
- **Size**: ~300K+ rows (varies depending on dataset version).  
- **Key Columns**:
  - `Airline` — Airline name/code  
  - `Flight` — Flight number/identifier  
  - `Source` & `Destination` — Airport details  
  - `Date_of_Journey` — Travel date  
  - `Dep_Time`, `Arrival_Time` — Flight timings  
  - `Duration` — Total journey time  
  - `Route` — Flight route information  
  - `Price` — Ticket price  
  - `Additional_Info` — Other flight details  

---

## 🔄 Workflow
1. **Data Loading**: Imported dataset into pandas dataframe.  
2. **Data Cleaning**:
   - Converted date and time columns into datetime format.  
   - Handled missing values and duplicates.  
   - Standardized categorical fields like `Airline`, `Route`, and `Additional_Info`.  
3. **EDA (Exploratory Data Analysis)**:
   - Price distribution across airlines, routes, and travel classes.  
   - Correlation between duration, stops, and ticket price.  
   - Analysis of departure/arrival times and their effect on pricing.  
   - Airline-wise performance comparisons.  
4. **Visualization**:
   - Bar plots and box plots for price distribution.  
   - Heatmaps for correlation analysis.  
   - Count plots for categorical features.  
5. **Summary & Insights**:
   - Identified patterns affecting flight prices.  
   - Analyzed which airlines/routes have higher delays and costs.  
   - Derived recommendations for pricing strategy and route planning.  

---

## 🧹 Data Cleaning
- Replaced missing values in `Route` and `Additional_Info` with `"Unknown"`.  
- Removed duplicate rows.  
- Standardized text columns (stripping spaces, unifying labels).  
- Converted categorical features into numerical values where required for analysis.  

---

## 📊 Exploratory Data Analysis (EDA)
Key analyses performed:
- **Ticket Price Analysis**: Prices vary significantly across airlines, with premium airlines charging 2–3x more than budget carriers.  
- **Route Comparison**: Multi-stop flights are generally cheaper than non-stop flights but take much longer.  
- **Duration Impact**: Longer flights correlate with higher ticket prices.  
- **Time of Journey**: Evening departures showed slightly higher average ticket prices.  
- **Airline Performance**: Some airlines consistently priced higher while others positioned as low-cost carriers.  



## 🛠️ Tech Stack
- **Language**: Python  
- **Libraries**: pandas, numpy, matplotlib, seaborn  
- **Environment**: Jupyter Notebook  




