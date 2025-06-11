# Matiks-_Game_User_Analytics_and_Revenue_Performance_Dashboard
This project analyzes user behavior and revenue performance for an online gaming platform called **Matiks**. It covers data from May 2023 to May 2025, comprising 10,000 users. The goal is to identify trends in user engagement, revenue generation, and platform performance, and to uncover areas for improvement.

---

## 🧠 Problem Statement

The gaming platform needed to assess:

- How engaged users are across different platforms and subscription tiers.
- What’s driving revenue and which channels are most effective.
- Where users drop off or underperform (e.g., session activity, conversion to paid plans).
- How to improve retention and monetization efforts.

---

## 🛠 Tools Used

- **Python**: Data cleaning and preprocessing (Pandas, NumPy).
- **Tableau Public**: Interactive dashboards for performance visualization.

---
## 📌 Key Insights

### ✅ What’s Working
- **Balanced Engagement**: Equal usage across genders and device types (PC, Console, Mobile).
- **Top Performer**: *Mysticwar* is the highest grossing and most played game.
- **Revenue Leaders**: Premium subscriptions (especially Platinum) generated the most revenue (~$129.4K).
- **Referral Performance**: Friend referrals generated ~$124K revenue, making it a strong channel.

### ❌ What’s Not Working
- **Low Session Volume**: 97% of users have fewer than 30 sessions, with just 1.35% playing over 30 times.
- **Free Tier Retention**: 25% of users are still on the free plan despite high engagement.
- **Low Avg. Purchase Value**: At just $10.1, in-game purchases are not being made frequently or in bulk.

### 🚀 Opportunities
- **Upsell Free Users**: Offer first-time discounts or gamified incentives to convert them.
- **Leverage Social Play**: Add features like “Friends Online” notifications or co-op missions.
- **Re-engagement Campaigns**: Target users with declining play sessions via email/push notifications.
- **Referral Incentives**: Reward users for successful friend invites with in-game perks.
---

## 📈 KPIs Summary

| Metric                      | Value         |
|----------------------------|---------------|
| Total Users                | 10,000        |
| Avg Revenue per User       | $50.2         |
| Avg Revenue per Session    | $2.5          |
| Avg Purchase Value         | $10.1         |
| Total Revenue              | $501,774      |
| Free Tier Users            | 25% (2,536)   |
| Most Played Game           | Mysticwar     |
| Most Used Device           | Console (~34%)|

---
## 📊 Dashboards Overview

### 1. **Revenue Dashboard**
**Location**: `Revenue Dashboard` tab in Tableau  
**Purpose**: Displays revenue trends, ARPU, and breakdowns by device type, game title, and subscription level.

#### Components:
- **KPI Tiles**: Total Revenue, Avg Purchase Value, Avg Rev. per User & Session
- **Bar Charts**: Revenue by Year & Month
- **Pie Charts**:
  - Revenue by Game
  - Revenue by Device Type (PC, Console, Mobile)
  - Revenue by Subscription (Free, Silver, Gold, Platinum)

---

### 2. **User Analytics Dashboard**
**Location**: `Analysis Dashboard` tab in Tableau  
**Purpose**: Highlights user activity, session behavior, acquisition sources, and segment breakdowns.

#### Components:
- **KPI Tiles**: Total Users, Active Users (Last 30 Days), Sessions/User
- **Session Distribution**: Play session frequency ranges
- **Trend Chart**: Monthly new user acquisitions
- **Pie Charts**:
  - Users by Game Played
  - Users by Subscription Type
  - Users by Referral Source (Organic, Ads, Friend, Social Media)

---

## 📌 How to Use the Dashboard (on Tableau Public)

- **Filters Available**: Use dropdowns to filter by year, gender, and activity window.
- **Navigation Buttons**: Click "Revenue" or "Analysis" on the top-right to switch dashboards.
- **Hover to Explore**: Hover over charts to see detailed tooltips and metrics.
- **Compare Segments**: Use pie charts to compare performance and user base across games, devices, subscriptions, and referral sources.

---

## 👨‍💻 Author

**Jayesh Wagh**  
Aspiring Data Analyst | Tools: Python, SQL, Tableau, Excel  
📧 jayeshwagh0502@gmail.com  

---

## 🌐 Live Dashboard

👉 https://public.tableau.com/app/profile/jayesh.wagh3436/viz/UserAnalyticsRevenueDashboard/AnalysisDashboard 

