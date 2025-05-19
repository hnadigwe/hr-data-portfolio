# 📊 HR Data Analytics Portfolio

## 📘 Overview

This project showcases exploratory data analysis (EDA) on an anonymized Human Resources (HR) dataset. The primary objective is to clean the data and have a more structured data to uncover insights related to employee demographics, departmental structure, compensation, and performance.

## 🧾 Dataset Description

- **Source**: Synthetic HR dataset with 1,000 employee records
- **Key Columns**:
  - `Name`: Employee names (anonymized)
  - `Age`: Age of employees (with some missing data)
  - `Salary`: Monthly salary
  - `Gender`: Male/Female
  - `Department`: Departmental assignment
  - `Position`: Job position/title
  - `Joining Date`: Employment start date
  - `Performance Score`: Subjective performance indicator
  - `Email` and `Phone Number`: Contact info (incomplete)

## 🔍 Exploratory Data Analysis

- Identified and addressed missing values in `Age`, `Email`, and `Phone Number`
- Standardized salary data and summarized key salary statistics
- Extracted and visualized:
  - Salary distribution
  - Department and Position frequency
  - Joining date trends
- Computed and visualized years of experience from `Joining Date`
- Highlighted top-performing departments and average salary per department

## 📁 Project Structure

| Folder           | Description                                   |
|------------------|-----------------------------------------------|
| `EDA_CSVs/`      | CSV files of summary statistics (e.g., salary stats) |
| `EDA_Plots/`     | PNG visualizations of EDA results             |
| `notebooks/`     | Jupyter notebooks with all data processing and EDA |
| `README.md`      | Project overview and documentation            |
| `LICENSE`        | MIT License for usage and distribution        |

## 💡 Key Insights

- **Salary Range**: ₦50,000 – ₦70,000 with a mean of ₦60,216
- **Most Common Roles**: Clerk, Assistant, Director
- **Experience**: Many employees have 5–10 years of experience
- **Department Spread**: Balanced distribution with notable trends in performance scores
- **Data Gaps**: Significant missing data in `Age`, `Phone Number`, and `Email`

## 🛠️ Tools & Libraries

- Python (Jupyter Notebooks)
- `pandas` for data cleaning and manipulation
- `matplotlib` and `seaborn` for visualizations
- `os` for file management
- `datetime` for calculating years of experience

## 🚀 How to Use

1. Clone the repository to your local machine.
2. Open and run the Jupyter notebooks in the `notebooks/` directory.
3. View saved charts and summaries in the `EDA_Plots/` and `EDA_CSVs/` folders.

```bash
git clone https://github.com/hnadigwe/hr-data-portfolio.git
cd hr-data-portfolio



## 📝 License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/hnadigwe/hr-data-portfolio/blob/main/LICENSE) file for more information..




## 📎 Related Links
-Medium Blog Post – [From Messy to Meaningful: Showcasing the Power of Data in Uncovering Hidden Patterns and Transforming HR Insights](https://medium.com/@helennellieadigwe/from-messy-to-meaningful-showcasing-the-power-of-data-in-uncovering-hidden-patterns-and-9134c73d77bb) 


-GitHub Repository – [hr-data-portfolio](https://github.com/hnadigwe/hr-data-portfolio)



## 📎 Appendix A – Glossary of Terms
## Term	Description
### EDA	Exploratory Data Analysis – understanding and visualizing data
### pandas	Python library for data manipulation and analysis
### matplotlib	Python library for plotting and data visualization
### Joining Date	The date an employee was officially hired
### Performance Score	A qualitative rating of employee performance
### Years of Experience	Difference between current date and joining date
### Missing Data	Null or empty values requiring cleanup or imputation
### Boxplot: A visualization that shows the distribution, median, and outliers in a dataset.
### Outliers: Values that are significantly different from the majority of the data.
### Categorical Data: Data that represents categories or labels (e.g., Gender, Department).
### Null Values: Missing entries in the dataset.
### Code Repository: A link to the GitHub repository containing the code used for the analysis.
### Data Dictionary: A detailed description of the variables and data used in the analysis.
