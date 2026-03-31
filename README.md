# E-commerce Funnel Analysis & Conversion Dashboard

## Project Overview

This project analyzes user behavior across an e-commerce platform by building a funnel analysis dashboard in Power BI. It identifies drop-off points, evaluates conversion rates, and provides insights to improve the user journey and overall business performance.

## Objectives

* Analyze the user journey from home to purchase (home → product → cart → checkout → confirmation)
* Identify major drop-off stages in the funnel
* Measure overall conversion rate
* Compare performance across different segments:

  * Device types
  * Countries
  * Traffic sources
* Generate actionable insights for improving conversions

## Dataset

The dataset simulates user interactions on an e-commerce platform and includes the following fields:

* `UserID` – Unique user identifier
* `SessionID` – Session tracking
* `Timestamp` – Activity timestamp
* `PageType` – Funnel stage (home, product_page, cart, checkout, confirmation)
* `DeviceType` – Desktop, Mobile, Tablet
* `Country` – User location
* `ReferralSource` – Traffic source (Google, Email, Social Media, Direct)
* `TimeOnPage_seconds` – Time spent on each page
* `ItemsInCart` – Number of items added to cart
* `Purchased` – Purchase flag (1 = completed purchase, 0 = not completed)

## Tools & Technologies

* Power BI (Dashboard development and visualization)
* DAX (Measures and calculations)
* Data modeling (relationships and transformations)

## Key Metrics

* Total Users (Distinct count of users)
* Total Purchases (Users who completed purchase)
* Conversion Rate (Purchases / Total Users)

## Dashboard Features

* Funnel visualization of user journey stages
* KPI cards for key metrics (Users, Purchases, Conversion Rate)
* Interactive slicers for:

  * Device Type
  * Country
  * Referral Source
* Trend analysis using line chart (users over time)
* Segment-based analysis using filters

## Key Insights

* Approximately 42% of users complete the purchase in overall data
* The largest drop occurs at the cart stage, indicating possible friction
* Product page engagement is strong compared to later stages
* Conversion rates vary significantly across different segments

## Business Recommendations

* Improve cart experience to reduce drop-offs
* Optimize checkout flow to minimize friction
* Analyze low-performing traffic sources for quality improvement
* Personalize experience based on device and region

## How to Use

1. Open the Power BI dashboard file (.pbix)
2. Use slicers to filter by device, country, and traffic source
3. Analyze funnel behavior and conversion metrics
4. Review trends and insights for decision-making

## Future Improvements

* Add drop-off percentage per stage
* Include cohort analysis for retention tracking
* Build predictive models for conversion probability


