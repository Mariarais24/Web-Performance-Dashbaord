# 🛒 E-Commerce Analytics: Page Performance & Conversion Diagnosis

**Investigating why an e-commerce store with steady traffic is failing to convert and where in the buying journey users are being lost.**

---

## 🔗 [View Live Interactive Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMGFjY2MzZTMtOGViNi00NjBjLTgzZWYtMjI1NTRlYzUxYzFjIiwidCI6IjNiNWIwMDgyLTczNmQtNGIwNi1hYjU1LWUyYzQ0ZGI3YWIzMSIsImMiOjl9)

---

## 📂 Data Source

Simulated e-commerce dataset **3 months of data (July – September 2025)**, structured across three tables:
- **Sessions**:  session-level behavior (device, source, duration, bounce)
- **Page Performance**:  page-level load times, exits, and add-to-cart events
- **Sales Activity**:  completed orders and transaction values

---

## 💡 Dashboard Breakdown

### Business Problem
An e-commerce store had 900 sessions but only a 2.22% conversion rate well below the industry average of 3–4%. Page load times exceeded Google's 3-second threshold across every page. The business had traffic. It didn't have visibility into where and why it was losing customers.

### Goal
Diagnose whether page performance was the root cause of low conversions, identify the highest-friction points in the purchase funnel, and give the business a clear, prioritized action plan.

---

### 🖥️ Walkthrough of Key Pages

---

**Page 1  Executive Overview**

![Executive Overview](https://github.com/Mariarais24/Web-Performance-Dashbaord/blob/main/executive-overview.png)

The entry point for any stakeholder asking "should we be worried?" Five KPIs surface the headline story immediately — 900 sessions, 2.22% conversion rate, 37.50% checkout abandonment, 4.5 sec average page load time. A color-coded bar chart (red = critical, yellow = monitor, green = healthy) shows all top pages breaching the 3-second load time threshold. The purchase funnel makes the drop-off undeniable: 900 sessions enter, only 20 convert. The Key Findings panel on the right delivers the verdict plainly — *traffic isn't the problem, performance is silently killing conversions.*

---

**Page 2  Session-Level Analysis**

![Session Analysis](https://github.com/Mariarais24/Web-Performance-Dashbaord/blob/main/Sessions.png)

Examines how performance is affecting user behavior across devices and traffic sources. The slow session rate sits at 12.33% — above the 8% industry benchmark. Mobile drives the highest slow session rate at 15.6%. Organic traffic drives the longest sessions (4.1 min) while Direct traffic averages just 0.7 min, the shortest by far and the highest bounce risk at 50%. The verdict: performance issues aren't just technical, they're directly shaping how users experience the site.

---

**Page 3  Page-Level Performance**

![Page Level Performance](https://github.com/Mariarais24/Web-Performance-Dashbaord/blob/main/page-performance.png)

Identifies which pages are creating friction and should be fixed first. Product page has the highest exit rate at 83%, users are leaving at the exact moment they should be adding to cart. Home page has the slowest load time at 4.7 seconds, meaning users form a bad first impression before seeing any products. A combo chart overlays load time and time spent per page, showing that faster pages retain users longer. The verdict: fix the product page first.

---

**Page 4  Checkout & Conversion Analysis**

![Checkout and Conversion](https://github.com/Mariarais24/Web-Performance-Dashbaord/blob/main/conversion.png)

Answers the critical question: is performance actually affecting revenue, not just engagement? Checkout abandonment is 37.50% and product exit rate is 82.73%. A scatter plot of page load time vs conversion rate by page makes the relationship visual, pages above 4 seconds convert at near 0%, consistently. UAE drives the highest conversion at 5.6%. The Key Findings panel confirms the verdict: *performance is contributing to direct revenue loss, not just poor UX. Optimization = business ROI.*

---

### Business Impact & Insights

- 🔴 **2.22% conversion rate** below the 3–4% e-commerce benchmark, with page speed as the primary cause
- ⏱️ **Every page exceeds Google's 3-second load threshold**  Home page at 4.7 sec is the worst first impression possible
- 📱 **Mobile slow session rate at 15.6%**  nearly double the industry average of 8%
- 🛒 **Product page exit rate at 83%**  users are abandoning at the highest-value decision point
- 💸 **Pages above 4 sec load time convert at near 0%**  performance is a revenue issue, not a UX complaint

---

## ✅ Recommendations

| # | Action |
|---|---|
| 1 | Fix the **Product page first** - 83% exit rate at the highest-value decision point |
| 2 | Reduce **Home page load time** below 3 seconds - 4.7 sec means users leave before seeing products |
| 3 | Prioritize **mobile performance** - slow session rate is nearly double the industry benchmark |
| 4 | Target **Direct traffic bounce risk** - 50% bounce rate means paid or direct campaigns are landing on broken experiences |

---

## 🛠 Tech Stack

- 📊 Power BI Desktop
- 🧠 DAX (custom KPI measures)
- 📂 Power Query
- 📝 Data Modeling (3-table relational schema)
---

> ⚠️ *Simulated dataset generated for portfolio purposes. Designed to reflect realistic e-commerce behavior.*
