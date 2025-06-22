# Netflix_dashboard
📌 Problem Statement
The entertainment industry is rapidly evolving with a massive influx of digital content. Studios, platforms, and audiences require accurate insights into what kinds of content perform best, what genres are most prevalent, and how production variables affect audience engagement. The challenge lies in consolidating this complex metadata—ranging from runtime, genre, certification, country of origin, and critical ratings—into a clean, reliable format that fuels dynamic insights.

This project tackles the need to extract, clean, model, and analyze entertainment content data—ultimately helping stakeholders make informed, data-driven decisions.

🧩 Project Overview: Applied BI for Streaming Content Analysis (Power BI Dashboard)
This Power BI project explores a dataset named “1910_m4_assign_dataset_v1.0”, focusing on titles, cast/crew roles, and extensive metadata about movies and web series. The objective was to design a visually engaging, interactive dashboard that brings clarity to content performance and genre trends, using Power BI’s data modeling and visualization tools.

✅ Key Steps Performed:
Data Connection & Cleaning:

Imported Excel data into Power BI.

Cleaned null entries, standardized fields, corrected data types, and removed inconsistencies via Power Query Editor.

Data Modeling:

Established relationships between Credits and Title tables using Team ID (Id).

Ensured a one-to-many relationship for effective filtering and lookup.

Measure Creation (DAX):

Total Content and Runtime Hours metrics created using DAX for dynamic aggregation.

Visualizations:

Bar Chart: Top 5 genres by content count, segmented by type (Movie/Web Series).

Line Chart: Count of content released per year, categorized by type.

Map Visualization: Runtime and production country plotted geographically.

Donut Chart: Distribution of content type (Movie vs. TV show).

Cards: KPIs for total runtime, total count of titles, and IMDb average rating.

Slicers: Filters for genre, release year, and title to enable flexible exploration.

Branding: Netflix logo with a concise text introduction using hex color scheme (#D40400 for red, #FFFFFF for white, #000000 for black).
