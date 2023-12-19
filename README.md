# Arizona Bureau of Labor (BLS) Mortgage Statistics 2001 - 2021
This project uses the Arizona Bureau of Labor Statistics (BLS) Wages from the U.S. Bureau of Labor Statistics to answer several questions using the R programming language. I used the R programming language to analyze the data from the National Mortgage Database and created graphs that answered the prompting questions.

## Dataset Information

Title: Bureau of Labor Statistics (BLS) Wages - Arizona

Date of Study: 2021

**Original owners:** U.S. Bureau of Labor Statistics (BLS)

**Source:** https://www.bls.gov/cew/downloadable-data-files.htm

**Relevant Information:** https://www.bls.gov/cew/about-data/downloadable-file-layouts/annual/naics-based-annual-layout.htm

## Table Columns
The table used is a simplified version of the BLS Wages in Arizona, with some columns removed or modified. All data comes from the state of Arizona.

own_code - 1-character ownership code.

industry_code - 6-character industry code (NAICS, SuperSector).

agglvl_code - 2-character aggregation level code.

year - 4-character year.

area_fips - 5-character FIPS code.

annual_avg_wkly_wage - Average weekly wage based on the 12-monthly employment levels and total annual wage levels.

annual_avg_emplvl - Annual average of monthly employment levels for a given year.

avg_annual_pay - Average annual pay based on employment and wage levels for a given year.

agglvl_title - Multi-character aggregation title associated with the agglvl code (Excluded from singlefile).

industry_title - Multi-character industry title associated with the industry code (Excluded from singlefile).

own_title - Multi-character ownership title associated with the ownership code (Excluded from singlefile).

area_title - Since this is only in Arizona, all area_title values are "Arizona Statewide".

## Retrieved table from
- https://www.bls.gov/cew/downloadable-data-files.htm

# Charts Generated For This Project
## What are some of the key characteristics of employment size and salaries in the State of Arizona?
![Image](https://github.com/SMarbella/Arizona-Mortgage-Statistic/blob/main/Images/mean_employees_industries.png)
- **Figure 1.** Loess curve line plot showing the locally weighted average number of employees working in the top six industries in the state of Arizona.

In Figure 1, the Healthcare and Retail industries have the highest average number of employees. The Healthcare industry’s average number of employees increased the most from approximately 9,300 in 2001 to 14,100 in 2021, which is a 52% increase. The Mining industry had the lowest average number of employees and remained relatively stable at approximately 1,100 from 2001 to 2021. The 2008-2010 recession negatively affected the average number of employees in the Retail, Agriculture, Manufacturing, and Healthcare industries while the Mining and Information Technology industries remained relatively stable. After the recession, the average number of employees in the top 6 industries, except for Agriculture and Mining, increased. However, in 2020-2021, some industries decreased slightly in their number of employees possibly due to the Covid-19 pandemic.

![Image](https://github.com/SMarbella/Arizona-Mortgage-Statistic/blob/main/Images/median_pays_industries.png)
- **Figure 2.** Loess curve line plot describing locally weighted median annual pay of employees for the top six industries in the state of Arizona.

In Figure 2, Information Technology is the highest-paying industry, with the employees’ median annual pay from approximately $40,000 in 2001 to $65,000 in 2021, which is a 63% increase. The Agriculture industry has the lowest median annual pay but has the highest percentage of increase from approximately $22,000 in 2001 to $45,000 in 2021, which is a 105% increase. The employees’ median annual pay in the Mining industry significantly decreased from around $25,000 in 2001 to less than $5,000 in 2003. From 2003 to 2021, it fluctuates significantly but increases overall. The median annual pay of employees in Agriculture, Healthcare, Information Technology, Manufacturing, and Retail slightly increased over time from 2001 to 2021.

![Image](https://github.com/SMarbella/Arizona-Mortgage-Statistic/blob/main/Images/mean_employees_company_types.png)
- **Figure 3.** Loess curve line plot showing the locally weighted average number of employees working in each company type in the state of Arizona.

In Figure 3, the Federal Government companies have the highest average number of employees. Their average number of employees increased from 9,200 in 2001 to 11,500 in 2021, which is a 25% increase. Private companies have the lowest average number of employees. Their average number of employees increased from 5,900 in 2001 to 7,100 in 2021, which is a 20% increase. Local Government companies’ average number of employees increased the most from 8,000 in 2001 to 10,200 in 2021, which is a 27.5% increase. In the 2008 recession, the Federal Government, Local Government, and Private companies had a decrease in their average number of employees while the average number of employees in the State Government remained stable and increased over time. In 2020-2021, the number of employees in Private companies did not increase nor decrease because they possibly stopped hiring due to the Covid-19 pandemic.

![Image](https://github.com/SMarbella/Arizona-Mortgage-Statistic/blob/main/Images/median_pays_company_types.png)
- **Figure 4.** Loess curve describing locally weighted median annual pay of employees for all company types in the state of Arizona.

In Figure 4, from 2001 to 2021, the State Government’s median salaries remained the highest compared to the rest of the company types. The State Government’s median annual pay increased from approximately $35,000 in 2001 to $55,000 in 2021, which is a 57% increase. Although the median annual pay in Private companies remained the lowest, it has the highest percentage of increase from approximately $26,000 in 2001 to $50,000 in 2021, which is a 92% increase.

In conclusion, in the state of Arizona, the Information Technology industry and State Government companies have the highest median pay. The Agriculture industry and Private companies have the lowest median pay. The largest number of employees are in the Healthcare industry, Retail industry, and Federal Government companies. The Mining industry and Private companies have the lowest number of employees.
