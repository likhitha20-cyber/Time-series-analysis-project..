# Time Series Analysis — Statistics Project

> **Under Graduation Project | Department of Statistics**
> Sri Vivekananda Degree College, Anantapur, Andhra Pradesh
> Academic Year: 2021–2022

---

## 👩‍🎓 Submitted By

| Name | Registration No. |
|------|-----------------|
| Chitluri Likhitha | 202121005 |
**Internal Guide:** K. Bhagyalakshmi, Head of Department, Statistics
-

## 📋 Table of Contents

- [Unit I — Sleep & Obesity Study](#unit-i--sleep--obesity-study)
- [Unit II — Motorbike Sales Time Series Analysis](#unit-ii--motorbike-sales-time-series-analysis)

---

## Unit I — Sleep & Obesity Study

### Research Question
> *Can sleep, or the lack of it, cause obesity?*

### Background
This study investigates the relationship between the number of hours of sleep and body weight of students at Sri Vivekananda Degree College. The research aims to evaluate whether sleeping less leads to weight gain.

### Objectives
- To test whether sleeping less causes weight gain
- To determine if students who sleep less are heavier than those who sleep more
- To analyze the real effect of sleep on body weight

### Scope
- **Sample Size:** 50 students (2nd and 3rd year)
- **Sections:** M.E.Cs, M.S.Cs, B.Com
- **Age Range:** 17–21 years

### Statistical Analysis

| Variable | Mean | Std. Deviation | n |
|----------|------|---------------|---|
| Hours of Sleep | 7.22 hrs | 1.5848 | 50 |
| Weight | 48.88 kg | 9.8725 | 50 |

**Pearson Correlation Coefficient:** `r = -0.0736`

### Hypothesis Testing

- **H₀:** There is no significant relationship between hours of sleep and weight
- **Level of Significance:** α = 0.05 (2-tailed)
- **Degrees of Freedom:** n - 2 = 48
- **t-critical value:** 2.011
- **t-calculated:** -0.5099

### Conclusion
Since `t_cal (-0.5099) ≤ t_value (2.011)`, we **fail to reject H₀**.
There is **no statistically significant relationship** between the number of hours of sleep and the weight of the surveyed students.

### Recommendations
- Students should aim for **8–10 hours of sleep** per day
- If weight loss is desired, **exercise** is recommended over sleep deprivation
- Manage time wisely and maintain healthy sleep habits

---

## Unit II — Motorbike Sales Time Series Analysis

### Study Overview
Time series analysis on sales, services, and spare parts at **Narasimha Hero Showroom** (established 2012), using data from 2012–2017.

### Objectives
1. Determine whether there is an increase or decrease in sales, services, and spare parts
2. Forecast future sales using the **Linear Trend (Least Squares) Method**

### Data

| Year | Sales (Bikes) | Services | Spare Parts Sold |
|------|--------------|----------|-----------------|
| 2012 | 2014 | 1800 | 6000 |
| 2013 | 2755 | 2800 | 8015 |
| 2014 | 3024 | 3950 | 9990 |
| 2015 | 6010 | 6040 | 10560 |
| 2016 | 5990 | 10230 | 11720 |
| 2017 | 7012 | 11000 | 12900 |

### Statistical Method: Method of Least Squares

The trend line fitted to sales data:

```
y = a + bx
```

**Normal Equations:**
```
Σy  = na + bΣx
Σxy = aΣx + bΣx²
```

**Solved Values:**
- `a = -377.2`
- `b = 1076.6`

**Fitted Trend Line:**
```
y = -377.2 + 1076.6x   (where x = Year - 2010)
```

### Forecast

**Predicted Sales for 2022** (x = 12):
```
y = -377.2 + 1076.6 × 12 = 12,919 bikes
```

### Conclusions
1. There is a **consistent upward trend** in sales, services, and spare parts at Narasimha Hero Showroom
2. Forecasted sales for **2022 ≈ 12,919 bikes**

---

## 🛠️ Tools & Techniques Used

- Pearson Correlation Coefficient
- t-Test for significance of correlation
- Method of Least Squares (Linear Trend)
- Scatter Diagrams & Line Charts

---

## 📁 Project Structure

```
├── README.md
└── final_updated.pdf       # Full project report
```

---

*Submitted in partial fulfilment of the requirements for the award of Under Graduation in Statistics — July 2022*
