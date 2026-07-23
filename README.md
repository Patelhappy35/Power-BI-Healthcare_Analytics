# 🏥 Healthcare Data Analysis Dashboard | Power BI

## 📌 Project Overview

This project presents an interactive **Healthcare Data Analysis Dashboard** developed using **Microsoft Power BI**. The dashboard analyzes hospital and patient data to provide insights into patient admissions, medical conditions, hospital revenue, insurance providers, billing patterns, departments, and patient-level information.

The project consists of three interactive dashboard pages:

1. **Hospital Patient Analysis**
2. **Patient Details**
3. **Billing Analysis**

---

## 🎯 Project Objectives

- Analyze overall hospital and patient performance.
- Track important healthcare KPIs.
- Analyze patient distribution by medical condition.
- Identify top-performing hospitals by revenue.
- Monitor monthly patient admission trends.
- Understand insurance provider distribution.
- Analyze department-wise billing performance.
- Compare billing across medical conditions and insurance providers.
- Provide detailed patient-level information.
- Build an interactive and user-friendly Power BI dashboard.

---

## 🛠️ Tools & Technologies Used

| Tool | Purpose |
|---|---|
| Microsoft Power BI | Dashboard development and visualization |
| Power Query | Data cleaning and transformation |
| DAX | Creating calculated measures and KPIs |
| Data Modeling | Managing data relationships |
| Power BI Visuals | Interactive data visualization |

---

## 🧹 Data Cleaning & Transformation

The healthcare dataset was cleaned and transformed using **Power Query** before creating the dashboard.

- Checked data quality and column distributions.
- Corrected column data types.
- Handled negative billing values.
- Created `Billing_Amount_Fixed` for billing analysis.
- Calculated patient length of stay.
- Created age categories.
- Created billing tiers: Standard, Silver, Gold, and Platinum.
- Created stay categories based on length of stay.
- Created patient risk categories.
- Created admission year and month fields.
- Added department information based on medical conditions.
- Created summary tables for hospital, insurance, condition, and monthly analysis.

---

# 📊 Dashboard Pages

## 🏥 Page 1: Hospital Patient Analysis

The **Hospital Patient Analysis** page provides an overall summary of hospital and patient performance.

### Key KPIs

- **Total Patients:** 55.384K
- **Total Revenue:** 1.42bn
- **Average Billing:** 35.55K
- **Average Length of Stay:** 15.51 Days

### Visualizations

- **Insurance Mix:** Shows patient distribution across Cigna, Medicare, UnitedHealthcare, Blue Cross, and Aetna.
- **Top 10 Hospitals by Revenue:** Ranks the top-performing hospitals based on revenue.
- **Patients by Condition:** Compares patient counts across Arthritis, Diabetes, Hypertension, Obesity, Cancer, and Asthma.
- **Monthly Admissions:** Displays monthly patient admission patterns.

### Interactive Filters

- Admission Type
- Medical Condition
- Admission Year

![Hospital Patient Analysis](HospitalDashboard.png)

---

## 👥 Page 2: Patient Details

The **Patient Details** page provides detailed patient-level information with interactive filtering.

### Key KPIs

- Selected Patients
- Average Billing
- Average Length of Stay

### Patient Information

The detailed table includes:

- Patient Name
- Age and Age Category
- Gender
- Medical Condition
- Department
- Admission Type
- Stay Category
- Length of Stay
- Billing Amount
- Insurance Provider
- Test Results

### Interactive Filters

- Medical Condition
- Admission Type

![Patient Details](Patientdetails.png)

---

## 💰 Page 3: Billing Analysis

The **Billing Analysis** page focuses on healthcare financial performance.

### Key KPIs

- **Total Billing:** Approximately 1.42bn
- **Average Billing Amount:** 25.54K
- **Highest Billing Tier:** Gold
- **Total Departments:** 6
- **Conditions Analyzed:** 6

### Visualizations

- **Average Billing by Department:** Compares average billing across departments and billing tiers.
- **Total Billing by Medical Condition & Insurance Provider:** Compares billing across medical conditions and insurers.
- **Billing Tier Distribution:** Shows the contribution of Gold, Platinum, Silver, and Standard tiers.
- **Total Billing by Billing Tier:** Highlights the billing contribution of each tier.

### Interactive Filter

- Admission Year

![Billing Analysis](BillingAnalysis.png)

---

## 💡 Key Dashboard Insights

- The dashboard analyzes approximately **55.4K patient records**.
- Total hospital revenue is approximately **1.42 billion**.
- The average length of stay is approximately **15.51 days**.
- Patient counts are relatively balanced across the six major medical conditions.
- The insurance mix is distributed fairly evenly across five insurance providers.
- The **Gold billing tier** generates the highest total billing.
- Department-level analysis helps compare billing patterns across healthcare specialties.
- Monthly admission analysis highlights changes in patient volume throughout the year.

---

## 🎛️ Interactive Dashboard Features

Users can dynamically explore the dashboard using filters for:

- Medical Condition
- Admission Type
- Admission Year

The dashboard also includes navigation buttons for moving between report pages.

---

## 📂 Repository Structure


---

## 🚀 How to Use

1. Download the `PR_2.pbix` file.
2. Open it using Microsoft Power BI Desktop.
3. Navigate between the three dashboard pages.
4. Use slicers and filters to interact with the report.
5. Explore the visualizations to discover healthcare insights.

---

## 📚 Skills Demonstrated

- Microsoft Power BI
- Power Query
- DAX
- Data Cleaning
- Data Transformation
- Data Modeling
- Data Visualization
- Dashboard Design
- Healthcare Data Analysis
- Business Intelligence

---

## 📌 Conclusion

This project demonstrates the process of transforming raw healthcare data into an interactive and visually engaging **Power BI Dashboard**.

The three dashboard pages provide insights into **patient demographics, hospital revenue, medical conditions, insurance distribution, admission trends, patient details, and billing performance**, demonstrating practical skills in data cleaning, transformation, analysis, visualization, and dashboard development.

## 👩‍💻 Author

**HAPPY PATEL**

Aspiring Data Analyst | Power BI | SQL | Python | Excel
