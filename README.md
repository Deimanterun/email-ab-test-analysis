# email-ab-test-analysis

# 📧 A/B Test Analysis – Email Campaign

## 📌 Problem Statement

The marketing team tested a new landing page to see if it would improve email campaign conversion rates. This project analyzes whether the new design led to a measurable increase in conversions.

---

## 📊 Dataset Description

- **Source**: [Kaggle - A/B Testing](https://www.kaggle.com/datasets/zhangluyuan/ab-testing)
- **Original Dataset Size**: ~294,000 user records
- **Columns**:
  - `user_id`: Unique user identifier
  - `group`: A/B group assignment (`control` or `treatment`)
  - `landing_page`: Page variant shown (`old_page` or `new_page`)
  - `converted`: Binary indicator (1 = converted, 0 = not converted)
  - `timestamp`: Timestamp of the visit (not used in this version)

After cleaning, only valid group/page pairings were kept:
- `control` → `old_page`
- `treatment` → `new_page`

Duplicate user_ids and mismatched rows were removed to ensure analysis accuracy.
---

## 🛠 Tools Used

- **Microsoft Excel**:  
  - Data cleaning & filtering  
  - Pivot tables  
  - Conversion rate analysis  
  - Dashboard design

---

## 📈 Metrics & Insights

| Group     | Total Users | Conversions | Conversion Rate |
|-----------|-------------|-------------|------------------|
| Control   | 147,274     | 17,746      | 12.04%           |
| Treatment | 147,202     | 17,492      | 11.88%           |
| **Difference** |       –       |       –       | **−0.16%**        |

---

## 💡 Business Recommendation

> The new design underperformed by 0.16 percentage points compared to the original page. Given the small negative change and no indication of a significant uplift, we recommend continuing with the current (Control) landing page.

---

## 🖼 Dashboard Preview

![Dashboard](dashboard.png)

---
