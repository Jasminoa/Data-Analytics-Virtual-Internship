# Data Dictionary

## Project: Skill2Scale Data Analytics Virtual Internship

This document describes the structure, meaning, and usage of all datasets used throughout the internship project.

---

# 1. Campaign_Data_Q3.csv

| Column Name | Data Type | Description                                | Example      |
| ----------- | --------- | ------------------------------------------ | ------------ |
| Date        | Date      | Date campaign activity was recorded        | 2025-07-15   |
| Campaign    | Text      | Name of the marketing campaign             | Summer Promo |
| Channel     | Text      | Marketing platform used for the campaign   | Meta Ads     |
| Spend USD   | Float     | Amount spent on the campaign in USD        | 1500.00      |
| Revenue USD | Float     | Revenue generated from the campaign in USD | 5100.00      |
| ROI Percent | Float     | Return on investment percentage            | 340          |
| Clicks      | Integer   | Total number of ad clicks                  | 5400         |
| Conversions | Integer   | Number of successful conversions           | 320          |

---

# 2. Leads_Report.xlsx

| Column Name              | Data Type | Description                                | Example                                       |
| ------------------------ | --------- | ------------------------------------------ | --------------------------------------------- |
| Contact Name             | Text      | Name of the lead/contact                   | John Doe                                      |
| Email                    | Text      | Email address of the lead                  | [johndoe@email.com](mailto:johndoe@email.com) |
| Lead Source              | Text      | Channel/source where the lead originated   | Google Ads                                    |
| Funnel Stage             | Text      | Current stage in the sales funnel          | Qualified                                     |
| Conversion Status        | Text      | Indicates whether the lead converted       | Converted                                     |
| Estimated Deal Value USD | Float     | Estimated revenue value of the lead in USD | 2500.00                                       |

---

# 3. Ad_Spend_July-Sept.csv

| Column Name     | Data Type | Description                        | Example    |
| --------------- | --------- | ---------------------------------- | ---------- |
| Date            | Date      | Date spend activity was recorded   | 2025-07-01 |
| Month           | Text      | Month of spend activity            | July       |
| Channel         | Text      | Advertising platform/channel       | TikTok Ads |
| Daily Spend USD | Float     | Daily advertising spend in USD     | 200.00     |
| Impressions     | Integer   | Number of times ads were displayed | 15000      |

---

# Notes

* All monetary values are represented in USD.
* ROI Percent was calculated using campaign revenue and spend data.
* Datasets were cleaned and standardized before analysis.
* Missing values, duplicates, and inconsistent formatting were handled during preprocessing.
