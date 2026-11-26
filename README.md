<div align="center">
    
# People-Pulse📊📈
People Pulse is an HR analytics project analyzing1,470 employees to explore the relationships between training,education,experience, satisfaction, work-life balance, and performance. Using SQL, Python, Excel, Power Query, DAX, and Power BI, we will create an interactive dashboard with KPIs, workforce insights, segmentation, and actionable findings.

### Excel . Power BI . Phyton . SQL 
 </div>

---
# 📂Project Resources

| Resource | Link |
|---|---|
| Google Drive Folder | [Open Project Files](https://drive.google.com/drive/folders/1iOcOm-y572f2N3wVo78Q6O3ZRq1CvXkC?usp=drive_link)

 ---
 
# 👥 Team Members & Responsibilities

| Team Member | Role |
|---|---|
| ⭐️Rana Mohamad Askar | Team Leader, Presentation, Project Coordination, Supporting All Project Phases & Dashboard Design|
| ⭐️ Rawan hani mariee | Dashboard Visualization & Dashboard Development |
| ⭐️ Aya sobh galal |  Dashboard Visualization & Dashboard Development  |
| ⭐️Habiba Ahmed Mohamed | DAX Measures & Calculations  |
| ⭐️Farah Mohamed Ahmed |Data Cleaning, Data Preparation, Data Storage & Data Modeling|
  
---
# 🧹 Data Cleaning
The HR data arrived with everything mixed together in a single flat file, so the first step was to inspect it and understand its structure and quality. Each column was then assigned the correct data type, and the first name and last name columns were merged into one Full Name column. The data was checked and confirmed to contain no errors, null values, or duplicate records. Finally, the flat file was split into separate tables, each focused on a single subject: Employee Master, Employee Job, Employee consumption, Employee experience, and PerformanceRating.

---
# 🔗 Data Modeling (1): Structure
The cleaned tables were loaded into Power BI and organized around one central table, Employee Master, which holds one row per employee (1,470 employees). The Employee Job, Employee consumption, and Employee experience tables each connect to it through EmployeeID with a one-to-one relationship, since every employee has exactly one record in each. PerformanceRating holds 6,709 reviews, so it connects to Employee Master with a many-to-one relationship, tying each review to its employee. This design avoids repeating employee details with every review.

---
# 🔗 Data Modeling (2): Lookup Tables
 Ratings, satisfaction scores, and education levels are stored as numeric codes from 1 to 5, which are not meaningful on their own. To fix this, three lookup tables were created: RatingLevel, SatisfiedLevel, and EducationLevel. They were connected to the model with many-to-one relationships on Education, SelfRating, and JobSatisfaction, so reports show readable labels instead of numbers. The remaining rating and satisfaction columns stay numeric from 1 to 5 in the current model.
 ---
 # 📂 DAX Measures & Calculations
 To turn the People Pulse HR data into measurable insights, I wrote 27 DAX measures and stored them in a single dedicated table, organized into six folders that follow the report structure. I used CALCULATE to apply filters such as overtime and attrition status, DIVIDE to calculate rates safely, and variables (VAR) to keep complex logic like the top attrition job clear and efficient. These measures answer the key business questions: how many employees leave, who is most likely to leave, how satisfied employees are, whether training improves performance, and how pay compares across genders.
# 👨‍🏫 Instructor
### ENG. Mohamed Assem
 ---
 # 📌 Final Outcome

The project successfully transformed raw governmental accident reports into a complete analytical solution that includes:

- ✅ Clean and structured datasets
- ✅ Interactive Power BI dashboards
- ✅ Professional storytelling presentation
 ---
# ⭐ Project Status

## ✅ Completed Successfully
