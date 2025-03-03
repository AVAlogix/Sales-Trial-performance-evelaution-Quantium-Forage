# Sales Trial Performance Evaluation

## Project Overview
This project evaluates a **store trial conducted in stores 77, 86, and 88** by comparing them with a **control store (224)**. The goal is to determine if the trial had a significant impact on sales performance and to identify the key drivers of change, such as:  

- Increased number of customers  
- More transactions per customer  
- Higher spend per transaction  

To ensure valid comparisons, **Pearson correlation** and **magnitude distance metrics** are used to find the best-matching control stores.

---

## Data Source
https://www.theforage.com/virtual-experience/NkaC7knWtjSbi6aYv/quantium/data-analytics-rqkb/experimentation-and-uplift-testing

- Task 2 of the Data analysis job simulation at Quantium by Forage
---

## Analysis Breakdown
The evaluation considers **monthly sales experience** of each store based on:  
1. **Total Sales Revenue**  
2. **Total Number of Customers**  
3. **Average Number of Transactions per Customer**  

###  1️. Determining the Control Store
- Compute **Pearson correlation** to find stores with similar historical trends.
- Compute **magnitude distance** to measure absolute sales similarity.
- Select the store with the highest combined similarity score.

---

###  2️. Trial vs. Control Store Comparison
- Perform a **T-test** between trial and control stores during the trial period.
- Evaluate whether sales changes are statistically significant (`p < 0.05`).
- Identify whether the change is due to:
  - Increased **customers**
  - More **transactions per customer**
  - Higher **spend per transaction**

---

###  3️. Visualization of Trial vs. Control
- Plot **total sales trends** for trial and control stores.
- Visualize **customer and transaction behavior** during the trial.
- Show percentage change in **sales, customers, and transactions**.

---

## Future Improvements
🔹 Compare multiple control stores instead of just one.  
🔹 Include additional metrics such as product categories and discount effects.  
🔹 Improve visualizations with Seaborn/Matplotlib.  

---

### Contributions & Issues 
Feel free to **fork, contribute, or report issues** to improve this project! 🚀  
