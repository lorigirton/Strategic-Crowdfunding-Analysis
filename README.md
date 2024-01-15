# excel-challenge
## Introduction
In the scope of this project, I was tasked with the analysis of crowdfunding campaigns, sourced from an Excel dataset supplied by edX Boot Camps LLC, wherein crowdfunding referes to the strategic utilization of social media platforms by users for the purpose of fundraising.  

Figure 1: <img src="Visuals/Crowdfunding.png">
In the "Crowdfunding" worksheet (Figure 1), I implemented advanced formulas and formatting to generate a "Percent Funded" column, employing distinctive color-coding for cells based on specific conditions. Additionally, I engineered an "Average Donation" column and performed a systematic segmentation of the "Category and Sub-Catergory" column into two distinct columns to enhance data clarity and analysis. 

Figure 2: <img src="Visuals/Success_by_Category.png">
Subsequently, I established a "Success by Category" sheet (Figure 2), wherin I devised a comprehensive pivot table to analyze the count of successful, live, failed and canceled campaigns categorized by their respective categories. Furthermore, I complemented this analysis with a pivot chart visualization for enhanced interpretability. 

Figure 3: <img src="Visuals/Success_by_Subcategory.png">
The "Success by Subcategory" sheet (Figure 3) features a stacked-column pivot chart examining campaigns based on their subcategories, providing a visually informative representation of the distribution and outcomes within each subcategory. 

Figure 4: <img src="Visuals/Success_by_Date.png">
To construct the "Success by Date" sheet (Figure 4), I initially enhanced worksheet 1 by creating two new columns, "date_created_conversion," through the application of formulas to convert the "launched_at" and "deadline" timestamps, into standard date formats. Subsequently, I designed a pivot table with "outcome" as columns, "Date Created Conversion" as rows, values based on the count of "outcome," and filters based on "parent category" and "Years." Finally, I implemented a pivot table line chart to visualize this data.

Figure 5: <img src="Visuals/Goal_Analysis.png">
In the "Goal Analysis" sheet (Figure 5), I introduced a new column called "Goal" employing the COUNTIFS() formula to count the number of successful, failed, and canceled projects categorized into various goal ranges. 

Figure 6: <img src="Visuals/Statistical_Analysis.png">
Finally, the "Statistical Analysis" sheet (Figure 6) was formulated to gain a better understanding of campaign backers. Beginning with the establishment of four columns, distinguishing successful outcomes and the corresponding number of backers, as well as unsuccessful outcomes and their associated backers, I subsequently applied formulas to compute the mean, median, minumum, maximum, variance, and standard deviation of backers for both successful and unsuccessful campaigns. 

# Analysis

## Given the provided data, what conclusions we can draw about crowdfunding campaigns?

1.  **Monthly Success Rates:**
  - June and July stand out as the most successful months, while August shows the least success, characterized by a low number of successful campaigns and a relatively high number of failures.

2. **Category and Subcategory Insights:**
  - The theater category, particularly within the subcategory of plays, emonstrates the highest frequency of crowdfunding campaigns, indicating notable interest in this niche.

3. **Goal Analysis:**
  - Campaigns with goal amounts ranging between $15,000 to $19,999 and $30,000 to $34,999 achieve a 100% success rate, albeit with a smaller number of campaigns (10 and 7, respectively).
  - Among the top three total crowdfunding campaign goal ranges, the $1,000 to $4,999 range attains the highest success rate at 82%, followed by $5,000 to $9,999 with a 52% success rate.
  - In contrast, campaigns with goals exceeding $50,000 exhibit a lower success rate of 36%.

These conclusions provide valuable insights into the patterns and trends within crowdfunding campaigns, allowing for strategic considerations in planning and optimizing future endeavors.

## What are some limitations of this dataset?

1. **Limited Information about Creators:**
  - The dataset lacks comprehensive information about the creators of the campaigns, limiting a detailed understanding of success. Additional details such as the creator's social media followers and external promotional efforts could provide valuable context.

2. **Single Donor Analysis:**
   - Absence of data on individual donations within each campaign limits the ability to identify trends related to large contributions from single donors. Exploring the presence of substantial donations in successful campaigns compared to failed ones could unveil additional insights.

3. **Success Definition:**
   - The definition of success in this project is based on whether the creator reached their financial goal or the number of backers. However, success could also be measured by the effective utilization of raised funds for the intended purpose. This dataset does not capture such nuanced success criteria.
  - Success, as defined in the project, focuses on achieving fundraising goals. Yet, there is a potential discrepancy between reaching the defined financial target and the actual fulfillment of the project's intended purpose. Assessing project success beyond financial metrics may provide a more comprehensive understanding.
  - While the current definition of success is straightforward, measuring success based on the actual impact or fulfillment of project goals might be more complex and challenging to assess efficiently within the scope of this dataset.

Recognizing these limitations is crucial for a nuanced interpretation of the findings and emphasizes the potential for further data enrichment and refinement in future analyses.

## What are some other possible tables and/or graphs that we could create, and what additional value would they provide?

1. **Average Goal vs. Average Donation Analysis:**
   - **Table:** Create a pivot table comparing the average goal for successful campaigns versus failed campaigns alongside the average donation for successful campaigns versus failed campaigns.
   - **Graph:** Visualize the relationship between goal size, donation size, and campaign success/failure. This analysis could provide insights into correlations, helping future campaigners set realistic goals for success.

2. **Percentage of Successful/Failed Campaigns by Category and Subcategory:**
   - **Graph Enhancement:** Add an additional pivot graph to the category and subcategory tabs to display the percentage of successful and failed campaigns within each category or subcategory. This will offer a clearer comparison of success/failure rates across different categories, addressing the current challenge of interpretation due to varying campaign counts.

3. **In-Depth Analysis of "Greater than $50,000" Failed Campaigns:**
   - **Table:** Create a pivot table to examine the percentage of pledged amount relative to the goal within ranges (e.g., 0-25%, 26-50%, 51-75%, 76-99%) for failed campaigns with goals exceeding $50,000.
   - **Graph:** Visualize the distribution of failed campaigns in different pledge/goal ranges. This analysis can shed light on whether lofty goals in the "greater than $50,000" category receive higher pledge amounts and help understand the distribution of failed campaigns within various pledge/goal ranges.

These additional tables and graphs would provide valuable insights into the nuances of crowdfunding dynamics, allowing for a more informed and strategic approach in future crowdfunding endeavors.

## Credits

This project was conducted using fictional data provided by edX Data Analytics Bootcamp. 

Special thanks to:
-**[ablebits.com](https://www.ablebits.com/)**: Utilized for assistance with the COUNTIFS formula. 

-**AskBCS Learning Assistants**: Grateful for their support in adding newly created columns to the pivot table by clicking "refresh" under "data."
