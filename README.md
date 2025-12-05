# Canada-Immigration-Population-Analysis-1990-2025-

## Introduction

As a recent immigrant to Canada, I became curious about how immigration shapes the country socially, economically, and demographically. I often saw headlines and discussions about *“Canada needing immigration,”* and I wanted to move beyond headlines and into hard data.

This project is a deep analytical exploration of Canada’s immigration patterns over 35 years, examining where immigrants come from, how gender patterns have shifted, and how immigration influences Canada’s population structure and sustainability.

## Objective of the Project

The main objectives of this project were to:

+ Understand long-term trends in immigration to Canada

+ Identify which countries contribute the most immigrants

+ Examine the gender composition of immigrants

+ Analyze how immigration affects Canada’s total population

+ Investigate whether Canada’s natural birth rate alone can sustain population growth

+ Provide a data-driven perspective on Canada’s demographic future

## What Inspired the Project (Personal Motivation)

Coming to Canada myself, I experienced the immigration system firsthand. I also observed how Canadian society and economy openly emphasize the importance of newcomers in universities, healthcare, IT, and workforce development.

This led me to ask: *“Is immigration simply an economic boost, or is it actually critical for Canada’s survival as a growing nation?”*

This project is my attempt to answer that question with data rather than opinion.

## Tools Used

+ Power BI - Data modeling & dashboard visualization

+ Power Query - Cleaning & transforming data

+ DAX - Creating measures & calculations

+ Excel - Initial data formatting

## Data Sources

UN International Migrant Stock Dataset - https://www.un.org/development/desa/pd/content/international-migrant-stock                                                                           Provides total counts of foreign-born people living in Canada from various countries over time.

Worldometer - Canada Population Dataset - https://www.worldometers.info/world-population/canada-population/#google_vignette  Includes total population, median age, fertility rate, and population growth metrics.

Country Standard code - https://unstats.un.org/unsd/methodology/m49/overview

After merging and standardizing the three datasets, I created a single analytical dataset that enabled demographic comparisons and population projections.

## Steps Taken
### 1. Data Collection

 + Downloaded UN migrant stock data (1990 - 2024)

 + Downloaded Worldometer population statistics (1990 - 2025)

 + Downloaded country ISO codes for mapping

### 2. Data Cleaning

 + Removed merged header rows

 + Fixed hidden column labels

 + Standardized country names

 + Converted year values to numeric

 + Standardized gender values

 + Merged ISO country codes into the master table

### 3. Data Modeling

 + Created a calendar table for time intelligence

 + Established one-to-many relationships

 + Implemented proper date/Year links

### 4. DAX Calculations

  Created measures for:

 + Total Immigrants

 + Total Male / Female Immigrants

 + Latest year values

 + Immigrant share of population

 + Net migration contribution

 + Natural population growth

### 5. Visualization & Page Structure
 The dashboard consists of 4 analytical pages.

 ## PAGE 1 - Canada Immigration Overview
 ### Highlights:

+ Canada’s foreign-born population grew from 4.2 million in 1990 to 8.8 million in 2025.

+ The percentage of immigrants as a share of Canada’s population rose from 15.22% in 1990 to 22.16% in 2025.

+ Peak immigration year (net migration): 2022–2023, reaching 460 thousand plus new arrivals.

+ Canada ranks 38th globally by population.

### Insight:

The chart shows that Canada continues to rely heavily on immigration to support labour needs, population growth, and demographic sustainability.<img width="2234" height="1250" alt="Page 1" src="https://github.com/user-attachments/assets/aa8d4b90-31e3-458a-814e-9abe1288b5d9" />

## Page 2 - Immigration by Country of Origin
### Historical Immigrant Totals (All years combined)

#### Top countries contributing to total immigrants:

+ United Kingdom - 4.6 million

+ China - 4.5 million

+ India - 4.2 million

+ Philippines - 3.4 million

+ Italy - 2.2 million

#### Recent Immigration (Latest Year Only)

+ India - 1.02 million

+ China - 0.84 million

+ Philippines - 0.84 million

+ Pakistan - 0.27 million

+ United States - 0.26 million

### Insight:

+ Historically, immigration was dominated by Europe, especially the United Kingdom and Italy.

+ Modern immigration is dominated by Asia, especially India, China, and the Philippines.

+ Canada’s shift reflects changes in global labor migration and Canadian immigration policy diversification.<img width="2246" height="1252" alt="Page 2" src="https://github.com/user-attachments/assets/7ab8d751-65a1-4a26-aa4e-6e8339abd377" />

## Page 3 - Gender Composition
### Highlights:

+ Female immigrants: 52.6%

+ Male immigrants: 47.4%

+ Female-led migration is higher from the USA, Venezuela, and Ukraine

+ Male-led migration is higher from the United Arab Emirates

### Insight:

The immigrant population in Canada is slightly female-majority, and this difference has gradually increased over time. When examining gender distribution by country of origin, most countries show a higher share of female immigrants, including the United Kingdom, United States, Ukraine, Venezuela, Viet Nam, Zimbabwe, and Uruguay, all of which have more than half of their immigrants being women. The only country showing a male-leaning immigrant share in the data is the United Arab Emirates, with around 53% male representation. The rise in female migration suggests greater family-based relocation and skilled professional migration among women.<img width="2010" height="1160" alt="Age   Gender" src="https://github.com/user-attachments/assets/0269ed9f-86f9-4193-a253-a7e8c943c6bd" />


## Page 4 - Population Context of Canada
### Highlights:

+ Canada grew from 27.6 million in 1990 to 40 million in 2025
+ Immigrants increased from 4.2 million to  8.8 million
+ Canada’s fertility rate declined to 1.34, below the replacement fertility level (2.1)
+ Median age increased to 40.5 years
+ Immigration now accounts for 60–80% of population growth
+ Natural Population Growth (births vs deaths) has decreased since the 1990s; without immigration, Canada’s population would stagnate

### Insight:

Canada’s demographic trajectory over the past three decades shows a dramatic shift toward immigration-driven population growth. The country expanded from 27.6 million people in 1990 to 40 million in 2025, and international migration has been a major contributor to this growth. During that same period, the immigrant population more than doubled, rising from 4.2 million to 8.8 million, demonstrating Canada’s increasing reliance on foreign-born residents to sustain its workforce and economy.

At the same time, internal demographic indicators reveal a declining natural growth trend. The national fertility rate has fallen to 1.34, significantly below the population replacement threshold of 2.1 children per woman, while Canada’s median age has risen to 40.5 years, reflecting an aging population. These patterns indicate that births alone are no longer sufficient to maintain population stability.

As a direct consequence, immigration now accounts for 60–80% of Canada’s total population growth, overtaking natural births as the dominant source of expansion. The data shows a steady decline in *Natural Population Growth (births minus deaths)* since the 1990s, meaning that, without sustained immigration, Canada would face population stagnation, labour shortages, and increased pressure on pension and healthcare systems.

Lastly, the evidence clearly illustrates that immigration is not just an economic policy choice for Canada, it has become a *structural requirement for national sustainability*.<img width="2234" height="1268" alt="Page 4(i)" src="https://github.com/user-attachments/assets/d6b9cacb-2ae5-4c51-bc2b-b1afdcb65318" />
<img width="2008" height="1160" alt="Population Cont&#39;d" src="https://github.com/user-attachments/assets/528f6a37-687f-4e01-8fb0-93a07b7c70db" />



## Conclusion

This analysis highlights the pivotal role immigration now plays in shaping Canada’s demographic and economic future. While the country has steadily grown to nearly 40 million residents, the internal natural growth rate has slowed, fertility continues to decline, and the population is aging. In this context, immigration has shifted from a supplementary driver of population growth to an essential pillar of national sustainability.

The data clearly demonstrates that newcomers are not only filling population gaps but also revitalizing the labor force, contributing to cultural diversity, strengthening innovation capacity, and supporting the long-term balance of Canada’s demographic structure. Without immigration, Canada would face shrinking workforce participation, reduced economic expansion, and long-term population stagnation.

Overall, this project reinforces a key reality that Canada’s future, economically, socially, and demographically, is deeply intertwined with its ability to attract, retain, and integrate immigrants.

### PowerBI Dashboard - https://app.powerbi.com/groups/me/reports/5564cc39-d744-4260-be84-f051197982da/730543c24d5018dc922d?experience=power-bi







