# Market_Basket_Analysis
Market Basket Analysis is a popular data mining technique used to identify associations between products purchased together. This project applies the Apriori algorithm to transactional data to extract frequent itemsets and generate association rules, which can help businesses
Data Simulation

Generates 500 synthetic transactions using common shopping patterns and random products.

Based on aisle_id from a dataset, which maps to product names.

Apriori Algorithm (mlxtend)

Identifies frequent itemsets with a minimum support of 5%.

Extracts association rules with confidence ≥ 60% and lift ≥ 1.5.

Rule Metrics

Support: How frequently itemsets appear.

Confidence: Likelihood of buying B if A is bought.

Lift: Strength of the relationship between A and B.

Visualizations

Matplotlib & Seaborn: Bar charts, scatter plots, heatmaps, parallel coordinates.

Plotly (Interactive): Sankey diagram and bubble charts for exploring rules.

User-Readable Rules

Rules like milk → eggs are easy to understand, visualize, and use in marketing.

Output Summary
Rules like coffee → cereal or milk → eggs are discovered.

Visual tools highlight:

Strongest product associations (lift > 1.5)

Most frequent and confident rules

Great for:

Product bundling

Layout optimization

Personalized recommendations

Conclusion
This code demonstrates a full Market Basket Analysis pipeline using Python:

From data generation to rule mining

From statistical filtering to powerful visual insights

It’s reusable, extensible, and can work with real retail data to boost business strategies.
