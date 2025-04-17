📊 Capstone: Swire Coca-Cola Logistics Optimization

✅ Business Problem
Swire Coca-Cola operates two delivery methods: white truck (ARTM) for low-volume customers and red truck (direct delivery) for higher-volume ones. Our business challenge was to identify high-growth potential customers currently on ARTM who should be moved to red truck delivery, enabling cost-efficient logistics while fueling future growth.

✅ Our Solution
We used a combination of XGBoost classification models and decision trees to segment customers by growth potential. By analyzing transactional volume, delivery frequency, cost-per-delivery, and order channel, we identified which ARTM customers show signs of scaling and should be prioritized for red truck service.

We also evaluated bulk ordering strategies to reduce delivery frequency, which could result in up to 56.6% cost savings per customer. Route optimization and ZIP-level targeting were also explored to guide implementation.


✅ My Contribution (Wayne Park)
Led exploratory data analysis and delivery cost modeling using R.

Developed ARIMA forecasting (benchmarked, not deployed) to evaluate growth trends.

Designed bulk order cost-reduction scenarios and delivery frequency insights.

Wrote majority of the business insights and recommendation slides.

Contributed to GitHub notebook structure and README documentation.


✅ Business Value of Our Solution
Cost Reduction: Reducing high-frequency deliveries (232 to 100/year) could save $380–$525 per customer annually.

Targeted Growth: Prioritizing red truck service in ZIPs with high volume and low delivery cost (e.g., KS, MA) improves ROI.

Sales Enablement: Empowering reps with predictive insights fosters stronger customer relationships and higher retention.

Strategic Expansion: Market-level analysis (e.g., Kansas as a hub) provides a roadmap for smart logistics investments.


✅ Difficulties We Encountered
Delivery frequency data was noisy and highly skewed, requiring multiple data cleaning passes.

Growth rate calculation was sensitive to outliers and inconsistent customer behavior.

Integrating cost data from multiple sources (cases vs. gallons, per truck type) introduced merging challenges.

Our early ARIMA forecasting was not predictive enough due to volatility in the data.


✅ What I Learned
How to use R and modeling (e.g., XGBoost) to make segment-specific logistics decisions.

The importance of pairing analytics with business logic — e.g., recognizing when a customer is not just growing, but also logistically affordable to serve.

How to translate a technical model into an executive-facing recommendation.

The importance of teamwork and iteration when refining customer-level strategies in real-world data.
