# 📊 A/B Testing Case Study: CTA Button & Click-Through Rate

## 📝 Project Overview
This project explores the impact of a design change in the CTA (Call-to-Action) button on the hero section of a website. Using **A/B testing and hypothesis testing**, we analyze whether the modification led to a statistically significant increase in **Click-Through Rate (CTR)**.

## 🔬 Methodology
The project follows a rigorous statistical approach:
1. **Data Collection**: Click data is gathered for both the control (old CTA) and variation (new CTA) groups.
2. **Total Clicks Per Group**: The total number of clicks is computed for each group.
3. **Pooled Probability Estimation**: The pooled probability of a click is calculated to estimate expected behavior under the null hypothesis.
4. **Pooled Variance & Standard Error Calculation**: These help quantify uncertainty in the estimates.
5. **Z-Test for Hypothesis Testing**:
   - **Null Hypothesis (H₀)**: The change in CTA button does not significantly impact CTR.
   - **Alternative Hypothesis (H₁)**: The new CTA button leads to a significant change in CTR.
6. **p-Value Analysis**: If \( p \leq 0.05 \) (at 5% significance level), we reject the null hypothesis in favor of the alternative.
7. **Confidence Interval Calculation**: Provides an estimated range of the true effect size.

## 📊 Key Findings
- The statistical test results, p-values, and confidence intervals help determine whether the new CTA button has a significant impact on user engagement.
- Visualizations (such as probability plots) illustrate the results.

## 📁 Project Structure
- **UI_UXAB_Testing_Case_Study.ipynb**: Jupyter notebook containing the full analysis.
- **ab_test_click_data.csv**: Folder containing raw and processed datasets.

## 🛠️ Technologies Used
- **Python**
- **Pandas** for data manipulation
- **NumPy** for mathematical operations
- **Matplotlib & Seaborn** for visualizations
- **SciPy** for statistical hypothesis testing

## 📢 Conclusion
This project demonstrates a practical **A/B testing** case study, showing how businesses can use statistical analysis to optimize user engagement. The approach can be extended to other website elements like headlines, images, and layouts.
