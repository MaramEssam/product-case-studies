# Case Study #17 — The Experiment That Improved Conversion but Hurt Long-Term Value

## 🎯 Focus Areas

- A/B Testing
- Product Analytics
- Customer Behavior
- Retention Analysis
- Experimentation
- Unit Economics
- Customer Experience
- Product Decision-Making
- Stakeholder Management

---

## 📌 Scenario

I am the Product Owner for an e-commerce application.

The Growth team proposes a checkout incentive:

> **"Get 15% off your order if you complete checkout within 10 minutes."**

The objective is to:

- Reduce cart abandonment
- Increase checkout conversion
- Increase completed orders
- Create urgency
- Improve short-term revenue

The team runs an A/B test for **6 weeks** with **100,000 users**:

- **50,000 users:** Control group
- **50,000 users:** Variant group

### Control

The existing checkout experience.

### Variant

The existing checkout experience +:

- 15% discount
- 10-minute countdown timer

---

# 📊 Experiment Results

| Metric | Control | Variant | Change |
|---|---:|---:|---:|
| Checkout Conversion | 18% | 23% | +5 pp |
| Completed Orders | 9,000 | 11,500 | +27.8% |
| AOV | $42 | $37 | -11.9% |
| Revenue / User | $7.56 | $8.51 | +12.6% |
| Gross Margin / User | $3.10 | $2.40 | -22.6% |
| Cart Abandonment | 82% | 77% | -5 pp |
| 30-Day Repeat Purchase | 34% | 29% | -5 pp |
| 60-Day Retention | 27% | 21% | -6 pp |
| Refund Requests | 3% | 5% | +2 pp |
| Cancellation Rate | 4% | 7% | +3 pp |
| Support Contacts | — | +18% | Increased |

---

# 1. 🧠 First Reaction

I would **not immediately declare the variant a success**.

There are strong positive signals:

- Checkout conversion increased.
- Completed orders increased.
- Cart abandonment decreased.
- Revenue per user increased.

However, the experiment also created several warning signs:

- AOV decreased.
- Gross margin per user decreased significantly.
- Repeat purchase decreased.
- 60-day retention decreased.
- Refund requests increased.
- Cancellation increased.
- Support contacts increased.

This suggests that the experiment may be improving **short-term conversion while damaging long-term customer and business value**.

My first reaction would therefore be:

> **"The experiment is promising, but it is not yet a sustainable winner."**

---

# 2. 📈 Positive Signals

The strongest positive signals are:

### Checkout Conversion

Conversion increased from:

**18% → 23%**

That's a **5 percentage-point increase**, or approximately **27.8% relative growth**.

This indicates that the incentive successfully encouraged more customers to complete checkout.

### Completed Orders

Completed orders increased from:

**9,000 → 11,500**

This is a substantial increase and suggests that the experiment generated additional transactions.

### Cart Abandonment

Cart abandonment decreased:

**82% → 77%**

This supports the original hypothesis that the incentive can reduce checkout abandonment.

### Revenue per User

Revenue per user increased:

**$7.56 → $8.51**

That's approximately a **12.6% increase**.

However, revenue alone is not enough to determine whether the experiment created sustainable business value.

---

# 3. 🚨 Warning Signs

Several metrics require immediate investigation.

## AOV Decreased

AOV decreased:

**$42 → $37**

Possible explanations:

- Customers are buying lower-value products.
- Customers are optimizing their basket to use the discount.
- The discount encourages smaller purchases.
- Customers are purchasing only products eligible for the promotion.
- Price-sensitive customers are overrepresented in the variant.

---

## Gross Margin Decreased

Gross margin per user decreased:

**$3.10 → $2.40**

That's approximately a **22.6% decrease**.

This is particularly important because revenue increased while profitability decreased.

The key business question is:

> **Are the additional orders generating enough incremental profit to justify the cost of the discount?**

At the moment, the answer is unclear and requires further analysis.

---

## Repeat Purchase Decreased

30-day repeat purchase:

**34% → 29%**

This could indicate that customers are responding to the immediate discount but are not necessarily becoming more valuable long-term customers.

---

## Retention Decreased

60-day retention:

**27% → 21%**

This is a major warning sign.

I would investigate whether the discount is attracting customers who:

- Are highly price-sensitive
- Only purchase when discounts are available
- Have lower long-term value
- Experience poor post-purchase satisfaction

However, I would validate these hypotheses using the randomized experiment and cohort analysis rather than assuming the reason.

---

## Refunds and Cancellations Increased

Refund requests:

**3% → 5%**

Cancellation rate:

**4% → 7%**

These increases could indicate:

- Rushed purchasing decisions
- Customers misunderstanding the promotion
- Customers regretting purchases
- Discount eligibility confusion
- Checkout or pricing issues
- Customers buying products they did not really intend to purchase

---

## Support Contacts Increased

Support contacts increased by:

**18%**

This is another important customer-experience signal.

I would categorize the support contacts to understand the main reasons.

For example:

- "Why did my discount disappear?"
- "Why isn't my product eligible?"
- "Why did the countdown expire?"
- "Why didn't I receive the discount?"
- "Can I cancel my order?"
- "Why is my final price different?"

---

# 4. 🔎 Hypotheses

I would create several hypotheses and validate them with data.

### Hypothesis 1 — The Countdown Creates Too Much Pressure

The 10-minute timer may encourage customers to make rushed decisions.

This could explain:

- Higher conversion
- Higher cancellation
- Higher refund requests
- Lower repeat purchase
- Higher support contacts

---

### Hypothesis 2 — The Discount Attracts Highly Price-Sensitive Customers

Customers who would not normally purchase may convert because of the discount.

These customers might have:

- Lower AOV
- Lower repeat purchase
- Lower retention
- Higher discount dependency

---

### Hypothesis 3 — Customers Are Optimizing Their Basket Around the Discount

Customers may reduce their basket value or select cheaper products because they know they will receive 15% off.

This could contribute to the AOV decline.

---

### Hypothesis 4 — Discount Conditions Are Not Clear

Customers may not fully understand:

- Which products are eligible
- The maximum discount
- The expiration time
- Excluded categories
- Whether the discount can be combined with other offers

This could explain the increase in Support contacts and refunds.

---

### Hypothesis 5 — Customers Become Trained to Wait for Discounts

If discounts are repeatedly offered, customers may learn:

> "I should wait for a discount before purchasing."

This could create long-term discount dependency and negatively affect full-price purchasing behavior.

---

# 5. 🔬 Investigation Plan

Before making a rollout decision, I would analyze the experiment more deeply.

## Customer Segmentation

I would segment users by:

- New vs. existing customers
- First-time vs. repeat purchasers
- Country
- Device type
- Customer frequency
- Customer lifetime value
- Order value
- Discount size
- Product category
- Seller
- Number of items in the basket

The goal is to identify whether the negative impact is concentrated in specific segments.

---

## Cancellation Analysis

I would analyze cancellation reasons and compare:

**Control vs. Variant**

For example:

| Cancellation Reason | Control | Variant |
|---|---:|---:|
| Changed mind | — | — |
| Price issue | — | — |
| Product unavailable | — | — |
| Discount issue | — | — |
| Delivery issue | — | — |

This can help determine whether the countdown or discount is influencing cancellations.

---

## Refund Analysis

I would categorize refund requests by reason and compare the two cohorts.

I would specifically look for evidence of:

- Impulse purchases
- Wrong expectations
- Promotion misunderstandings
- Product dissatisfaction
- Checkout problems

---

## Support Analysis

I would categorize the additional Support contacts by theme.

If a large percentage are related to the promotion, this would indicate a potential UX or communication problem.

---

# 6. 💰 Revenue vs. Profitability

An important Product Management lesson from this case is:

> **Higher revenue does not automatically mean higher business value.**

Revenue per user increased:

**$7.56 → $8.51**

But gross margin per user decreased:

**$3.10 → $2.40**

The company is generating more revenue but keeping less gross margin per user.

Therefore, I would not optimize the product based on revenue alone.

I would evaluate:

- Gross margin
- Contribution margin
- Discount cost
- Incremental revenue
- Incremental profit
- Customer acquisition value
- Repeat purchase
- Customer lifetime value

---

# 7. ⏱️ Investigating the 10-Minute Countdown

The countdown is one of the biggest elements I would investigate.

The timer may successfully create urgency, but it could also create unnecessary pressure.

I would test:

### Experiment A

**15% discount + countdown**

vs.

### Experiment B

**15% discount without countdown**

This would help isolate whether the negative customer outcomes are related to the timer itself.

Other possible experiments:

- 10-minute countdown vs. 30-minute countdown
- 10% discount vs. 15% discount
- Countdown vs. no countdown
- Personalized discount vs. generic discount
- Minimum order value for discount
- Selected categories only

---

# 8. 📊 Metrics

## Primary Metric

The primary metric should reflect sustainable business value.

### Primary:

**Incremental Gross Profit / Contribution Margin per User**

The objective is not simply to generate more orders.

The objective is to generate **profitable incremental orders**.

---

## Secondary Metrics

I would monitor:

- Checkout conversion
- Completed orders
- Revenue per user
- AOV
- Repeat purchase
- 30-day retention
- 60-day retention
- Customer lifetime value

---

## Guardrail Metrics

I would monitor:

- Cancellation rate
- Refund rate
- Support contacts
- Customer complaints
- Customer satisfaction
- Discount cost
- Gross margin

These metrics help ensure that improving the primary metric does not create unacceptable negative consequences.

---

# 9. 🧪 Experiment Quality

Before making a final decision, I would also verify that the experiment itself is reliable.

I would check:

- Statistical significance
- Sample size
- Experiment duration
- Randomization
- Treatment/control balance
- Seasonality
- External campaigns
- Technical issues
- Novelty effects

I would also ensure that the 30-day and 60-day retention measurements have enough time to mature before drawing conclusions.

---

# 10. 🚀 Rollout Decision

I would **not roll out the feature to 100% of users yet**.

I would choose:

### ✅ Option C

> **Keep the experiment limited, modify the risky elements, and run a second controlled experiment focused on sustainable profitability and customer retention.**

I would not completely kill the feature because the positive signals are significant.

However, I would not scale it blindly because the current version is associated with:

- Lower margin
- Lower repeat purchase
- Lower retention
- Higher refunds
- Higher cancellations
- Higher Support volume

---

# 11. 🛠️ Proposed Next Step

My approach would be:

**1. Investigate**  
Analyze the negative metrics and segment the results.

↓

**2. Identify root causes**  
Understand whether the problems come from the discount, countdown, UX, or customer segment.

↓

**3. Modify the experience**  
Improve discount transparency and reconsider the countdown.

↓

**4. Run a controlled experiment**  
Test the modified experience against the control.

↓

**5. Measure short-term + long-term impact**  
Evaluate conversion, margin, repeat purchase, retention, and CX.

↓

**6. Gradually roll out**  
Scale only if the experiment demonstrates sustainable business and customer value.

---

# 💡 Key Product Takeaway

This case demonstrates that **A/B testing is not simply about finding the variant with the highest conversion rate.**

A feature can improve:

📈 Conversion  
📈 Orders  
📈 Revenue  

while simultaneously hurting:

📉 Profitability  
📉 Retention  
📉 Customer experience  
📉 Long-term customer value

As a Product Owner, I need to look beyond the headline metric and understand the **trade-offs created by the product decision**.

> **The best experiment is not necessarily the one that creates the biggest short-term lift. It's the one that creates sustainable value for both the customer and the business.**

---

## 🧠 Skills Demonstrated

- Product Analytics
- A/B Testing
- Experiment Design
- Customer Segmentation
- Retention Analysis
- Unit Economics
- Funnel Analysis
- Hypothesis Development
- Customer Experience
- Product Prioritization
- Risk Management
- Stakeholder Management
- Data-Driven Decision Making

---

## 📌 Final Decision

**Decision: Keep the experiment limited → modify the risky elements → run a second controlled experiment → validate profitability and retention → scale gradually if successful.**
