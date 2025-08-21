# email-campaign-lift-analysis

📌 Situation

Our company wanted to evaluate whether personalized emails drive higher customer engagement compared to generic emails. Marketing efforts were being split, but no concrete evidence existed to prove which strategy delivered better results.

🎯 Task

The goal was to:

Compare conversion rates between customers receiving personalized vs generic emails.

Quantify the lift (absolute & relative) in conversions from personalization.

Statistically validate whether personalization provides a significant business advantage.

⚙️ Action

We conducted a two-proportion z-test (statistical hypothesis test) on campaign data:

📩 Personalized Emails (Nₚ = 431)

📩 Generic Emails (N_g = 1627)

Steps followed:

Data Preparation – Organized conversion outcomes by group (personalized vs generic).

Statistical Testing – Applied a z-test for proportions to check if conversion rates differ significantly.

Lift Calculation – Measured both absolute lift (percentage point increase) and relative lift (percentage growth).

Confidence Interval – Computed a 95% confidence interval for the lift to ensure reliability.

Business Interpretation – Translated results into insights for marketing stakeholders.

📊 Results

Conversion Rate (Personalized): 40.60%

Conversion Rate (Generic): 8.48%

Absolute Lift: +32.12 percentage points

Relative Lift: +378.71%

Statistical Test: z = 16.511, p < 0.001 (highly significant)

95% CI for Lift: [27.47%, 36.92%]

✅ Result (Business Impact)

Personalized emails drove nearly 5x higher conversions compared to generic emails.

The results are statistically significant, giving confidence that personalization is not just due to chance.

Recommendation: Prioritize personalized email campaigns to maximize engagement and ROI.
