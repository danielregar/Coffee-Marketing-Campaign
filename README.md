# Coffee Marketing Campaign

![Marketing Analysis](https://github.com/user-attachments/assets/01d794a4-05b5-47f7-97f7-4801cfb23fba)

---
# 📊 Marketing Campaign Analysis (2022–2024)

This is an end-to-end data analytics project marketing case.

The project answers key stakeholder questions to help optimize campaign performance, maximize ROAS, and reallocate marketing budget efficiently.

---

## 🧠 Business Context

The marketing team ran over 300 campaigns between 2022 and 2024 across multiple channels and regions. The goal was to identify:

- Which channels perform best
- Which campaigns are wasting budget
- How to optimize future spend based on historical data

---

## 🎯 Stakeholder Questions

1. Which channel performs best in terms of ROAS?
2. Are we overspending on low-converting campaigns?
3. Which region and year delivered the best results?
4. How should we shift budgets for 2025?

---

## 🧮 Tools Used

- **MySQL** – data cleaning & transformation
- **Power BI** – dashboard creation & storytelling
- **DAX** – custom measures (ROAS, CPA, CTR, Conversion Rate)

---

## 📁 Dataset Overview

Period: 2022 - 2024

Key Columns:

- campaign_name, channel, region, year

- spend, revenue, conversions

- Derived metrics: ROAS, CPA, conversion_rate

---

## 📌 Executive Summary
Between 2022 and 2024, the Company ran multiple marketing campaigns across various digital channels and regions. Using SQL, Power BI, and DAX, we evaluated campaign performance based on Return on Ad Spend (ROAS), Cost Per Acquisition (CPA), and Conversion Rate.

Key takeaways:

- Email and In-App Banner channels consistently delivered the highest ROAS and lowest CPA, making them the most efficient investments.
- Cashback 50% and Flash Sale were high-budget campaigns with weak returns, indicating areas for budget optimization.
- Bandung emerged as the top-performing region, while Jakarta showed inefficiencies despite high spending.
- Year-by-year trends highlight the volatility of campaign performance, underlining the importance of agile budget allocation.
- These findings support strategic shifts in marketing strategy,  focusing more on regional and channel-level performance, scaling top campaigns, and reallocating spend from underperforming assets.

---

## Business Insights

### 1. Which channel performs best in terms of ROAS?

<img width="748" height="252" alt="image" src="https://github.com/user-attachments/assets/8dbca3b1-c153-4a4e-a318-96f1aefb1ef3" />

**Email** performed best overall with an average **ROAS of 8.06**, followed by **In-App Banner** (**7.45**). 
While **TikTok** had the **lowest** average (**6.40**), it performed exceptionally in **Jakarta** in 2024 with the highest **ROAS** of **11** and the lowest **CPA** (**~5K**).

**Yearly Highlights:**

2022: Instagram peaked at **12.67**

2023: In-App Banner hit **13.87**

2024: Email reached **10.11**, followed by Google Ads at **8.82**

Insight: While average ROAS gives a good benchmark, campaign effectiveness varies by region and year, making a granular channel strategy essential.

---

### 2. Are we overspending on low-converting campaigns?

<img width="817" height="396" alt="image" src="https://github.com/user-attachments/assets/3bf227b3-43fb-4284-adf7-15865e32850c" />

Yes. Multiple campaigns had disproportionately high budgets with only moderate or below-average ROAS.

Overspending Examples:

- **Cashback 50%**: Across years, it had the **highest spend** (~600M) but consistently **ROAS < 6**
- **Flash Sale and End Year Treat**: Each exceeded **500M+** spend but achieved only **average ROAS (~6–7)**.

**🟢 1. Best Performing Campaigns (High ROAS)**

**Valentine Promo** → Very high ROAS (~11), low spend → ⭐ most efficient

**Buy 1 Get 1**

- High spend and high ROAS (~10)
- 💸 Big campaign that paid off

**Loyalty Points Boost**

- Mid spend, strong ROAS (~8.5)
- 🎯 Reliable, scalable

**🔴 2. Low-Performing Campaigns (High spend, low ROAS)**

**Cashback 50%**
- **Highest spend**(~600M) but **low ROAS** (~5.5)
- 🚩 Might be wasting budget, reconsider targeting or promo structure

**Flash Sale and End of Year Treat**
- Decent spend (~550M) with only average ROAS (~7)
- Consider optimizing messaging or test alternatives

**🟡 3. Underperformers, but Low Risk**

**Coffee Festival, New Store Opening, Free Delivery**
- Modest spend (~350–400M), average ROAS (5–6)
- Not ideal, but safe to test/improve

Consider scaling down or redesigning these campaigns. Reallocate 10–20% of their budget to higher-performing campaigns like “Buy 1 Get 1” and “Valentine Promo”.

---

### 3. Which region and year delivered the best results?
<img width="631" height="339" alt="image" src="https://github.com/user-attachments/assets/e099baec-1ce5-41ac-84bd-d000954d46d2" />

**2023** was a breakout year for **Bandung** with **ROAS hitting ~10** and a peak conversion rate of **27%**.

**2024** saw **Surabaya**’s ROAS rise from **~6 to over 8.5**, with the highest conversion rate at **27%.**

On the other hand, **Jakarta** maintained **high ad spend** but returned lower ROAS **(~7.3)** and the lowest conversion rate **(~20%)** throughout the years.

---

### 4. How should we shift budgets for 2025?

Regional Budget Strategy (Based on CPA & ROAS):

- **Bandung**:

🔼 In-App Banner (highest ROAS), Email (lowest CPA ~5K)

🔽 Google Ads (low ROAS, high CPA)

- **Jakarta**:

🔼 TikTok (strong ROAS + lowest CPA ~5K)

🔽 Google Ads (CPA ~13K, low ROAS)

- **Medan**:

🔼 Instagram (best ROAS and CPA ~6K)

🔽 TikTok (highest CPA ~11K, low ROAS)

- **Surabaya**:

🔼 Google Ads (strong ROAS + lowest CPA)

🔽 TikTok (highest CPA ~17K, ROAS ~4.35)

- **Yogyakarta**:

🔼 Shopee Ads (best ROAS & CPA)

🔽 Instagram (CPA ~18.9K, ROAS ~3.28)

**Yearly Campaign Strategy**

**2022**:

✅ Buy 1 Get 1: Low spend, ROAS ~15 → 💡 Very scalable

❌ Cashback 50%: High spend, low efficiency

**2023**:

✅ Coffee Festival: Top ROAS (~16.36), very low cost

✅ Buy 1 Get 1: High ROAS and volume (ROAS 11.55)

❌ Ramadan Deals, End Year Treat: Low ROAS, high spend

**2024**:

✅ Valentine Promo: ROAS ~13 — top campaign of the year

⚖️ Loyalty Points Boost: Strong ROAS (~10)

❌ Buy 1 Get 1, End Year Treat: Below average ROAS despite high spend

💡 Strategic budget reallocation could boost revenue by IDR 1.5B+ in 2025 with the same total spend.

---

## 🧠 Recommendations

- **Maximize Efficiency**: Prioritize Email and In-App Banner campaigns to scale results with lower acquisition costs. Channels like Instagram or TikTok may work well in select regions.
- **Optimize Media Buying**: Reduce spending on high-CPA, low-ROAS campaigns like Cashback 50%, especially in regions like Jakarta.
- **Region-Based Targeting**: Invest more heavily in Bandung and Surabaya, which consistently convert better than Jakarta.
- Focus on proven campaigns like **Valentine Promo and Buy 1 Get 1**. Deprioritize high-cost, low-return offers.
- Use small budgets to test **mid-tier performers like Coffee Festival or Loyalty Point Boost**, they’ve shown occasional breakout potential.


---

## 📷 Dashboard Preview

[here](https://github.com/danielregar/Coffee-Marketing-Campaign/blob/main/Coffee%20Marketing%20-%20Dashboard.pdf)

---

