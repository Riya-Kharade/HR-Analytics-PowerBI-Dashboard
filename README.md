# HR Analytics and Employee Attrition Analysis Dashboard

An interactive HR Analytics project developed using **Python and Microsoft Power BI** to analyze employee data, identify attrition patterns, and understand workforce trends through data visualization.

## Project Overview

This project uses the IBM HR Analytics Employee Attrition dataset, containing **1,470 employee records and 35 attributes**.

Python is used for dataset loading, inspection, preprocessing, and Exploratory Data Analysis (EDA). Microsoft Power BI is used for data transformation, DAX-based KPI calculations, and interactive dashboard development.

The project consists of five dashboard pages that provide insights into employee demographics, attrition, salary, performance, satisfaction, and career development.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Data analysis and preprocessing |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Microsoft Power BI | Interactive dashboards |
| Power Query | Data cleaning and transformation |
| DAX | KPI calculations and measures |

## Dataset Information

- **Dataset:** IBM HR Analytics Employee Attrition
- **Total Records:** 1,470
- **Total Attributes:** 35
- **Target Column:** Attrition

The dataset contains employee information related to demographics, department, job role, salary, performance, satisfaction, work-life balance, and attrition.

## Project Workflow

1. Dataset collection and understanding.
2. Dataset loading using Python.
3. Data inspection and preprocessing.
4. Exploratory Data Analysis using Python.
5. Data cleaning and transformation using Power Query.
6. KPI calculation using DAX.
7. Development of interactive Power BI dashboards.
8. Dashboard testing and validation.

## Dashboard Pages

### 1. Overview Dashboard

Provides a summary of employee information through KPI cards and visualizations.

- Total Employees
- Employees Left
- Attrition Rate
- Average Salary
- Average Age
- Average Tenure
- Employee distribution by department, gender, education field, age group, job role, and marital status.

### 2. Attrition Analysis Dashboard

Analyzes employee departures across different categories.

- Attrition by Department
- Attrition by Gender
- Attrition by Education Field
- Attrition by Age Group
- Attrition by Job Role
- Attrition by Marital Status

### 3. Performance and Compensation Dashboard

Focuses on employee salary and performance.

- Average Salary
- Average Salary Hike
- Average Performance Rating
- Average Job Satisfaction
- Salary by Department and Job Role
- Employee departures by Department and Job Role
- Average Tenure by Department

### 4. Workforce and Employee Insights Dashboard

Explores employee demographics and workplace conditions.

- Employee distribution by Age Group
- Gender Distribution
- Marital Status Distribution
- Overtime and Attrition
- Average Work-Life Balance by Department
- Employees by Business Travel

### 5. Career Growth and Employee Development Dashboard

Analyzes employee development and satisfaction.

- Average Relationship Satisfaction
- Average Job Satisfaction
- Average Environment Satisfaction
- Average Work-Life Balance
- Employees Working Overtime
- Average Training Sessions
- Employee Tenure Groups
- Years Since Last Promotion

## Key Performance Indicators (KPIs)

| KPI | Result |
|---|---:|
| Total Employees | 1,470 |
| Employees Left | 237 |
| Attrition Rate | 16.12% |
| Average Salary | 6.50K |
| Average Age | 36.92 |
| Average Tenure | 7.01 |
| Average Job Satisfaction | 2.73 |
| Average Work-Life Balance | 2.76 |
| Average Performance Rating | 3.15 |
| Average Salary Hike | 15.21 |

## Repository Structure

```text
HR-Analytics-Employee-Attrition-Dashboard/
│
├── Python/
│   └── HR_Analytics_EDA.ipynb
│
├── PowerBI/
│   └── HR_ANALYSIS.pbix
│
├── Dataset/
│   └── README.md
│
├── Screenshots/
│   ├── Overview_Dashboard.png
│   ├── Attrition_Analysis.png
│   ├── Performance_Compensation.png
│   ├── Workforce_Insights.png
│   └── Career_Growth.png
│
├── Documentation/
│   └── HR_Analytics_Project_Report.pdf
│
├── README.md
└── LICENSE
```

## How to Run the Project

### Python Analysis

1. Clone or download this repository.
2. Open the `Python` folder.
3. Open the Jupyter Notebook in Jupyter Notebook or Google Colab.
4. Download the dataset from the source mentioned in the Dataset folder.
5. Update the dataset file path if required.
6. Run the notebook cells to perform data analysis.

### Power BI Dashboard

1. Install Microsoft Power BI Desktop.
2. Open the `HR_ANALYSIS.pbix` file from the `PowerBI` folder.
3. If required, update the dataset source path.
4. Refresh the data.
5. Explore all five dashboard pages using interactive slicers and filters.

## Key Results

- Analyzed 1,470 employee records.
- Identified 237 employees who left the organization.
- Calculated an overall attrition rate of 16.12%.
- Examined workforce distribution across departments and job roles.
- Analyzed salary, performance, and employee satisfaction.
- Developed five interactive Power BI dashboard pages.

## Future Scope

- Implement machine learning models for employee attrition prediction.
- Integrate regularly updated HR datasets.
- Add more advanced HR analytics and visualizations.
- Develop automated HR reporting.
- Explore cloud-based dashboard hosting.

## Author

**Riya Kharade**

- GitHub: [Riya-Kharade](https://github.com/Riya-Kharade)
- Portfolio: [Visit Portfolio](https://riyakharade-portfolio.netlify.app/)

---

**Project Domain:** Data Analytics | HR Analytics | Business Intelligence

**Tools:** Python | Microsoft Power BI

*Developed as an academic project.*
