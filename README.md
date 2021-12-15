# Kickstarter Data Analysis  

Data analysis and visualization using charts and pivot tables in Excel.

## Description

This repository is designed to uncover market trends by analyzing and visualizing data from 4,000 Kickstarter projects. 
### Data tab
- Conditional formatting is used in the **State** column to color code projects as successful (green), failed (red), canceled (yellow), or live (grey). 
- The **Percent Funded** column uses a formula to uncover how much money a campaign made to reach its initial goal, and conditional formatting is used to color code funding amounts (0-99; red, 100-199; green, 200; blue).
- The **Average Donation** column uses a formula to uncover how much each backer for the project paid on average.
- The **Category** and **Sub-Category** columns use formulas to split the **Category and Sub-Category** column into two parts.
- The **Date Created Conversion** column uses a formula to convert the Unix timestamp data in the **launched_at** column into Excel's date format.
- The **Date Ended Conversion** column uses a formula to convert the Unix timestamp data in the **deadline** column into Excel's date format.
<p align="center">
  <img src="https://user-images.githubusercontent.com/74067302/146103340-29efbfab-be63-4fef-a516-22c16e8d376d.png" alt="Dashboard Image"/>
</p>

### Pivot 1_Category tab
- This sheet contains a pivot table that analyzes the **Data** worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category. The stacked column pivot chart can be filtered by country.

### Pivot 2_Subcategory tab
- This sheet contains a pivot table that analyzes the **Data** worksheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category. The stacked column pivot chart can be filtered by country and parent-category.
<p align="center">
  <img src="https://user-images.githubusercontent.com/74067302/146103546-87260a18-21d7-4b89-923b-cc47ab3e095c.png" alt="Dashboard Image"/>
</p>

### Pivot 3_Dates tab
- This sheet contains a pivot table with a column of state, rows of Date Created Conversion, values based on the count of state, and filters based on parent category and Years, and a pivot chart line graph that visualizes this table.
<p align="center">
  <img src="https://user-images.githubusercontent.com/74067302/146104544-17c9e503-a770-4b64-a71a-2ee1981f542e.png" alt="Dashboard Image"/>
</p>




## Getting Started

### Technologies Used 

* Microsoft Excel

### Installing

* Clone this repository to your desktop.
* Navitage to the home directory and open index.html in your browser.

### Data Sources

* Hulcr J, Latimer AM, Henley JB, Rountree NR, Fierer N, et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. PLoS ONE 7(11): e47712. doi:10.1371/journal.pone.0047712 [Access Data](http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/)


## Authors

Katlin Bowman, PhD

E: klbowman@ucsc.edu

[LinkedIn](https://www.linkedin.com/in/katlin-bowman/)
