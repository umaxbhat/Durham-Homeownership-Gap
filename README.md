# Durham-Homeownership-Gap

This exploratory analysis uses 5-year American Community Survey data and 1-year American Community Survey data to confirm a statistic found in the most recent Durham County Community Health Assessment. The county-wide CHA is conducted every three years. The 2023 Durham County CHA noted that the gap in homeownership rates between Black and white participants had markedly increased since 2019. However, the CHA's sample size was small. This analysis aims to see whether the indicated trend is applicable on a broader scale. 

Data used in this analysis was pulled from the Census Bureau API via tidycensus. All data points come from the 5-year and 1-year American Community Surveys for the years in question. The specific tables that were referenced were `B25003A` (Tenure (White Alone Householder)) and `B25003B` (Tenure (Black or African American Alone Householder)).

Thanks to Warren Lowell at Duke University for suggesting a closer look at the 2023 Durham County CHA.
