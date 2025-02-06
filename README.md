# Diversity-and-Inclusion


## Project Objective


This dashboard aims to support our telecom client in improving gender balance within their executive management by identifying key performance indicators related to hiring, promotion, performance, and turnover. These KPIs will offer valuable insights into the company's gender dynamics, enabling a data-driven approach to address existing imbalances. By examining metrics such as the percentage of women hired, promoted, and their average performance ratings, we seek to identify the underlying causes of slow progress in achieving gender diversity at the executive level.


## Dataset used


- <a href = "https://github.com/tonyvolen/Diversity-and-Inclusion/blob/main/03%20Diversity-Inclusion-Dataset.xlsx">Dataset</a>


## questions (KPIs)


- What is the total number of men ?
- What is the total number of women ?
- What is the total number of leavers ? 
- What is the percentage of employees promoted (FY21) ?
- What is the percentage of women promoted ?
- What is the percentage of hires for men ?
- What is the percentage of hires for women ?
- What is the percentage turnover ? 
- What is the average performance rating for men ?
- What is the average Performance ratingnfor women ?

  ## Dashboard link


- <a href = "https://github.com/tonyvolen/Diversity-and-Inclusion/blob/main/DIVERSITY%20INCLUSION.pbix">View Dashboard</a>



## Steps followed


- Load data into Power BI Desktop, dataset is a csv file.
- Verified data for any missing values and anomalies and sort out the same.
- Made sure data is  consistent and clean with respect to data types , data format and values used.
- Merged all pivot tables into one dashboard and apply slicers to make it dynamic.
- Navigated to the "Model" view to establish relationships between different tables.
- Used DAX to create calculated measures for KPIs such as gender distribution, promotion rates, and turnover rates.
- Visual filters (Slicers) were added for four fields named "Department", "Age group", "Job Level" & "Region group".
- In the Report view, I selected and customized appropriate visualizations from the Visualizations pane to effectively represent the KPIs. This process involved tailoring each visualization to accurately display the data, ensuring clarity and alignment with the project's objectives
  



  ## Dashboard




  ![DIVERSITY INCLUSION 2_6_2025 11_51_17 AM](https://github.com/user-attachments/assets/2b6ea87c-72f7-46a1-a7e7-55e71799a754)










![DIVERSITY INCLUSION 2_6_2025 11_49_03 AM](https://github.com/user-attachments/assets/03cfc0b8-07c1-4184-891e-5727882a2e71)






## project Insights 

### 1. Hiring


Upon analyzing the KPI data for hires across various job levels, the following gender distribution was observed:


- Junior Officer Level: 63% female hires and 37% male hires.
- Manager Level: 60% female hires and 40% male hires.
- Senior Manager Level: 30% female hires and 70% male hires.
- Director Level: 25% female hires and 75% male hires.
- Executive Level: 100% male hires.

  
This data indicates a significant gender disparity, with a higher proportion of female hires at junior and manager levels, and a predominance of male hires at senior manager, director, and executive levels. Notably, the executive level comprises entirely male hires, highlighting a critical area for intervention to promote gender diversity at the top management tier.

A column chart was used to represent hires across various job levels.


![DIVERSITY INCLUSION 2_6_2025 11_51_17 AM](https://github.com/user-attachments/assets/68e43c67-6002-4f83-9c09-946a295a2279)



Overally, there was a 52% of female hires and 48% of male hires

Snapshot of overal hires

![overal hires](https://github.com/user-attachments/assets/c9a637f8-a75a-4dd8-83f3-627406ce1dc0)





### 2. Promotions


Upon analyzing the promotion data visualized through a line and clustered column chart, the following gender distribution across job levels after fiscal year 2021 promotions was observed:

- Junior Officer Level: 91 female employees and 78 male employees.
- Senior Officer Level: 50 female employees and 46 male employees.
- Manager Level: 25 female employees and 54 male employees.
- Senior Manager Level: 11 female employees and 46 male employees.
- Director Level: 4 female employees and 29 male employees.
- Executive Level: 3 female employees and 16 male employees.
  
The line plot further revealed the following promotion rates for female employees:

22% promoted to Senior Officer.

8% promoted to Manager.

27.27% promoted to Senior Manager.

25% promoted to Director.

33.33% promoted to Executive.

These findings indicate a gender disparity in both the distribution of employees across job levels and the promotion rates to higher positions. Notably, the proportion of female employees decreases as the job level increases, with a significant underrepresentation at the Senior Manager, Director, and Executive levels. Additionally, the promotion rates for female employees vary across levels, suggesting potential areas for improvement in promoting gender equity within the organization.

A line and clustered column chart was used to represent promotions across various job levels for Male and Female 


![job levels after FY21 promotions](https://github.com/user-attachments/assets/c795c76e-d7eb-474a-827d-735fa93652d4)





Upon analyzing the average tenure data visualized through a clustered bar chart, the findings indicate that, in most job levels, male employees have a slightly longer average tenure compared to their female counterparts. Notably, at the Senior Manager level, male employees have a tenure of 2.3 years, which is 0.5 years longer than the 1.8 years observed for female employees. Conversely, at the Executive level, female employees have a tenure of 3 years, which is 1.14 years longer than the 1.86 years for male employees.

A snapshot of average tenure of employees across the job levels



![Tenure](https://github.com/user-attachments/assets/12c683c8-faf8-4da5-bec8-15636ba1048a)




### Performance Rating


Upon analyzing the performance rating data across genders, the following distribution was observed:


- Rating 4: 37% of female employees and 63% of male employees
- Rating 3: 40% of female employees and 60% of male employees
- Rating 2: 38% of female employees and 62% of male employees
- Rating 1: 38% of female employees and 62% of male employees

  
These findings indicate a gender disparity in performance ratings, with male employees consistently receiving higher ratings across all categories. Such disparities may be influenced by various factors, including unconscious biases in performance evaluations. Research suggests that numerical performance reviews can be biased against women, potentially due to cultural perceptions associated with rating scales.


Snapshot of performance Rating


![Performance rating](https://github.com/user-attachments/assets/63e22434-67df-4456-896d-1f7ea8b927f9)


The average performance rating for female was 2.41 and the average performance rating for male was 2.42.

Snapshot of average performance rating


![Average rating](https://github.com/user-attachments/assets/c813cbe5-aeef-4dd3-a033-43555cfa1b83)





### Executive Gender Balance


An analysis of the executive gender distribution for Fiscal Year 2020 (FY20) shows that out of a total of 16 executives, only 2 (12.5%) were female, while 14 (87.5%) were male. In terms of new executive hires, all 15 hires were male, and the 2 promotions to the executive level were also exclusively male. This indicates a significant gender disparity, with no female representation among the new hires or those promoted to the executive level, suggesting possible barriers to entry for women in senior leadership roles.

In Fiscal Year 2021 (FY21), the total number of executives increased to 19, with female representation rising slightly to 15.79% (3 executives), while male executives accounted for 84.21% (16 employees). Despite this modest increase in female representation, men continued to dominate the executive level. The data highlights that while there was some progress in gender diversity, the overall proportion of female executives remains low, indicating ongoing challenges for women in reaching senior leadership positions.


A snapshot of Executive Gender Balance


![Executive split](https://github.com/user-attachments/assets/a10667d5-df80-4860-acf5-e4a38299db43)
