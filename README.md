# AIRLINE DELAY
## INTRODUCTION 
 Delay is one of the most remembered performance indicators of a transportation system. This is a capstone project for the 30days of learning challenge Data Analysis using Powerbi Track. Thorough research was conducted on the causes of airline delay, and which brings about an interactive insights. The Documentation includes:
 
 •	Data Gathering and Transformation
 
•	Data Modelling

•	Recommendation 

•	Conclusion 

## Data Gathering and Transformation:

The data was provided on https://aka.ms/30DLDATGitHubRepo and which was sourced from https://www.kaggle.com/datasets/jimschacko/airlines-dataset-to-predict-a-delay. After extracting the data, a lot of research work was done on airline delay and the causes of airline delay. Here are some of the things that was done before proper visualizations.

•	Changing the airline abbreviations: This was done through research, searching for the airline with the abbreviations provided. Conditional column was used to code and rename the airline.

•	Days of the week: for proper visualization and understanding of the days of the week provided. It is required to change it from numbers to text format and this was also done using conditional column

•	Adding a new column to represent the state where the airline was located: This was also done through research work by searching for the airline where the state was located.

•	Changing the flight delay: This was also done by using create column by example and 0 was represented as flight delay while 1 was represented as flight not delayed. 
After all the steps were taken, errors and empty spaces were removed, and the dataset was transformed to the powebi desktop.

## Data Modelling

After the data was transformed into the powerbi desktop, I discovered there was a need for a relationship  and looking at the data available there is no relationship, and that was what brought about creating a new sheet for airport from and airport to and researching on where the airport was located in other to build a relationship with the airline data. The relationship was created, and it looked like this.


![Airline Model](https://user-images.githubusercontent.com/106280893/179356274-15f83a7b-0ec5-4da9-ae5d-8665ab5fbd65.png)

## Insights

![Airline](https://user-images.githubusercontent.com/106280893/179356355-0f62c09d-2337-4c45-84e4-0040959d7d82.png)

![Airline Dashboard](https://user-images.githubusercontent.com/106280893/179356405-6eb25b6a-a43f-4993-b89a-3f02667bc8ae.png)

![Airline Route](https://user-images.githubusercontent.com/106280893/179356421-ba2aff92-f074-41ed-871c-f14b62f2aaf4.png)


## Recommendation
According to the research carried out it was discovered that the causes of airline delay can be attributed to weather, lengthy onboarding process i.e waiting for those with no direct flight etc. But according to my analysis and the data provided, here are my recommendations:

•	Tuesday had the highest number of flight delay during weekdays.So,Passengers can try to avoid travelling on Tuesdays unless they are willing to pay more on lodging.

 •	southwest Airline had the highest number of flight delay.so,Southwest airline should put in place procedures to speed up the onboarding process to make travelling easier and faster for passengers.
 
•	Also based on the analysis carried out, it was also discovered that the state with the highest number of flight delay is Dallas,Texas. It is assumed that most passengers stop at Dallas,Texas before going to their final stop, Airlines in Dallas should suggest an alternative route for passengers to stop before thier final stop to avoid delay  


## Conclusion: 

History on flight delay from the past is majorly due to the weather condition or overloading of passengers. Based on my analysis and observation flight delay might also be as a result of not getting a direct flight to a desired destination and this can be overcome by building more airports in the location where it was affected.
