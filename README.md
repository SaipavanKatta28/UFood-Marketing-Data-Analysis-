# Customer Marketing Strategy Analysis & Re-Allocation

*A data-driven solution to optimize marketing spend*

## Project Overview

### The Business Problem

This project directly addresses the business problem from the provided [UFood Data Analyst Case.pdf](https://github.com/SaipavanKatta28/UFood-Marketing-Data-Analysis-/blob/main/UFood%20Data%20Analyst%20Case.pdf). The company's profit growth perspectives for the next three years are not promising, and strategic initiatives are needed to reverse this trend. The marketing department, in particular, is under pressure to spend its annual budget more wisely and prove the value of its campaigns.

### My Solution & Impact

My analysis provides a direct, data-driven solution. I identified high-value, untapped customer segments and pinpointed the company's most effective (and currently underutilized) sales channel. The result is a clear, two-pronged strategy to re-allocate marketing spend from inefficient, generic campaigns to highly targeted, high-ROI actions.

* **Notebook:** [`UFoodMarketingAnalysis.ipynb`](https-in-app-file-link-removed)

* **Case Study:** [`UFood Data Analyst Case.pdf`](https-in-app-file-link-removed)

* **Data Dictionary:** [`ufood_marketing_Dictionary.jpg`](https-in-app-file-link-removed)

## Key Skills Demonstrated

* **Tools:** Python, Pandas, Matplotlib, Seaborn

* **Techniques:**

  * Data Cleaning & Preprocessing

  * Feature Engineering (e.g., `Total_Children`, `Age_Group`, `MntTotal`)

  * Exploratory Data Analysis (EDA)

  * Advanced Correlation Analysis (Pearson)

  * Data Visualization & Business Storytelling

  * Strategic Recommendation & ROI Justification

## Analytical Workflow: From Data to Strategy

My analysis followed a multi-stage process to move from raw data to a specific, actionable strategy.

1. **Data Cleaning & Feature Engineering:**

   * Processed and cleaned the raw dataset, handling nulls and duplicates.

   * Engineered new features (e.g., `Age_Group`, `Total_Children`) to enable meaningful behavioral analysis.

2. **Exploratory Data Analysis (EDA):**

   * Identified the primary drivers of customer behavior.

   * **Key Finding:** `Total_Children` was the strongest *negative* predictor of spending.

   * **Key Finding:** `Age` showed a "U-shaped" pattern, with **21-30** and **71+** groups being the most receptive to campaigns, flagging them as a high-potential growth audience.

   * **Key Finding:** Ruled out `Education` and `Marital_Status` as non-impactful, identifying them as poor targets for marketing spend.

3. **Advanced Behavioral Analysis (The Core Insight):**

   * The project's key insight came from moving beyond simple *volume* metrics (like "total store purchases") which were misleading.

   * I built correlation heatmaps to analyze *behavioral patterns*, connecting specific **Products** (e.g., `MntWines`) to **Channels** (e.g., `NumCatalogPurchases`) for key demographics.

   * **The Core Insight:** The low-volume **Catalog** channel has the highest correlation (e.g., **0.73**) with high-value sales (Wine & Meat) for our most valuable customer demographic (41-70 age group). This identified the catalog as the company's most powerful, underutilized sales tool.

## Final Recommendations for Stakeholders

This analysis led to a clear, two-pronged strategy to optimize the marketing budget:

### 1. Primary Target (Maximize Revenue)

* **Action:** Stop generic ads. **Invest in a premium Wine & Meat catalog** and send it directly to our most valuable demographic: **High-Income, 41-70-year-olds, with no children.**

* **Why:** This demographic is our proven revenue driver. Our correlation analysis (Cell 209) proves the *catalog* is the most effective channel to sell our most profitable products (Wine & Meat) to them. This is a targeted, data-backed action to maximize ROI.

### 2. Secondary Target (Build Future Growth)

* **Action:** Launch targeted **catalog campaigns** with introductory offers for Wine and Meat.

* **Why:** The **21-30** and **71+** age groups are the easiest to convert (highest campaign acceptance rate).

* **How:** Our data (from Cell 207) shows this group *also* has its strongest purchase correlation for **Wine (0.58)** and **Meat (0.53)** when using the **Catalog**. This gives us a clear, data-driven starting point to convert this high-engagement audience into loyal, high-value customers.

## How to Use This Repository

1. Clone the repository.

2. Ensure you have the required libraries: `pandas`, `matplotlib`, `seaborn`.

3. Open and run the [`UFoodMarketingAnalysis.ipynb`](https-in-app-file-link-removed) notebook to see the full analysis.

4. Review the `Executive Summary` markdown cell at the end of the notebook for a final summary.
