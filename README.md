# excel-challenge
For this project, I was tasked with analyzing crowdfunding campaigns from an Excel dataset provided by edX Boot Camps LLC. Crowdfunding is when users utilize social media platforms to raise money for a cause. 

For the "Crowdfunding" worksheet (Figure 1), I utilized formulas and formatting to create a percent funded column with cells filled with different colors based on conditions. I also created an average donation column and splitted the column "Category and Sub-Catergory" column into two separate columns. 

Next, I created a "Success by Category" sheet (Figure 2) with a pivot table analyzing the number of successful, live, failed and canceled campaigns by category and a pivot chart visualization. 

The "Success by Subcategory" sheet (Figure 3) is a stacked-column pivot chart analyzing campaigns by subcategory. 

In order to create the "Success by Date" sheet (Figure 4), I first had to add a column to worksheet 1 coverting the "launched_at" column  to a new column "date_created_conversion" using a formula to convert the timestamp to a normal date. I did the same to convert the "deadline" timestamp to a new column "date_ended_conversion." Next, I was able to utilize the converted columns into a pivot table that has a column of "outcome", row of "Date Created Conversion," values based on the count of "outcome," and filters based on "parent category" and "Years." Last, I created a pivot table line chart to visualize this data.

For the "Goal Analysis" sheet (Figure 5), I created a new column called "Goal" where I utilized the COUNTIFS() formula to count how many successful, failed, and canceled projects were created with goals of differing ranges. 

Lastly, the "Statistical Analysis" sheet (Figure 6) was created in order to gain a better understanding of campaign backers. I first created four columns; successful outcomes, number of backers, unsuccessful outcomes, number of backers. I then utilized formulas to find the mean backers, median backers, minumum backers, maximum backers, variance of the number of backers, and the standard deviation of backers for both successful and unsuccessful campaigns. 

<img src="Visuals/Crowdfunding.png">

*Figure 1


<img width="877" alt="Worksheet 1" src="https://github.com/lorigirton/excel-challenge/assets/134968527/3cc5da62-da03-4a7a-b142-fe89bb75375a">

*Figure 1




<img width="738" alt="Sheet 2" src="https://github.com/lorigirton/excel-challenge/assets/134968527/d3cec5e7-e158-49fa-9c2c-92efe28c72ac">

*Figure 2

