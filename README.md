📊Student Feedback Survey Analysis

📎Project Overview

This project analyzes student feedback survey responses to quantitatively assess overall satisfaction and identify specific strengths and weaknesses in course delivery and student support. The analysis utilizes core data science techniques to transform raw rating data into clear, actionable business insights.

📎Methodology & Analysis Steps

The analysis was performed using Python (Pandas/NumPy) and involved the following steps:
1. Data Preparation: The raw rating columns were cleaned and prepared for numerical analysis.
2. Feature Engineering: An Overall Rating was calculated for each student by taking the average of all individual rating scores.
3. Satisfaction Classification: Each student was categorized into one of three groups based on their Overall Rating:
Satisfied (Rating > 7)
Neutral (Rating 5 - 7)
Dissatisfied (Rating < 5)
4. Key Metric Calculation: Mean scores for all eight course aspects were computed to rank performance.

📎How to Run the Analysis
ToTo reproduce the analysis and generate the final output file (student_feedback_with_insights csv):
1. Clone the Repository: Download the files to your local machine.
2. Install Dependencies: Ensure you have the necessary libraries installed (e.g., pandas, numpy ).
3. Run the Notebook: Open and run all cells in the Student_Feedback_Analysis.i pynb notebook.

The notebook will automatically load the CSV, perform the analysis, and save the final dataset with the added insight columns.
