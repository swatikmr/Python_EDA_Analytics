# Movie Data Analytics Project

## Overview
This project performs extensive exploratory data analysis (EDA) on a movies dataset to uncover insights about movie performance, franchises, and industry trends. The analysis includes financial metrics (budget, revenue, ROI), audience reception (ratings, popularity), and various categorical analyses.

## Prerequisites
- Python 3.x
- pandas
- matplotlib
- wordcloud

## Installation
1. Clone this repository
2. Install required packages:
```bash
pip install pandas matplotlib wordcloud
```
3. Ensure you have the `movies_complete.csv` dataset in your working directory

## Dataset
The project uses a comprehensive movies dataset (`movies_complete.csv`) containing the following key fields:
- title
- budget_musd (budget in millions USD)
- revenue_musd (revenue in millions USD)
- vote_count
- vote_average
- popularity
- genres
- release_date
- original_language
- belongs_to_collection
- director
- tagline

## Features

### 1. Financial Analysis
- Best and worst movies by various metrics (budget, revenue, ratings)
- ROI calculations for movies with budgets over $5 million
- Top movies by revenue and profit
- Franchise success analysis

### 2. Performance Metrics
- Rating analysis with minimum vote thresholds
- Popularity rankings
- Genre-specific performance analysis

### 3. Visualization
- Title word cloud generation
- Tagline word cloud generation
- Multiple sorting and filtering capabilities

### 4. Specialized Queries
- Action/Thriller movie analysis with language and rating filters
- Franchise performance metrics
- Director success analysis


## Key Functions

### highest_lowest()
Parameters:
- `by`: Column to sort by
- `ascending_order`: Sort direction (default: False)
- `budget`: Minimum budget filter (default: 0)
- `votes`: Minimum votes filter (default: 0)

Returns: Filtered and sorted DataFrame with title and specified metric


## Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License
This project is available under the MIT License. See the LICENSE file for more details.

