# Airbnb-Dashboard
A Power BI dashboard analysing Airbnb activity across 10 cities, using the Maven Analytics dataset (about 280K listings, 182K hosts, 5.4M reviews). It covers listing growth, city market share, ratings, review behaviour and host trust.

Page 1: Overview and New Listings
<img width="1327" height="747" alt="Page 1" src="https://github.com/user-attachments/assets/aa7dd9e1-dfa2-42c8-91a8-df0885263ee1" />

At-a-glance page with KPI cards for listings, cities, hosts, property types and reviews. The main chart plots new listings by year and room type over a shaded total-listings area, with the timeline divided into life-cycle phases and Annotated key points.




Page 2: Market Share and Ratings
<img width="1326" height="742" alt="Page 2" src="https://github.com/user-attachments/assets/19ad23f5-36f8-4fb5-898c-1b853b182981" />

Compares cities by number of listings, split by superhost status, with a cumulative percentage line for market share. A bar chart shows average price by room type, and a rating matrix breaks scores down by city and category. Bookmarks on the icon buttons switch the matrix between overall and detailed views.


Page 3: Review Frequency, Seasonality and Trust
<img width="1327" height="741" alt="Page 3" src="https://github.com/user-attachments/assets/c4404cb5-479e-4278-9e81-1fef47d4afa5" />

The Line and Stacked Column chart shows how many reviewers wrote a given number of reviews, using a calculated column and cumulative DAX measures. A ribbon chart shows each city's share of monthly reviews, and a custom shield visual shows host verification and profile picture status.


Conclusion:

This project turns a large, multi-table Airbnb dataset into a clear three-page story, moving from platform growth to city-level performance and then to guest and host behaviour. It shows how listing volume, pricing, ratings, review patterns and verification can be viewed together to understand how the marketplace works. The report is built to be explored, with bookmarks, cumulative measures and annotated visuals that let a viewer move from the big picture to the detail.

Data source: Maven Analytics

