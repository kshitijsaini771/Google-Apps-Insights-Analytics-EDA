# Google Play Store App Analytics (EDA)

## Problem Statement
App developers and marketers need clear insights into **what drives app success** on Google Play Store—ratings, installs, reviews, pricing, and category performance. This **EDA project** analyzes 10K+ apps to uncover patterns in user engagement, monetization strategies, and market competition, providing actionable guidance for app optimization and launch decisions.

---

## Dataset Overview
- **Size:** 10,841 unique apps across **34 categories** with **13 core features**.
- **Key metrics:**
  - Average rating: **4.19** (1-5 scale).
  - **Free apps:** 92.6% (10,040) vs Paid (801).
  - Top categories: **FAMILY** (1,972 apps), **GAME**, **TOOLS**.
  - **Install ranges:** From 0-100 to **1B+**, with **1M+** most common (1,579 apps).
  - **Content ratings:** "Everyone" dominates (8,714 apps), followed by **Teen (1,146)**, **Mature 17+ (447)**.
  - Paid app prices: **$0.99–$400**, mostly under **$5**.
- **Features:** App name, category, rating, reviews, size (MB), installs, type (Free/Paid), price, content rating, genres, last updated, current version, Android version.
- **Data quality:** ~1,474 missing ratings; size/version sometimes "Varies with device" requiring preprocessing.

---

## EDA & Insights
- **Descriptive analysis:**
  - **Category distribution** and **average ratings**: **EDUCATION** and **ART_AND_DESIGN** lead at **4.37**, while **DATING (4.01)** and **MAPS_AND_NAVIGATION (4.06)** trail.
  - **Free vs Paid:** Free apps dominate volume; paid apps show nuanced rating/install patterns.
  - **Content rating breakdown:** "Everyone" apps form the bulk, with Teen and Mature segments showing distinct behaviors.
- **Performance patterns:**
  - **Install-rating correlation:** Higher install brackets correlate with **better ratings** (peak **4.37** at 50M-1B installs).
  - **Reviews by app type:** Analyzed average reviews for free vs. paid to gauge engagement.
  - **Category-wise app size:** Identified resource-heavy categories (e.g., Games, Tools).
  - **Top performers:** Most reviewed apps: **Facebook (78M reviews)**, **WhatsApp (69M)**, **Instagram (66M)**—all **1B+ installs**.
- **Advanced explorations:**
  - **Correlation analysis:** Examined relationships between installs/ratings/price/size.
  - **Binned analysis:** Rating trends across install brackets.
  - **Temporal patterns:** Update frequency and potential seasonality in app maintenance.
  - **Genre performance:** High-install genres (>1M) and their ratings.
- **Visualizations:**
  - **Bar charts** for category ratings and install distributions.
  - **Scatter plots** for installs vs. ratings, price vs. ratings.
  - **Top N lists** for reviews, installs, and high-rated apps.

---

## How to Use the Notebook
- **Libraries:** pandas, numpy, seaborn, matplotlib, plotly.
- Open `google-play-store-analytics.ipynb` in **Jupyter Notebook**, **JupyterLab**, or **Google Colab**.
- **Run sequentially:**
  1. Data loading and initial inspection.
  2. Data cleaning (missing ratings, size standardization).
  3. EDA sections generate summary stats, plots, and insights.
  4. Optional: Extend to predictive modeling (installs by category/size/pricing).
- **Original notebook:** [Google Play Store Analysis (Kaggle)](https://www.kaggle.com/code/kshitijsaini121/google-play-store-analysis)
- **Customization ideas:**
  - Filter by specific categories or content ratings for targeted market analysis.
  - Add **sentiment analysis** on reviews (if text available).
  - Build **time-series analysis** of update frequency vs. rating changes.
  - Create **predictive models** estimating installs from category, size, pricing.
  - Compare **free vs. paid performance** across regions/genres.

---

## Author & Contact
**Name:** `Kshitij Saini`  
**LinkedIn:** [Kshitij Saini](https://www.linkedin.com/in/kshitijsaini-b950b7299?utm_source=share_via&utm_content=profile&utm_medium=member_android)
