# UN-World-Population-Prospects--Lebanon-Population-Analysis

Project Title: UN World Population Prospects 2024 - Lebanon Population Analysis  

**Introduction**

This project analyzes Lebanon's demographic evolution using UN World Population Prospects 2024 (Medium Variant).

**Data Source**

Official source: https://population.un.org/wpp/

File: WPP2024_Demographic_Indicators_Medium.csv

**Main Objective**  

To analyze population trends for Lebanon using official UN WPP data, understand how Lebanon’s demographics changed from 1950 to 2023 and what the UN projects until 2100.  

**Data and Features Chosen**

  Chosen features - efficient minimal set covering demographic balancing equation:

- Time: Year 1950-2100
- TPopulation1July: Total population in thousands (mid-year)
-  PopGrowthRate: Annual growth %
-  MedianAgePop: Median age - aging indicator
-  TFR: Total Fertility Rate - average kids per woman - MOST IMPORTANT
- LEx: Life Expectancy at birth
- CBR: Crude Birth Rate - births per 1000 people
- CDR: Crude Death Rate - deaths per 1000 people
- NetMigrations: Immigrants - Emigrants (negative = people leaving)



**Specific Objectives**

To answer:

- How did Lebanon's total population change from 1950-2023 ?
 
- When was the fastest growth?
 
- Is Lebanon getting older? (MedianAgePop)
 
- How did fertility rate (TFR) drop?

- How did life expectancy (LEx) improve and why did it crash?

- How does Lebanon compare to World for Total fertility rate (TFR) and  World average rate (LEx) ?
 
- How did net migration change?

- What is the UN scenario Immigration projection for Lebanon 2030, 2050, 2100?

**Methodology**  

Tools: Python, pandas, matplotlib / plotly  
Choose Lebanon from the table of UN measurements by Filtering ISO3 = LBN, then clean, visualize  .

**Analysis and Output**  
4-6 charts (population curve, median age, fertility, life expectancy, comparison,immigration)  

