# HR Attrition Analysis

This project analyzes employee attrition using HR data, with visual insights provided through an interactive Power BI dashboard. The analysis helps identify attrition trends across departments, age groups, and education levels.

---

## Tools Used

- **Microsoft Power BI**  
  For building interactive dashboards and visualizing attrition trends and patterns.

- **Microsoft Excel**  
  Used for initial data cleaning, preparation, and exploration.

- **Bash Scripting**  
  For summarizing and reporting key findings in a command-line friendly format.

- **CSV Data Files**  
  The raw HR data is stored in CSV format for easy manipulation and analysis.

---

## Dashboard Overview

The main findings and visuals are presented in the [Power BI dashboard PDF](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/62445056/0c54cb07-4c8b-4551-982d-e7761ed8eb11/hr_analysis_powerbi_report.pdf), which includes:

- **Key Metrics:**  
  - Total Employees: 1,470  
  - Active Employees: 1,233  
  - Attrition (Ex-Employees): 237  
  - Average Age: 37

- **Attrition by Department:**  
  - R&D: 133 (56.12%)  
  - Sales: 92 (38.82%)  
  - HR: 12 (5.06%)

- **Attrition by Age Band:**  
  - 25–34: 454  
  - 35–44: 220  
  - 45–54: 112  
  - Under 25: 38  
  - Over 55: 51

- **Job Satisfaction by Age Band:**  
  - 25–34: 554  
  - 35–44: 505  
  - 45–54: 245  
  - Under 25: 97  
  - Over 55: 69

- **Education Levels:**  
  - Associates Degree  
  - Bachelor’s Degree  
  - Doctoral Degree  
  - High School  
  - Master’s Degree

- **Interactive Filters:**  
  The dashboard allows filtering by education, department, and age to explore specific groups in more detail.

---

## Data Sources

- [hrdata.csv](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/62445056/c2859a1a-9bff-40e7-bca4-935a52180f26/hrdata.csv): Raw HR dataset including employee demographics, job roles, education, and attrition status.
- [hr_analysis_powerbi_report.pdf](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/62445056/0c54cb07-4c8b-4551-982d-e7761ed8eb11/hr_analysis_powerbi_report.pdf): Power BI dashboard with summary charts and interactive visuals.

---

## Summary of Findings

- **Attrition is highest in the R&D and Sales departments, especially among employees aged 25–44.**
- **All education levels experience attrition, indicating it is a multifactorial issue.**
- **Job satisfaction varies by age band but is not the sole predictor of attrition.**

---

## How to Use

1. Open the Power BI dashboard PDF for interactive visual insights.
2. Use the CSV data for your own analysis or to extend the findings.
3. Refer to the Bash script (see `/scripts/` if available) for quick command-line summaries.

---

## License

This project is intended for educational and analytical purposes.
