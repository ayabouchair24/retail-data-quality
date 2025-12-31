# retail-data-quality
This project focuses on assessing and structuring the quality of retail product data before it is used for reporting or business intelligence dashboards.

## Data
The dataset comes from Open Food Facts (kaggle) which has retail product information such as "product name", "nutritional values"..etc

## Approach
- EDA
- measure data completeness per product
- apply simple business rules e.g (energy > 0, macros ≤ 100g)
- compute a quality score combining completeness and consistency
- map scores to business (easy to read) labels: Good / Acceptable / To fix.
