# KDM-Nutrition-Analytics

## Project Overview: AI-Powered Promotion for Independent Associates (IA)

### Problem Statement
Independent Associates (IA) in the wellness industry, specifically those promoting products like **Ambrotose 2x** and **OSP**, often face the challenge of "one-size-fits-all" marketing. This project uses Knowledge Discovery and Data Mining (KDM) to:

1. **Segment Customers:** Use K-Means++ to identify specific health "Personas" (e.g., High-Stress Tech Workers vs. Wellness Seekers).
2. **Optimize Recommendations:** Use FP-Growth to discover product associations, ensuring customers receive the most relevant nutrition advice.

### KDM Methodology
* **Customer Segmentation:** Using clustering to define target groups.
* **Association Rule Mining:** Using FP-Growth to find product relationships.
* **Evaluation:** Using Silhouette Scores and Lift metrics to ensure model quality.

### Data Source Note
Due to privacy reasons, this project utilizes a high-quality synthetic dataset generated to follow real-world business logic for health and nutrition products.
