# Measure-Diversity-Inclusion-With-SQL
For this project, I obtained the <a href="https://www.kaggle.com/datasets/rhuebner/human-resources-data-set">HR dataset from Kaggle containing employees' details</a>. Before importing the CSV file into the MySQL workbench, I made some amendments on the dataset using Excel. For example, fill in the blank cell in the “DateofTermination” column with “NA”, and standardized the date formats. You may find the raw dataset and cleaned dataset in this repo. 

# Hypothetical Questions & Results
1. Create a view called “eng_hr_dataset” that includes all the columns of the dataset, except the “HispanicLatino” column and columns with “ID” in their names. Then, calculate the age, job level, and service period of all employees. Finally, determine generational diversity in the workplace, as well as the average (trimmed) service period of each generation. <br><br><img src="https://miro.medium.com/max/1100/1*YlXAft5Ojr0VN0Nrpz-5PQ.png" alt="Result for query 1">
2. <br><br><img src="" alt="Result for query ">
3. <br><br><img src="" alt="Result for query ">
4. <br><br><img src="" alt="Result for query ">
5. <br><br><img src="" alt="Result for query ">
6. <br><br><img src="" alt="Result for query ">
7. <br><br><img src="" alt="Result for query ">
8. <br><br><img src="" alt="Result for query ">
9. <br><br><img src="" alt="Result for query ">

# Summary
For the complete code explanation & analysis, please check out <a href="https://jadangpooiling.medium.com/analyzing-hr-metrics-with-sql-to-measure-diversity-inclusion-1c00bf4b6bae">my article on Medium</a>. Below are summary of the analysis.
1. Most of the current employees are Generation Y (102), followed by Generation X (87), and finally Baby Boomers (10). Generally, the average service period of Generation X is longer than that of Generation Y (also known as millennials).
2. 
