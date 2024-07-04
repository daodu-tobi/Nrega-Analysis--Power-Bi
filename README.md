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

- Job cards rate were high in states with many districts and high number of work force.

   'BIHAR' with 38 districts and 23million workers got 18million job cards

   'UTAH' with 75 districts, 23million workers got 18million job cards

   'MAHARASHATRA' with 34 districts, 28million workers got 13million job cards

   'WEST BENEGAL' with 23 districts, 26 million workers got  9 million job cards

   'RAJASTHAN' with 33 districts, 23 million work force got 12 million job cards

- States with relatively high number of districts but lower number of work force were given few numbers job cards.

  'PUNJAB' with 23 districts, 3 million worker were given 2 million job cards.

  'KARALA' with 14 districts, 6 million workers were given 4 million job cards.

  'JAMMU' with 20 districts, 2 million workers were given 1 million job cards

  'MEGHALAYA' with 12 districts, 1 million workers got 655k job cards
 
- There are regional disparities in the distribution of employment in states with higher number of districts, as some states with more work force got less job card compared with some states with same number of districts and workers
    
  'WEST BENEGAL' with 23 districts, 26 million workers got  9 million job cards

  'RAJASTHAN' with 33 districts, 23 million work force got 12 million job cards

  Generally, job card distribution ratio in states with lower number of districts and work force was close

- Step 9 : Creation of hierarchy to make the districts a subset of each states and creating visuals through the use of line charts to display the budget allocation and its correlation with employment opportunities.

  Snap of visuals for budget allocation

  ![Power bi 3](https://github.com/daodu-tobi/Nrega-Analysis--Power-Bi/assets/145832039/23676f71-6b81-48b2-a885-c0c5f1612af4)

   #### INSIGHT FROM BUDGET ALLOCATION ANALYSIS
   
 - States with higher number of districts got higher budgets, however, WEST BENGAL had no budget all despite high number of districts.

      'UTTAH' with 75 district was allocated 210 million Rupee  from the total budget of (2 billion) Rupee 

      'ANDHRA' with 26 districts was allocated the highest budget 215 million

      'MADHYA' with 52 districts was allocated 200 million

 - Higher budgets in states with many districts resulted higher in number of employment

      'UTTAH' with 210 million budget had two million jobs available

      'ANDHRA' with 215 million budget had one million jobs available

      'MADHYA' with 200 million budget had one million jobs available

- With reduced budgets, employment rates in states reduced drastically.

        'NAGALAND' with 15 million budgets had only fifteen thousand jobs available
   
       'TRIPURA' with 20 million budjects had only 269 thosands jobs available

 - Completion of work was majorly high in states with higher job card rate
    

- Step 10 : The use of tables to calculate the sum of completed works, factors that contributed to the completed works
   
   Snap of visuals for completed works

   ![Power bi 4](https://github.com/daodu-tobi/Nrega-Analysis--Power-Bi/assets/145832039/17452cb4-3b3f-4bab-a8a3-557aced91ada)
  

   #### INSIGHT FROM COMPLETED WORK ANALYSIS

  - States with higher ratio of completed works to available works had higher number of active
 
  'UTTAH' has 16,630,532 active workers thereby completing 342,531 works

  'KANATAKA' has 10,627,340 active workers thereby completing 401,120

  'MADHYA' has 13,292,232 active workers thereby completing 420,359 works
  
  - Lack of approved funds to support workers in a state led to large number of uncompleted work



  #### RECOMMENDATIONS

  - For full effectiveness of the scheme budget distribution should be well monitored to avoid lack of funds in some states

  - Adding more budgets to the scheme will create more employment in states with more districts thereby more active workers for the completion of projects.

