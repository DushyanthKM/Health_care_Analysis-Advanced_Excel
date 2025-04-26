# Healthcare Data Analysis & Insights

## ❓ Problem Statement
Built a dynamic dashboard to analyze healthcare data to extract actionable insights that could help improve patient care and healthcare resource management. By working with multiple datasets, I utilized various Excel techniques to clean, transform, and analyze the data to uncover meaningful patterns.

## Project Overview
I have focused on analyzing healthcare data, such as patient health profiles, medical histories, and healthcare costs. The insights gained from this analysis are intended to assist healthcare stakeholders in making informed decisions regarding patient care and resource allocation.

## 📊 Data Understanding
The dataset includes the following key attributes:
- **Patient Health Profile**: BMI, Blood Sugar Levels, Smoking Status
- **Medical History**: Heart Issues, Transplants, Cancer History, Number of Major Surgeries
- **Healthcare Costs**: Hospital Charges, Hospital Tier, City Tier
- **Demographics**: Age, State ID

## ⚙️ Technology Stack
- **ETL Process in Excel**: Data preprocessing using formulas and functions
- **Pivot Tables:** Data aggregation and summarization
- **Data Visualization:** Charts, slicers, and dashboards

## 🏗️ Methodology
1. **Data Cleaning & Preparation**
   - Removed duplicates and unnecessary columns.
   - Standardized data format using text functions - TRIM , SEARCH , LENGTH , PROPER  
   - Bucketing(using NESTIF) - Categorized BMI into Underweight, Healthy, Overweight, and Obese.
   - Bucketing(using NESTIF) - Classified blood sugar levels as Normal, Pre-Diabetic, and Diabetic.
   - Performed EDA to unlock key metrics of the dataset using logical and conditional formulas i.e, `AVERAGEIF`,  `COUNTIF`, `SUMIF`, for aggregation
   - Utilized Vlookup for joining multiple sheets and transfered the cleaned data into a new sheet using paste-values.
   - Created Pivot Tables to generate key insights.
  
2. **Dashboard Creation**
   - Designed an **interactive Excel dashboard**.
   - Used dynamic charts and slicers for filtering insights.
   - Visualized trends in BMI, Blood Sugar, and Hospital Charges.

3. **📈 Data Analysis & Key Insights Generated**
   - **Smoking and Cancer Risk:** Non-smokers had a higher cancer history, suggesting that other factors contribute to cancer risk.
   - **Obesity & Cancer Correlation:** Overweight and obese patients showed a higher incidence of cancer.
   - **Obesity & Hospital Costs:** Obese patients incurred higher hospital charges, even with normal blood sugar levels.
   - **Region-Wise Costs:** Tier 2 hospitals had the highest charges, potentially due to limited healthcare infrastructure.
   - **Age & Cost Relaionship:** Hospital charges increased with age, with a sharp rise after 60.

## 🔹Conclusion
This analysis highlights the importance of maintaining a healthy weight and blood sugar levels to prevent cancer and reduce healthcare costs. Additionally, Tier 2 cities should focus on improving healthcare infrastructure and awareness to minimize hospital charges.

## 🚀 Getting Started
1. Download the dataset and open in Excel.
2. Follow the data cleaning and transformation steps.
3. Use Pivot Tables to analyze key metrics.
4. Build the dashboard using slicers and charts.

## 🤝 Contributing
💡 Open for feedback & collaborations! Feel free to suggest improvements and contribute to this project.

## 👨‍💻 Author & 📌 Contact
**Dushyanth KM** 🔗 [LinkedIn](https://www.linkedin.com/in/dushyanth-km-666660260/)

## 📢 About
This project showcases how **Advanced Excel techniques** can be leveraged for effective healthcare data analytics and visualization.
