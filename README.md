# Insert the dashboard image into the README just below the title

final_readme_content = """
# 📊 Data Professional Survey Breakdown – Power BI Dashboard

![Dashboard Preview](Images/Dashboard.png)

## 📝 Project Overview

This project is a comprehensive visualization of survey data collected from data professionals worldwide. The goal was to analyze various aspects of their careers, such as job titles, salaries, programming preferences, work-life balance, and career transitions into data.

Using **Power BI**, I imported, cleaned, transformed, and visualized the data to generate meaningful insights about the data industry.

> ⚠️ **Note**: The **dataset used in this project is credited to [Alex The Analyst](https://www.youtube.com/@AlexTheAnalyst)**, who collected it via a global survey. All transformations, visualizations, and analysis presented here were done independently.

## 🧩 Data Source

- **Dataset Origin**: Collected via online survey by Alex the Analyst
- **Format**: Excel
- **Number of Respondents**: 504
- **Fields Included**:
  - Unique ID
  - Email (anonymized)
  - Date & Time Taken
  - Time Spent on Survey
  - Referrer
  - Q1 – Job Title
  - Q2 – Career Switch into Data?
  - Q3 – Current Yearly Salary
  - Q4 – Industry
  - Q5 – Favorite Programming Language
  - Q6 – Happiness with:
    - Management
    - Upward Mobility
    - Learning New Things
  - Q7 – Difficulty Breaking into Data
  - Q8 – Most Important Factor When Job Hunting
  - Q9 – Gender
  - Q10 – Age
  - Q11 – Country
  - Q12 – Highest Level of Education
  - Q13 – Ethnicity

## 🔧 Data Cleaning & Transformation

Performed in Power Query within Power BI:
- Removed unnecessary columns
- Renamed headers for clarity
- Split and extracted nested values
- Handled missing values
- Normalized categorical data
- Added calculated columns (e.g., average age, difficulty index)

## 📈 Visualizations Included

- **Tree Map**: Data professionals by country
- **Bar Chart**: Average salary by job title
- **Gauge Chart**: Happiness index by salary and work-life balance
- **Pie Chart**: Perceived difficulty of breaking into data
- **Bar Chart**: Favorite programming language by job title
- **KPIs**: Number of survey respondents and their average age

## 📌 Key Insights

- **Python** is by far the most popular programming language.
- **Data Scientists** report the highest average salary.
- Most respondents find it **moderately difficult** to break into data roles.
- The average happiness score based on **work-life balance (5.72)** is higher than that based on **salary (4.26)**.

## 📺 Credit

- **Dataset Credit**: Alex The Analyst ([YouTube Channel](https://www.youtube.com/@AlexTheAnalyst))
- **Project Execution**: Transformation, modeling, and dashboard design by *[Shashank Pokala]*.

## 🧠 Tools Used

- Power BI
- Power Query
- DAX
- Excel (for data preview and cleaning)
"""

# Save final README
final_readme_path = Path("/mnt/data/FINAL_README.md")
final_readme_path.write_text(final_readme_content.strip())

final_readme_path.name
