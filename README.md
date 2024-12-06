# Power-BI-Dashboard---Data-Professionals-Survey-
This repository is a Power BI Dashboard decsribing the characteristics and insights gained after analysing the data about data professionals collected through a survey a few months ago. 

- First observed the raw data about the data professionals. Contains information with the following fields:
  * Unique ID: A unique identifier for each survey taker
  * Email : email id of each survey taker. This column has only one value 'anonymous' for all survey takers
  * Date Taken (America/New_York) : Date on which survey was taken
  * Time Taken (America/New_York) : Time on which survey was taken
  * Browser : Blank column
  * OS : 
  * City : Blank column
  * Country : Blank column
  * Referrer : Blank column
  * Time Spent : Time spent to fill the survey
  * Q1 - Which Title Best Fits your Current Role? : Job Title
  * Q2 - Did you switch careers into Data? : Consists of 2 values Yes/No
  * Q3 - Current Yearly Salary (in USD) : The current annual salary in USD of each employee. Consists of saalry ranges as values 0-40k, 41k-65k, 66k-85k, 86k-105k, 106k-125k, 125k-150k, 150k-225k, 225k+
  * Q4 - What Industry do you work in? : values specifying the industry in which they worked in. Agriculture, Construction, Education, Finance, Heathcare, Real Estate, Tech, Telecommunication , and many different categories of other values for ex: 'Other (Please Specify):Igaming','Other (Please Specify):Coworking space' etc.
  * Q5 - Favorite Programming Language : Favourite programming languages. values are 'C/C++','Java','JavaScript','Python', 'R', and many categories of other values for ex: 'Other:Mostly use sql but that’s not programming language..', 'Other:Qlik sense script' etc.
  * Q6 - How Happy are you in your Current Position with the following? (Salary) : contains ratings from 0 to 10. Also has some blanks.
  * Q6 - How Happy are you in your Current Position with the following? (Work/Life Balance) : contains ratings from 0 to 10. Also has some blanks.
  * Q6 - How Happy are you in your Current Position with the following? (Coworkers) : contains ratings from 0 to 10. Also has some blanks.
  * Q6 - How Happy are you in your Current Position with the following? (Management) : contains ratings from 0 to 10. Also has some blanks.
  * Q6 - How Happy are you in your Current Position with the following? (Upward Mobility) : contains ratings from 0 to 10. Also has some blanks.
  * Q6 - How Happy are you in your Current Position with the following? (Learning New Things) : contains ratings from 0 to 10. Also has some blanks.
  * Q7 - How difficult was it for you to break into Data? : contains values describing how difficult it was to brak into data. Contains values 'Very Difficult','Difficult','Easy','Very Easy','Neither easy nor difficult'
  * Q8 - If you were to look for a new job today, what would be the most important thing to you? : contains values 'Remote Work','Good Work/Life Balance','Better Salary', 'Good Culture', and many other values for ex: 'Other (Please Specify):I would say a combination of good work/life balance with a better pay and the exposure to a workplace that supposed growth','Other (Please Specify):Currently very happy with where I am.' etc.
  * Q9 - Male/Female? : Gender. Contains 2 values Male/Female
  * Q10 - Current Age  :Current age of the professionals. contains values in range 18 to 92.
  * Q11 - Which Country do you live in? : contains values 'Canada', 'India', 'United Kingdom', 'United States', and many other values for ex: 'Other (Please Specify):Republic democratic of Congo ', 'Other (Please Specify)', 'Other (Please Specify):Serbia' etc.
  * Q12 - Highest Level of Education : contains values 'Associates', 'Bachelors', 'High School', 'Masters', 'PhD'. Also has blanks.
  * Q13 - Ethnicity : Ethnicity of the professionals. Contains values 'White or Caucasian', 'Asian or Asian American', 'Black or African American', 'Hispanic or Latino', 'Native Hawaiian or other Pacific Islander', 'American Indian or Alaska Native', and many other values for ex: 'Other (Please Specify):African ', 'Other (Please Specify):Bi-racial people should be able to check 2 options in 2022. ' etc.

    - Secondly cleaned and standardized the data in power query editor. removed and corrected any errors, dealt with blank columns, standardized the values , changed data types, created custom columns
    - Thirdly used the cleaned and standardized data to create visualizations as a dashboard which gives insights and visually compare, contrast and learn about various characteristics. Created visualizations such as Country of Survey Takers (Treemap), Average Salary by Job Title (Stacked bar chart), Count of Survey Takers (Card), Average Age of Survey Taker (Card), Count of Voters by  Favorite Programming Language (stacked column chart), Difficulty to Break Into Data (Donut chart), Happiness with Work/Life Balance (Gauge), Happiness with Salary (Gauge).
   
    - The final dashboard has all teh above mentioned visualizations. 
