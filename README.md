
# Data Description

The [`cc-rmcc.xlsx`](cc-rmcc.xlsx) and [`screening.xlsx`](screening.xlsx) files contain 4 tabs with the raw Komodo Healthcare Map count data displayed in different ways--by ZIP-3 only, by ZIP-3 and age, by ZIP-3 and insurance, and by ZIP-3, age, and insurance. In each tab, there are columns for r/mCC, CC, and eligible enrollee patient counts. Censored patient counts are shown as "<=3".

The [`zip3-state-region.xlsx`](zip3-state-region.xlsx) file contains the mapping from ZIP-3 to state to region. The [`brachy.xlsx`](brachy.xlsx) file contains a list of ZIP-5s with at least 1 American Brachytherapy Society (ABS) member, retrieved from https://www.americanbrachytherapy.org/about-abs/member-list/. The [`census.xlsx`](census.xlsx) file contains ZIP-3 data collected from the US Census Bureau's 2018-2022 5-year American Community Survey (ACS), originally ZIP-5 data that was aggregated to the ZIP-3 level, to complete the univariate association analyses. The variable `frac_pov` represents the proportion of families in a ZIP-3 with an income less than 200% of the federal poverty limit (FPL), retrieved from the table labeled "Ratio of Income to Poverty Level of Families in the Past 12 Months". The  variables `frac_asian`, `frac_black`, `frac_hispanic`, `frac_nonhispanicother`, and `frac_white` represent the proportions of people in a ZIP-3 that are belong to each race/ethnicity group, retrieved from the table labeled "Hispanic or Latino Origin by Race".



