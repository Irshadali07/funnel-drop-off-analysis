# Funnel Drop-off Analysis

## Project Overview

This project analyzes a user signup funnel using Microsoft Excel. The goal is to identify how many users reach each stage of the funnel, calculate conversion rates, identify the biggest drop-off point, and provide recommendations to improve the user journey.

## Dataset

The dataset contains event-level records with the following columns:

- User_ID
- Step
- Timestamp

Funnel Stages:

1. Visited Site
2. Signup Started
3. Details Filled
4. Email Verified
5. Purchase Completed

## Tools Used

- Microsoft Excel
- Pivot Tables
- Excel Formulas
- Funnel Chart
- Bar Chart
- Conditional Formatting


## Analysis Performed

- Counted unique users at each funnel stage
- Calculated stage-to-stage conversion rate
- Calculated drop-off percentage
- Identified the biggest drop-off stage
- Created Funnel Chart
- Created Bar Chart
- Added automated drop-off flagging
- Compared user segments
- Provided product recommendation

## Key Findings

| Stage | Users | Conversion |
|--------|------:|-----------:|
| Visited Site | 200 | 100% |
| Signup Started | 150 | 75% |
| Details Filled | 96 | 64% |
| Email Verified | 52 | 54% |
| Purchase Completed | 44 | 85% |

### Biggest Drop-off

**Details Filled → Email Verified**

Drop-off: **45.83% (≈46%)**

## Recommendation

The email verification step has the highest user drop-off. Simplifying email verification with one-click verification links and reminder emails can reduce friction and improve overall conversion.

## Repository Contents

- `funnel_events.xlsx` – Complete Excel analysis
- `funnel_events_sample.csv` – Sample dataset

## Author

**Md Irshad**

GitHub: https://github.com/Irshadali07
