# Project Title

# Tabacco Consumption in USA

### Dashboard Link : https://drive.google.com/drive/folders/1qA8AAX5-fim_cq2ddxPih1uj-wuaglzX

## Problem Statement

This dashboard helps the us tp understand the smoking trend in USA and worldwide. The reports focus on the below areas.
1. Smoking in USA
2. World wide scenario of Smoking
3. Exports and Imports for smoking in USA
4. Activities for cessation. 

To assess progress toward this objective, CDC analyzed self-reported data from the 2000 National Health Interview Survey (NHIS) sample Adult Core questionnaire and Cancer Control module. 

This report summarizes the findings of this analysis, which indicate that, in 2000, approximately 23.3% of adults were current smokers compared with 25.0% in 1993, reflecting a modest but statistically significant decrease in prevalence among U.S. adults. In 2000, an estimated 70% of smokers said they wanted to quit, and 41% had tried to quit during the preceding year; however, marked differences in successful quitting were observed among demographic groups. 

A comprehensive approach to cessation that comprises economic, clinical, regulatory, and educational strategies is required to further reduce the prevalence of smoking in the United States.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present.
- Step 5 : In the report view, under the view tab, theme was selected.
- Step 6 : Six card visuals were added to the canvas, one representing all the Measure values like "Smokes","Cigarattes","Tabacco".
           Using visual level filter from the filters pane, basic filtering was used.
- Step 7 : A Stacked bar chart was also added to the report design area representing the number of Total & Total Per Capita. While creating this visual, field named "Measure" was also added to the Legends bucket. 
- Step 8 : Filters and Slicers are also added to the report. 
In our dataset, Some parameters were assigned value 0, representing those parameters are not applicable for some customers.


ETL 
This basically the Step 1 - Step 3. In which after apply data profiling, I have replaced the "null" values in flag codes column to "Not available"

Thereafter the data is transformed to power query editor. 

