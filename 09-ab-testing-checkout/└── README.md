# 🧪 Case Study #9 — The Experiment That Improved Conversion

> **30 Product Case Studies — Case #9**
>
> A hypothetical Product Case Study focused on A/B testing, Product Analytics, experimentation, and evidence-based decision making.

---

## 📌 Overview

A food delivery app is testing a new checkout experience designed to:

- Increase completed orders
- Increase Average Order Value (AOV)
- Reduce checkout abandonment

The Marketing team believes the experiment is a clear success because conversion, AOV, and revenue per user all increased.

However, Customer Support contacts also increased significantly.

The Product question is:

> **Should we immediately roll out the new experience to 100% of users?**

My answer: **Not yet.**

---

# 🎯 Business Context

The team introduced a new checkout message:

> **"Free delivery if you add one more item to your order."**

The hypothesis is that encouraging customers to increase their basket size will:

1. Increase Average Order Value
2. Increase completed orders
3. Reduce checkout abandonment
4. Improve revenue per user

---

# 🧪 Experiment Setup

The experiment compares:

### Control

The existing checkout experience.

### Variant

The new checkout experience with the free-delivery incentive.

---

# 📊 A/B Test Results

After two weeks:

| Metric | Control | Variant | Observation |
|---|---:|---:|---|
| Checkout Users | 50,000 | 50,000 | Equal sample |
| Completed Orders | 10,000 | 11,000 | Positive |
| Conversion Rate | 20% | 22% | Positive |
| Average Order Value | $18 | $20 | Positive |
| Checkout Abandonment | 80% | 78% | Positive |
| Revenue per User | $3.60 | $4.40 | Positive |
| Customer Support Contacts | 1,200 | 1,900 | ⚠️ Negative |

At first glance, the Variant looks like a clear winner.

But the increase in Customer Support contacts requires further investigation.

---

# 🚦 Initial Decision

I would **not immediately roll out the Variant to 100% of users**.

Instead, I would:

1. Continue validating the experiment.
2. Investigate the increase in Support contacts.
3. Analyze the checkout funnel.
4. Segment the results.
5. Validate statistical significance.
6. Understand the customer complaints.
7. Consider a gradual rollout if the results remain positive and guardrails are acceptable.

---

# 🔎 1. Look Beyond the Headline Metrics

The Marketing team's argument is:

> "Conversion increased, AOV increased, and revenue increased."

These are strong positive signals.

However, Product decisions should not be based on a single set of positive metrics.

The Variant also generated:

> **700 additional Support contacts**

That raises an important question:

> **Why are more customers contacting Support after seeing the new experience?**

The increase could indicate confusion, unexpected behavior, or another customer experience issue.

---

# 📈 2. Understand the Conversion Increase

Conversion increased from:

**20% → 22%**

This represents:

### Absolute increase

**+2 percentage points**

### Relative increase

**+10%**

Because:

**(22% - 20%) / 20% = 10%**

Both numbers are useful, but they describe different things.

I would communicate the result precisely rather than simply saying:

> "Conversion increased by 10%."

A clearer statement is:

> **"Conversion increased from 20% to 22%, representing a 2-percentage-point or 10% relative increase."**

---

# 🔍 3. Analyze the Checkout Funnel

I would investigate the full funnel:

**Checkout Started**

↓

**Delivery Information**

↓

**Payment Selection**

↓

**Payment Attempt**

↓

**Order Confirmation**

↓

**Completed Order**

The goal is to identify where the Variant behaves differently from the Control.

For example:

### Hypothesis A

Users understand the offer but cannot find an eligible item.

### Hypothesis B

The free-delivery condition is unclear.

### Hypothesis C

The user adds an item but discovers another restriction later.

### Hypothesis D

A technical issue occurs during checkout.

### Hypothesis E

The customer changes their mind after seeing the additional cost.

The funnel helps identify **where** the problem occurs before investigating **why**.

---

# 👥 4. Segment the Results

I would not rely only on the overall experiment results.

I would segment the data by:

### Customer Type

- New customers
- Returning customers
- Frequent customers
- Occasional customers
- High-value customers
- Casual customers

### Geography

- Country
- City
- Delivery area

### Device

- iOS
- Android
- Web

### Restaurant

- Restaurant category
- Restaurant
- Delivery area
- Order size

### Order Behavior

- Low-value orders
- High-value orders
- Frequent vs. occasional ordering

This could reveal that the Variant performs well for one segment but poorly for another.

---

# 💡 5. Hypotheses for Customer Support Increase

The increase from:

**1,200 → 1,900 contacts**

could have several explanations.

### Hypothesis 1 — Offer Confusion

Customers don't understand the free-delivery condition.

### Hypothesis 2 — Eligibility Issues

Customers believe they qualify but discover that their order doesn't meet the requirements.

### Hypothesis 3 — Restaurant Constraints

Some restaurants may have different delivery or minimum-order rules.

### Hypothesis 4 — Checkout Bug

The incentive may not be applied correctly.

### Hypothesis 5 — Poor UX

The message may be confusing or poorly placed.

### Hypothesis 6 — Increased Order Complexity

Encouraging customers to add items could create unexpected friction.

These are hypotheses, not conclusions.

---

# 💬 6. Investigate Customer Feedback

I would review the Support contacts and categorize them by issue.

For example:

| Complaint Category | Number of Contacts |
|---|---:|
| Offer confusion | TBD |
| Eligibility issue | TBD |
| Payment issue | TBD |
| Restaurant issue | TBD |
| Technical issue | TBD |
| Other | TBD |

This would help identify the dominant complaint pattern.

I would also consider:

- Customer surveys
- Customer interviews
- Session recordings
- Support ticket analysis
- Funnel analysis

The objective is to connect quantitative data with qualitative customer evidence.

---

# 🧪 7. Validate the Experiment

Before making a permanent decision, I would verify the quality of the experiment.

### Statistical Significance

I would confirm whether the conversion uplift is statistically significant.

A positive-looking result does not automatically mean the change is statistically meaningful.

### Sample Size

The experiment has:

**50,000 users per group**

which provides a strong sample, but I would still validate the statistical result.

### Experiment Duration

The test ran for two weeks.

I would check whether this period is sufficient to capture normal user behavior.

Potential factors include:

- Weekday vs. weekend behavior
- Payday effects
- Promotions
- Campaigns
- Seasonality
- Short-term novelty effects

### Randomization

I would verify that users were properly randomized between Control and Variant.

---

# 📊 8. Define the Metrics

I would organize the metrics into three levels.

## 🎯 Primary Metric

### Checkout Conversion Rate

This is the main outcome because the experiment is designed to improve the percentage of checkout users who complete an order.

---

## 📈 Secondary Metrics

- Completed Orders
- Revenue per User
- Average Order Value
- Checkout Abandonment

These help understand the broader business impact.

---

## 🛡️ Guardrail Metrics

- Customer Support Contact Rate
- Customer Complaints
- Cancellation Rate
- Refund Rate
- Payment Failure Rate
- Customer Satisfaction

The purpose of guardrail metrics is to make sure the improvement doesn't create unacceptable negative side effects.

---

# 💰 9. Revenue Analysis

Revenue per user increased from:

**$3.60 → $4.40**

This is a strong positive signal.

However, I would not use this metric alone to justify rollout.

I would ask:

- Is the increase statistically significant?
- Is it consistent across customer segments?
- Is it sustainable?
- Is the revenue increase driven by healthy customer behavior?
- Are we creating additional operational or Support costs?
- Are cancellations or refunds increasing?
- Is the result affected by a short-term promotion?

The objective is to understand **incremental business value**, not just a temporary revenue increase.

---

# 🚦 10. Rollout Strategy

My preferred approach would be:

**Continue Experiment**

↓

**Investigate Support Increase**

↓

**Validate Statistical Significance**

↓

**Monitor Primary + Guardrail Metrics**

↓

**Gradual Rollout**

↓

**Monitor Post-Rollout Performance**

I would avoid immediately moving from an experiment to:

**100% rollout**

without understanding the negative signal.

---

# 🧠 11. Possible Decision Scenarios

## Scenario A — Positive Results + Acceptable Guardrails

If:

- Conversion improvement is statistically significant
- Revenue improvement is sustained
- Customer complaints are manageable
- Support impact is understood

Then:

> **Proceed with a gradual rollout.**

---

## Scenario B — Positive Conversion + Serious Customer Impact

If:

- Conversion improves
- Revenue improves
- But Support complaints are severe

Then:

> **Do not scale yet.**

First fix the customer experience issue and rerun the validation.

---

## Scenario C — Results Are Not Statistically Significant

If the observed improvement is not statistically significant:

> **Continue or stop depending on the experiment design and available evidence.**

We should not make a major product decision based on random variation.

---

# 🏆 12. Final Product Recommendation

I would **not immediately roll out the Variant to 100% of users**.

I would continue validating the experiment while investigating the significant increase in Support contacts.

If:

- The conversion uplift remains statistically significant
- Revenue improvement is sustainable
- Customer impact is understood
- Guardrail metrics remain within acceptable limits

Then I would recommend a **gradual rollout**.

This allows the team to capture the potential business value while reducing the risk of scaling a problematic experience.

---

# 🔄 Product Decision Framework

**Experiment Results**

↓

**Check Statistical Significance**

↓

**Analyze Funnel**

↓

**Segment Users**

↓

**Investigate Negative Signals**

↓

**Understand Customer Feedback**

↓

**Evaluate Business Impact**

↓

**Check Guardrails**

↓

**Decide: Stop / Continue / Gradual Rollout**

↓

**Monitor Post-Launch Impact**

---

# 💡 Key Product Insights

### 1. A positive experiment result doesn't automatically mean "ship it."

A Product Owner needs to understand the complete impact of the change.

---

### 2. Don't optimize one metric in isolation.

Higher conversion is valuable, but not if it creates significant customer problems.

---

### 3. Guardrail metrics matter.

Support contacts, complaints, cancellations, and refunds can reveal hidden costs of an apparently successful experiment.

---

### 4. Statistical significance matters.

Observed improvement and statistically significant improvement are not necessarily the same thing.

---

### 5. Segment before making a broad decision.

A feature can perform well overall while creating problems for a specific customer segment.

---

### 6. Data tells us what happened. Qualitative research helps explain why.

Combining:

**Analytics + Funnel Analysis + Customer Feedback**

creates a stronger basis for Product decisions.

---

# 🧩 Skills Practiced

- A/B Testing
- Experiment Design
- Product Analytics
- Funnel Analysis
- Conversion Rate Analysis
- Statistical Significance
- Customer Segmentation
- Hypothesis Generation
- Customer Feedback Analysis
- Primary Metrics
- Secondary Metrics
- Guardrail Metrics
- Business Impact Analysis
- Experimentation Strategy
- Gradual Rollout
- Data-Driven Decision Making

---

# 📚 About This Series

This is **Case Study #9 of 30 hypothetical Product Case Studies** created as part of my Product Management learning journey.

The goal of this series is to turn Product theory into practical problem-solving and strengthen my ability to approach realistic and ambiguous Product problems.

### Topics Across the Series

- Product Thinking
- Product Discovery
- Product Analytics
- Experimentation
- Prioritization
- Technical Product Management
- Agile Product Delivery
- AI Product Management

**9 cases. 9 problems. One goal: become a better Product thinker. 🚀**

---

## ⚠️ Disclaimer

This is a **hypothetical case study** created for learning and portfolio purposes.

The scenario, metrics, customer feedback, business context, and experiment results are fictional and are not presented as real company data or confidential work experience.
