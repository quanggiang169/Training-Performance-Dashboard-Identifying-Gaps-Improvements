# Training Dashboard Project

## Overview
This project demonstrates the process of cleaning and preparing data using Excel and visualizing the cleaned data in a dynamic dashboard using Tableau. The dashboard focuses on analyzing training-related metrics to provide insights into training performance and effectiveness.

## Objectives
- **Track the company’s training activities over the course of a year** by creating a comprehensive dashboard that monitors training organization, schedules, and progress towards completion.
- **Analyze learner data** using key metrics such as training hours, completion rates, and demographic factors (e.g., department, age, job title), which helps in understanding how different groups are engaging with training programs.
- **Evaluate cost allocation** by assessing how the training budget is distributed across various programs and comparing it against key metrics to determine whether the investment aligns with training outcomes and organizational goals.
- **Address inefficiencies in resource allocation** by providing insights into where resources (both time and budget) are being underutilized or overinvested, helping improve future training strategies and cost-effectiveness.
  
## Analysis Scope

### 1. Training Performance
- Analyze training completion rates, including on-time vs. delayed courses.  
- Compare actual vs. planned participation to identify gaps in engagement.  

### 2. Learner Insights
- Segment learners by demographics (e.g., department, role, age) to uncover participation patterns.  
- Evaluate engagement levels and module completion to highlight learning effectiveness.  

### 3. Cost Analysis
- Compare budgeted vs. actual training costs to detect overruns.  
- Assess cost per learner and per training hour to measure efficiency. 

## Tools Used
- **Excel**:
  - Data cleaning and preprocessing.
  - Transformations and basic analytics.
- **Tableau**:
  - Dashboard creation and visualization.
  - Publishing dashboard on Tableau Public.
 
## Workflow
1. **Data Collection**  
   - Gather raw training data from internal sources.  

2. **Requirement Document Creation**  
   - Define the objectives, scope, and key metrics of the dashboard.  
   - Specify data sources, target audience, and any specific needs or constraints.  
   - Ensure alignment with business goals and stakeholder expectations.  

3. **Data Cleaning (Excel)**  
   - Remove duplicates and irrelevant columns.  
   - Handle missing data (e.g., filling, dropping).  
   - Standardize column names and data formats.  

4. **Data Analysis (Excel)**  
   - Calculate key metrics such as total hours, completion rates, and averages.  

5. **Dashboard Creation (Tableau)**  
   - Import cleaned data into Tableau.  
   - Create visualizations like bar charts, line charts, and scatter plots.  
   - Design an interactive and user-friendly dashboard layout.  

6. **Insight Generation & Reporting**  
   - Analyze dashboard outputs to identify issues such as delays, budget overruns, or low completion rates.  
   - Create a structured report highlighting key findings and areas for improvement.  
   - Propose actionable recommendations for HR and training strategy.  
  
## Dataset Description
- **Source**: Simulated training dataset with fictional employee training data, provided in an Excel file containing three sheets:
  
  - **ListofCourses**: Contains details about each training course, including the course name, trainee status, training mode, budgeted costs, and other related information.
    - Key columns:
      - `Course Name`: Name of the training course.
      - `Current Trainees`: Number of current trainees in the course.
      - `New Trainees`: Number of new trainees in the course.
      - `Training Mode`: The method of delivering the training (e.g., external, internal).
      - `Training Time`: Duration of the training.
      - `Budgeted Training Costs per Participant`: The planned cost per participant for the training.
      - `Budgeted Training Costs`: Total planned cost for the course.
      - `Course Code`: Unique identifier for each course.
      - `Status`: The current status of the course (e.g., done, learning).
      - `Required Status`: Whether the course is mandatory or non-mandatory.
      - `Training Type`: Type of training (e.g., plan, out of plan).

  - **TrainingProgress**: Tracks the progress of each training course, detailing the training content, status, actual costs, duration, and other metrics for each employee.
    - Key columns:
      - `Course Code`: Identifier linking the training progress to a specific course.
      - `Employee ID`: Unique identifier for the employee.
      - `Training Content`: The content covered in the training.
      - `Status`: The current status of the employee's training (e.g., done, learning).
      - `Start Date`: Date when the training started.
      - `End Date`: Date when the training ended.
      - `Vendor`: The external training provider (if applicable).
      - `Training Location`: Location where the training was held.
      - `Country`: Country where the training took place.
      - `Training Mode`: Method used to deliver the training (e.g., online, face-to-face).
      - `Training Time Frame`: Duration or period for completing the training.
      - `Actual Training Costs`: The actual cost incurred for the training.
      - `Start Time`: Time when the training session started.
      - `End Time`: Time when the training session ended.
      - `Duration (Hours/Days)`: Duration of the training session in hours or days.
      - `Number of Days`: Total number of days the training took.
      - `Total Duration`: Overall training duration.
      - `Delivery Method`: The method used to deliver the training (e.g., online, offline).

  - **ListofLearner**: Contains demographic and employment details of each trainee.
    - Key columns:
      - `Employee ID`: Unique identifier for each employee.
      - `Employee Type`: Type of employee (existing, new).
      - `DOB`: Date of birth of the employee.
      - `Gender`: Gender of the employee.
      - `Education`: Highest level of education completed by the employee.
      - `Management Level`: The level of management the employee belongs to.
      - `Branch`: The branch where the employee works.
      - `Dept`: The department of the employee.
      - `Job Title`: The job title of the employee.
 
## Key Insights
- **Training Progress Dashboard**: 
  - A significant delay in course completion began in late Q2 due to a sudden increase in the number of courses scheduled during this period compared to the first four months. This overload affected the overall completion rate and training effectiveness.

- **Cost Dashboard**: 
  - The cost overrun rate reached 51%, with actual expenses amounting to 7,164M, exceeding the budgeted 4,742M.
  - 29% of courses (39 courses) surpassed their budgets, with planned courses contributing 2,047M to the overrun and unplanned courses adding 356M.
  - Unplanned courses in office areas accounted for 61% of the cost overrun within this category, highlighting the need for better budget flexibility and foresight for office-based training activities.

## How to View the Dashboard
1. Visit the [Tableau Public](https://github.com/quanggiang169/Analytics-Arsenal/blob/main/Dashboard/Training%20Dashboard%20(Excel%2BTableau)/Training%20Dashboard.twbx) to access the dashboard.
2. Use filters to explore specific training metrics by department, training type, or date range.

## Files Included
- `Training original data.xlsx`: Original raw dataset.
- `Training cleanned data.xlsx`: Dataset after cleaning and preprocessing.
- `Training Dashboard.twbx`: Tableau dashboard file.
- `Dashboard Requirements Document.pdf`: Document outlining the requirements for the dashboard.
- `Dashboard Screenshot.pdf`: Screenshots of the dashboards.
- `Training Report.pdf`: Insights of the dashboards
- `README.md`: This documentation file.

## Contact
For any questions or feedback, feel free to reach out to:
- **Name**: Quang Giang
- **Email**: lequanggiang.hrm@gmail.com
- **LinkedIn**: [Lê Quang Giảng](https://www.linkedin.com/in/quang-giang/)
