# Ryota Shimizu

## Description

I would like to show how local medical resources in Japan are unbalanced and overly concentrated in specific regions. In Japan, thanks to the universal health insurance system, all people can access sufficient medical services regardless of their wealth or location. However, since a large portion of medical expenditures is publicly covered, medical resources—such as doctors, hospitals, and hospital beds—are not necessarily distributed efficiently. This can lead to unnecessary expansion of medical expenditures. In this project, using prefecture-level data in Japan, I aim to demonstrate that an excessive concentration of hospital resources in certain prefectures can lead to the provision of unnecessary medical services, thereby increasing medical expenditures, while contributing relatively little to improving people’s health status.

## Data Sources

1: Hospital report(Ministry of health, Labour and Welfare in Japan)
2: NDB open data(Ministry of health, Labour and Welfare in Japan)
3: About the 2022 Healthy Life Expectancy Data(Ministry of health, Labour and Welfare in Japan)
4: Population estimates


### Data Source 1: Hospital report(Ministry of health, Labour and Welfare in Japan)

URL: https://www.e-stat.go.jp/stat-search/files?page=1&toukei=00450023&tstat=000001030749

Size: 48 rows, 6 columns, 5-6 seats
From this dataset, we can extract the number of patients and hospital beds by type at the prefectural level.

### Data Source 2: NDB open data(Ministry of health, Labour and Welfare in Japan)

URL: https://www.mhlw.go.jp/stf/seisakunitsuite/bunya/0000177221_00016.html

Size: 632 rows, 53 columns

From this dataset, we can extract medical expenditures, the number of provided medical services by type, health status at the prefectural level.

### Data Source 3: About the 2022 Healthy Life Expectancy Data(Ministry of health, Labour and Welfare in Japan)

URL: https://www.mhlw.go.jp/content/10904750/001363069.pdf

Size: 47 rows, 5 columns

From this dataset, we can extract life expectancy and health life expectancy at the prefectural level.

### Data Source 4: Population estimates

URL: https://www.e-stat.go.jp/dbview?sid=0003448237

Size: 48 rows, 19 columns

From this dataset, we can extract population by age group at the prefectural level.

## Questions

{Numbered list of questions for course staff, if any.}

1. Most of my sources are from Japanese government websites and are written in Japanese. Would this cause any problems in the review or evaluation process?
2. Sometimes data without proper controls can be misleading (e.g., medical expenditure per capita in each prefecture might need to be adjusted for age structure). However, too much adjustment can make visualizations more complex. How carefully should we balance ensuring true causal relationships while avoiding misleading conclusions by introducing control variables or using other statistical methods?
3.