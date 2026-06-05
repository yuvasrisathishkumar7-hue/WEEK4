<!DOCTYPE html>
<html>
<head>
    <title>Student Performance Analysis System</title>
</head>
<body>

<h1>Student Performance Analysis System (Synthetic Data)</h1>

<h2>Problem Statement</h2>
<p>
Educational institutions generate large amounts of student data, but manual analysis is difficult and time-consuming.
This project builds a simple system to generate and analyze student performance data to identify trends,
top performers, and students who need improvement.
</p>

<h2>Dataset</h2>

<p>A synthetic dataset of 250 students is generated using Python.</p>

<h3>Columns</h3>
<ul>
    <li><b>Student_ID</b> – Unique ID</li>
    <li><b>Name</b> – Student Name</li>
    <li><b>Gender</b> – Male / Female</li>
    <li><b>Department</b> – CSE / IT / ECE</li>
    <li><b>Year</b> – 1st / 2nd / 3rd</li>
    <li><b>Maths</b> – Marks</li>
    <li><b>Science</b> – Marks</li>
    <li><b>English</b> – Marks</li>
    <li><b>Attendance</b> – 50–100%</li>
    <li><b>Internal_Marks</b> – 0–25</li>
</ul>

<h2>Objectives</h2>

<ul>
    <li>Generate synthetic student dataset</li>
    <li>Clean and preprocess data</li>
    <li>Perform exploratory data analysis (EDA)</li>
    <li>Calculate total, average, and grades</li>
    <li>Identify top and fail students</li>
    <li>Compare performance by department, gender, and year</li>
    <li>Analyze Attendance vs Performance</li>
    <li>Analyze Internal Marks vs Total Marks</li>
    <li>Visualize data using charts</li>
</ul>

<h2>Workflow</h2>

<h3>1. Data Generation</h3>
<ul>
    <li>Created 250 student records using Faker and random values</li>
</ul>

<h3>2. Data Preprocessing</h3>
<ul>
    <li>Checked missing values</li>
    <li>Removed duplicates</li>
    <li>Verified dataset structure</li>
</ul>

<h3>3. Feature Engineering</h3>
<p>Calculated:</p>
<ul>
    <li>Total Marks</li>
    <li>Average Marks</li>
    <li>Grade Classification (A, B, C, Fail)</li>
</ul>

<h3>4. Analysis</h3>
<ul>
    <li>Top 5 students identified</li>
    <li>Fail students filtered</li>
    <li>Department-wise analysis</li>
    <li>Gender-wise analysis</li>
    <li>Year-wise analysis</li>
</ul>

<h3>5. Visualization</h3>

<p><b>Bar Chart – Department Performance</b></p>
<img src="https://github.com/user-attachments/assets/1eea0569-7ece-401a-a4b7-9a84e5a8c1b2" width="450">

<p><b>Pie Chart – Gender Distribution</b></p>
<img src="https://github.com/user-attachments/assets/aca72c40-1c7b-4aa3-8826-34f94ac5496f" width="400">

<p><b>Histogram – Average Marks Distribution</b></p>
<img src="https://github.com/user-attachments/assets/707afb89-6e31-4cee-967b-b29bd3ff28d5" width="450">

<p><b>Scatter Plot – Attendance vs Average Marks</b></p>
<img src="https://github.com/user-attachments/assets/b78b24a7-3e71-4ef2-ba9f-af7e21ae0d0f" width="450">

<p><b>Scatter Plot – Internal Marks vs Total Marks</b></p>
<img src="https://github.com/user-attachments/assets/9de59eed-1e14-4534-bd8b-fca7926100b6" width="450">

<h2>Key Insights</h2>

<ul>
    <li>Higher attendance leads to better performance</li>
    <li>Internal marks strongly affect total marks</li>
    <li>Performance varies across departments and years</li>
    <li>Visualization helps understand patterns clearly</li>
</ul>

<h2>Tools Used</h2>

<ul>
    <li>Python</li>
    <li>Pandas</li>
    <li>NumPy</li>
    <li>Matplotlib</li>
    <li>Seaborn</li>
    <li>Faker</li>
    <li>Jupyter Notebook</li>
</ul>

<h2>Conclusion</h2>

<p>
This project demonstrates how data analytics can be used to analyze student performance effectively.
It helps in identifying trends, improving academic planning, and supporting decision-making.
</p>

<h2>Author</h2>

<p><b>Yuvasri S</b></p>

</body>
</html>
