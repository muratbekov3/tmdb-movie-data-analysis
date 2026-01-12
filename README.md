# TMDb Movie Data Analysis 🎬

## Overview
This project analyzes a dataset of ~10,000 movies from The Movie Database (TMDb) to uncover insights about:
- Movie budgets vs revenue
- Runtime trends over time
- Genre popularity

The analysis focuses on inflation-adjusted financials to allow fair comparison across decades.

---

## Key Questions Answered
- Is higher budget associated with higher revenue?
- How have movie runtimes changed over time?
- Which genres are most popular among TMDb users?

---

## Dataset
- Source: TMDb Movie Dataset
- Size after cleaning: **3,808 movies**
- Key fields:
  - `budget_adj`, `revenue_adj`
  - `runtime`
  - `genres`
  - `popularity`
  - `release_year`

---

## Data Cleaning & Wrangling
- Removed irrelevant text-heavy columns
- Converted release dates to datetime
- Filtered out movies with zero budget or revenue
- Handled missing categorical values
- Removed duplicate movie titles
- Normalized genres using explode

---

## Exploratory Data Analysis Highlights

### Budget vs Revenue
- Moderate-to-strong positive correlation
- High budgets increase potential revenue but do not guarantee success

### Runtime Trends
- Movie runtimes peaked in the 1960s–70s
- Modern movies are more standardized (~90–120 minutes)

### Genre Popularity
- Most popular genres:
  - Science Fiction
  - Adventure
  - Action
- Indicates strong audience preference for high-concept, visual-driven films

---

## Limitations
- Excluded ~60% of movies due to missing financial data
- Results mainly reflect mainstream commercial cinema
- Correlation does not imply causation

---

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib

---

## Author
**Akylbek Muratbek uulu**  
Computer Science Graduate | Data & Security Enthusiast
