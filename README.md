# UN-World-Population-Prospects--Lebanon-Population-Analysis

Project Title: UN World Population Prospects 2024 - Lebanon Population Analysis
Main Objective:
To analyze population trends for Lebanon using official UN WPP data, understand how Lebanon’s demographics changed from 1950 to 2023 and what the UN projects until 2100.  

Specific Objectives:

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

Lebanon vs neighboring countries: Syria, Jordan, Turkey  
Lebanon vs MENA average vs World average  

**5. Future Projections**  
What are the 3 UN scenarios (Low, Medium, High) for Lebanon in 2050?  
When will Lebanon’s population peak and start to decline?  

**Methodology**  

Data source: UN WPP 2024 Standard Projections (CSV format)  
Tools: Python, pandas, matplotlib / plotly  
Load data directly via pandas.read_csv() from UN official URL  
Filter ISO3 = LBN, clean, visualize  

**Expected Output:**
4-5 charts (population curve, median age, fertility, life expectancy, comparison)  
Streamlit dashboard (optional)  
Insights summary in README  
