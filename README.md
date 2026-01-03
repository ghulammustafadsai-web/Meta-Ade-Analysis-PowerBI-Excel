# Meta Ad Performance Analysis 🚀

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-blue) ![Excel](https://img.shields.io/badge/Tool-Excel-green) ![Status](https://img.shields.io/badge/Status-Completed-success)

---

## 1. Project Background
This project analyzes a **Meta advertising campaign** with a total investment of **$2.5M**. The goal is to understand why a high engagement rate (**11.76% CTR**) is not fully converting into completed purchases.  

By analyzing **user behavior** and **ad formats**, the project identifies friction points in the conversion funnel and provides actionable strategies to optimize future marketing spend.

---

## 2. Data Set Overview & Model
The campaign data is structured in a **relational database**, tracking user interactions from **first impression** to **final sale**.

<details>
<summary>Click to expand: Data Model & Column Details</summary>

### Tables & Columns

| Table       | Description | Key Columns |
|------------|------------|------------|
| **Campaigns** | Tracks high-level campaign data | `campaign_id`, `name`, `duration_days`, `total_budget` |
| **Ads** | Contains creative attributes | `ad_platform` (Facebook/Instagram), `ad_type` (Video/Stories), `target_interests` |
| **Users** | Contains demographic profiles | `user_gender`, `age_group`, `country`, `user_interests` |
| **Ad Events** | Central fact table recording interactions | `event_type` (Impression, Click, Purchase), `timestamp`, `time_of_day` |

### Data Model Overview
<img width="499" height="293" alt="Data_model_screenshot" src="https://github.com/user-attachments/assets/1328a87d-9514-4b25-95ba-abafc57406b0" />

</details>

---

## 3. Executive Summary
The Meta advertising campaign successfully captured the attention of a large audience. The ads reached a total of **216k people** and achieved an impressive **click-through rate (CTR) of 11.76%**, far above the industry average of 1–2%. This means that the campaign was very effective at attracting interest and getting people to click on the ads.

However, despite this high engagement, the number of **actual purchases was much lower**, with only **1,300 purchases** coming from **25,400 clicks**. This indicates that while the ads were successful in getting users’ attention, many potential customers were **dropping off before completing their purchase**. The main friction appears to be in the final steps—like the website experience, checkout process, or product details.

By looking closely at the campaign data, we can identify **who engaged with the ads, which ad formats worked best, and when users were most active**. This provides valuable insights for **optimizing future campaigns** to make sure clicks actually turn into purchases.

### Key Data Points (for easy reference)

- **Total Impressions:** `216K`  
- **Click-Through Rate (CTR):** `11.76%`  
- **Total Clicks:** `25.4K`  
- **Total Purchases:** `1.3K`  

### Dashboard Overview
**Image-1**

<img width="661" height="379" alt="img1" src="https://github.com/user-attachments/assets/e5105fdb-429d-4747-9b2c-82f881e9801f" />



**Imaage-2**

<img width="661" height="377" alt="img2" src="https://github.com/user-attachments/assets/4ab774dd-e92f-4f9c-ae9b-32870681a3e8" />


---

## 4. Key Insights
<details>
<summary>Click to expand: Key Insights</summary>

- **Demographic Reach:** Women are the most active participants (`13K engagements`) vs men (`6K engagements`).  
- **Core Audience:** Young adults aged **18–30** form the primary user base.  
- **Format Performance:** Video ads lead with `11.9% CTR` and `5.2% purchase rate`.  
- **Brand Exposure:** Stories are highly effective, contributing `72K impressions`.  
- **Geography & Timing:** Highest engagement from **US, India, Brazil**, especially `15:00–20:00`.

</details>

---

## 5. Recommendations & Impact
<details>
<summary>Click to expand: Recommendations</summary>

- **Target Optimization:** Focus on women aged **18–30** in **US and India**.  
- **Creative Spend Shift:** Invest more in **Video and Stories**, reduce static image spend.  
- **Temporal Strategy:** Schedule ads during **afternoon and evening**.  
- **UX Improvements:** Optimize **landing pages** to reduce friction and boost conversions.  

**Expected Impact:**  
Reduces wasted ad spend on low-performing segments and improves **click-to-purchase conversion rate**.

</details>

---

## 6. Tools Used
| Tool       | Purpose |
|------------|--------|
| **Power BI** | Data modeling, DAX calculations, interactive dashboards |
| **Excel** | Initial data inspection, summaries |

---

## 7. Author 
 **Ghulam Mustafa**

