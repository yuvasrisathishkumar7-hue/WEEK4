<h1>Student Performance Analysis System (Synthetic Data)<h1>
Problem Statement
 Educational institutions generate large amounts of student data, but manual analysis is difficult and time-consuming. This project builds a simple system to generate and analyze student performance data to identify trends, top performers, and students who need improvement.

                 Dataset

                         A synthetic dataset of 250 students is generated using Python.

                                          Columns:
                                              Student_ID – Unique ID
                                              Name – Student Name
                                              Gender – Male / Female
                                              Department – CSE / IT / ECE
                                              Year – 1st / 2nd / 3rd
                                              Maths – Marks
                                              Science – Marks
                                              English – Marks
                                              Attendance – 50–100%
                                              Internal_Marks – 0–25
                  Objectives
                            Generate synthetic student dataset
                            Clean and preprocess data
                            Perform exploratory data analysis (EDA)
                            Calculate total, average, and grades
                            Identify top and fail students
                            Compare performance by department, gender, and year
                            Analyze relationships:
                                  Attendance vs Performance
                                  Internal Marks vs Total Marks
                            Visualize data using charts
                  Workflow
                       1. Data Generation
                               Created 250 student records using Faker and random values
                       2. Data Preprocessing
                                * Checked missing values
                                * Removed duplicates
                                * Verified dataset structure
                       3. Feature Engineering
                              Calculated:
                                    Total Marks
                                    Average Marks
                                    Grade Classification (A, B, C, Fail)
                       4. Analysis
                                    Top 5 students identified
                                    Fail students filtered
                                    Group analysis:
                                             Department-wise
                                             Gender-wise
                                             Year-wise
                        5. Visualization
                                * Bar Chart – Department performance
 <img width="423" height="314" alt="image" src="https://github.com/user-attachments/assets/1eea0569-7ece-401a-a4b7-9a84e5a8c1b2" /> 


 
                                * Pie Chart – Gender distribution
  <img width="355" height="338" alt="image" src="https://github.com/user-attachments/assets/aca72c40-1c7b-4aa3-8826-34f94ac5496f" />


  
                                *  Histogram – Average marks distribution
  <img width="423" height="315" alt="image" src="https://github.com/user-attachments/assets/707afb89-6e31-4cee-967b-b29bd3ff28d5" />



                                * Scatter Plot – Attendance vs Average
  <img width="424" height="311" alt="image" src="https://github.com/user-attachments/assets/b78b24a7-3e71-4ef2-ba9f-af7e21ae0d0f" />




                               * Scatter Plot – Internal Marks vs Total
<img width="430" height="311" alt="image" src="https://github.com/user-attachments/assets/9de59eed-1e14-4534-bd8b-fca7926100b6" />



                        Key Insights
                                 * Higher attendance leads to better performance
                                 * Internal marks strongly affect total marks
                                 * Performance varies across departments and years
                                 * Visualization helps understand patterns clearly
                      
                       Tools Used
                             * Python
                             * pandas
                             * numpy
                             * matplotlib
                             * seaborn
                             * Faker
                             * Jupyter Notebook
                 Conclusion

                               This project demonstrates how data analytics can be used to analyze student performance effectively. It helps in identifying trends, improving academic planning, and supporting decision-making.

                   Author

                  Yuvasri S 
