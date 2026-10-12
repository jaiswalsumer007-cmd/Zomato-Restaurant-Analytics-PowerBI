# Zomato Restaurant Analytics Dashboard \| Power BI

An interactive, multi-page Power BI project exploring restaurant
distribution, ratings, cuisine trends, pricing, and customer engagement
using a Zomato-style restaurant dataset.

> **Project purpose:** Educational and portfolio use. The findings
> describe the dataset used in this project and should not be treated as
> verified representations of the current real-world restaurant market.

## Dashboard Preview

Add your dashboard screenshots to a folder named `screenshots/` in this
repository, then uncomment and update the image links below.

```{=html}
<!--
### 1. Overview
![Overview dashboard](screenshots/overview.png)

### 2. Geographic Analysis
![Geographic analysis dashboard](screenshots/geographic-analysis.png)

### 3. Cuisine & Pricing Analysis
![Cuisine and pricing dashboard](screenshots/cuisine-pricing.png)

### 4. Rating & Customer Engagement
![Rating and engagement dashboard](screenshots/ratings-engagement.png)

### 5. Restaurant Explorer
![Restaurant Explorer dashboard](screenshots/restaurant-explorer.png)
-->
```
## Project Objectives

-   Summarize restaurant coverage and rating performance.
-   Explore geographic patterns across countries and cities.
-   Compare cuisine representation and restaurant price ranges.
-   Investigate relationships between ratings and customer engagement.
-   Provide an interactive explorer for reviewing individual restaurant
    records.

## Key Insights

The following figures are based on the dashboard and dataset used in
this project.

  -----------------------------------------------------------------------
  Area                                Finding
  ----------------------------------- -----------------------------------
  Dataset coverage                    9,551 restaurant records

  Rated restaurants                   7,403 records

  Average rating                      3.44 out of 5

  Highly rated restaurants            1,380 records with ratings of 4.0
                                      or higher

  Geographic coverage                 15 countries and 141 cities

  City concentration                  New Delhi is shown with 5,473
                                      restaurant records

  Cuisine representation              North Indian and Chinese cuisine
                                      records are prominent, with 3,960
                                      and 2,733 mentions/records
                                      respectively

  Price range                         Price Range 1 represents 46.53% of
                                      records; Price Range 2 represents
                                      32.59%

  Customer engagement                 Approximately 1.50 million votes in
                                      total
  -----------------------------------------------------------------------

**Interpretation notes** - Cuisine counts may represent cuisine records
or mentions, not unique restaurants, because a restaurant can list
multiple cuisines. - Geographic and other counts reflect the dataset's
records and definitions; they do not necessarily represent the entire
real-world market. - The Key Influencers visual explores associations
with high ratings. Associations should not be interpreted as proof of
causation.

## Dashboard Pages

### 1. Overview

A high-level summary of restaurant coverage, rated restaurants, average
ratings, votes, online delivery, highly rated restaurants, cuisine
representation, price ranges, and rating distribution.

### 2. Geographic Analysis

A map-based view of restaurant distribution, city concentration, and
average ratings by country.

### 3. Cuisine & Pricing Analysis

A look at popular cuisine records, the distribution of restaurant price
ranges, and the relationship between average ratings and customer
engagement.

### 4. Rating & Customer Engagement

Uses Power BI's **Key Influencers** visual to investigate factors
associated with highly rated restaurants and a **Decomposition Tree** to
explore vote totals across dimensions such as country, city, price
range, and online delivery.

### 5. Restaurant Explorer

An interactive table with filters for exploring restaurant records,
including restaurant name, city, cuisines, aggregate rating, votes,
price range, and related details.

## Tools & Techniques

-   **Power BI Desktop** --- report design and interactive
    visualizations
-   **Power Query** --- data cleaning and transformation
-   **DAX** --- measures and analytical calculations
-   **Data visualization** --- KPI cards, bar charts, treemap, donut
    chart, map, scatter plot, Key Influencers, and Decomposition Tree
-   **Interactive reporting** --- slicers, page navigation, and
    restaurant-level exploration

## Repository Structure

``` text
Zomato-Restaurant-Analytics-PowerBI/
├── Zomato_Restaurant_Analytics.pbix
├── README.md
└── screenshots/
    ├── overview.png
    ├── geographic-analysis.png
    ├── cuisine-pricing.png
    ├── ratings-engagement.png
    └── restaurant-explorer.png
```

Use your actual `.pbix` filename if it differs from the example above.

## How to Explore the Project

1.  Download the `.pbix` report from this repository.
2.  Open it with **Microsoft Power BI Desktop**.
3.  Use the page navigation and slicers to explore different views.
4.  Select or filter the data to investigate restaurant records and
    patterns.

## Data Disclaimer

This project is intended for educational and portfolio purposes. The
analysis is based entirely on the dataset used for this project, and the
figures and insights should not be interpreted as verified
representations of the current real-world restaurant market. Please
verify the dataset's provenance, licensing, and sharing permissions
before redistributing the source data.

## Feedback

Feedback and suggestions are welcome. I am continuing to build my skills
in data analytics, data visualization, Power Query, and DAX through
practical projects.
