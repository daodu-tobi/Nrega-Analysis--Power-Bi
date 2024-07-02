# NREGA ANALYSIS

This project analyzes NREGA data to evaluate its effectiveness, regional disparities, budget utilization, and factors affecting completion.

## Problem Statement

NREGA is a vital initiative to alleviate rural unemployment and poverty. This project seeks to address 
several key questions and challenges associated with NREGA:

● How effective is NREGA in providing employment opportunities to rural households?

● Are there regional disparities in the implementation and outcomes of the scheme?

● What is the utilization of the allocated budget, and how does it correlate with 
employment generation?

● What are the key factors contributing to the completion of NREGA works, and are there 
any roadblocks to its success?

● Can data-driven insights guide policymakers and administrators in optimizing the 
scheme's impact?

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.

- Step 2 : Open power query editor to clean data and get data ready for analyzes.

- Step 3 : Reduction of entries names in categorical columns to aid better vizualization.
  
         'SILIGURI MAHAKUMA PARISAD' was reduced to 'SILIGURI M'
         'Darjeeling Gorkha Hill Council (DGHC) was reduced to 'DGHC
         'EASTERN WEST KHASI HILLS' was reduced to 'E.W.KHASI H.'
        
- Step 4 : State names were group based on similar prefixes
  
     For example 'ANDHRA PRADESH' occured so many times, so it was reduced to 'ANDHRA'.
  
     'ANDAMAN AND NICOBAR' was reduced to 'ANDAMAN'
  
- Step 5 : Changing datatype of numerical columns from decimal to fixed decimal to change some of the values to two decimal places for easy calculation .

  Snap of dataset after cleaning,

![Powerbi 1](https://github.com/daodu-tobi/Nrega-Analysis--Power-Bi/assets/145832039/c2b9e08d-6587-432d-9732-65987958befa)

- Step 6 : Creation of first visual set to display the effectivness of the scheme to provide employment opportunities across the states.

- Step 7 : The use of card visual were used to display two fields named, total number of 'states' and the total number of 'districts'

  Snap of visuals for counting states and districts

  ![Count of state and districts](https://github.com/daodu-tobi/Nrega-Analysis--Power-Bi/assets/145832039/c0da95aa-98ac-4bac-bc90-2f9997b53b70)

   

- Step 8 : The use of clustered column charts was used to create a visual to display fields such as 'Total number of job cards', 'Active job cards', 'Total workers' and 'Active workers'.

   Snap of visuals for employment opportunities across states and districts

   ![Power bi 2](https://github.com/daodu-tobi/Nrega-Analysis--Power-Bi/assets/145832039/6ff65698-305c-4e0f-994f-bcf4d1a420ad)

   #### INSIGHT FROM EMPLOYMENT ANALYSIS 

  - Job cards rate were high in states with many districts.

  - States with less districts were given few numbers employment.

  - There are more workers in states with many districts therefore job cards to active job card ratio was high.

  - There are no regional disparities in the distribution of employment as states with more districts got more employment due to higher number of workers and states with fewer districts got fewer number of employment due to low number of workers.
    

- Step 9 : Creation of hierarchy to make the districts a subset of each states and creating visuals through the use of line charts to display the budget allocation and its correlation with employment opportunities.

  Snap of visuals for budget allocation

  ![Power bi 3](https://github.com/daodu-tobi/Nrega-Analysis--Power-Bi/assets/145832039/23676f71-6b81-48b2-a885-c0c5f1612af4)

   #### INSIGHT FROM BUDGET ALLOCATION ANALYSIS 

    - States with higher number of districts got higher budgets, however, WEST BENGAL had no budget all despite high number of districts.

    - Higher budgets in states with many districts resulted higher in number of employment

     - With reduced budgets, employment rates in states reduced drastically.

  - Completion of work was majorly high in states with higher job card rate
    

- Step 10 : The use of tables to calculate the sum of completed works, factors that contributed to the completed works
   
   Snap of visuals for completed works

   ![Power bi 4](https://github.com/daodu-tobi/Nrega-Analysis--Power-Bi/assets/145832039/17452cb4-3b3f-4bab-a8a3-557aced91ada)
  

   #### INSIGHT FROM COMPLETED WORK ANALYSIS

  - States with higher ratio of completed works to available works had higher number of active 
  
  - Lack of approved funds to support workers in a state led to large number of uncompleted work



  #### RECOMMENDATIONS

  - For full effectiveness of the scheme budget distribution should be well monitored to avoid lack of funds in some states

  - Adding more budgets to the scheme will aid in acquiring more active workers for the completion of projects


