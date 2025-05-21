
# Art Gallery Data Analysis Project – SQL

## Project Overview

This project focuses on simulating and analyzing data from a fictional global art gallery network using SQL. The aim is to answer complex business questions by exploring patterns in artwork distribution, artist contributions, gallery operations, and pricing strategies. Through a collection of structured SQL queries, the project provides meaningful insights that can support decision-making for curators, art investors, and cultural institutions.

## Objectives

- Identify the most influential artists and popular art styles  
- Analyze gallery operational efficiency and accessibility  
- Detect pricing anomalies and trends in canvas sizes  
- Evaluate geographic spread and data quality of gallery information  
- Clean and prepare data to improve accuracy and usability

##  Tools & Technologies

- **Database**: MySQL  
- **Language**: SQL  
- **Tables Used**:  
  - `artist`  
  - `work`  
  - `museum`  
  - `museum_hours`  
  - `product_size`  
  - `canvas_size`  
  - `subject`

## Key Insights & Query Highlights

- Artists with works displayed across multiple countries  
- Top 10 most popular themes and styles  
- Artworks sold significantly below or above listed prices  
- Galleries open every day vs. those open on weekends only  
- Least and most utilized canvas sizes  
- Most prolific artists by number of works  
- Galleries without any artworks on display  
- Countries and cities with the highest concentration of galleries  
- Highest and lowest priced artworks and their corresponding artists and galleries  
- Most popular Portrait artists outside the USA

## Data Cleaning Performed

- Identified and removed duplicate entries in multiple tables (`work`, `product_dimensions`, `theme`, `image`)  
- Corrected misspelled weekday values (e.g., “Thusday” to “Thursday”)  
- Validated city entries and flagged inaccurate information  
- Ensured data consistency across related tables

## Sample Business Questions Answered

- How many galleries are open every day of the week?  
- Which artist has the most portrait artworks outside the USA?  
- What are the most and least common artwork styles?  
- Which gallery has the highest number of artworks in the most popular style?  
- Which country has the fifth-highest number of artworks?

## Project Deliverables

- 22 well-documented SQL queries answering real-world operational and artistic questions  
- Cleaned and validated datasets for reliable analysis  
- Insightful reports ready for dashboard integration or stakeholder presentations

## Folder Structure

```
├── art_gallery_analysis.sql         # Main SQL script containing all queries
├── sample_datasets/                # (Optional) Folder for mock data if shared
├── README.md                       # Project description and documentation
```
