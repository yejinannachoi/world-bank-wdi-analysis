# Codebook

## Dataset Overview
- **Dataset name**: `asian_countries.csv`
- **Total rows**: 3315
- **Total columns**: 6
- **Data source**: World Bank Open Data via [wbdata](https://pypi.org/project/wbdata/)
- **Indicators used**:
  - GDP per capita (constant 2015 US$) – `NY.GDP.PCAP.KD`
  - Employment to population ratio, 15+, total (%) – `SL.EMP.TOTL.SP.ZS`
  - GDP growth (annual %) – `NY.GDP.MKTP.KD.ZG`
  - Population growth (annual %) – `SP.POP.GROW`
- **How it was created**: This dataset was created by merging four World Bank indicator datasets using `country` and `date` as keys, and filtered using SQL to include only Asian and Middle Eastern countries for analysis.

## Variable Descriptions
| Variable | Description | Type | Non-Null Values | Unique Values | Sample Value |
|----------|-------------|------|------------------|----------------|---------------|
| `country` | Country or region name | object | 3315 | 51 | Afghanistan |
| `year` | Calendar year | int64 | 3315 | 65 | 2024 |
| `gdp_per_capita` | GDP per capita (constant 2015 US$) | float64 | 2627 | 2627 | 1159.668902 |
| `employment_population_ratio` | Employment to population ratio (15+, %) | float64 | 1731 | 1689 | 32.511 |
| `gdp_growth` | Annual GDP growth (%) | float64 | 2572 | 2570 | 6.599343 |
| `population_growth` | Annual population growth (%) | float64 | 3183 | 3183 | 2.744 |