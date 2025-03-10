1.2 VISUALIZATION OF RESULT USING POWER BI 
In this process, we will be implementing the software, Power BI as our business intelligence tool to visualize the output of the students’ results. In this first step, the sample data of students’ mark which is in the form of Excel format are integrated into Power BI. Therefore, to begin, we get data from the Excel workbook to locate our database which to be integrated into the software. 
 
 
 
Figure 4.5 Step 1 of data visualization 
 
 
 
 
 
 
 
In our next step, before we load the data, we would transform the data first to do some modification to the queries like renaming the column names, removing null fields, and filter out only the significant information we need for analysis. This is done so that we could consolidate them into a useful and meaningful query. 
  
 
 
Figure 4.6 Step 2 of visualization 
 
 
In our third step, we had renamed and filtered the rows and it is ready to be loaded into the platform by clicking “Close & Apply” to save the changes made to the queries. 
 
 
 
Figure 4.7 Step 3 of visualization 
 
 
 
 
In our final step, we visualize the data in the form of graphical representations like stacked column chart, pie-chart, table, funnel, clustered bar chart, area chart, Tree map, and line chart by dragging the data on the right side into the visualization fields.  
 
Figure 4.8 Step 4 of visualization 
 
 
 
 
 
 
 
  
 
Figure 4.9 Dashboard overview of the SPAPS system 
 
 
Figure 4.9 shows a menu with several tabs or buttons labeled: 
Menu 
Student results 
Student performance dashboard semester one 
Student performance dashboard semester 
Dashboard for performances across two semesters 
 
  
Figure 4.10 Dashboard overview of students results for both semesters 
 
Figure 4.10 is a comprehensive student performance analysis tool for Takoradi Technical University, specifically designed to showcase student results across two semesters. Here's a detailed breakdown: 
1. Title and University Branding 
Title: STUDENT RESULTS FOR BOTH SEMESTERS 
- Branding: The Takoradi Technical University logo is prominently displayed, indicating the institution associated with the data. 
2. Data Layout 
The dashboard is divided into two main sections: 
-	Semester One Final Results: This section is the upper half of the table. 
-	Semester Two Final Results: This section is the lower half of the table. 
3. Columns of Data 
Each section includes the following columns: 
-	STUDENT ID: A unique identifier for each student (e.g., TTU01, TTU02, etc.). 
-	FIRST NAME: The first name of the student (e.g., Paul, Danielle). 
-	LAST NAME: The last name of the student (e.g., Casey, Sandoval). 
-	GENDER: The gender of the student (male or female). 
-	FINAL SCORE (Subject or Assessment Specific): Several columns labeled with scores (e.g., FINAL SCORE(A1), FINAL SCORE(B1), FINAL SCORE(C1)) indicating the scores students achieved in different assessments or subjects. 
4. Filters and Interaction Panel 
-	On the right-hand side of the dashboard, there is a Filter Panel allowing users to interact with the data: 
-	Student ID Selector: A list of checkboxes with student IDs (TTU01, TTU02, etc.), allowing the user to filter the data and view the performance of specific students. 
5. Data Presentation 
-	Tabular Format: The data is displayed in a tabular format, which makes it easy to compare individual student performances across different assessments within each semester. 
-	Comparison Across Semesters: The layout facilitates a straightforward comparison of a student’s performance across the two semesters. 
6. User Interface 
-	The dashboard is designed within Power BI, a tool known for its interactive and dynamic data visualization capabilities. 
-	Navigation Tabs: Below the main dashboard, there are multiple tabs for navigating between different sections: 
Menu 
Student Results (The Current Tab Selected) 
Student Performance Dashboard Semester One 
Student Performance Dashboard Semester 
Dashboard For Performances Across Two Semesters 
7. Purpose and Usage 
-	Academic Tracking: The dashboard is likely used by academic staff or administrators to track and evaluate student performance over the course of an academic year. 
-	Intervention Identification: It can be used to identify students who may need additional academic support or to highlight top-performing students. 
-	Data Analysis: The dashboard allows for detailed analysis and data-driven decisionmaking regarding student performance. 
8. Visual Design 
-	Clean Layout: The design is clean and focused on data clarity. It uses a minimalistic approach, which ensures that the user’s attention is on the data itself. 
-	Interactive Elements: The use of filters and navigation tabs suggests that the dashboard is designed to be interactive, allowing users to drill down into the data for deeper insights. 
This dashboard serves as a powerful tool for monitoring and analyzing student performance, providing a clear and structured overview of how students are performing across different subjects and semesters. It allows for quick identification of trends, outliers, and potential areas for intervention. 
1.3 ANALYSIS OF POWER BI RESULTS AND DISCUSSIONS (SEM 1) 
4.1.2 DASHBOARD OF STUDENT PERFORMANCE OF SEM 1 
The Power BI application consists of student performance dashboard, presented in Figure 4.11 conveys is a detailed visual representation of student performance data for Semester one. 
  
 
Figure 4.11 Dashboard overview of student performance (Sem 1) using Power BI 
 
4.1.2.1 ANALYSIS AND DISCUSSIONS 
The dashboard in figure 4.11 is a detailed visual representation of student performance data for 
Semester One at Takoradi Technical University. Here’s a detailed breakdown of the components and insights provided by the dashboard: 
1. Title and Overview 
-	Title: STUDENT PERFORMANCE DASHBOARD SEMESTER ONE 
-	Total Number of Students: The dashboard indicates that the total number of students analyzed is 1,000. 
2. Gender Distribution - 	Count of Gender:  
-	Male: 506 students. 
-	Female: 494 students. 
-	This section provides a quick overview of the gender distribution among the students. 
3. Top Five Performing Students 
-	Bar Chart: Displays the top five performing students based on the sum of their average scores across all courses. 
-	Student IDs: The specific student IDs listed (e.g., TTU248, TTU657, TTU140, TTU241, TTU363) represent the top performers. 
-	Performance Metrics: The chart uses different colored bars to represent performance, likely correlating to different subjects or assessments. 
4. Key Influencers 
-	Influence on Final Score (CG1): 
-	This section analyzes the factors influencing final scores, particularly focusing on attendance. 
-	Key Insight: Attendance score impacts the final score, with a noted increase in average final scores (CG1) by 5.2 points when the attendance score is more than 5. This suggests a strong correlation between attendance and academic performance. 
5. Average Scores by Subject 
Gauge Charts: These charts represent the average scores in different subjects. Each gauge indicates the performance in specific subjects: 
-	Computer Graphics I: 76.77 
-	Computer Networks: 76.97 
-	Economics: 74.85 
-	Enterprise Security: 72.54 
-	Information System Security: 77.74 
-	Operating System: 76.99 
-	System Administration I: 78.07 
-	These scores provide a clear view of how well students are performing in each subject area. 
6. Average of Final Scores by Gender 
Horizontal Bar Chart:  
-	Displays the average final scores for both male and female students. 
-	This allows for a comparison of performance between genders across the different subjects. 
7. User Interface and Design 
-	Interactive Filters: The dashboard likely includes interactive elements, such as filters or slicers, allowing users to drill down into specific data points (e.g., by gender, subject, or student ID). 
-	Visuals: The dashboard employs various visuals (bar charts, gauge charts) to represent the data clearly and concisely, making it easy to interpret at a glance. 
-	Color Coding: The use of different colors helps in distinguishing between different categories, such as gender and subject performance. 
8. Insights and Usage 
-	Performance Analysis: The dashboard is designed to give quick insights into which students are excelling and which subjects might need more attention. 
-	Gender Comparison: It offers a clear comparison of performance by gender, which can be useful for identifying any potential disparities. 
-	Attendance Impact: The key influencers section highlights how critical attendance is to academic success, potentially guiding interventions to improve student performance. 
9. Educational Application 
-	Academic Monitoring: Teachers, administrators, and academic counselors can use this dashboard to monitor student performance and implement targeted support where needed. 
-	Student Feedback: Students can also use this data to understand their standing in class and identify areas where they might need to improve. 
Overall, this dashboard is a powerful tool for analyzing and understanding student performance at a granular level, allowing for data-driven decisions to enhance educational outcomes. 
1.4 ANALYSIS OF POWER BI RESULTS AND DISCUSSIONS (SEM 2) 
4.4.1 DASHBOARD OF STUDENT PERFORMANCE OF SEM 2 
The Power BI application consists of student performance dashboard, presented in Figure 4.12 conveys is a detailed visual representation of student performance data for Semester two. 
  
Figure 4.12 Dashboard overview of student performance (Sem 2) using Power BI 
 
4.4.1.1 ANALYSIS AND DISCUSSIONS 
The dashboard in figure 4.12 is a detailed visual representation of student performance data for 
Semester two at Takoradi Technical University. Here’s a detailed breakdown of the components and insights provided by the dashboard: 
1. Title Section: 
-	Title: STUDENT PERFORMANCE DASHBOARD SEMESTER TWO  
-	Total Number of Students: Below the title, there is a large number "1000," indicating the total number of students included in the dashboard. 
2. Gender Distribution: 
Count of Gender: The dashboard displays the number of male and female students. 
-	Male: 506 students. 
-	Female: 494 students. 
-	Visualization: The gender count is represented with icon-based visuals (a male and female icon with their respective numbers). 
3. Top Ten Performing Students: 
Horizontal bar chart: 
-	The chart lists the top ten performing students across all courses, identified by their student IDs (e.g., TTU824, TTU46, etc.). 
-	It displays the average scores of these top-performing students, with a color-coded bar representing each student’s performance. 
4. Final Score by Gender: 
A bar chart shows the distribution of the final scores by gender.  
-	Both male and female students seem to have similar performance levels, with scores grouped around similar values - The x-axis represents gender. 
-	The y-axis represents the sum of final scores. 
5. Key Influencers: 
-	Influencing Factors: This section shows what factors (like "Sum of Absence Weeks") influence the final scores. It suggests that as the "Sum of Absence Weeks" decreases, the final score for all courses increases. 
-	Segment Analysis: The analysis appears to show a numeric or visual representation of this relationship. 
6. Average Scores by Course: 
Gauge Charts: The right side of the dashboard features gauge charts for average scores in specific courses. 
Courses: The courses listed include: 
-	Computer Graphics 2 (75.62) 
-	Computer Organization (70.87) 
-	E-Commerce (72.62) 
-	Information Security 2 (76.59) 
-	System Administration 2 (72.84) 
 Interpretation: These gauges show how students performed on average in each subject, with the needle pointing to the respective score. 
7. Visual Design: 
-	Color Coding: The dashboard uses color coding (e.g., blue for male, pink for female, yellow for gauges) to differentiate between different data points. 
-	Icons: Gender icons are used to represent male and female students visually. 
This dashboard is a comprehensive tool for analyzing student performance, providing insights into the top performers, gender-wise score distribution, and the influence of attendance on academic outcomes. 
1.5 ANALYSIS OF POWER BI RESULTS AND DISCUSSIONS (BOTH SEM) 4.1.3 DASHBOARD OF STUDENT PERFORMANCE ACROSS THE TWO SEM 
The Power BI application consists of student performance dashboard, presented in Figure 4.13 conveys is a detailed visual representation of student performance data across the two Semester. 
 
  
Figure 4.13 Dashboard overview of student performance across the two semesters using Power BI 
4.1.3.1 ANALYSIS AND DISCUSSIONS 
1. Title Section: 
-	Title: DASHBOARD FOR PERFORMANCES ACROSS TWO SEMESTERS 
-	Navigation Tabs: Directly below the title are tabs for easy navigation across different sections: 
2. Top Performing Students (First and Second Semester): 
First Semester: 
Vertical bar chart. 
-	This chart shows the average performance of the top 8 performing students in the first semester. The student IDs are listed along the x-axis (e.g., TTU449, TTU590, TTU933, etc.), and the scores are plotted on the y-axis. 
Second Semester: 
Similar vertical bar chart. 
-	This chart shows the average performance of the top 8 performing students in the second semester. The student IDs are different (e.g., TTU964, TTU573, TTU696, etc.), and their scores are plotted similarly on the y-axis. 
3. Top Eight Performing Students Across Two Semesters: 
Horizontal bar chart. 
- This chart aggregates the top-performing students across both semesters. It lists the student IDs on the y-axis (e.g., TTU449, TTU590, TTU953, etc.), and their performance scores are shown with color-coded horizontal bars along the x-axis. 
4. Average Performance Across Two Semesters: 
Gauge chart/donut chart. 
-	This section compares the average performance across the two semesters: 
-	SEM 1: Average score is 76.31. 
-	SEM 2: Average score is 73.68. 
-	Visual Representation: These scores are shown as parts of a circular gauge, visually representing the average performance. 
5. Count of Students by Gender Across Two Semesters: 
This section displays the count of male and female students across the two semesters. 
-	Male: 506 students. 
-	Female: 494 students. 
-	Visual Design: The gender distribution is shown using solid color blocks (green for male and pink for female). 
6. Key Influencers: 
-	Influencing Factors: This section identifies factors that influence the performance (100% of SEM 1) across the two semesters. 
-	Example Factor: It shows that the "ATTENDANCE SCORE (100%)" decreases when the average of 100% of SEM 1 decreases by a specific amount. 
-	Impact Indicator: A small numeric or graphical indicator shows the extent of influence (e.g., a score or percentage). 
7. Visual Design: 
-	Color Coding: Different colors are used to differentiate students, genders, and performance metrics. 
-	Charts: A mix of bar charts and gauge charts provides both categorical and quantitative insights. 
-	Layout: The dashboard is organized into distinct sections, making it easy to compare performance data across semesters. 
This dashboard is an analytical tool designed to track and compare student performance across two semesters, providing insights into top performers, gender distribution, and key factors affecting academic outcomes. 



