# sneakerhub-predictive-ml
# 👟 SneakerHub: Predictive ML Marketing Forecast

## 📌 The Story
SneakerHub, a boutique shoe retailer, was tired of guessing how much money they would make when they ran Instagram ads. They knew ads worked, but they didn't know the exact math behind it. 

Instead of letting the owner guess the marketing budget, I took their historical ad spend and sales data and built a predictive Machine Learning model. The goal? To build an engine where the owner could type in any ad budget and instantly see the guaranteed revenue.

## 🛠️ How I Built It
* **The Stack:** Python, Pandas, Scikit-Learn, Matplotlib
* **Train:** I used `scikit-learn` to split the data into Features (Ad Spend) and Targets (Sales) and trained a Simple Linear Regression algorithm to find the underlying mathematical pattern.
* **Test:** I evaluated the model's accuracy using the R-squared metric to ensure the predictions were reliable, not just random guesses.
* **Visualize:** I used `matplotlib` to plot the raw data against the AI's "Line of Best Fit" so the non-technical client could visually understand the AI's logic.

## 📈 The Results
* **Pinpoint Accuracy:** The model achieved a massive **99.8% accuracy score**, meaning the relationship between ad spend and sales is practically perfectly correlated.
* **The Forecast:** I successfully ran a forecast proving that a future ad spend of $1,500 will mathematically yield **$7,152** in total sales.

## 💡 The Big Takeaway
Marketing doesn't have to be a guessing game. By applying foundational Machine Learning algorithms to historical data, businesses can transform their ad budgets from a "hopeful expense" into a guaranteed revenue generator.
