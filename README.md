
# 🚲 Cyclistic (Divvy) Bike Share Analysis


**Oussama Ait-Idmou**

---

## The Question

Cyclistic wants more annual members. Members generate stable, long-term revenue. Casual riders bring volume, but not predictability.

So the real question I explored was:

> How do casual riders behave differently from annual members, and how can those differences guide a smarter marketing strategy?

Everything in this analysis revolves around that.

---

## What the Data Shows

### Ride Duration

Average ride time:

* Casual riders: **18.5 minutes**
* Annual members: **11 minutes**

That’s a big gap.

The difference is even stronger between **March and October**, where casual rides average **18–23 minutes**, while members stay around **10–13 minutes**.

In winter (Dec–Feb), both groups drop:

* Casual: 12–15 minutes
* Members: 10–13 minutes

Seasonality affects everyone — but the structural gap remains.

---

### Weekends vs Weekdays (The Clearest Signal)

Weekend rides:

* Casual: **54%**
* Members: **46%**

Weekday rides:

* Members: **67%**
* Casual: **33%**

This is where the separation becomes obvious.

Members ride during the week.
Casual riders spike on weekends.

Even when total rides increase in July and August, both groups follow the same seasonal curve — but this weekday/weekend split doesn’t disappear.

That consistency tells us this isn’t random behavior. It’s usage intent.

---

### Ride Length Distribution

Under 30 minutes:

* Members: ~**4.5 million rides**
* Casual: ~**2 million rides**

Members dominate short rides.

Between 30–60 minutes:

* Casual: ~**40,000 rides**
* Members: ~**25,000 rides**

Longer rides lean casual — but total volume in this range is small compared to short trips.

Short, frequent rides drive the system. And those belong to members.

---

### Hourly Patterns

Members peak at:

* **8 AM**
* **7 PM**

Classic commuting hours.

Casual riders:

* One main peak around **7 PM**
* No strong morning spike

Members use bikes as transportation.
Casual riders use them more flexibly.

---

## What This Means for Marketing

If the goal is conversion, broad campaigns won’t work.

The data suggests:

* Target high-frequency casual riders during summer months.
* Focus on weekend users who consistently take 18–23 minute rides.
* Highlight cost savings for riders who repeatedly cross short-trip thresholds.
* Offer short-term membership trials to reduce commitment friction.


---

## Tools Used

R
tidyverse
dplyr
lubridate
ggplot2
R Markdown

---

## Full Work

Detailed workflow (cleaning, transformation, visual analysis):
[https://rpubs.com/OUss0606/1351369](https://rpubs.com/OUss0606/1351369)

Final presentation report:
[https://rpubs.com/OUss0606/1351725](https://rpubs.com/OUss0606/1351725)

---

## Final Thought


Members commute.
Casual riders ride for leisure.

And any serious conversion strategy has to start there.

