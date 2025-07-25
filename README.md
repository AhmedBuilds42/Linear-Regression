# Linear-Regression
 Linear Regression with Outliers A practical walkthrough of linear regression using synthetic data with outliers. Demonstrates the mathematical intuition behind the best-fit line and how outliers distort model accuracy. Visualizations included to show error minimization and regression fitting.




Corporate‑speak version: We run a least-squares optimization pipeline to minimize the total “error gap” between our predictions and reality.

Plain English version: For every point, we check how far it is from our line (that’s called error or residual). We adjust the line’s slope and position again and again until the overall error is as small as mathematically possible.

The final line is:

𝑦 = 𝑚𝑥 + 𝑏
Where:

m = slope (how steeply your output changes when input changes)

b = intercept (where your line crosses the Y-axis when X=0)

Linear regression = best‑fit straight line to make predictions.

Why is it useful?

To predict: “If we spend $10k more on marketing, how many more units might we sell?”

To understand relationships: “Does more study time actually lead to higher scores?”

To simplify complexity: real-world messy data → one clean predictive rule.
