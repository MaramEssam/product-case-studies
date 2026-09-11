# Case Study #18 — Smart Delivery Slots: Solving the Customer Problem Without Creating an Operational Nightmare

## 🎯 Focus Areas

- Product Operations
- Product Analytics
- Customer Experience
- Operational Scalability
- Unit Economics
- Customer Segmentation
- Experimentation
- Product Metrics
- Stakeholder Management
- Data-Driven Decision Making

---

## 📌 Scenario

I am the Product Owner for a food-delivery platform.

Customers frequently complain that their orders arrive late, especially during peak hours.

To address this problem, the Product team proposes a feature called **Smart Delivery Slots**.

Instead of showing customers only one estimated delivery time, the app offers three delivery options:

| Delivery Option | ETA | Price |
|---|---|---:|
| ⚡ Fast | 30–40 minutes | +$2 |
| 🕐 Standard | 45–60 minutes | Free |
| 🌱 Flexible | 60–90 minutes | $1 discount |

---

## 🎯 Business Goals

The feature is designed to:

1. Reduce delivery delays.
2. Improve customer satisfaction.
3. Better balance courier capacity.
4. Reduce peak-hour operational pressure.
5. Reduce cancellations caused by long ETAs.
6. Generate additional delivery-fee revenue from customers choosing Fast delivery.
7. Give customers more control over their delivery experience.

---

# 📊 Results After 6 Weeks

The feature is available to **70% of customers**.

| Metric | Before | After | Change |
|---|---:|---:|---:|
| On-time delivery | 78% | 86% | +8 pp |
| Customer satisfaction | 3.8/5 | 4.1/5 | +0.3 |
| Delivery-related cancellations | 9% | 6% | -3 pp |
| Fast-slot adoption | — | 28% | — |
| Standard-slot adoption | — | 52% | — |
| Flexible-slot adoption | — | 20% | — |
| Average delivery cost/order | $3.10 | $3.70 | +$0.60 |
| Courier utilization | 82% | 94% | +12 pp |
| Support contacts | — | +25% | Increased |
| Refund requests | 4% | 6% | +2 pp |
| Peak-hour orders | — | +12% | Increased |

---

# 1. 🧠 First Reaction

I would **not immediately classify the feature as a complete success or failure**.

The feature is clearly solving the original customer problem.

### Positive signals

- On-time delivery improved from **78% to 86%**.
- Customer satisfaction improved from **3.8 to 4.1/5**.
- Delivery-related cancellations decreased from **9% to 6%**.
- Peak-hour orders increased by **12%**.

These results suggest that giving customers delivery-time choices is improving delivery reliability and customer experience.

However, there are also important warning signs:

- Delivery cost per order increased.
- Courier utilization reached 94%.
- Support contacts increased by 25%.
- Refund requests increased from 4% to 6%.

Therefore, I would describe the feature as:

> **A promising solution that is solving the original problem, but still requires optimization before a full rollout.**

---

# 2. 📈 Positive Signals

## On-Time Delivery

On-time delivery increased:

**78% → 86%**

This is one of the strongest indicators that the feature is addressing the original problem.

Customers are receiving orders within the expected delivery window more often.

---

## Customer Satisfaction

Customer satisfaction increased:

**3.8 → 4.1/5**

This suggests that improved delivery reliability is having a positive effect on the customer experience.

However, I would still investigate whether satisfaction differs significantly between Fast, Standard, and Flexible users.

---

## Delivery-Related Cancellations

Cancellations decreased:

**9% → 6%**

This is another strong signal.

Customers may be less likely to cancel when they have clearer and more realistic delivery expectations.

---

## Peak-Hour Orders

Orders during peak hours increased by:

**12%**

This could indicate that customers are more willing to order during busy periods when they have more visibility and control over delivery timing.

However, I would also investigate whether this increase is contributing to the higher courier utilization and delivery cost.

---

# 3. 🚨 Warning Signs

## Delivery Cost Increased

Average delivery cost per order increased:

**$3.10 → $3.70**

This is a significant business concern.

The Product team needs to understand:

- Why delivery cost increased.
- Which slot is responsible for the increase.
- Whether Fast orders have a higher operational cost.
- Whether additional courier incentives are required.
- Whether peak-hour operations are becoming more expensive.

---

## Courier Utilization Reached 94%

Courier utilization increased from:

**82% → 94%**

Higher utilization can initially look positive because it means the company is using available capacity more efficiently.

However, **94% may be difficult to sustain**.

Potential risks include:

- Courier burnout
- Lower courier satisfaction
- More delivery delays
- Less flexibility when demand spikes
- Higher cancellation rates
- Reduced ability to handle unexpected incidents

I would investigate whether 94% utilization is:

- Temporary
- Limited to peak hours
- Consistent throughout the day
- Causing operational degradation

I would not immediately decide to hire more couriers without understanding the underlying capacity problem.

---

## Support Contacts Increased

Support contacts increased by:

**25%**

This is a strong customer-experience signal.

I would categorize Support contacts to understand the main reasons.

Possible categories:

- Customers don't understand the difference between slots.
- Fast delivery was not delivered within the expected window.
- Customers expected Standard to be faster.
- Pricing is unclear.
- Customers don't understand the $1 Flexible discount.
- Customers don't understand eligibility.
- Customers selected the wrong slot.

---

## Refund Requests Increased

Refund requests increased:

**4% → 6%**

This requires investigation.

Possible causes include:

- Customers expected faster delivery.
- Fast delivery promises were not met.
- Customers misunderstood the delivery window.
- Orders were delayed despite selecting Fast.
- Poor delivery experience.
- Restaurant preparation delays.

I would compare refund reasons across different delivery slots.

---

# 4. 🔎 Hypotheses

## Hypothesis 1 — Customers Prefer the Free Standard Option

Standard adoption is **52%**, compared with:

- Fast: 28%
- Flexible: 20%

One possible explanation is that customers don't see enough additional value in paying $2 for Fast delivery.

However, I would not assume price is the only reason.

Customers may simply find the Standard ETA acceptable.

I would validate this through:

- Customer surveys
- Interviews
- Slot-level conversion analysis
- Customer feedback
- Pricing experiments

---

## Hypothesis 2 — Courier Capacity Is Becoming a Bottleneck

The increase to **94% courier utilization** may indicate that demand is approaching the available delivery capacity.

I would investigate:

- Courier availability by hour
- Orders per courier
- Peak vs. non-peak utilization
- Delivery delays
- Courier acceptance/rejection rates
- Courier earnings
- Courier satisfaction
- Geographic capacity

Before hiring additional couriers, I would confirm whether the capacity issue is sustained and whether it is actually causing service degradation.

---

## Hypothesis 3 — Fast Delivery May Have a Higher Operational Cost

Fast delivery may require:

- More couriers
- Additional incentives
- More efficient routing
- Lower batching opportunities
- Faster restaurant preparation
- Higher operational coordination

This could explain the increase in delivery cost.

I would calculate the incremental cost of Fast orders specifically.

---

## Hypothesis 4 — Slot Information Is Not Clear Enough

Support feedback suggests that customers don't understand the difference between Fast and Standard.

Possible UX issues include:

- Unclear delivery windows
- Poor pricing visibility
- Weak explanation of the benefit
- Confusing labels
- Unclear eligibility
- Poor visibility of the selected slot

The solution should not simply be a popup.

The customer should clearly understand:

> **What am I paying for?**  
> **When will my order arrive?**  
> **What happens if the promised window is missed?**

---

# 5. 🔬 Customer Segmentation

I would segment the results to identify where the feature performs well and where problems are concentrated.

### Customer Segments

- New vs. existing customers
- Frequent vs. occasional customers
- High-value vs. low-value customers
- Country
- Device
- Customer location

### Order Segments

- Order value
- Number of items
- Restaurant
- Restaurant category
- Delivery zone
- Peak vs. non-peak
- Selected delivery slot

### Operational Segments

- Courier availability
- Courier utilization
- Distance
- Delivery route
- Restaurant preparation time
- Time of day

This would help determine whether the problem is primarily:

**Customer → Restaurant → Courier → Zone → Pricing → Capacity**

---

# 6. 💰 Business Impact and Unit Economics

The Fast slot generates an additional:

**+$2**

However, average delivery cost per order increased:

**$3.10 → $3.70**

I would not simply compare the $2 fee against the $0.60 overall cost increase.

The important question is:

> **What is the incremental contribution margin of Fast delivery?**

I would calculate:

**Incremental Revenue**

minus

**Incremental Delivery Cost**

minus

**Additional Courier Cost**

minus

**Additional Operational Costs**

minus

**Refunds/Cancellations/Support Costs**

=

**Incremental Contribution Margin**

I would perform this analysis specifically for Fast-slot users rather than relying only on the overall average.

---

# 7. 🧑‍💻 Customer Experience Improvements

Because Support reports confusion between Fast and Standard, I would improve the presentation of delivery options.

For example:

### ⚡ Fast
**30–40 min | +$2**

"Get your order sooner."

### 🕐 Standard
**45–60 min | Free**

"Reliable delivery at no extra cost."

### 🌱 Flexible
**60–90 min | Save $1**

"Choose a longer window and save."

The UI should make the trade-off immediately understandable.

I would also make the expected delivery window highly visible throughout checkout and order tracking.

---

# 8. 🚴 Operational Scalability

The feature should not be considered successful if it improves customer metrics by pushing the delivery network beyond sustainable capacity.

At **94% courier utilization**, I would investigate:

- Whether the utilization increase occurs only during peak hours.
- Whether courier supply is sufficient.
- Whether delivery delays increase when utilization reaches 94%.
- Whether courier satisfaction is declining.
- Whether additional incentives are required.
- Whether Fast delivery should only be available when capacity exists.

A potential solution is:

> **Capacity-based slot availability**

For example, Fast delivery could only be offered when sufficient courier capacity exists.

This prevents the product from promising a Fast experience that the operation cannot reliably deliver.

---

# 9. 📊 Metrics Framework

## 🎯 Primary Metric

Because the original problem is delivery reliability:

**On-Time Delivery Rate**

This measures whether the product is actually delivering on its core customer promise.

---

## Secondary Metrics

- Customer satisfaction
- Delivery-related cancellation rate
- Completed orders
- Average delivery time
- Slot adoption
- Repeat purchase
- Revenue per order
- Contribution margin

---

## 🚨 Guardrail Metrics

- Courier utilization
- Courier satisfaction
- Support contacts
- Refund rate
- Complaints
- Late deliveries
- Cancellation rate

These ensure that improving on-time delivery does not create unacceptable operational or customer-experience problems.

---

## 💰 Business Metrics

- Incremental revenue from Fast slots
- Incremental delivery cost
- Courier cost
- Support cost
- Refund cost
- Contribution margin
- Profit per order

---

## ❤️ Customer Experience Metrics

- Customer satisfaction
- Delivery-related complaints
- Refund requests
- Cancellation rate
- Support contacts
- Slot-selection confusion
- On-time delivery

---

# 10. 🧪 Experimentation Strategy

I would not immediately roll out the feature to 100%.

I would first address the major operational and CX risks and then run another controlled experiment.

### Experiment 1 — Slot Presentation

Test:

**Current UI**

vs.

**Clearer delivery-slot explanation**

Measure:

- Slot selection
- Cancellation
- Refunds
- Support contacts
- Customer satisfaction

---

### Experiment 2 — Fast Delivery Pricing

Test different prices:

- $1
- $2
- $3

Measure:

- Fast-slot adoption
- Incremental revenue
- Delivery cost
- Contribution margin
- Customer satisfaction

---

### Experiment 3 — Capacity-Based Availability

Test:

**Fast slot always available**

vs.

**Fast slot available only when courier capacity is sufficient**

Measure:

- On-time delivery
- Courier utilization
- Cancellation
- Customer satisfaction
- Contribution margin

---

### Experiment 4 — Peak-Hour Availability

Test whether Fast delivery should be available:

- All day
- Only during selected periods
- Only in zones with sufficient capacity

This could help balance customer demand with operational capacity.

---

# 11. 🚀 Rollout Decision

If Leadership asks:

> **"Why don't we launch this to 100% of customers?"**

I would choose:

## ✅ Option C

> **Keep the feature controlled, fix the operational and customer-experience issues, and run another controlled experiment.**

I would not choose **A** because:

- Courier utilization is already 94%.
- Delivery costs increased.
- Support contacts increased 25%.
- Refund requests increased.
- We still have customer confusion.

I would not choose **B** because the feature is clearly solving the original problem:

- On-time delivery improved.
- Customer satisfaction improved.
- Delivery-related cancellations decreased.

Therefore, the right decision is to **optimize rather than kill the feature**.

---

# 12. 🛠️ Recommended Product Approach

My overall approach would be:

### 1. Investigate
Analyze the positive and negative metrics.

↓

### 2. Segment
Identify which customers, restaurants, zones, slots, and time periods are driving the results.

↓

### 3. Identify Root Causes
Understand why costs, Support contacts, and refunds increased.

↓

### 4. Improve the Experience
Make slot differences and delivery expectations clearer.

↓

### 5. Optimize Operations
Investigate courier capacity and consider capacity-based slot availability.

↓

### 6. Experiment
Test pricing, availability, UX, and delivery windows.

↓

### 7. Validate Economics
Measure incremental contribution margin.

↓

### 8. Gradually Scale
Roll out further only when customer, operational, and business metrics remain healthy.

---

# 💡 Key Product Takeaway

This case demonstrates an important Product Management principle:

> **Solving the original customer problem is necessary, but it is not enough.**

A feature can improve:

📈 On-time delivery  
📈 Customer satisfaction  
📈 Order volume  
📉 Delivery-related cancellations  

while simultaneously creating:

⚠️ Higher delivery costs  
⚠️ Higher courier utilization  
⚠️ More Support contacts  
⚠️ More refunds  
⚠️ Operational scalability risks

As a Product Owner, I need to look at the **entire system**, not just the customer-facing metric.

### Customer
↓
### Restaurant
↓
### Courier
↓
### Delivery Network
↓
### Operations
↓
### Cost
↓
### Business Value

The goal is not simply to build a feature that works.

The goal is to build a solution that is:

**Useful for customers + operationally sustainable + financially viable + scalable.**

---

## 🧠 Skills Demonstrated

- Product Operations
- Product Analytics
- Customer Experience
- Operational Scalability
- Unit Economics
- Customer Segmentation
- Hypothesis Development
- Experiment Design
- Product Metrics
- Stakeholder Management
- Root Cause Analysis
- Data-Driven Decision Making

---

## 📌 Final Decision

**Keep the feature controlled → investigate the operational and CX risks → improve the experience → optimize courier capacity and pricing → run controlled experiments → validate contribution margin → scale gradually.**
