# Arizona-Mortgage-Statistic
This project uses the Arizona Bureau of Labor Statistics (BLS) Wages from the U.S. Bureau of Labor Statistics to answer several questions using the R programming language.

## Dataset Information

Title: Bureau of Labor Statistics (BLS) Wages - Arizona

Date of Study: 2021

**Original owners:** U.S. Bureau of Labor Statistics (BLS)

**Source:** https://www.bls.gov/cew/downloadable-data-files.htm

**Relevant Information:** https://www.bls.gov/cew/about-data/downloadable-file-layouts/annual/naics-based-annual-layout.htm

**PDF:** 

## Table Columns
The table used is a simplified version of the BLS Wages in Arizona, with some columns removed or modified.

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
