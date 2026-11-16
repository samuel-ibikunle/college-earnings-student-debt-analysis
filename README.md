# College Earnings and Student Debt Analysis

## Overview

This project uses Python to compare long-term earnings and student debt across U.S. bachelor’s-degree institutions.

The analysis focuses on three college types:

- Public
- Private nonprofit
- Private for-profit

The main question is:

**Which college type offers the strongest long-term earnings relative to student debt?**

## Tools

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Analysis Process

The project follows a six-step data analysis process:

1. Define the problem
2. Collect the data
3. Clean the data
4. Analyze the data
5. Visualize the results
6. Interpret and make decisions

The analysis compares:

- Median student debt at graduation
- Median earnings 10 years later
- Median debt-to-earnings ratio
- Percentage differences between college types
- Debt-to-earnings quartiles

## Dataset

The dataset contains institution-level information on U.S. colleges, including degree level, institution type, student debt, and long-term earnings.

The analysis was filtered to bachelor’s-degree institutions and records with the financial measures required for comparison.

The final dataset included **1,727 institutions**:

- **582 Public**
- **1,020 Private nonprofit**
- **125 Private for-profit**

## Key Findings

| College Type | Median Debt | Median 10-Year Earnings | Median Debt-to-Earnings Ratio |
|---|---:|---:|---:|
| Public | $21,000 | $54,664.50 | 0.383 |
| Private nonprofit | $24,994 | $54,659.50 | 0.444 |
| Private for-profit | $26,123 | $40,092 | 0.539 |

- Public institutions had the **lowest median debt-to-earnings ratio**.
- Private nonprofit institutions had similar median 10-year earnings to public institutions but higher median student debt.
- Private for-profit institutions had the highest median debt, lowest median 10-year earnings, and highest debt-to-earnings ratio.
- The private nonprofit debt-to-earnings ratio was approximately **16% higher** than the public ratio.
- The private for-profit ratio was approximately **41% higher** than the public ratio.
- Debt-to-earnings ratios also showed greater variation among private for-profit institutions.

## Conclusion

Among the bachelor’s-degree institutions analyzed, public colleges showed the strongest observed balance between long-term earnings and student debt.

## Limitations

The analysis is descriptive and shows associations, not causation.

College type alone does not determine future earnings. Outcomes may also be influenced by field of study, geographic location, student characteristics, labor-market conditions, and career choices.

The college-type groups also differ substantially in size, particularly because fewer private for-profit institutions are represented.

## Repository Files

- `college_earnings_student_debt_analysis.ipynb` — complete Python analysis
- `us_college_earnings.csv` — source dataset
- `README.md` — project documentation

## AI Assistance

ChatGPT was used as a development assistant for Python code support, project structure, and analytical interpretation. I reviewed the code, ran the analysis, evaluated the results, and determined the final conclusions presented in this project.

## Author

Samuel Ibikunle
