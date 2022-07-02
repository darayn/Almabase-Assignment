# Almabase-Assignment
 Assignment activity consists of methodology of finding duplicate profiles based on attributes given

## How to test this project

1. Open the Jupyter Notebook 'Almabase Final'
2. Install Pandas, Fuzz if required by just using "!pip install {library Name}"
3. Run all The cells from Starting 
4. We can pass multiple Profiles at a time, as duplicate finder fuction forms the pair and calcultes the score with each other.
5.Check into "database.csv" where profiles matched having score more than 1 are stored.



## 1 -> Declaring the Profile Class
     It has members such as first_name, last_name, email_field, date_of_birth(not mandatory), class_year(not mandatory)
     Also applied some validations
     
     
## 2 -> Duplicate Finder Helper
    In this method we can pass on 3 arguments i.e 1. Profile 1 2. Profile 2 3. Fields
    This method computes the total score of profile 1 against profile 2 and return the desired string and score in te form of dictionary
    
## 3 -> Duplicate Finder
    This methods takes into considerarion all the list of profile as argument 1 and Fields to be considered as argument 2. 
    It call Duplicate Finder Helper by passing unique pairs of profile in a Profiles List.
    The return string is prinited and score is used to determine whether to add the profile into the Duplicate Profile Table.
     
     

