# AIRBNB DATA ANALYSIS (2008–2021)

This project analyzes over 250,000 Airbnb listings and 5.4 million reviews from 10 major cities, spanning the years 2008 to 2021. The analysis explores pricing, host distribution, amenities, review trends, and city-level insights to uncover how location, room type, and guest preferences shape the Airbnb marketplace.

## Dataset Features

- **Listings:** 250,000+ entries with host info, pricing, location, room type, and amenities.
- **Reviews:** 5.4 million historical reviews analyzed for seasonality and sentiment.
- **Cities Analyzed:** New York, Hong Kong, Paris, Rome, Istanbul, Bangkok, Cape Town, Sydney, Rio de Janeiro, Mexico City.

## Preview
<img width="1856" height="669" alt="analysis" src="https://github.com/user-attachments/assets/13d90458-50fe-4799-aa01-a5d7721cd503" />


## Key Insights

### 1. City Differences

| City            | Avg Price (USD/night) | Median Price | Notes                         |
|-----------------|----------------------|--------------|-------------------------------|
| New York        | ~$55.95              | ~$41.25      | Most expensive overall         |
| Paris           | ~$53.41              | ~$38.54      | Premium market                 |
| Sydney          | ~$44.92              | ~$31.67      | Expensive, but below NYC/Paris |
| Rio de Janeiro  | ~$46.58              | ~$33.84      | Pricey for the local economy   |
| Hong Kong       | ~$39.27              | ~$24.49      | Wide price range               |
| Rome            | ~$38.41              | ~$32.81      | Balanced pricing               |
| Cape Town       | ~$31.46              | ~$21.14      | Competitive mid-range          |
| Istanbul        | ~$24.49              | ~$14.08      | Cheapest, highest review volume|
| Mexico City     | ~$22.80              | ~$14.08      | Budget-friendly                |
| Bangkok         | ~$22.57              | ~$13.55      | Lowest cost overall            |

- **Western cities** (NYC, Paris, Sydney) command premium prices.
- **Asian/Latin American cities** (Bangkok, Istanbul, Mexico City) offer lower prices.

### 2. Attributes That Influence Pricing

- **Room Type:**
  - Entire Place: ~$42–$45/night (highest)
  - Hotel Room: ~$31–$33/night (mid-range)
  - Private Room: ~$38–$40/night
  - Shared Room: ~$32–$34/night (cheapest)
- **Amenities:**
  - Safety, hygiene, and entertainment lead to significant price increases.
  - Mobility, kitchen utilities have moderate effects.
  - High-amenity listings average ~$25.88/night vs. low-amenity ~$22.08/night.
- **Other Factors:** "Instant Bookable" flag and bedroom categories have lesser impact.

### 3. Seasonality & Review Trends

- **Peak Review Months:** July (552K), May (510K), August (496K)
- **Lowest:** November (375K)
- **Review Sentiment:**
  - “Excellent” reviews dominate (~91–92%)
  - “Perfect” reviews peak in Jan–Feb
  - Fewer than 1% are “Bad” or “No Review”
- **Travel Insight:** Highest guest activity in summer, with consistently high satisfaction.

### 4. Host Trends

- **Hosts peaked during 2015–2016** with ~31.4K hosts.
- Regulatory changes and market saturation caused declines post-2017.
- Pandemic led to a sharp drop after 2020.
- Market has matured with slow post-pandemic recovery.

### 5. Best Value City

- **Istanbul:**
  - Cheapest listings (~$0.15/night for some)
  - Largest total reviews (5.4M)
  - High guest ratings (avg. 93.41%)
  - **Conclusion:** Istanbul delivers the best value for travelers.

### 6. Extra Insights

- **Cheapest Host:** Hong Kong ($0.03/night)
- **Most Expensive Host:** Brazil ($23,682.4/night)
- **Top-Rated Period:** Jan–Feb (high “Perfect” reviews)
- **Amenity Trends:** Safety & hygiene amenities have seen price increases since 2020.
- **Booking Type:** Instant Bookable listings boast higher engagement and slightly better ratings.

---

## Project Structure

- **Excel dashboard**
- **datasets**
  

## Usage

This dataset and analysis can be used by travelers, hosts, urban planners, and data scientists to:
- Compare city Airbnb markets
- Predict pricing based on listing attributes
- Track host and guest behavior trends
- Optimize listings for higher ratings and engagement

---

> **Average city rating across the dataset:** 93.41%
> **Period covered:** 2008–2021
