🚚 Swire Coca-Cola Capstone Project
Team 8: Wayne Park, Estefany Alvarado, Nick Acosta, Jocelyn Chang, Anais Corral
University of Utah – MSBA Spring 2025

🧩 Business Problem and Project Objective
Swire Coca-Cola delivers products through two primary methods: ARTM (white truck) for low-volume customers and direct delivery (red truck) for higher-volume accounts. However, some ARTM customers show signs of high growth. Moving these customers to ARTM too early could limit future revenue potential, while keeping stagnant accounts on red truck routes increases unnecessary costs. Additionally, many customers place frequent low-volume orders, which inflates delivery costs.


The objective of this project was to use data science and business analytics to (1) identify which ARTM customers are likely to grow and should remain on red truck delivery, and (2) encourage bulk ordering behavior to reduce delivery frequency and overall logistics cost.


💡 Our Group's Solution
We developed a data-driven framework combining segmentation, forecasting, and machine learning:

XGBoost classification was used to predict high-growth customers based on historical delivery data and business attributes.

Delivery cost optimization was explored by estimating the impact of reducing annual delivery frequency through bulk ordering incentives.

Customers were segmented by ZIP code, delivery channel, order frequency, and growth potential to identify target zones for route strategy changes.

The team also performed benchmarking using ARIMA models to validate growth trends for selected customers, though these were not the final model deployed.


👤 My Contribution (Wayne Park)
Conducted exploratory data analysis and delivery frequency modeling in R.

Calculated customer-level delivery costs and created a framework to estimate cost savings from bulk order reductions.

Performed ARIMA time series forecasting for high-growth customer benchmarking.

Wrote delivery optimization recommendations and the associated cost-benefit breakdowns.

Helped format and structure the final GitHub notebook and README.


💼 Business Value of the Solution
Cost Savings: Reducing average deliveries per customer from 232 to 100/year could save up to $380 per customer annually.

Growth Enablement: Identifying high-potential ARTM customers ensures they stay on direct delivery routes, supporting long-term revenue generation.

Operational Efficiency: Delivery frequency modeling and channel analysis empower Swire to align routing strategy with scalable customer behavior.


⚠️ Difficulties We Encountered
Customer behavior was highly variable, with significant noise in delivery volume and frequency.

Delivery cost data was spread across multiple categories (e.g., cases vs. gallons, per route type) and required extensive cleaning.

Early forecasting models (e.g., ARIMA) did not generalize well due to inconsistent order timing and volume.

Defining growth and segment thresholds required balancing business judgment with model performance.


📚 What I Learned
How to apply supervised machine learning to real-world segmentation and classification problems.

The business impact of delivery frequency and how logistics strategies translate directly into cost or profit.

Techniques for balancing cost efficiency with customer service quality in a data-driven way.

The importance of storytelling and clear recommendation framing when presenting to stakeholders.
