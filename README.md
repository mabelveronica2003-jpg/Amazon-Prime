# Amazon-Prime
## Objective

The main objective of this Power BI dashboard is to analyze and visualize Amazon Prime’s content library to uncover insights about:

Content distribution across movies and TV shows

Popular genres, ratings, and categories

Availability of content across countries and regions

Trends over time in released content

This helps users, researchers, or business analysts understand viewer preferences, regional strategies, and overall growth trends of Amazon Prime content.

## Questions

- The dashboard aims to answer questions such as:

- How many movies vs TV shows are available on Amazon Prime?

- Which genres/categories are most popular?

- What is the distribution of content ratings (e.g., PG, R, etc.)?

- How has the content release trend changed over the years?

- Which countries produce the most content on Amazon Prime?

- Are there patterns in TV shows vs movies by region or genre?

- What percentage of titles belong to top contributing countries?

## Process

### Data Collection

Dataset of Amazon Prime titles containing fields like Title, Type, Genre, Release Year, Rating, Country, etc.

## Data Cleaning & Preparation

Removed missing/null values in critical columns (e.g., Genre, Rating, Release Year).

Standardized categorical values (e.g., unified ratings like "TV-MA" vs "TV MA").

Converted release years into a proper date hierarchy for trend analysis.

### Data Modeling

Loaded dataset into Power BI.

Built relationships (if multiple tables).

Created calculated columns and DAX measures (e.g., Count of Titles, % Contribution by Country).

### Visualization

Pie/Donut Charts → Movies vs TV Shows, Ratings distribution.

Bar/Column Charts → Top genres, content by country.

Line Chart → Year-wise content release trends.

Maps → Content availability across countries.

Cards/KPIs → Total titles, unique genres, earliest/latest release.

### Dashboard Design

Used interactive filters (slicers) for Type, Genre, Country, Rating.

Ensured intuitive, user-friendly navigation with visuals

## Dashboard
<img width="1180" height="661" alt="Screenshot 2025-09-22 014022" src="https://github.com/user-attachments/assets/bb30172a-9580-4de9-8ac8-9cc0067573c7" />
