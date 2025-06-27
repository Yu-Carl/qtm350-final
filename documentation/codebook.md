# Codebook

## 1_Adolescent fertility rate (births per 1,000 women ages 15–19).csv

| Variable Name    | Description                                              | Type    |
|------------------|----------------------------------------------------------|---------|
| `Country Name`   | Name of the country                                      | text    |
| `Country Code`   | Code representing the country                            | text    |
| `Indicator Name` | Name of the WDI Indicator                                | text    |
| `Indicator Code` | Abbreviated code of indicator                            | text    |
| `1960`           | Fertility rate in 1960                                   | numeric |
| ...              | One column per year from 1961-2022                       | numeric |
| `2023`           | Fertility rate in 2023                                   | numeric |


## 1_Population growth (annual %).csv

| Variable Name    | Description                                              | Type    |
|------------------|----------------------------------------------------------|---------|
| `Country Name`   | Name of the country                                      | text    |
| `Country Code`   | Code representing the country                            | text    |
| `Indicator Name` | Name of the WDI Indicator                                | text    |
| `Indicator Code` | Abbreviated code of indicator                            | text    |
| `1960`           | Fertility rate in 1960                                   | numeric |
| ...              | One column per year from 1961-2022                       | numeric |
| `2023`           | Fertility rate in 2023                                   | numeric |


## 2_Age dependency ratio (% of working-age population).csv

| Variable Name    | Description                                              | Type    |
|------------------|----------------------------------------------------------|---------|
| `Country Name`   | Name of the country                                      | text    |
| `Country Code`   | Code representing the country                            | text    |
| `Indicator Name` | Name of the WDI Indicator                                | text    |
| `Indicator Code` | Abbreviated code of indicator                            | text    |
| `1960`           | Fertility rate in 1960                                   | numeric |
| ...              | One column per year from 1961-2022                       | numeric |
| `2023`           | Fertility rate in 2023                                   | numeric |


## 2_Life expectancy at birth, total (years).csv

| Variable Name    | Description                                              | Type    |
|------------------|----------------------------------------------------------|---------|
| `Country Name`   | Name of the country                                      | text    |
| `Country Code`   | Code representing the country                            | text    |
| `Indicator Name` | Name of the WDI Indicator                                | text    |
| `Indicator Code` | Abbreviated code of indicator                            | text    |
| `1960`           | Fertility rate in 1960                                   | numeric |
| ...              | One column per year from 1961-2022                       | numeric |
| `2023`           | Fertility rate in 2023                                   | numeric |


## 3_Births attended by skilled health staff (% of total)

| Variable Name    | Description                                              | Type    |
|------------------|----------------------------------------------------------|---------|
| `Country Name`   | Name of the country                                      | text    |
| `Country Code`   | Code representing the country                            | text    |
| `Indicator Name` | Name of the WDI Indicator                                | text    |
| `Indicator Code` | Abbreviated code of indicator                            | text    |
| `1960`           | Fertility rate in 1960                                   | numeric |
| ...              | One column per year from 1961-2022                       | numeric |
| `2023`           | Fertility rate in 2023                                   | numeric |


## 3_Mortality rate, infant (per 1,000 live births)

| Variable Name    | Description                                              | Type    |
|------------------|----------------------------------------------------------|---------|
| `Country Name`   | Name of the country                                      | text    |
| `Country Code`   | Code representing the country                            | text    |
| `Indicator Name` | Name of the WDI Indicator                                | text    |
| `Indicator Code` | Abbreviated code of indicator                            | text    |
| `1960`           | Fertility rate in 1960                                   | numeric |
| ...              | One column per year from 1961-2022                       | numeric |
| `2023`           | Fertility rate in 2023                                   | numeric |


# metadata.csv

| Variable Name    | Description                                              | Type    |
|------------------|----------------------------------------------------------|---------|
| `Country Code`   | Code representing the country                            | text    |
| `Region`         | Region of the country                                    | text    |
| `IncomeGroup`    | Income group of the country                              | text    |
| `SpecialNotes`   | Information on the country and select WDI indicators     | text    |
| `TableName`      | Name of the country                                      | text    |


## fertility_vs_population_change

| Variable Name             | Description                                                                | Type    | 
|---------------------------|----------------------------------------------------------------------------|---------|
| `Country Name`            | Name of the country                                                        | text    |
| `code`                    | Code representing the country                                              | text    | 
| `region`                  | World Bank region classification                                           | text    | 
| `income`                  | Country income classification                                              | text    | 
| `fertility_rate_change`   | Change in birth rate (births per 1000 women, ages 15-19) from 1961-2023    | numeric |
| `population_growth_change`| Change in population growth rate (annual %) from 1960-2023                 | numeric |


## life_vs_dependency_change

| Variable Name             | Description                                                                | Type    | 
|---------------------------|----------------------------------------------------------------------------|---------|
| `Country Name`            | Name of the country                                                        | text    |
| `code`                    | Code representing the country                                              | text    | 
| `region`                  | World Bank region classification                                           | text    | 
| `income`                  | Country income classification                                              | text    | 
| `life_expectancy_change`  | Change in life expectancy at birth (in years) from 1960-2023               | numeric |
| `age_dependency_change`   | Change in age dependency ratio (% working-age population) from 1960-2023   | numeric |


## health_change_summary

| Variable Name             | Description                                                                | Type    | 
|---------------------------|----------------------------------------------------------------------------|---------|
| `Country Name`            | Name of the country                                                        | text    |
| `code`                    | Code representing the country                                              | text    | 
| `region`                  | World Bank region classification                                           | text    | 
| `income`                  | Country income classification                                              | text    | 
| `infant_mortality_change` | Change in infant mortality rate (per 1000 live births) from 2000-2019      | numeric |
| `skilled_births_change`   | Change in births attended by skilled health staff (% total) from 2000-2019 | numeric |