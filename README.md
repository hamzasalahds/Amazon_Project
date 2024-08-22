# Amazon FC - Employee Performance System
Powerpoint for the project can be seen [**here**](https://1drv.ms/p/s!Aon19ecNhTKCgb531Ekf0iWr290kDg?e=vcABXb).

## Objective
The primary objective of the project was to develop a system capable of analyzing performance to aid the OPS team in tracking and improving employee performance and productivity.

## Overview of the System
- **About the system**: 
  - An Excel workbook with integrated formulas, macros, and automation features. It refreshes on demand, providing several resources in a single location and allowing data to be searchable.
  - Helps managers make instant business decisions using a dashboard showing various metrics and KPIs.

- **Data Generation**:
  - The system generates data used to create employee performance reports.
  - Identifies areas for improvement, such as training processes and technology.

## System Creation Process
1. **Identified Stakeholders**:
   - The Ops Team, which included 10 people as end users.

2. **Created a Statement of Requirements**:
   - **User Interface**: Dashboard with customizable views and reports based on user roles and preferences.
   - **Performance Analysis**: Automated calculations of metrics such as productivity, efficiency, and goal attainment.
   - **Reporting**: Required specific reports and dashboards to visualize performance trends and identify areas for improvement.

3. **Designed the System**:
   - Structure of the Excel system, including worksheets and tables.
   - User-friendly interfaces using Excel's features like buttons and dropdown lists.
   - Calculations, formulas, functions, and macros for automation and analysis.

4. **Implementation**:
   - Imported data into the system.
   - Automated formulas and macros for calculations.
   - Provided training documentation for users.

## Technical Skills
- Utilized Microsoft Office Tools such as Excel.
- Implemented charts, dashboards, calculations, functions, and lookup methods.
- Enhanced project development using Amazon’s internal wiki and learning materials.

## Project Steps
- Identified metrics for KPIs.
- Imported employee CSV data sheets.
- Cleaned data using Power Query.
- Created sheets using LOOKUP formulas.
- Developed formulas for calculations using `SUMIFS`, `AVERAGE`, `COUNTS`, and `VLOOKUPS`.
- Created a dashboard with relevant metrics.

## Data Collection and Preparation
- **Primary Data Sources**: CSV files from various internal sources.
- **Data Cleaning**:
  - Imported CSV files into Excel using Power Query.
  - Identified and corrected inconsistencies, missing values, and formatting issues.
  - Standardized text fields for analysis.

### **Challenges with Data**:
- Data needed transformations for use in formulas.
- Lack of summarizations.
- Extra columns.

## Employee Analysis
- **Headcount Trends & Forecasts**:
  - Compared planned headcount with digital and actual headcounts.
  - Used linear regression in Excel for forecasting hourly headcount.
  - ```=COUNTIF('AA H.Rate'!H7:H3828, "<>0")```
  - Forecasts: ```=IF(B5=0,NA(),FORECAST.ETS(A6,B4:B5,A4:A5))```
 
  ![image](https://github.com/user-attachments/assets/c567ea5b-37fe-45e7-83a1-05b90900c30e)

- **Employee Rates**:
  - Tracked individual and group employee rates.
  - Used lookup functions and conditional formatting to highlight high and low rates.
 
  ![image](https://github.com/user-attachments/assets/23af2224-b798-46ab-9bf7-08b1a7df8c8e)

- **Work Details**:
  - Created a comprehensive repository of employee work details using VLOOKUP.
  - Displayed task durations and total hours worked.
  - Used graphs for visual representation.
  - ``=IFERROR(VLOOKUP(E4,'2100'!D:J,5,FALSE),0)``
 
![image](https://github.com/user-attachments/assets/30a65191-a0ec-4977-a79f-a0941ecf80dd)

## Other Metrics
- Work Piles
- Successful diverts and forecasts
- Number of errors made
- Safety Reports
- Daily Volume Percentage of Goal Achieved/Remaining

## Challenges & Solutions
- **Challenges**:
  - Performance issues and complexity of charts.
- **Solutions**:
  - Avoided volatile functions to improve speed.
  - Improved dashboard aesthetics with colors and dynamic filtering.
  - Diversified visualizations and added explanatory text for non-technical users.

## Proposed Training Initiatives
- Collaborated with senior management for targeted training of 50 employees.
- Used the employee system to track performance and identify struggling employees.
- Conducted surveys to enhance job satisfaction and training needs.
- Streamlined workflows with updated documentation and problem-solving techniques.

## Impact
- **Results**:
  - Achieved a 10% improvement in sorting efficiency.
  - Provided valuable insights for strategic decision-making.

## Summary
Implementing targeted training initiatives alongside our Excel-based performance tracking system resulted in significant improvements in sorting efficiency and productivity in our 300+ employee department, leading to a 10% performance increase and the processing of over 262,000 items.

## Evaluation
The system underwent iterations and improvements, including color adjustments for visibility and the addition of new metrics like safety reports.






