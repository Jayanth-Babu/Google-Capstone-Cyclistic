# How Does a Bike-Share Navigate Speedy Success ?

## Business Task:
How do annual members and casual riders use Cyclistic bikes differently?
Design a new marketing strategy to convert casual riders into annual members

## Key Stakeholders:
Director of Marketing and Cyclistic Executive Team.

## Data Sources:
Datasets are obtained from Motivate International Inc. Raw Data is structured data, complete and relevant to the problem being solved. There were no issues with bias or credibility as it is the internal and primary data collected by the Cyclistic team. Further, it satisfies the ROCCC i.e. Reliable, Original, Comprehensive, Current and Cited which ensures that data is from a good data source. The data is for complete six-month period with accuracy, consistency and trustworthiness which verifies the data’s integrity. The given data need to be cleaned for further analysis.

## Process: Cleaning and Manipulation of Data
1.	Used Excel for the whole process staring from cleaning to creating visualizations as it is handy for me.
2.	Cleaned the data with data entry errors by calculating the ride length and deleting the rows within 30 seconds of ride length.
3.	Searched for NULLs using Conditional formatting and filters.
4.	Located some misspelled words and corrected.
5.	Checked and formatted the all the data formats like numeric, date, string data are type casted correctly and ensured to be consistent and meaning throughout the datasets.
6.	Removed extra spaces and characters using TRIM function
7.	Removed Duplicates using the Remove Duplicates function
8.	Renamed the columns meaningfully 
9.	Checked for truncated or any missing data which needs correction
10.	Lastly, checked that whether the data makes sense to solve the given business task

## Summary of Analysis:
1.	Summarized the variation of average ride length, no. of ride trips of both the type of riders throughout the week for 6 months. Also, the usage of different bike types of the riders.
2.	It was found that the no. of ride trips of the member riders is higher than the casual riders.
3.	But, surprisingly it was discovered that the average length of casual riders is more than the member riders.
4.	Significant decrease in no. of ride trips of both types of riders from December to February (Winter season) and further linear increase from February.  
5.	Further, docked bikes are found to be least preferred among Classic bikes, docked bikes and electric bikes.
6.	Further, a similar day-wise trend was observed for the both types of riders throughout the six months.

## Supporting Visualizations and Key findings:
### 1.	Average Ride Length Trend of both Casual and Member riders

![image](https://github.com/user-attachments/assets/109b92fe-12ba-4184-8c9d-d5f344c84779)



### 2.	Variation in number of Ride trips of Casual and Member riders

![image](https://github.com/user-attachments/assets/966934be-35f6-406b-a8b9-7585fc6df552)



### 3.	Usage of different bike types by riders

a)	Casual Riders

![image](https://github.com/user-attachments/assets/7368d368-ffec-4cb2-b3dc-ce4d4e670211)

b)	Member Riders

![image](https://github.com/user-attachments/assets/314b8587-c7c1-4280-8c9a-b7c0f4d2706e)

### 4.	Day-wise breakdown of no.of trips of riders.

a)	Casual Riders

![image](https://github.com/user-attachments/assets/054eb436-f59c-4071-b202-29d4d1aa7ce6)

b)	Member Riders

![image](https://github.com/user-attachments/assets/c25a5677-d1ce-482d-92ba-f0d9e59480e9)


## Recommendations:
1.	As average ride length of the casual riders is higher than that of member riders, we can try offering a free membership subscription to those with ride length above a certain limit (i.e., for a limited time period). This way we can retain some of the riders as members.
2.	Offering coins equivalent to currency on basis of ride length for only member riders. Since, casual riders’ ride length is high they might prefer taking the membership to take advantage of high ride length. 
3.	We found that trips count declined during the winter season so, it is recommended to implement this strategy after winter season.
4.	Moreover, docked bike types are very less preferred so, we can exclude this type and increase the electric bikes to cater to the needs of new trial members.






















