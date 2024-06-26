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

- Step 4 : State names were group based on similar prefixes

- Step 5 : Changing datatype of numerical columns from decimal to fixed decimal to change some of the values to two decimal places .

  Snap of dataset after cleaning,

![Powerbi 1](https://github.com/daodu-tobi/Nrega-Analysis--Power-Bi/assets/145832039/c2b9e08d-6587-432d-9732-65987958befa)

- Step 6 : Creation of first visual set to display the effectivness of the scheme to provide employment opportunities across the states.

- Step 7 : The use of card visual were used to display two fields named, total number of 'states' and the total number of 'districts'

  Snap of visuals for counting states and districts

  ![Count of state and districts](https://github.com/daodu-tobi/Nrega-Analysis--Power-Bi/assets/145832039/c0da95aa-98ac-4bac-bc90-2f9997b53b70)

- Step 8: The use of clustered column charts was used to create a visual to display fields such as 'Total number of job cards', 'Active job cards', 'Total workers' and 'Active workers'.

   Snap of visuals for employment opportunities across states and districts

   ![Power bi 2](https://github.com/daodu-tobi/Nrega-Analysis--Power-Bi/assets/145832039/6ff65698-305c-4e0f-994f-bcf4d1a420ad)

- Step 9: Creation of hierarchy to make the districts a subset of each states and creating visuals through the use of line charts to display the budget allocation and its correlation with employment opportunities

  Snap of visuals for budget allocation

  ![Power bi 3](https://github.com/daodu-tobi/Nrega-Analysis--Power-Bi/assets/145832039/23676f71-6b81-48b2-a885-c0c5f1612af4)

- Step 10: The use of tables to calculate the sum of completed works, factors that contributed to the completed works
   
   Snap of visuals for completed works

   ![Power bi 4](https://github.com/daodu-tobi/Nrega-Analysis--Power-Bi/assets/145832039/17452cb4-3b3f-4bab-a8a3-557aced91ada)

