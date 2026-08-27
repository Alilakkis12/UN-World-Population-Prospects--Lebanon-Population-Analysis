# UN-World-Population-Prospects--Lebanon-Population-Analysis

Project Title: UN World Population Prospects 2024 - Lebanon Population Analysis  

**Introduction**

This project analyzes Lebanon's demographic evolution using UN World Population Prospects 2024 (Medium Variant).

**Data Source**

Official source: https://population.un.org/wpp/

File: WPP2024_Demographic_Indicators_Medium.csv

**Main Objective**  

To analyze population trends for Lebanon using official UN WPP data, understand how Lebanon’s demographics changed from 1950 to 2023 and what the UN projects until 2100.  

**Specific Objectives**

**1. Population Growth Analysis**

How did Lebanon’s total population change from 1950-2023?  
When was the fastest growth?  
What does UN project for 2030, 2050, 2100? 

**2. Age Structure Analysis**  

Is Lebanon getting older?   


**3. Fertility & Life Expectancy**  
How did fertility rate (TFR) drop?  
How did life expectancy improve?  

**4. Comparison Analysis**  
Compare Total fertility rate of Lebanon vs  World average rate  
Compare Life Expectancy at birth of Lebanon vs  World average rate    

**5. Future Projections**  
What is the UN scenario Immigration projection for Lebanon in 2050?  
 

**Methodology**  

Data source: UN WPP 2024 Standard Projections (CSV format)  
Tools: Python, pandas, matplotlib / plotly  
Load data directly via pandas.read_csv() from UN official url: https://population.un.org/wpp/downloads?folder=Standard%20Projections&group=CSV%20format  
Filter ISO3 = LBN, clean, visualize  

**Expected Output:**  
4-6 charts (population curve, median age, fertility, life expectancy, comparison,immigration)  

