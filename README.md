#  Statistical Modeling & Multi-Platform Benchmarking: Airline-Tourism Arrivals
* **Objective:** Developed an end-to-end forecasting framework to transform raw macroeconomic logs into a structured time-series predictive model for international arrivals in Myanmar.
* **Core Methodology:** Applied an advanced statistical modeling framework (implemented during undergraduate final year research paper at YUECO) to analyze 6 years of monthly transactional data extracted from the Central Statistical Organization (CSO).
* **Cross-Platform Benchmarking:** Built and tested identical forecasting configurations across **Python, SAS, SPSS, R Studio and R** to mathematically isolate the analytics engine with the lowest error variance.

---

####  Statistical Modeling Pipeline & Roadmap
The time-series forecasting engine was engineered through a rigorous 5-step applied statistical framework under precise structural assumptions:
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/f3e09039-2396-4625-b80d-a03d9ee1aef1" />

---

####  Time-Series Visualizations & Model Fitting
Below are the comprehensive analytical graphs capturing the trend decomposition, deseasonalized baselines, and predictive forecast confidence intervals (95% Prediction Interval) generated during the optimization process:

<img width="1600" height="1600" alt="1000031072 (1)" src="https://github.com/user-attachments/assets/83c5dcab-4cdc-46de-8463-788164a06103" />

---

####  Model Evaluation Metrics & Benchmarking
After completing all 5 framework steps, Holt-Winters' Exponential Smoothing (three parameters) both Additive & Multiplicative Models are chosen. Multiple evaluation metrics (SSE, MSE, RMSE, MAPE) were benchmarked across these two primary mathematical variations to guarantee high-performing, fast, and accurate insights.


| Analytics Tool | Metrics | Additive Model | Multiplicative Model | Performance Status |
| :--- | :--- | :---: | :---: | :--- |
| **Python** | SSE <br> MSE <br> RMSE <br> **MAPE** | 2372.69 <br> 28.24 <br> 5.31 <br> **3.80%** | 2482.51 <br> 29.55 <br> 5.43 <br> **3.87%** |  **Top Performer** (Lowest Error Rate) |
| **SAS** | SSE <br> MSE <br> RMSE <br> **MAPE** | 2535.22 <br> 30.18 <br> 5.49 <br> **3.95%** | 3547.58 <br> 42.23 <br> 6.49 <br> **4.03%** |  **Strong Second** (Highly Reliable) |
| **SPSS** | SSE <br> MSE <br> RMSE <br> **MAPE** | 2630.47 <br> 31.31 <br> 5.59 <br> **3.96%** | 3676.80 <br> 43.77 <br> 6.61 <br> **4.03%** |  **Strong Second** |
| **R / RStudio** | SSE <br> MSE <br> RMSE <br> **MAPE** | 5013.49 <br> 59.68 <br> 7.72 <br> **5.34%** | 5590.42 <br> 66.55 <br> 8.15 <br> **5.11%** |  High Variance on this Dataset |

---

####  Key Strategic Takeaways
* **Data Cleansing & Integrity:** Re-structured 6 years of unstructured historical data, managing missing values and formula derivations to achieve a data architecture fit for predictive analytics.
* **Optimal Framework Selection:** Identified that **Python's Additive Configuration** yielded the maximum forecasting accuracy with a **MAPE of only 3.80%**.
* **End-to-End Ownership:** Managed the entire analytics lifecycle independently, spanning raw data aggregation, multi-tool code benchmarking, regression-driven variance tracking, and strategic slide documentation.

####  Tech Stack & Skills Demonstrated
* `Python` `SAS` `SPSS` `R` `RStudio`
* Time-Series Forecasting, Statistical Roadmap (Deseasonalization, Least Squares Method, Sign Test), Regression Analysis, Error Benchmarking.


