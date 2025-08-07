# Travel Industry Conversion Funnel Analysis (SQL Case Study)

## Overview  
This SQL project simulates user behavior in the travel booking industry, focusing on user acquisition, engagement, and conversion performance. The aim was to calculate the conversion rate of new users who installed the app, signed up, and placed a flight booking order within 7 days of signup.

## Project Goals
- Identify new users who signed up post-installation
- Track user visits and behaviors across multiple touchpoints
- Measure the 7-day conversion window from signup to flight booking
- Optimize SQL queries to enable business decision-making

## Tools Used
- SQL (SQLite syntax): data transformation and analysis  
- Excel:  initial data review, structure validation  
- Relational database design: normalized schema for install orders, signups, and visits

## Key Tables
- `install_orders`: App install and booking information
- `signups`: User signup timestamps
- `visits`: User sessions segmented by product type

## What I Did
- Wrote multiple **CTEs (Common Table Expressions)** to simulate app install behavior, align signup dates, and identify post-install users.
- Filtered and aggregated flight booking orders within a **7-day window** from user signup.
- Built logic to **exclude duplicate device IDs**, ensuring clean cohort analysis.
- Delivered a final summary table with:
  - Total new users
  - Converting users (within 7 days)
  - Overall conversion rate (%)

## Key Results
- Extracted actionable funnel metrics to assess acquisition and booking efficiency.
- Demonstrated ability to structure SQL queries to model real world digital user journeys.
- Delivered insights that can inform **user retention**, **activation strategies**, and **campaign ROI** tracking.
