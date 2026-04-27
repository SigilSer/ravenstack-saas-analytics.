# ravenstack-saas-analytics.
Diagnosing Churn Accelerants in a High-Growth SaaS Environment.
# RavenStack SaaS Analytics Dashboard

> Pilot cohort analysis · 500 accounts · Jan 2023 – Dec 2024  
> Dataset by [River @ Rivalytics](https://rivalytics.com)

---

## Executive Summary

- **Churn is accelerating and now critical.** Monthly churn events grew from near-zero in early 2023 to **117 events in December 2024 alone** — a trajectory that threatens the $121.9M ARR base if left unaddressed. The 22% overall churn rate across 500 accounts signals a systemic retention problem, not isolated incidents.

- **DevTools accounts churn at nearly 2× the rate of the healthiest verticals.** At **31.0%**, DevTools churn dwarfs EdTech (16.5%) and Cybersecurity (16.0%). Meanwhile, the #1 churn driver across all industries is **missing features** (114 events), closely followed by poor support (104) and budget constraints (104) — pointing to a product-market fit gap, not purely a pricing issue.

- **Event-sourced customers are your highest-risk cohort — and your most preventable loss.** Accounts acquired through events churn at **30.2%**, more than double the rate of partner-sourced accounts (14.6%). Additionally, 20.5% of all churn events come from customers who had *just upgraded* — a strong signal that upgrade promises aren't being delivered on.

---

## Interactive Visuals

![RavenStack SaaS Dashboard Preview](dashboard_screenshot.png)

> **➡️ [Open the live dashboard](ravenstack_dashboard.html)** to explore all charts interactively (monthly churn trends, plan MRR, ticket priority breakdown, and more).

---

## Dataset at a Glance

| Metric | Value |
|---|---|
| Total accounts | 500 |
| Total subscriptions | 5,000 |
| Active MRR | $10.2M |
| Active ARR | $121.9M |
| Overall churn rate | 22.0% (110 accounts) |
| Total churn events | 600 |
| Support tickets | 2,000 |
| Usage events | 25,000 |
| Period | Jan 2023 – Dec 2024 |

---

## The "So What?" — Actionable Recommendations

### 🔴 Recommendation 1: Launch a DevTools "30-Day Rescue" Protocol
DevTools accounts churn at **31%** — nearly 2× the rate of EdTech and Cybersecurity. Implement a high-touch onboarding sequence specifically for DevTools customers: a dedicated CSM check-in at Day 7, a feature adoption audit at Day 21, and a direct engineering feedback call at Day 30. A 5-point churn reduction in this vertical alone would save an estimated **~$870K in ARR** (based on average Enterprise/Pro MRR blended across 113 accounts).

### 🟠 Recommendation 2: Build a "Feature Promise Tracker" Into Your Sales-to-CS Handoff
Features are the #1 churn driver (114 events, 19% of all churn). The fact that **20.5% of churns happen post-upgrade** strongly suggests customers upgrade expecting new capabilities that don't materialize. Require sales to log specific feature commitments at deal close, and trigger an automated CS alert if those features aren't used within 60 days of upgrade.

### 🟡 Recommendation 3: Audit and Restructure Your Event Marketing Pipeline
Event-sourced accounts churn at **30.2%** vs. 14.6% for partner-sourced. This likely reflects a mismatch in ICP qualification at conferences and trade shows. Consider adding a qualification gate (e.g., a product demo requirement before trial activation) for event leads, and redirect budget toward partner channels which produce more durable customers.

### 🟢 Recommendation 4: Treat Post-Upgrade Churn as a Product Bug, Not a CS Problem
With **123 churns occurring after an upgrade**, the data suggests your upgrade UX creates false expectations. Conduct exit interviews specifically with this cohort and instrument your product to measure feature adoption *within the first 14 days post-upgrade*. If adoption is low, trigger an in-app walkthrough — not an email.

### 🔵 Recommendation 5: Investigate the "Unknown" Churn Bucket
**95 churn events (15.8%)** have no recorded reason. At $10.2M MRR, every percentage point of churn is material. Mandate exit survey completion before account cancellation is processed, and offer a small incentive (extended trial, discount on return) to improve response rates. You can't fix what you can't measure.

---

## Files in This Repo

| File | Description |
|---|---|
| `ravenstack_dashboard.html` | Self-contained interactive dashboard (Chart.js) |
| `dashboard_screenshot.png` | Static preview image |
| `README.md` | This file |

---

*Dataset: RavenStack synthetic SaaS · Credit: River @ Rivalytics*
