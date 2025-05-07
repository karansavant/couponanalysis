
# Coupon Acceptance Prediction

This project explores **factors influencing whether a driver will accept a coupon delivered while driving**, using data-driven analysis and predictive modeling.

## Project Overview

Imagine you're driving and receive a coupon on your phone for a nearby restaurant or bar. Do you take a detour to use it? This analysis explores such behavior using a classification approach on real-world-like data.

Key questions:
- Does age, marital status, or presence of children affect coupon acceptance?
- Are drivers more likely to accept a bar coupon if they go to bars frequently?
- Does time of day or weather matter?

---

## Dataset

The dataset contains features such as:
- Demographics (age, gender, income, education)
- Driving context (weather, time, companion)
- Lifestyle habits (frequency of visiting bars/restaurants)
- Coupon details (type, expiration)

---

## Analysis Highlights

- Drivers who go to bars at least once are significantly more likely to accept bar coupons.
- Age < 30, no children, and not widowed further increase the acceptance rate.
- Income below $50K and frequenting cheap restaurants reduces acceptance likelihood.
- A combination of favorable traits can raise acceptance probability to over 70%.

---

## Technologies Used

- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook


---

## File Structure

```
├── prompt.ipynb          # Main notebook with analysis and visualizations
├── README.md             # Project overview and summary
└── data/                 # Directory to place dataset if needed
└── images/               # Directory to place images of plots
```

---

## 🧠 Conclusion

This project showcases how behavior data and machine learning can help businesses tailor real-time marketing strategies. Understanding drivers' habits and context can greatly improve targeted coupon delivery success.
