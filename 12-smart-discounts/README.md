# Case Study #12 — Smart Discounts: When Revenue Goes Up but Retention Goes Down

## 📌 Overview

**Product:** Food Delivery App  
**Feature:** Smart Discounts  
**Case Focus:** Product Analytics, Customer Experience, Experimentation, Trade-offs, Product Strategy

Smart Discounts is a personalized promotion feature designed to use customer behavior to provide relevant discounts and encourage customers to place more orders.

After six weeks, the feature showed positive short-term business results, including higher orders, conversion, and revenue per user.

However, several warning signals also appeared:

- 30-day retention decreased
- Cancellation rate increased
- Support contacts increased
- Average Order Value decreased
- Customers reported confusion about discount eligibility

This case explores how I would evaluate whether Smart Discounts is truly successful and decide whether to scale, improve, or change the feature.

---

# 🎯 Business Context

The primary objectives of Smart Discounts are to:

- Increase order frequency
- Improve conversion
- Increase revenue per user
- Encourage customers to place orders
- Provide personalized offers
- Improve the overall customer experience

After six weeks, the following results were observed:

| Metric | Before | After | Direction |
|---|---:|---:|---|
| Orders per User | 2.1 | 2.5 | 📈 Positive |
| Conversion Rate | 18% | 21% | 📈 Positive |
| Revenue per User | $32 | $38 | 📈 Positive |
| AOV | $22 | $21 | 📉 Negative |
| 30-Day Retention | 31% | 27% | 📉 Negative |
| Cancellation Rate | 5% | 8% | 📈 Negative |
| Support Contacts | — | +20% | ⚠️ Negative |
| Discount Usage | — | 42% | 📈 Strong adoption |

---

# 🔍 Initial Assessment

At first glance, Smart Discounts appears successful.

Orders per user increased from **2.1 to 2.5**, conversion increased from **18% to 21%**, and revenue per user increased from **$32 to $38**.

However, looking only at these metrics would be misleading.

At the same time:

- 30-day retention dropped from **31% to 27%**
- Cancellation rate increased from **5% to 8%**
- Support contacts increased by **20%**
- AOV decreased from **$22 to $21**

Customers also reported that they did not understand why some users received better discounts than others.

Therefore, I would classify the feature as:

> **Partially Successful**

The feature appears to be achieving a meaningful portion of the short-term business goal, but customer value, long-term retention, and customer experience still require investigation.

---

# 🧩 Problem Statement

Smart Discounts is generating stronger short-term business performance, but there are signs of negative customer and potentially commercial impact.

The key Product question is:

> **Can we maintain the positive revenue impact without negatively affecting retention, customer experience, cancellations, and margins?**

Before expanding the feature to 100% of users, I would investigate the root causes behind these trade-offs.

---

# 💡 Key Product Hypotheses

I would avoid assuming that one problem has one cause.

Instead, I would investigate several hypotheses.

## Hypothesis 1 — Customers Are Confused About Discount Eligibility

Some customers may discover that another user received a better discount and feel that the promotion system is unfair.

This could lead to:

- Complaints
- Lower trust
- Lower satisfaction
- Increased Support contacts
- Reduced future engagement

---

## Hypothesis 2 — Discount Communication Is Incorrect or Delayed

Some discounts may be:

- Expired
- Already used
- Sent too late
- Restricted to specific users
- Subject to conditions that are not clear

For example, a customer may receive a notification after the promotion has already expired.

This could explain part of the increase in Support contacts and cancellations.

---

## Hypothesis 3 — Large Discounts Increase Short-Term Orders but Reduce Long-Term Value

Customers may respond strongly to large discounts and place more orders in the short term.

However, some of these customers may become highly promotion-dependent.

Once the discount disappears, they may stop ordering.

This could potentially explain:

**Orders ↑**

while:

**30-Day Retention ↓**

---

## Hypothesis 4 — Checkout or Redemption Problems

Customers may successfully discover a discount but experience problems when trying to use it.

Possible causes include:

- Discount not being applied
- Minimum order requirements
- Payment issues
- Restaurant restrictions
- Expired promotions
- Incorrect eligibility rules
- Technical bugs

---

## Hypothesis 5 — Restaurant-Level Problems

The effectiveness of Smart Discounts may vary by restaurant.

Possible issues include:

- Poor restaurant reputation
- Item availability
- Long preparation time
- High delivery fees
- Low food quality
- Restaurant-specific restrictions

A customer may use the discount but still cancel because the overall offer is not attractive enough.

---

## Hypothesis 6 — The Feature Performs Differently Across Customer Segments

The overall results may hide significant differences between customer groups.

For example:

- New customers may respond positively
- Existing customers may feel the discounts are unfair
- Frequent users may need smaller incentives
- Infrequent users may respond better to larger discounts

---

# 🔬 Segmentation Strategy

I would segment the data before making a major product decision.

## Customer Segment

- New vs. existing customers
- Frequent vs. occasional customers
- High-value vs. low-value customers
- Promotion-sensitive vs. non-promotion-sensitive customers

## Discount Segment

- Small discount
- Medium discount
- Large discount
- Percentage-based vs. fixed-value discount
- One-time vs. recurring discount

## Geography

- Country
- City
- Delivery area

## Device

- iOS
- Android
- App version

## Restaurant

- Restaurant
- Restaurant category
- Restaurant rating
- Average delivery time

## Customer Behavior

- Orders per month
- Previous AOV
- Previous retention
- Previous discount usage
- Cancellation behavior

---

# 📊 Investigating the Retention Drop

The decrease in retention should not automatically be attributed to Smart Discounts.

A before-and-after comparison alone does not prove causation.

I would compare:

### Treatment Group

Customers who received or used Smart Discounts.

### Control Group

Similar customers who did not receive or use Smart Discounts.

I would compare:

- 30-day retention
- Order frequency
- Cancellation rate
- Revenue per user
- AOV
- Repeat purchase behavior

Ideally, I would use a randomized experiment where possible.

This would help answer:

> **Did Smart Discounts actually cause the retention decline, or did another factor contribute to it?**

---

# 👥 Customer Fairness & Transparency

Customer Support reported that customers were asking:

> "Why does another customer get a better discount than me?"

I would consider this a **Product and Customer Experience issue**, even if the discount system is technically working as designed.

The problem is not necessarily that every customer receives a different offer.

Personalization can be valuable.

The problem is whether customers understand:

- Why they received the offer
- Who is eligible
- When it expires
- What conditions apply
- Why another offer may be different

Potential improvements could include:

- Clearer eligibility messaging
- Transparent promotion conditions
- Clear expiration dates
- Better in-app explanations
- Clearer notification content
- Showing applicable discounts directly in the checkout experience

The goal is to make personalized offers feel **relevant rather than unfair or misleading**.

---

# 💰 Commercial Trade-off

AOV decreased from:

**$22 → $21**

While Revenue per User increased from:

**$32 → $38**

I would not make a decision based on AOV alone.

A $1 decrease in AOV may be acceptable if the increase in order frequency and revenue creates sustainable value.

However, I would investigate:

- Revenue per user
- Gross margin
- Discount cost
- Contribution margin
- Orders per user
- Customer Lifetime Value
- Cancellation cost
- Refund cost

The most important question is:

> **Are we generating profitable incremental revenue, or are we simply buying more orders through discounts?**

---

# 🧪 Experimentation Strategy

If the analysis shows that large discounts increase orders but negatively affect retention and margin, I would not immediately remove Smart Discounts.

Instead, I would test alternatives.

## Experiment 1 — Smaller Discounts

Compare:

**Large Discount vs. Small Discount**

Measure whether a smaller incentive can generate similar incremental orders with lower margin impact.

---

## Experiment 2 — More Targeted Discounts

Instead of giving large discounts to a broad audience, target customers where the incentive is most likely to generate incremental behavior.

For example:

- Customers at risk of churn
- Infrequent customers
- Customers who have not ordered recently

---

## Experiment 3 — Different Eligibility Rules

Test whether changing the eligibility criteria improves:

- Customer perception
- Retention
- Margin
- Conversion

---

# 📈 Metrics Framework

## Primary Metric

### Incremental Revenue per User

The goal is not simply to increase revenue, but to understand whether Smart Discounts generate meaningful incremental business value.

Where possible, I would measure this against a control group.

---

## Secondary Metrics

I would monitor:

- Conversion Rate
- Orders per User
- Completed Orders
- Repeat Purchase Rate
- 30-Day Retention
- AOV
- Revenue per User
- Discount Redemption Rate

---

## Guardrail Metrics

I would closely monitor:

- Cancellation Rate
- Support Contact Rate
- Customer Complaints
- Refund Rate
- Discount Cost
- Gross Margin
- Contribution Margin
- Payment Failure Rate

A feature should not be considered successful if revenue increases while customer experience and profitability deteriorate significantly.

---

# 🏃 Stakeholder Management

## Growth

**Concern:**

> "Revenue and orders are up. Let's roll it out to 100%."

**My response:**

The short-term business impact is positive, but there are important warning signals in retention, cancellations, and Support contacts.

I would recommend continuing the experiment and investigating these issues before a full rollout.

---

## Commercial

**Concern:**

> "AOV is decreasing and we're giving away too many discounts."

**My response:**

I would investigate margin and incremental revenue rather than looking at AOV alone.

The key question is whether the additional orders generate sustainable profit.

---

## Customer Support

**Concern:**

> "Customers don't understand why some users receive better discounts."

**My response:**

This is an important customer experience signal.

I would analyze complaint themes and improve the transparency of discount eligibility and conditions.

---

## Engineering

**Concern:**

> "The feature is technically working."

**My response:**

That's important, but technical correctness is only one part of product success.

We also need to validate customer behavior, usability, business impact, and long-term outcomes.

---

## Leadership

**Concern:**

> "Revenue is up. Why not roll it out to 100%?"

**My response:**

Revenue growth is encouraging, but the feature currently has unresolved customer and long-term business risks.

I would prefer to keep the feature running while we investigate the retention and cancellation issues, test improvements, and monitor the guardrail metrics.

---

# 🚦 Product Decision

I would **not roll Smart Discounts out to 100% yet**.

Instead, I would:

1. Analyze the complete customer funnel
2. Segment performance by customer and discount characteristics
3. Investigate Support complaints
4. Validate the retention decline against a control group
5. Investigate cancellation reasons
6. Check technical and redemption issues
7. Analyze margin and discount economics
8. Test smaller or more targeted discounts
9. Monitor primary and guardrail metrics
10. Gradually expand the feature if results remain positive

---

# 🧭 Decision Framework

| Finding | Product Action |
|---|---|
| Technical bug | Fix before scaling |
| Expired or unclear offers | Improve communication |
| Customer confusion | Improve UX and transparency |
| Large discounts hurt margin | Test smaller discounts |
| Discounts hurt retention | Review targeting and eligibility |
| Revenue increases sustainably | Consider gradual rollout |
| Revenue increases but profitability declines | Reconsider discount strategy |
| Customer experience deteriorates significantly | Pause or limit affected experience |

---

# 🧠 Key Product Insights

## 1. Revenue Growth Does Not Automatically Mean Product Success

A feature can increase revenue in the short term while creating long-term problems.

---

## 2. Short-Term Incentives Can Have Long-Term Consequences

Discounts can increase orders immediately, but excessive reliance on promotions may affect customer retention and profitability.

---

## 3. Customer Experience Is a Business Metric

The +20% increase in Support contacts should not be ignored simply because revenue increased.

Customer confusion can eventually affect retention and trust.

---

## 4. Personalization Requires Transparency

Customers do not necessarily need identical offers, but they need to understand the offer they receive.

---

## 5. Correlation Is Not Causation

The retention decrease happened after Smart Discounts launched, but that does not automatically mean Smart Discounts caused it.

A control group or randomized experiment provides stronger evidence.

---

## 6. AOV Should Be Viewed in Context

A small decrease in AOV does not automatically make a feature unsuccessful.

It should be evaluated alongside:

- Order frequency
- Revenue
- Margin
- Discount cost
- Retention
- Customer Lifetime Value

---

# 🛠️ Skills Practiced

- Product Analytics
- Customer Segmentation
- Hypothesis Generation
- Root Cause Analysis
- Experimentation
- A/B Testing
- Causal Thinking
- Customer Experience
- Product Metrics
- Commercial Thinking
- Product Strategy
- Stakeholder Management
- Trade-off Analysis
- Data-Driven Decision Making

---

# 🎯 Final Takeaway

Smart Discounts demonstrates an important Product Management challenge:

> **A positive business metric does not automatically mean the product is healthy.**

The feature generated:

**More orders + Higher conversion + Higher revenue**

but also:

**Lower retention + Higher cancellations + More Support contacts + Customer confusion**

Therefore, I would consider the feature **partially successful** rather than immediately declaring it a success or failure.

My approach would be to understand the trade-offs, identify the root causes, validate causality, improve the customer experience, and test alternative discount strategies.

Only after confirming that we can generate sustainable business value without creating unacceptable customer or profitability problems would I recommend a broader rollout.

> **Good Product Management is not about maximizing a single metric. It's about finding the right balance between customer value, business impact, and long-term sustainability.**

---

*This is a hypothetical Product Management case study created for learning and portfolio purposes.*
