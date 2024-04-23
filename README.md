# Durham-Homeownership-Gap

This exploratory analysis uses 5-year American Community Survey to confirm a statistic found in the most recent Durham County Community Health Assessment. The county-wide CHA is conducted every three years. The 2023 Durham County CHA noted that the gap in homeownership rates between Black and white participants had markedly increased since 2019. However, the CHA's sample size was small. This analysis aims to see whether the indicated trend is applicable on a broader scale. 

Data used in this analysis was pulled from the Census Bureau API via tidycensus. All data points come from the 5-year American Community Survey for the year in question. The specific tables that were referenced were `B25003A` (Tenure (White Alone Householder)) and `B25003B` (Tenure (Black or African American Alone Householder)).

Results indicate that the trend identified in the most recent CHA report is not applicable on a broader scale. Between 2019 and 2022, the Black-white homeownership rate gap remained relatively stable.

Thanks to Warren Lowell at Duke for suggesting a closer look at the 2023 Durham County CHA.
