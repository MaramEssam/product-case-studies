# 🔄 Case Study #5 — Low Feature Adoption

> **30 Product Case Studies — Case #5**  
> A hypothetical Product Case Study created as part of my Product Management learning journey.

---

## 📌 Overview

A food delivery app launched a new **"Reorder"** feature three months ago.

The feature allows customers to quickly reorder a previous meal instead of searching for the restaurant and items again.

The expected outcome was to increase **feature adoption and repeat purchases**.

However, adoption is significantly below target.

---

## 🚨 The Situation

| Metric / Signal | Current Situation |
|---|---|
| Target Feature Adoption | **25%** |
| Actual Feature Adoption | **8%** |
| Repeat Order Rate | Almost unchanged |
| Customer Feedback | Users report difficulty finding the feature |
| Technical Health | No major technical issues reported |
| Marketing Recommendation | Increase promotion |
| Engineering Capacity | 2 other high-priority initiatives |

### The Product Question

> **Why is adoption only 8%, and should we improve the feature, promote it, or deprioritize it?**

---

# 🎯 Product Goal

Before proposing a solution, I want to understand:

1. Why are users not adopting the feature?
2. Are users aware that the feature exists?
3. Can users easily find and understand it?
4. Are users reaching the feature but choosing not to use it?
5. Is the feature providing enough value?
6. Are we measuring adoption against the right user population?
7. What would have the highest impact: UX improvement, marketing, or something else?

---

# 🔎 1. Start With the Reorder Funnel

The first thing I would investigate is the feature funnel:

**Eligible Users → Feature Exposure → Feature Click → Reorder Started → Reorder Completed**

This helps identify where the problem occurs.

### Example Interpretation

| Funnel Result | Potential Problem |
|---|---|
| Low Feature Exposure | Discoverability / placement |
| High Exposure + Low Clicks | Value proposition or UX |
| High Clicks + Low Reorder Starts | Usability / flow |
| High Starts + Low Completion | Friction or technical issue |
| High Completion + Low Repeat Orders | Feature may not influence broader behavior |

The goal is to understand **what users are doing before deciding why they are doing it**.

---

# 👥 2. Make Sure We Are Measuring the Right Users

Before interpreting the 8% adoption rate, I would confirm who is actually eligible to use the feature.

For example, users without a previous order may not have a meaningful reason to use Reorder.

Therefore:

> **Adoption should be measured against the relevant eligible user population, not necessarily all active users.**

This is important because an incorrect denominator can make a healthy feature look unsuccessful.

---

# 📊 3. Segment the Users

I would segment the eligible users to understand whether adoption differs across groups.

### Customer Type

- New vs. returning customers
- High-value vs. casual customers
- Frequent vs. infrequent buyers

### Platform

- iOS
- Android

### Location

- Country
- Region / city

### Behavior

- Number of previous orders
- Time since last order
- Frequently reordered restaurants
- Frequently reordered categories

### Restaurant / Category

- Restaurant
- Cuisine
- Product category

This could reveal that the feature is highly valuable for frequent customers but less relevant to occasional users.

---

# 💡 4. Main Hypotheses

I would treat the Support feedback as a strong signal, but not as confirmed root cause.

Several hypotheses could explain the low adoption.

---

## Hypothesis 1 — Poor Discoverability

Customers may not notice the Reorder option.

### Signals I would look for:

- Low feature exposure
- Low visibility in the UI
- Users searching for previous orders manually
- Support tickets mentioning difficulty finding Reorder

### Potential solution

Improve:

- Placement
- Visibility
- CTA
- Information hierarchy

---

## Hypothesis 2 — UX / Usability Problem

Users may see the feature but not understand how it works.

### I would investigate:

- User flow
- CTA clarity
- Number of steps
- Confusing screens
- Error messages
- Usability testing results

A quick usability review could help identify obvious friction.

---

## Hypothesis 3 — Low Perceived Value

Customers may understand the feature but simply don't find it useful.

For example:

- They frequently change their orders.
- Their previous orders are no longer relevant.
- They prefer discovering new restaurants.
- Reordering does not save enough time.

If this is the problem, increasing visibility alone won't solve it.

---

## Hypothesis 4 — Eligibility / Measurement Issue

The 8% adoption rate may look low because we're measuring it against too broad a population.

I would validate:

**Eligible Users vs. Total Active Users**

before making a product decision.

---

## Hypothesis 5 — Segment-Specific Behavior

The feature may perform very differently across customer groups.

For example:

**Frequent customers → High adoption**

while:

**Occasional customers → Low adoption**

In this case, the right strategy may be to target the feature toward users who are most likely to benefit from it.

---

# 🧪 5. Validate the Hypotheses

Before asking Engineering to make major changes, I would combine quantitative and qualitative evidence.

### Product Analytics

Analyze:

- Feature exposure
- Feature clicks
- Reorder starts
- Reorder completion
- Repeat orders
- Orders per active customer

### Customer Feedback

Review:

- Support tickets
- Surveys
- Customer interviews
- Existing feedback

### Usability Testing

I would also walk through the experience myself and conduct quick usability testing with customers.

The goal is to answer:

> **Can users find it, understand it, and successfully use it?**

---

# 🎯 6. Should We Invest More in Marketing?

Marketing wants to increase promotion of the feature.

I would **not recommend increasing marketing spend immediately**.

If the problem is discoverability or usability, driving more users toward the feature may not solve the underlying problem.

For example:

**More Promotion → More Feature Visits → Same Low Adoption**

Instead, I would first identify whether the issue is:

**Awareness → Discoverability → Understanding → Usage → Value**

Marketing may become valuable after we confirm that the feature provides meaningful value and the experience works well.

---

# ⚙️ 7. Engineering Capacity & Prioritization

Engineering is already working on two high-priority initiatives.

Therefore, I would not assume that improving Reorder should automatically become the next priority.

I would compare the opportunity based on:

| Factor | Question |
|---|---|
| Customer Impact | How significant is the problem? |
| Business Impact | Can Reorder increase repeat purchases? |
| Reach | How many eligible customers are affected? |
| Confidence | How strong is the evidence? |
| Effort | How much engineering capacity is needed? |
| Urgency | Is the problem getting worse? |
| Opportunity Cost | What would we delay? |

---

# 🛠️ 8. Potential Product Actions

The action depends on what the data tells us.

### If the problem is discoverability:

Implement a focused UX improvement.

Examples:

- Improve CTA visibility
- Move Reorder to a more relevant location
- Improve labeling
- Surface Reorder at the right moment

### If the problem is usability:

Simplify the flow and remove unnecessary steps.

### If the problem is perceived value:

Investigate why users don't see enough benefit and potentially rethink the experience.

### If the feature works well but adoption is limited to certain segments:

Consider targeted exposure rather than promoting it to everyone.

---

# 🧩 9. MVP / Quick Win

If the data confirms that discoverability is the main issue, I would avoid a large rebuild.

A possible quick win could be:

**Improve Reorder visibility → Release → Monitor adoption → Learn → Iterate**

This allows us to test whether a relatively small UX change can move adoption toward the 25% target.

---

# 📈 10. Success Metrics

The primary metric should directly reflect the problem we're trying to solve.

### Primary Metric

**Reorder Adoption Rate**

> Percentage of eligible users who use the Reorder feature.

---

### Supporting Metrics

- Reorder Completion Rate
- Repeat Order Frequency
- Orders per Active Customer
- Time to Reorder
- Feature Engagement

---

### Business Metrics

- Incremental Repeat Orders
- Revenue per Active Customer
- Customer Retention

---

### Guardrail Metrics

I would also monitor:

- Order cancellation rate
- Order failure rate
- Customer Support contacts
- Overall checkout conversion

The objective isn't simply to increase feature usage.

The objective is to determine whether the feature creates **meaningful customer and business value**.

---

# 🔄 Product Investigation Framework

**Low Feature Adoption**

↓

**Validate the Measurement**

↓

**Analyze Feature Funnel**

↓

**Segment Eligible Users**

↓

**Identify Drop-off**

↓

**Form Hypotheses**

↓

**Validate With Data + Users**

↓

**Identify Root Cause**

↓

**Prioritize the Right Intervention**

↓

**Measure Adoption + Business Impact**

---

# 🧠 Key Takeaways

### 1. Low adoption doesn't automatically mean low value.

Users may want the capability but fail to discover it.

### 2. Customer feedback is a signal, not proof.

Support tickets can help identify hypotheses that should be validated with data.

### 3. Fix the funnel before increasing traffic.

If users cannot find or use a feature, increasing marketing spend may simply amplify the problem.

### 4. Measure the right population.

Feature adoption should be calculated using the relevant **eligible users**.

### 5. Feature usage is not the final goal.

The real question is whether Reorder improves meaningful outcomes such as repeat purchases, retention, and customer value.

### 6. Product decisions require trade-offs.

Even a valuable improvement must be evaluated against engineering capacity and other initiatives.

---

# 🧩 Skills Practiced

- Feature Adoption Analysis
- Product Analytics
- Funnel Analysis
- User Segmentation
- UX & Usability
- Customer Problem Discovery
- Hypothesis Generation
- Root Cause Analysis
- Product Prioritization
- Experimentation
- Product Metrics
- Customer Experience
- Cross-functional Collaboration

---

# 📚 About This Series

This is **Case Study #5 of 30 hypothetical Product Case Studies** I'm working through as part of my Product Management learning journey.

The goal of this series is to turn Product theory into practical problem-solving and strengthen my ability to approach realistic and ambiguous Product problems.

### Areas Covered Throughout the Series

- Product Thinking
- Product Analytics
- Discovery & UX
- Prioritization
- Technical Product Management
- Agile Product Delivery
- AI Product Management

**30 cases. 30 problems. One goal: become a better Product thinker. 🚀**

---

## ⚠️ Disclaimer

This is a **hypothetical case study** created for learning and portfolio purposes.

The scenario, metrics, business context, customer feedback, and engineering constraints are fictional and are not presented as real company data or confidential work experience.
