
# Titanic Survival Analysis 


## Problem Statement          

The sinking of the Titanic in 1912 was a tragic event that resulted in the loss of over 1,500 lives. To understand the factors that contributed to the survival of the remaining passengers, we analyze detailed passenger data. The goal of this dashboard is to identify patterns and insights that reveal how different variables such as age, gender, class, and embarkation port influenced survival rates. By doing so, we aim to provide a clearer picture of the disaster and highlight key factors that affected survival chances.


### Steps followed 

- Step 1 : Import the Titanic dataset which is in .csv format for analysis and visualization.
- Step 2 : Checked for missing values, duplicates, and data consistency.
- Step 3 : Handled missing values by either imputing or removing them as appropriate. Used the downfill method to handle missing values in the Cabin column, ensuring continuity in data.

Snap of calculated column ,

![2024-07-21_12h53_35](https://github.com/user-attachments/assets/c06170d3-3c61-401e-97aa-38095f4d2455) 

![2024-07-21_12h54_04](https://github.com/user-attachments/assets/6f4b4405-df8a-4157-ad4f-5001d602a61f)

              
- Step 4 : Data Transformation, created age groups for simplified analysis.

Snap of calculated column ,

![2024-07-21_12h21_20](https://github.com/user-attachments/assets/80019ee7-937b-490b-b6fe-78eab6deed7c)
- Step 5 : Created pivot tables to summarize key data points such as survival rates by age group, gender, and embarkation port.
- Step 6 : Combined all visual elements into a single dashboard layout. Added interactive elements to allow users to explore different facets of the data.
 
 - Step 7 : Ensured the dashboard is ready for presentation and sharing.
 
 
![2024-07-21_13h26_39](https://github.com/user-attachments/assets/413e087d-f7de-49aa-a3a2-fdeb7f3a65ea)


# Insights

Following inferences can be drawn from the dashboard;

### [1] Total Passengers: 891

   Survival Count: 342 (38.38 %)

   Non-Survival Count: 549 (61.61 %)

   


           
           
### [2] Gender Distribution
Female Passengers: 233 (68.12 %)

 Male Passengers:  109 (31.87 %)

        Female passengers had a higher survival rate compared to male passengers.
  
 
  
  ### [3] Age-Based Survival Distribution
  Age Group (1-15):  56
  
  Age Group (16-30): 136
  
  Age Group (31-50): 126
  
  Age Group (51+):   24
  
        Younger passengers (16-30) had higher survival rates compared to older age groups.

 ### [4] Survival Outcome by Embarkation Port
 
Port C: 94

Port Q: 31

Port S: 217


 
         The embarkation port influenced survival rates, with Port S showing better outcomes.
 
 ### [5] Average Fare Analysis
 
 Survival: 48

 Non-Survival: 22
 
         Passengers who paid higher fares generally had better survival rates.
         
