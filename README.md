# Household Power Consumption — Time-Series Data Cleaning & Analysis

> **2M+ records. Missing data identified and handled. Cleaned time-series prepared for reliable analysis.**

---

## The Problem

Time-series datasets often look usable until missing values, fragmented timestamps, and inconsistent records start distorting the analysis.

This project focuses on cleaning and validating a large household electricity consumption dataset before analysis, with the goal of producing trustworthy hourly, daily, and yearly usage patterns.

---

## What Was Done

- combined separate **Date** and **Time** fields into a proper datetime column
- identified incomplete measurement rows
- removed unusable records from the analysis dataset
- prepared a clean time-series foundation for downstream analysis
- analyzed hourly, weekly, and yearly consumption patterns

---

## Key Findings

| Finding | Result | Why It Matters |
|---|---:|---|
| Dataset size | **2M+ records** | Large enough to require structured cleaning before analysis |
| Incomplete rows removed | **~1.25%** | Prevents distorted time-series metrics |
| Peak consumption window | **20:00–21:00** | Clear evening demand concentration |
| Lowest usage window | **03:00–05:00** | Stable overnight low-demand period |
| Weekend vs weekday | **Weekend usage higher** | Behavioral pattern visible after cleaning |

---

## Why This Project Matters

This was not just chart-making.

The value of the project was making the dataset reliable enough for analysis in the first place.  
Without cleaning incomplete rows and standardizing the time axis, the output would look polished but rest on weak foundations.

That is the core of data quality work:
**clean first, trust later.**

---

## Tech Stack

- **Python**
- **pandas**
- **matplotlib**
- **Jupyter Notebook**

---

## Repository Contents

- analysis notebook
- cleaning steps
- exploratory time-series analysis
- visual summaries of usage patterns

---

## Related Project

My main large-scale data quality project:  
**NYC Yellow Taxi — Data Quality Audit at Scale**  
https://github.com/darkdatastream/nyc-yellow-taxi-cleanup

---

## Work With Me

📧 **data.audit.contact@proton.me**

I help clean, validate, and audit messy datasets before they reach dashboards, reports, or decision-making.

---

## Notes

Dataset not included due to size.

---

## License

MIT
