🚚 Swire Coca-Cola Capstone Project
Team 8: Wayne Park, Estefany Alvarado, Nick Acosta, Jocelyn Chang, Anais Corral
University of Utah – MSBA Spring 2025

🧩 Business Problem and Project Objective
Swire Coca-Cola currently delivers products through two primary methods: ARTM (white truck) for low-volume customers and direct delivery (red truck) for higher-volume accounts. However, some ARTM customers are showing strong growth potential. Moving these customers to ARTM too early could limit future revenue opportunities, while keeping stagnant or declining customers on red truck routes drives up unnecessary logistics costs. Additionally, frequent low-volume orders by many customers inflate delivery costs and reduce operational efficiency.

The objective of this project was to apply data science and business analytics to:
(1) identify high-growth ARTM customers who should remain on red truck delivery to support long-term revenue;
(2) recommend bulk ordering behavior to reduce delivery frequency and improve cost efficiency; and
(3) strengthen Sales Rep engagement to drive customer loyalty, increase conversion to direct delivery, and unlock untapped revenue through performance-based incentives.


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
Cost Savings: Reducing average deliveries per customer from 232 to 100 per year could yield a 56.6% reduction in delivery costs, translating to $380 saved per customer annually. This significantly improves Swire’s cost-to-serve while maintaining service levels.

Growth Enablement: High-potential ARTM customers are identified and retained on red truck (direct delivery), ensuring scalable customer relationships and preserving future growth. Bulk-order strategies reduce logistics strain while supporting customer retention and expansion in key ZIP codes.

Sales Rep Conversion Opportunity: With nearly 20,000 customers ordering through Sales Reps, even a 5% conversion to direct delivery—supported by performance-based incentives—could generate $130M in new revenue and $39M in annual profit, assuming a 30% margin. This unlocks significant growth through more strategic sales engagement.


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
