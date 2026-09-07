# Case Study #15 — Free Delivery Pass: When Growth Goes Up but Profitability Goes Down

## 📌 Overview

This case study focuses on **Product Analytics, Unit Economics, Pricing, Experimentation, Customer Experience, and Product Strategy**.

The scenario explores an important Product Management challenge:

> **What happens when a feature improves customer engagement and retention, but significantly reduces profitability?**

The goal is to evaluate whether a **Free Delivery Pass** feature is truly creating sustainable business value and determine whether it should be scaled, optimized, or stopped.

---

# 🧩 Scenario

I am the **Product Owner** of a food delivery application.

The company launched a new subscription feature called:

### **Free Delivery Pass**

Customers can pay **$5/month** and receive free delivery on eligible orders.

The business expected the feature to:

- Increase order frequency
- Improve customer retention
- Generate subscription revenue
- Reduce customer sensitivity to delivery fees
- Increase customer lifetime value

After **3 months**, the Product team reviewed the results.

---

# 📊 Performance After Launch

| Metric | Before | After | Observation |
|---|---:|---:|---|
| Orders per subscribed user/month | 2.4 | 4.1 | 📈 Significant increase |
| 30-day retention | 32% | 41% | 📈 Strong improvement |
| Subscription adoption | — | 18% | Positive adoption |
| AOV | $24 | $22 | 📉 Decrease |
| Revenue per subscribed user | $48 | $50 | 📈 Slight increase |
| Delivery cost/order | $3.20 | $3.80 | 📈 Increase |
| Cancellation rate | 6% | 9% | ⚠️ Increase |
| Support contacts | — | +25% | ⚠️ Increase |
| Gross margin/subscribed user | $14 | $7 | 🚨 Significant decrease |

---

# 🎯 Initial Product Reaction

At first glance, the feature looks successful.

We have:

- Higher order frequency
- Higher retention
- 18% subscription adoption
- Higher revenue per subscribed user

However, looking deeper reveals a major business concern:

### Gross margin per subscribed user dropped from $14 to $7.

This means that although customers are ordering more frequently, the company is generating significantly less margin from each subscribed user.

Therefore, I would **not immediately classify the feature as fully successful**.

My initial conclusion would be:

> **The feature has strong customer engagement and retention signals, but it has not yet demonstrated sustainable business value.**

---

# 🔎 Core Product Problem

The main problem is not simply:

> "Customers are ordering more."

The real question is:

> **Are the additional orders generating enough incremental value to justify the additional delivery costs?**

The Free Delivery Pass may be increasing order frequency while creating unfavorable unit economics.

This creates a trade-off between:

**Customer Growth ↔ Business Profitability**

---

# 🔬 Key Hypotheses

Before changing the product, I would investigate several hypotheses.

## Hypothesis 1 — Heavy users are driving delivery costs

Some subscribers may be using the Free Delivery Pass much more frequently than others.

For example:

- Light users → 1–2 orders/month
- Medium users → 3–5 orders/month
- Heavy users → 8+ orders/month

The heavy-user segment could be responsible for a disproportionate amount of delivery costs.

---

## Hypothesis 2 — Free delivery is reducing AOV

AOV decreased from:

**$24 → $22**

Customers may be ordering smaller baskets because delivery fees are no longer part of the purchase decision.

I would investigate whether subscribers:

- Add fewer items
- Place smaller orders
- Order more frequently
- Have different restaurant preferences

---

## Hypothesis 3 — Delivery cost is increasing because of order frequency

Orders per subscriber increased significantly:

**2.4 → 4.1**

At the same time:

**Delivery cost/order increased from $3.20 → $3.80**

This could create a significant margin problem if the additional orders are not sufficiently profitable.

---

## Hypothesis 4 — Customers don't understand eligibility

Support contacts increased by **25%**.

Support reports that customers don't understand which restaurants qualify for free delivery.

Possible causes:

- Eligibility is not clearly displayed
- Terms and conditions are difficult to understand
- Customers expect free delivery everywhere
- Restaurant eligibility is not visible before checkout
- Customers discover restrictions too late

This is not only a Support problem.

It is also a **Product and UX problem**.

---

## Hypothesis 5 — Certain customer segments are less profitable

The feature may work well for some segments but poorly for others.

For example:

- New vs. existing customers
- Heavy vs. light users
- Different countries
- Different cities/areas
- Different restaurant categories
- Different device types
- Different subscription plans

---

# 📊 Data I Would Analyze

I would request deeper segmentation before making a scaling decision.

### 👤 Customer Segmentation

- New vs. existing customers
- Heavy vs. light users
- Customer frequency
- Customer lifetime
- Subscription duration
- Customer location
- Country
- Area
- Device type

### 🍔 Order Behavior

- Orders per subscriber
- Orders per week/month
- AOV
- Items per order
- Restaurant category
- Restaurant location
- Order value distribution
- Repeat purchase rate

### 💰 Unit Economics

- Delivery cost/order
- Delivery cost/subscriber
- Subscription revenue
- Revenue/subscriber
- Gross margin/subscriber
- Contribution margin
- Margin per order
- Incremental profit from additional orders

### ❌ Cancellation

I would analyze:

- Cancellation rate
- Cancellation reasons
- Cancellation by customer segment
- Cancellation by restaurant
- Cancellation by area
- Cancellation before vs. after subscription

### 💬 Customer Experience

I would analyze:

- Support contacts
- Support ticket categories
- Customer complaints
- Refund requests
- Customer satisfaction
- Eligibility-related complaints

---

# 💡 How I Would Determine Business Value

I would not evaluate success based only on:

- Orders
- Retention
- Adoption
- Revenue

I would compare the **incremental value generated by the subscription** against its incremental costs.

The key question would be:

> **Does the additional revenue and retention generated by the Free Delivery Pass compensate for the additional delivery and operational costs?**

For example:

If a customer generates more revenue but costs the company significantly more to serve, revenue growth alone may not represent a healthy product outcome.

This is why **unit economics** are critical.

---

# 🧮 Unit Economics

The most important signal in this case is:

### Gross Margin per Subscriber

**Before: $14**

**After: $7**

That is a **50% decrease**.

Therefore, I would investigate:

- Subscription revenue
- Delivery costs
- Order frequency
- AOV
- Discounts
- Refunds
- Operational costs
- Contribution margin

The goal is to determine whether the feature is:

### Growing profitably

or

### Growing at the expense of profitability.

---

# 📈 Metrics Framework

## ⭐ Primary Metric

### Contribution Margin per Subscribed User

This would help determine whether the subscription is generating sustainable economic value.

---

## 📊 Secondary Metrics

- Orders per subscribed user
- 30-day retention
- Subscription adoption
- Revenue per subscribed user
- AOV
- Repeat purchase rate
- Customer lifetime value

---

## 🛡️ Guardrail Metrics

I would monitor:

- Cancellation rate
- Support contacts
- Customer complaints
- Refunds
- Customer satisfaction
- Negative feedback

The goal is to improve profitability without damaging the customer experience.

---

## 💰 Unit Economics Metrics

- Delivery cost per order
- Delivery cost per subscriber
- Subscription revenue
- Revenue per subscriber
- Gross margin
- Contribution margin
- Incremental profit per subscriber

---

# 🧪 Experimentation Strategy

I would not immediately scale the feature to 100%.

Instead, I would test different approaches to improve the economics.

---

## Experiment 1 — Minimum Order Value

Introduce a minimum order value to qualify for free delivery.

For example:

> Free delivery for orders above $20.

This could help protect AOV and margin.

---

## Experiment 2 — Limit Free Deliveries

Instead of unlimited free delivery:

> Customers receive a fixed number of free deliveries per month.

For example:

- 5 free deliveries/month
- Additional deliveries receive a discount rather than being completely free

This could reduce excessive usage by heavy users.

---

## Experiment 3 — Pricing Experiment

Test different subscription prices.

For example:

- $4/month
- $5/month
- $6/month

The objective would be to find a price that balances:

**Subscription adoption + retention + profitability**

---

## Experiment 4 — Customer Segmentation

Test the Free Delivery Pass with specific customer groups.

For example:

- High-frequency customers
- Low-frequency customers
- New customers
- Customers with high predicted lifetime value

The feature may create significantly more value for some segments than others.

---

## Experiment 5 — Eligibility Rules

Test different eligibility models:

- Selected restaurants
- Selected geographic areas
- Minimum order value
- Specific delivery zones
- Selected restaurant categories

The objective is to control delivery costs without destroying the value proposition.

---

# 🧪 Experiment Design

Before implementing major changes globally, I would run a controlled experiment.

For example:

### Control Group

Existing Free Delivery Pass experience.

### Variant Group

Optimized experience with:

- Minimum order value
- Clearer eligibility
- Improved subscription messaging

Then compare:

- Contribution margin
- Orders/subscriber
- Retention
- AOV
- Cancellation
- Support contacts

If the variant improves unit economics without significantly harming customer value, we can gradually increase exposure.

---

# 💬 Customer Experience: Eligibility Problem

Support reports that customers don't understand which restaurants are eligible.

I would treat this as a **Product problem**, not only a Support problem.

Potential improvements:

### Before ordering

Clearly show:

> 🛵 Free delivery with your Pass

on eligible restaurants.

### On restaurant pages

Show:

> ✅ Free delivery included

or:

> ❌ Delivery fee applies to this restaurant

### During checkout

Clearly explain:

> "This restaurant is not eligible for Free Delivery Pass."

### Subscription page

Explain:

- Eligible restaurants
- Eligible locations
- Minimum order requirements
- Exclusions
- Delivery conditions

The goal is to reduce confusion before customers reach Support.

---

# 🤝 Stakeholder Management

## Growth

Growth sees increased:

- Orders
- Retention
- Adoption

I would acknowledge that these are strong signals.

However, I would explain:

> "The feature is generating strong growth, but we also need to make sure that growth is economically sustainable."

---

## Finance

Finance is concerned about declining margins.

I would work with Finance to understand:

- Contribution margin
- Delivery cost
- Subscriber profitability
- Incremental revenue
- Incremental profit

---

## Commercial

Commercial may focus on subscription revenue.

I would explain that subscription revenue alone does not determine profitability.

We need to evaluate the **complete unit economics**.

---

## Support

Support is reporting eligibility confusion.

I would work with Support to categorize tickets and identify the most common customer misunderstandings.

Then convert those findings into Product improvements.

---

## Engineering

Engineering says the feature is technically working as expected.

That may be true.

However:

> **A feature can be technically correct while still producing an undesirable product or business outcome.**

The Product team's responsibility is to evaluate the overall customer and business outcome.

---

# 🚦 Final Decision

### My choice:

## ✅ C. Optimize the economics and customer experience before scaling

I would **not roll out the feature to 100% immediately**.

However, I would also **not remove or completely pause the feature**.

There are strong positive signals:

- Orders increased
- Retention increased
- Adoption reached 18%
- Revenue per subscriber increased

But there are also serious concerns:

- Gross margin dropped from $14 → $7
- Delivery costs increased
- AOV decreased
- Cancellation increased
- Support contacts increased

Therefore, the best strategy is:

### **Optimize → Experiment → Validate → Scale**

---

# 🗺️ Proposed Product Plan

### Phase 1 — Diagnose

Analyze:

- Customer segments
- Order behavior
- Delivery costs
- Unit economics
- Cancellation reasons
- Support tickets
- Eligibility issues

↓

### Phase 2 — Identify Root Causes

Determine:

- Which customers are profitable?
- Which customers create excessive delivery costs?
- Why is AOV declining?
- Why are cancellations increasing?
- Why are customers confused about eligibility?

↓

### Phase 3 — Experiment

Test:

- Minimum order value
- Subscription pricing
- Free delivery limits
- Eligibility rules
- Customer segmentation
- Improved UX

↓

### Phase 4 — Measure

Track:

- Contribution margin
- Orders/subscriber
- Retention
- AOV
- Revenue/subscriber
- Cancellation
- Support contacts

↓

### Phase 5 — Scale

If the optimized version improves economics while maintaining customer value:

**Gradually increase exposure.**

If economics remain negative:

**Reconsider the business model or discontinue the feature.**

---

# 🧠 Key Product Learnings

### 1. Growth does not automatically mean success

Increasing orders and retention is positive, but sustainable products also need healthy economics.

---

### 2. Revenue is not the same as profitability

Revenue per subscriber increased from:

**$48 → $50**

while gross margin decreased:

**$14 → $7**

This shows why Product Managers need to understand the difference between:

**Revenue → Cost → Margin → Profitability**

---

### 3. Unit economics matter

For subscription and marketplace products, I need to understand how customer behavior affects:

- Cost to serve
- Revenue
- Margin
- Lifetime value

---

### 4. Support tickets can reveal Product problems

If customers repeatedly contact Support because they don't understand a feature, the root cause may be poor UX or unclear communication.

---

### 5. Don't scale a feature simply because the top-line metrics look good

Before scaling, I would ask:

> **Is the growth sustainable?**

> **Is the customer experience healthy?**

> **Is the business making enough incremental value?**

---

### 6. Product decisions require trade-offs

The objective isn't always to maximize one metric.

The goal is to find the right balance between:

**Customer Value + Business Value + Operational Sustainability**

---

# 🎯 Final Takeaway

The Free Delivery Pass demonstrates an important Product Management principle:

> **A feature can increase orders and retention while still creating a worse business outcome.**

As a Product Owner, I would avoid making the decision based on a single positive metric.

Instead, I would combine:

**Customer behavior + Product Analytics + Customer Experience + Unit Economics + Experimentation**

to determine whether the feature is creating sustainable value.

My final approach:

> **Don't kill the feature. Don't scale it blindly. Optimize the economics, improve the customer experience, validate through experimentation, and scale only when the results demonstrate sustainable value.**

---

## 🛠️ Skills Practiced

- Product Analytics
- Unit Economics
- Product Strategy
- Customer Segmentation
- Hypothesis Building
- Customer Experience
- Experimentation
- A/B Testing
- Pricing Strategy
- Subscription Products
- Stakeholder Management
- Prioritization
- Business Impact Analysis
- Sustainable Growth
