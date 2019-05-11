# india-pc-nfhs4
Parliamentary constituency factsheet for indicators of nutrition, health, and development in India using NFHS4 data.

Source: https://www.hsph.harvard.edu/population-development/indiapcfactsheets/

## List of tables - sample
![sample table of contents for indicators list](pc-nfhs-indicators.png)

## Table content - sample
![Nutritional Profile across 543 Parliamentary Constituencies](table1.png)

PDF: https://cdn1.sph.harvard.edu/wp-content/uploads/sites/1266/1266/20/PC-Factsheet-Nutrition-Health-and-Developmet-Indicators_HCPDS-working-paper_Volume-18_no_4.pdf

# Content extraction

I used [tabula](https://tabula.technology/) to extract data from PDF tables.

## Data cleaning

While Tabula can get so close to clean data it is not perfect (that's ok). I spent some effort for each table where tabula couldn't determine the table cells properly.

Please [report](https://github.com/bkamapantula/india-pc-nfhs4/issues/new) if you notice an error.

If you already know a machine-friendly format for this file, please let me know ([add an issue](https://github.com/bkamapantula/india-pc-nfhs4/issues/new)).
