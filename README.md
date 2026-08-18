# HeathCare-Dashboard

An interactive **Healthcare Analytics Dashboard built with Microsoft Power BI** using an Excel healthcare dataset.

The project focuses on analyzing patient records, admission and discharge dates, billing amounts, health insurance amounts and other healthcare-related attributes.

 📊 Project Overview

Healthcare data can become difficult to understand when it is stored only as rows and columns in an Excel file. This project converts the raw dataset into an interactive Power BI dashboard so that important trends and metrics can be explored visually.

 Main analysis areas

- 👤 Patient analysis using **Patient ID**
- 📅 Admission date analysis
- 🏥 Discharge date analysis
- 💰 Billing amount analysis
- 🛡️ Health insurance amount analysis
- 🩺 Diagnosis analysis
- 👨‍⚕️ Doctor-wise analysis
- 🛏️ Bed occupancy analysis
- ⭐ Feedback analysis
- 🔄 Follow-up date analysis

🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Microsoft Excel**
- **DAX** for calculations/measures where required
- **GitHub** for project hosting and documentation

 📁 Dataset

The source data is stored in an Excel file and contains healthcare-related fields such as:

| Column | Description |
|---|---|
| `Patient_ID` | Patient identifier |
| `Admit_Date` | Admission date |
| `Discharge_Date` | Discharge date |
| `Billing Amount` | Billing/healthcare amount |
| `Health Insurance Amount` | Insurance-related amount |
| `Diagnosis` | Diagnosis category |
| `Doctor` | Doctor information |
| `Bed_Occupancy` | Bed occupancy information |
| `Feedback` | Patient feedback |
| `Followup Date` | Follow-up date |
| `Test` | Test-related information |

 📈 Dashboard Features

 KPI / Card Analysis
Summary values can be displayed using Power BI Card visuals, such as:

- Total Patients
- Total Billing Amount
- Total Health Insurance Amount
- Average Billing Amount
- Other calculated KPIs

 Date Analysis

The `Admit_Date` field can be analyzed through the Power BI date hierarchy:

Year → Quarter → Month → Day**

This allows users to explore admission trends at different time levels.

Interactive Filtering

The dashboard supports interactive filtering through Power BI filters and visual interactions.

Users can focus the analysis on selected:

- Years
- Quarters
- Months
- Patients
- Diagnoses
- Doctors
- Other available categories

🧠 Key Insights

The dashboard helps users understand:

1. How patient records are distributed.
2. How admissions change over time.
3. How billing amounts vary across healthcare records.
4. The relationship between billing and insurance-related amounts.
5. Which diagnosis categories occur more frequently.
6. Doctor-wise and occupancy-related patterns.
7. Feedback and follow-up activity.

> **Note:** Actual insights depend on the values present in the supplied dataset.




 🚀 How to Use

1. Download or clone this repository.
2. Open `Healthcare_Analytics_Dashboard.pbix` using **Microsoft Power BI Desktop**.
3. If Power BI asks for the Excel source, update the data source path to `Healthcare_Data.xlsx`.
4. Refresh the dataset.
5. Use the dashboard filters and visuals to explore the data.

 🔐 Data Privacy

This project is intended for **educational, portfolio and demonstration purposes**.

If real patient information is ever used, personally identifiable or sensitive healthcare information should be removed/anonymized and handled according to applicable privacy and security requirements.

 🎯 Learning Outcomes

Through this project, the following practical skills are demonstrated:

- Data cleaning and preparation
- Excel data analysis
- Power BI dashboard development
- Data visualization
- Date hierarchy analysis
- KPI and card creation
- Filtering and interactive reporting
- Basic data modeling
- Business intelligence concepts
- GitHub project documentation

 🔮 Future Improvements

- Add patient length-of-stay analysis.
- Add advanced DAX KPIs.
- Add diagnosis and doctor drill-down pages.
- Add billing and insurance trend analysis.
- Add Power BI drill-through functionality.
- Connect the dashboard to a live database/cloud source.
- Implement automated data refresh.
- Add appropriate privacy and access controls for real-world healthcare use.

👩‍💻 Author

**Divyanshi Rajput**

Computer Science / Artificial Intelligence student

