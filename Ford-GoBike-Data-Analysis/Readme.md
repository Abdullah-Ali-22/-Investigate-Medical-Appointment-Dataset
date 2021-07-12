# Bike Share Analysis with Ford GoBike Data
### by Abdullah
## Dataset Overview
Ford Gobike Datasets a public bicycle sharing system represent trips taken by customers of the Ford Gobike service for the month of Feberaurary of 2019.
Currently has over 2,600 bicycles in 262 stations. Datasets consist of 16 columns and 183412 rows but after cleaning the data, I ended up with 174749 rows and 15 columns.

1   duration_sec                    
2   start_time                      
3   end_time                        
4   start_station_id                         
5   start_station_name                    
6   end_station_id                  
7   end_station_name                       
8   user_type                              
9   member_birth_year                       
10   member_gender                          
11  Enrolled_in_Bike_Share_Program        
12  member_age                              
13  start_day                               
14  Weekend                                  
15  weekday

# Prerequisites
## Before running the codes, you will need to install these:
### Libraries
Numpy, Matplotlip, Pandas, Seaborn
### Software
Jupter Notebook, Python 3

# Python Notebook and Scripts
Ford_GoBike_Exploration.ipynb- Main project file :a IPython Notebook that contains the analysis for the project.
##  
Ford_GoBike_Visualization.ipynb-- This IPython Notebook contains main sildes of the important viualizations.
##  
Readme.md

# Main Finding
1-Increasing the number of users as the increase of the user Age starting from age 20 years old till the peak with maximum nuber of user at age about 30 years old and then start to decrease again and almost there are no users above 80 years old.
2- Most of the trip durations are less than 20000 sec and duration of the bike trip start to decrease at age above 50 years old.
3- The Men gender at age between 20 and 50 yers old spent more time in their bike trip than Female gender at the same age period.
4-Both Customer users and Suscriber User showing similar distribution of the age and as expected Suscriber represent more Users than Customers.
5-Only 16.5 precent of the users started their riding in the weekend and the other during druing the week, That was not expecting as the people in the weekend have more time. The busiest day is Thursday which more users choosed this day to start their riding.
