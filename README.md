# Dengue-Outbreak-Forcasting-and-Early-Warning-system
A software-only web system that forecasts weekly dengue hospital admissions for each region of Bangladesh, one to two weeks ahead, and shows a simple risk level (Low, Moderate, High) on a public dashboard.

Status: Capstone project (BSc Software Engineering), in development. Numbers on the dashboard mockup below are sample data, not real forecasts.

Dashboard mockup

Mockup of the planned dashboard. All values are made up for illustration.

Why this project

Dengue is a yearly emergency in Bangladesh. 2023 was the worst year on record, with 321,179 hospitalizations and 1,705 deaths. The years after stayed above 100,000 cases, and by 13 October 2026 the DGHS had already reported 103,396 hospitalizations and 316 deaths for 2026 (figures from DGHS reports as covered by Dhaka Tribune).

Today the response is mostly reactive. DGHS publishes how many patients were admitted yesterday, but nobody gives hospitals or city corporations a forecast for next week. Mosquito control and hospital preparation often start after cases have already risen.

This project tries to close that gap with a weekly, region-level forecast that non-experts can read.

What it does (and does not do)

It does:

Forecast weekly dengue admissions for each DGHS reporting region, 1 to 2 weeks ahead
Turn each forecast into a risk level: Low, Moderate or High
Show the main factors behind each forecast
Compare every model against simple baselines, so we can tell if the AI actually helps
Show everything on a dashboard with a map, trends, a region ranking and short advice

It does not:

Diagnose anyone. It never decides whether a person has dengue. It forecasts hospital admissions for a region.
Use patient-level data. Only public aggregate counts and weather data are used.
Replace DGHS, IEDCR or official warnings. Forecasts are estimates.

