# NYC Public School SAT Performance Analysis

## Project Description
This project aims to analyze SAT performance data for New York City public schools to identify high-performing schools and understand variations across different boroughs. The analysis focuses on three key questions related to math performance, overall SAT scores, and the consistency of scores within boroughs.

## Data
The dataset used for this analysis is `schools.csv`. It contains information about various NYC public schools, including their names, borough, and average SAT scores for math, reading, and writing sections. Each section has a maximum possible score of 800 points.

## Analysis Questions
1.  **Which NYC schools have the best math results?**
    -   Defined as schools with an average math score of at least 80% of the maximum possible score (640).
2.  **What are the top 10 performing schools based on the combined SAT scores?**
    -   Calculated by summing the average scores of math, reading, and writing sections.
3.  **Which single borough has the largest standard deviation in the combined SAT score?**
    -   This helps identify boroughs with the most varied SAT performance among their schools.

## Key Findings
*   **Best Math Schools:** The analysis identified several schools excelling in math, with Stuyvesant High School leading with an average math score of 754.
*   **Top 10 Performing Schools (Combined SAT):** Stuyvesant High School also topped the list for combined SAT scores, followed closely by Bronx High School of Science and Staten Island Technical High School.
*   **Borough with Largest Standard Deviation:** Manhattan showed the largest standard deviation in combined SAT scores, indicating a wider range of SAT performance among its schools compared to other boroughs.

## Technologies Used
*   Python
*   Pandas (for data manipulation and analysis)

## How to Run
1.  Ensure you have Python and Pandas installed.
2.  Place the `schools.csv` file in the same directory as the Jupyter/Colab notebook.
3.  Run the cells in the notebook sequentially to reproduce the analysis and findings.
