# AirBnB Price & Revenue Insights

This repository contains a Tableau dashboard project analyzing Airbnb housing market data.  
The goal is to understand how bedroom count, location (zipcode), and time influence average prices and revenue trends.

---

## Key Visualizations

- **Average Price Per Bedroom**
  - 1 BR → $96.2  
  - 2 BR → $175.4  
  - 3 BR → $249.7  
  - 4 BR → $315.4  
  - 5 BR → $450.0  
  - 6 BR → $584.8  

- **Listings Distribution by Bedroom Count**
  - 1 BR → 1,811 listings  
  - 2 BR → 483 listings  
  - 3 BR → 206 listings  
  - 4 BR → 55 listings  
  - 5 BR → 20 listings  
  - 6 BR → 5 listings  

- **Price by Zipcode**
  - Comparison of average prices across Seattle zipcodes (98101–98136).  
  - Highlights localized demand and pricing variation.

- **Revenue Trend (2016)**
  - Weekly revenue growth from near 0K to ~2000K by year-end.  
  - Shows strong upward momentum in the housing market.

---

## Dataset

The raw dataset is stored in the `/data` folder:

- [`/listings.csv.zip`](/listings.csv.zip) → Property details (bedrooms, bathrooms, price, etc.)  
- [`/reviews.csv.zip`](/reviews.csv.zip) → Guest reviews and feedback  
- [`/calendar.csv.zip`](/calendar.csv.zip) → Availability and pricing over time  

Unzip these files before loading into Tableau or another analysis environment.

---

## Insights

- Larger bedroom counts significantly increase average price, but listings are concentrated in 1–2 BR properties.  
- Certain zipcodes consistently show higher average prices, indicating localized demand.  
- Revenue growth trend suggests strong market performance throughout the year.

---

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/anishpatil08/AirBnB-Price-Revenue-Insights.git
