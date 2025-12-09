# 📊 Project 8: YouTube Channel Performance Analysis

## 🔗 Repository Summary

This repository contains the complete data analysis project for the **BellaFiori** YouTube channel. The project's goal was to transition the channel from intuitive content planning to a data-driven strategy by identifying key performance indicators (KPIs) and determining the optimal days for video launch to maximize audience engagement.

The project demonstrates proficiency in **API communication (ETL), data cleaning, feature engineering, and statistical visualization.**

***

## 🎯 Project Goals

1.  **Robust Data Extraction (ETL):** Successfully utilized the YouTube Data API v3 to retrieve all historical video data by targeting the channel's dedicated **Uploads Playlist ID**.
2.  **Feature Engineering:** Cleaned raw statistics and created the crucial KPI: **Engagement Per 1,000 Views**, which accurately measures content quality independent of a video's age or total views.
3.  **Strategic Recommendation:** Provided a clear, data-backed recommendation on the **optimal days of the week** for content launch to maximize audience interaction.

## 🛠️ Technology Stack

* **Language:** Python
* **Libraries:** `google-api-python-client` (for API access), `pandas` (for data cleaning/analysis), `matplotlib` (for visualizations)
* **Tool:** Jupyter Notebook (`Youtube_API.ipynb`)

***

## 💡 Key Insights & Findings

Based on the full historical analysis of the channel's performance:

1.  **Optimal Launch Windows:** The analysis identified **Friday** (best day) and **Tuesday** (strong secondary day) as the optimal days for content launch, achieving the highest average engagement scores.
2.  **Engagement Gap:** Content posted on the best day delivered an engagement rate **$\mathbf{\approx 6.7}\%$** higher than content posted on the lowest-performing day, highlighting a significant opportunity for immediate optimization.
3.  **Content Strategy:** The correlation analysis distinguished between high-view content (mass appeal) and **high-engagement content** (community loyalty). The recommendation is to prioritize replicating the format of high-engagement videos.

## ✅ Final Recommendation

The channel should implement a two-pronged publishing strategy, prioritizing content launches on **Friday** and **Tuesday**. This shift leverages the audience's peak receptivity across the work week and the weekend, maximizing content visibility and potential subscriber conversion.

***

## 📁 Repository Structure

| File/Folder | Description |
| :--- | :--- |
| `Youtube_API.ipynb` | The core Jupyter Notebook containing all Python code for API calls, data cleaning, feature engineering, visualizations, and the final report. |
| `README.md` | This summary file, detailing the project, goals, and key findings. |
| `.gitignore` | Standard file to exclude sensitive data (like environment variables) and temporary files. |

## 🚀 How to Run the Project

1.  **Clone the Repository:** Use the direct HTTPS link for the repository:
    ```bash
    git clone [https://github.com/sreekarnati/YouTube_API](https://github.com/sreekarnati/YouTube_API)
    ```

2.  **Install Dependencies:**
    ```bash
    pip install google-api-python-client pandas matplotlib
    ```

3.  **Set Up API Key:**
    * Obtain a YouTube Data API v3 Key.
    * Set the key as an environment variable named `API` (or similar) on your system to protect your credentials.

4.  **Execute:** Open and run all cells in the `Youtube_API.ipynb` notebook sequentially. The final code cell provides the comprehensive analysis summary.
