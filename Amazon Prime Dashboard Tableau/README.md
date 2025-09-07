# Amazon Prime Video Dashboard (Tableau)

![Dashboard Preview](assets/dashboard.png)

## Overview
This Tableau project analyses the Amazon Prime Video catalogue of movies and TV shows.  
The dashboard provides insights into content distribution by country, genre, type, release year, and audience ratings.

## Key Features
- **Total Shows by Country**: World map of catalogue distribution.  
- **Top Ratings**: Viewer ratings breakdown.  
- **Top 10 Genres**: Most common content categories.  
- **Shows by Type**: TV shows vs Movies.  
- **Trend Over Time**: Catalogue growth by release year.  
- **Interactive Filters**: Type, Genre, Year, Duration.

## Data
- **Source**: `amazon_prime_titles.csv` (public dataset of Amazon Prime titles).  
- Columns include: `title`, `type`, `genre`, `cast`, `country`, `release_year`, `duration`, `rating`, and `description`.  

## Files
- `tableau/amazon_prime_dashboard.twbx` – Tableau packaged workbook  
- `data/amazon_prime_titles.csv` – dataset  
- `assets/dashboard.png` – screenshot preview  

## How to Use
1. Open `tableau/amazon_prime_dashboard.twbx` in Tableau Desktop or Tableau Public.  
2. Explore filters for **type, genre, release year, and duration**.  
3. Interact with the visualisations to discover catalogue patterns.

## Insights
- Drama is the most common genre, followed by Comedy and Drama Suspense.  
- Most titles are **movies (80.8%)** compared to **TV shows (19.2%)**.  
- The catalogue has grown significantly after 2010, especially for movies.  
- The majority of content is rated **13+ or 16+**, highlighting family-friendly and teen-focused programming.  
- The USA and India dominate in number of titles.

## Tools
- Tableau Public  
- Data source: CSV file  

## License
This project is for educational and portfolio purposes only. Data is provided as-is from the public dataset.
