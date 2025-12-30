**Project Overview**

This project applies a data-driven customer segmentation framework to a multi-channel retail brand, Chestnut Ridge. Using survey-based customer data, the analysis identifies distinct customer segments and translates statistical insights into actionable marketing strategy. The project combines unsupervised machine learning, rigorous validation and strategic evaluation tools to support informed targeting decisions.

**Business Context**

Chestnut Ridge operates across multiple product categories and sales channels. As customer needs diversified, a one-size-fits-all marketing strategy became ineffective. The objective of this project is to:

- Identify meaningful customer segments

* Understand differences in preferences and demographics

+ Evaluate which segments are most attractive to target

Recommend data-backed marketing priorities

Data Description

The dataset contains 200 customer survey responses with the following variables:

Store Attribute Ratings (1–10 scale)

Variety of choice

Electronics

Furniture

Quality of service

Low prices

Return policy

Demographics

Annual income (USD, thousands)

Age

Methodology

The analysis follows a structured, reproducible workflow:

Data inspection and descriptive statistics

Z-score normalization to address scale differences

Euclidean distance calculation

Hierarchical clustering (Ward.D2) with dendrogram analysis

K-means clustering for solution robustness

Cluster validation using NbClust

Segment profiling using attitudinal and demographic means

Strategic evaluation using the McKinsey GE Matrix

Both 3-cluster and 4-cluster solutions were tested, with validation supporting a 4-cluster solution as optimal.

Key Findings

The analysis identified four distinct customer segments:

Value-Conscious Traditionalists
Large segment prioritising product variety and tangible goods.

Budget-Focused Pragmatists
Highly price-sensitive customers with low long-term loyalty potential.

Service-Driven Tech Explorers
Small but affluent segment valuing electronics, service quality, and return policies.

Experience-Oriented Loyalists
High-income, older customers prioritising premium service and loyalty-driven experiences.

Each segment displays clearly differentiated preferences, income levels, and ages, confirming meaningful market heterogeneity.

Strategic Insights

Using the McKinsey GE Matrix, segments were evaluated on:

Business strength (internal capabilities)

Segment attractiveness (size, growth, profitability)

Strategic Recommendations:

Invest & Grow: Value-Conscious Traditionalists

Manage Selectively: Budget-Focused Pragmatists

Develop Long-Term: Service-Driven Tech Explorers & Experience-Oriented Loyalists

The findings emphasize alignment between analytics and strategic decision-making, rather than segmentation for its own sake.

Tools & Technologies

Language: R

Libraries: tidyverse, NbClust, flexclust, car

Techniques:

Hierarchical clustering (Ward.D2)

K-means clustering

Cluster validation

Segment profiling

Strategic matrix analysis
