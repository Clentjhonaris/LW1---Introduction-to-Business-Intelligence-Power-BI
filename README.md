# LW1---Introduction-to-Business-Intelligence-Power-BI

Step 1: Quick Visualization
1. Drag Sales into canvas
2. Power BI automatically creates a visual
                  Question:
                  ● What type of chart was created?
                  ANSWER: CLUSTERED COLUMN CHART
                  ● What does it show?
                  ANSWER: SALES


Step 2: Create a Sales by Region Chart
1. Click blank canvas
2. Select Clustered Column Chart
3. Drag:
○ Region → X-axis
○ Sales → Values
                  Question:
                  ● Which region has highest sales?
                  ANSWER: West Region


Step 3: Sales by Category
1. Insert a Pie Chart
2. Drag:
○ Category → Legend
○ Sales → Values
                  Question:
                  ● Which category dominates?
                  ANSWER: ELECTRONICS
                  ● Is the distribution balanced?
                  ANSWER: Mostly yes, but North underperforms compared to others.



Step 4: Sales Over Time
1. Insert Line Chart
2. Drag:
○ Date → X-axis
○ Sales → Values
                  Question:
                  ● Is there growth?
                  ANSWER:Nope, the sales go down
                  ● Any noticeable trend?
                  ANSWER: Nope



PART 4: Basic Data Insight Interpretation
Students must now interpret visuals.
                  Question:
                  ● Which region contributes most revenue?
                      ANSWER: West Region 
                      
                  ● Which product category performs best?
                      ANSWER: Electronics
                      
                  ● Are sales consistent across dates?
                     ANSWER:Mostly yes, but North underperforms compared to others. 
                     
                 ● What business recommendation can you suggest?
                    ANSWER: Office Supplies



LABORATORY QUESTIONS
Part A – Technical Questions

1. What are the five columns in the dataset?
       - Date, Product, Category, Region, Sales
   
3. What data type is assigned to the “Sales” column?
        - Decimal Number. It stores continuous numerical values representing revenue amounts.

5. Which Power BI view allows you to see raw data?
       - Data View - the table icon on the left-side navigation bar. It shows every row and column in the loaded dataset.
   
7. What chart type is best for showing trends over time?
       - Line Chart. It maps a continuous axis (Date/Time) on the X-axis, making patterns such as growth or decline immediately visible.
   
9. What aggregation is automatically applied to Sales?
       - SUM (Sum of Sales). Power BI defaults to summing numerical fields when they are dragged onto a visual.


Part B – Analytical Questions

6. Which region has the highest total sales?
    - West region. From the sorted bar chart , West has the tallest bar, followed closely by East, then South, with North recording the lowest figures.
      
7. Which category has the lowest performance?
    - Office Supplies. The pie chart shows it accounts for only 19.99% (~44K) of total sales, compared to Electronics (40.82%, ~90K) and Furniture (39.19%, ~86K).
      
8. Are sales increasing, decreasing, or stable?
    - Decreasing over the observed period. The line chart (p. 9) shows a steep downward slope from ~0.2M in 2024 to near zero in 2025, indicating a significant sales drop — likely due to incomplete  2025 data.
      
9. If you were a manager, which region would you prioritize?
      - North region should be prioritized for investigation and improvement, as it is the weakest performer. West and East should be studied as best-practice regions to  replicate their success strategies.
        
10. Provide one actionable recommendation based on the data.
     - Reallocate marketing and sales resources from Office Supplies to Electronics and Furniture, which jointly account for ~80% of revenue. In the  North region, deploy a targeted sales   campaign modeled after the West region's approach.


Question:
● What is the total sales amount?
ANSWER: 220K 

Question:
● What happens to other visuals when you click a region?
      - All visuals on the page filter to show data  
         ONLY for the selected region. 
         
● Why is filtering important in BI?
          - Filtering is important because it: 
 - Allows users to analyze specific segments of data 
 - Helps in comparing performance between regions


Question:
● Does sorting improve readability?
       - Yes 
       
● Why?
     - sorting dramatically improves readability by pre-attentively ordering information. - It allows immediate identification of best/worst performers without manual comparison. - Sorted charts are also easier to annotate (e.g., 'Top performer: West, +28% above average').


Task 4: Identify Outliers

● Which region is significantly higher or lower?
● What might explain that difference?
     - North is the clear negative outlier. Based on the sorted bar chart (West → East → South → North),  the North column is noticeably shorter than   the other three, which are relatively close in height.  Possible explanations: fewer sales representatives in the North territory; seasonal demand  differences; product-market mismatch where Electronics (the top category) is less in demand in that  geography; or simply a smaller target customer population. A manager should drill down into North's  product-level data using the Category slicer to isolate whether all categories underperform or just  one.
 



Google Slides Drive Link: https://drive.google.com/drive/folders/1ml-Oe0S6bN9uBdD_cWbosFHgARs46pbm?usp=drive_link
