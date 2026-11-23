# Paid Media Performance Dashboard | Power BI + SQL

> **Note:** This project uses a synthetic dataset and was developed to practise SQL, data modelling, DAX and dashboard design. The findings are descriptive and should not be interpreted as real-world business conclusions.

**Data source:** [Global Ads Performance Dataset – Kaggle](https://www.kaggle.com/datasets/nudratabbas/global-ads-performance-google-meta-tiktok)

## Project Overview

This project presents an interactive Power BI dashboard analysing paid advertising performance across Google Ads, Meta Ads and TikTok Ads.

The dashboard shows advertising spend, revenue and key performance metrics, including ROAS, CTR, CPC, CVR and CPA. Users can explore performance across advertising platforms, campaign types, industries, countries and months to identify trends and potential opportunities for further investigation.

## Skills Demonstrated

- **SQL (Google BigQuery):** Data preparation and transformation using SQL, including `CASE WHEN` statements.
- **Data Modelling:** Star schema with a fact table containing advertising performance data and a date dimension table.
- **DAX:** Creation of measures for key performance indicators, such as `ROAS = DIVIDE(SUM(revenue), SUM(ad_spend))`.
- **Power BI:** Interactive dashboard development using KPI cards, slicers, charts and tables.
- **Business Analysis:** Interpretation of advertising performance metrics and identification of potential areas for optimisation.

## Tools

- Google BigQuery (SQL)
- Power BI Desktop (Power Query, DAX)

## Key Findings

### 1. Advertising Platform Performance

Tiktok Ads achieved the highest annual ROAS (760%), alongside the lowest average CPC. In contrast, Google Ads generated the highest total revenue but recorded the lowest ROAS (350%), despite spending more than twice TikTok’ advertising spend. This suggests that higher advertising budget doesn’t necessarily gaurantee greater advertising efficiency.

### 2. Market and Campaign Performance

India achieved the highest overall ROAS among countries, while Ecommerce marginally outperformed SaaS among industries. Search campaigns recorded the highest overall conversion rate.

At a more granular level, the TikTok Ads–Australia–Search combination achieved a particularly high ROAS of approximately 1,700%, making it a potential area for further investigation.

### 3. Monthly Performance Trends

March and October achieved the highest overall ROAS, both exceeding 500%, while May recorded the lowest ROAS at 420%.

Google Ads recorded its lowest monthly ROAS in May, alongside its second-highest CPA of the year. This suggests that Google's weaker performance may have contributed to the decline in overall ROAS during May, although further analysis would be needed to determine the extent of its impact.

## Potential Business Applications

When applied to real-world advertising data, this dashboard could support:

- **Budget optimisation:** Identifying platforms and campaigns with relatively high or low returns.
- **Performance monitoring:** Tracking changes in advertising efficiency over time.
- **Market analysis:** Comparing campaign performance across countries and industries.

## Next Steps

- Apply more advanced SQL techniques to data preparation and analysis.
- Develop more sophisticated Power BI visualisations and interactive features.
- Extend the analysis using real-world and complex data to generate more actionable business insights.
