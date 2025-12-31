# Data-Driven Segmentation for Chestnut Ridge

# **Project Overview**

This project applies a data-driven customer segmentation framework to a multi-channel retail brand called Chestnut Ridge. Using 200 customer survey responses, the analysis identifies distinct customer segments and translates statistical insights into actionable marketing strategy. The project combines unsupervised machine learning, rigorous validation and strategic evaluation tools to support informed targeting decisions.

# **Project Context**

Chestnut Ridge operates across multiple product categories and sales channels. As customer needs diversified, a one-size-fits-all marketing strategy became ineffective. The objective of this project is to:

- Identify meaningful customer segments
- Understand differences in preferences and demographics
- Evaluate which segments are most attractive to target
- Recommend data-backed marketing priorities

# **Data Description**

- **Sample size:** 200 customers
- **Variables:** 8 behavioural + demographic features

## **Store Attribute Ratings (1-10 scale):**

- Variety of choice (mean: 7.57, range: 4-10)
- Electronics (mean: 4.45, range: 1-10)
- Furniture (mean: 3.27, range: 0-7)
- Quality of service (mean: 3.53, range: 1-9)
- Low prices (mean: 4.80, range: 1-10)
- Return policy (mean: 4.25, range: 1-10)

## **Demographics:**

- Income (mean: $32.2k, range: $13k-$95k)
- Age (mean: 32.5 years, range: 21-68 years)

# **Project Methodology**

The analysis follows a structured workflow:
- Descriptive statistics and scale diagnostics
- Z-score normalisation of all clustering variables
- Euclidean distance computation
- Hierarchical clustering (Ward.D2) with dendrogram analysis
- K-means clustering (nstart = 100, iter.max = 1000)
- Cluster validation using NbClust (15 indices)
- Segment profiling using cluster means and proportions
- Strategic evaluation using the McKinsey GE Matrix

Both 3-cluster and 4-cluster solutions were tested, with the majority rule (8 indices) supporting a 4-cluster solution as optimal.

# **Key Findings**

The analysis identified four distinct customer segments:

- **Value-Conscious Traditionalists:** Large segment prioritising product variety and tangible goods (customers: 94, share: 47%).
- **Budget-Focused Pragmatists:** Highly price-sensitive customers with low long-term loyalty potential (customers: 60, share: 30%).
- **Service-Driven Tech Explorers:** Small but affluent segment valuing electronics, service quality and return policies (customers: 17, share: 8.5%).
- **Experience-Oriented Loyalists:** High-income, older customers prioritising premium service and loyalty-driven experiences (customers: 29, share: 14.5%).

Each segment displays clearly differentiated preferences, income levels and ages, confirming meaningful market heterogeneity.

# **Strategic Insights**

Using the McKinsey GE Matrix, segments were evaluated on:

- Business strength (internal capabilities)
- Segment attractiveness (size, growth, profitability)

## **Recommendations:**

- **Invest and Grow:** Value-Conscious Traditionalists
- **Manage Selectively:** Budget-Focused Pragmatists
- **Develop Long-Term:** Service-Driven Tech Explorers and Experience-Oriented Loyalists

The findings emphasize alignment between analytics and strategic decision-making, rather than segmentation for its own sake.

# **Tools and Technologies**

- **Language:** R
- **Libraries:** tidyverse, NbClust, flexclust, car
- **Techniques:** Hierarchical clustering (Ward.D2), K-means clustering, Cluster validation, Segment profiling, Strategic matrix analysis

# Key Takeaway

This project demonstrates how unsupervised learning, when combined with rigorous validation and strategic frameworks, can convert raw customer data into clear, defensible marketing decisions.
