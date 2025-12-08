# 📊 Project 8: YouTube Channel Performance Analysis

## 🔗 Repository Summary

This repository contains the complete data analysis project for the **BellaFiori** YouTube channel (`UCaezsZGhwWgB4ZRmHNCfIyw`). The project's goal was to transition the channel from intuitive content planning to a data-driven strategy by identifying key performance indicators (KPIs) and determining the optimal day for video launch to maximize audience engagement.

The project demonstrates proficiency in **API communication (ETL), data cleaning, feature engineering, and statistical visualization.**

***

## 🎯 Project Goals

1.  **Robust Data Extraction (ETL):** Successfully utilized the **YouTube Data API v3** to retrieve all historical video data by targeting the channel's dedicated Uploads Playlist, bypassing API search limitations.
2.  **Feature Engineering:** Cleaned raw statistics and created the crucial KPI: **Engagement Per 1,000 Views**, which accurately measures content quality independent of a video's age or total views.
3.  **Strategic Recommendation:** Provided a clear, data-backed recommendation on the **optimal day of the week** for content launch to maximize audience interaction.

## 🛠️ Technology Stack

* **Language:** Python
* **Libraries:** `google-api-python-client` (for API access), `pandas` (for data cleaning/analysis), `matplotlib` (for visualizations)
* **Tool:** Jupyter Notebook (`Youtube_API.ipynb`)

***

## 💡 Key Insights & Findings

Based on the full historical analysis of the channel's performance:

1.  **Optimal Launch Day:** The analysis identified **Friday** as the single best day for content launch, achieving the highest average engagement score ($\mathbf{\approx 13.0}$ per 1,000 Views). **Tuesday** was confirmed as a strong secondary launch day.
2.  **Engagement Gap:** Content posted on the best day (Friday) delivered an engagement rate **$\mathbf{\approx 6.7}\%$** higher than content posted on the lowest-performing day, highlighting a significant and immediate opportunity for optimization.
3.  **Content Quality:** The correlation analysis (Views vs. Engagement) distinguished between high-view content (mass appeal) and **high-engagement content** (community loyalty). The channel must focus on replicating the formats of high-engagement videos to build a stronger community.

## ✅ Final Recommendation

Implement an immediate scheduling shift to **Friday** as the primary content launch day. This tactical change leverages the audience's peak receptivity, maximizing the content's initial visibility and potential subscriber conversion.

***

## 📁 Repository Structure

| File/Folder | Description |
| :--- | :--- |
| `Youtube_API.ipynb` | The core Jupyter Notebook containing all Python code for API calls, data cleaning, feature engineering, visualizations, and the final report. |
| `README.md` | This summary file, detailing the project, goals, and key findings. |
| `.gitignore` | Standard file to exclude sensitive data (like environment variables) and temporary files. |

## 🚀 How to Run the Project

1.  **Clone the Repository:**
    ```bash
    git clone [LINK](https://github.com/sreekarnati/YouTube_API)]
    ```

2.  **Install Dependencies:**
    ```bash
    pip install google-api-python-client pandas matplotlib
    ```

3.  **Set Up API Key:**
    * Obtain a YouTube Data API v3 Key from Google Cloud Console.
    * Set the key as an environment variable named `API` (or similar) on your system to protect your credentials.

4.  **Execute:** Open and run all cells in the `Youtube_API.ipynb` notebook sequentially. The final code cell provides the comprehensive analysis summary and recommendation.
