# Case Study #20 — Express Delivery: When a Feature Works for Customers but Operations Can't Keep Up

## 📌 Overview

An e-commerce marketplace launched a new **Express Delivery** feature.

Customers can pay an additional **$4** to receive their order within **24 hours**, instead of the standard 2–4 day delivery.

### 🎯 Business Goals

The feature was designed to:

- Improve customer satisfaction
- Reduce delivery-related cancellations
- Increase checkout conversion
- Generate additional delivery revenue
- Serve customers with urgent delivery needs
- Improve the overall delivery experience
- Increase repeat purchases

After **8 weeks**, Express Delivery was available to **70% of eligible customers**.

At first glance, the feature appeared successful because conversion, completed orders, customer satisfaction, and revenue all increased.

However, deeper analysis revealed significant **operational, financial, and customer experience risks**.

---

# 📊 Results After 8 Weeks

| Metric | Before | After |
|---|---:|---:|
| Express Delivery Adoption | — | **31%** |
| Checkout Conversion | 18% | **21%** |
| Completed Orders | 9% | **11%** |
| Customer Satisfaction | 3.7/5 | **4.2/5** |
| Delivery-related Cancellations | 8% | **5%** |
| Express Delivery Fee Revenue | — | **+$180K/month** |
| On-time Express Delivery | — | **84%** |
| Average Fulfillment Cost/Order | $4.10 | **$5.30** |
| Courier Utilization | 81% | **96%** |
| Support Contacts | — | **+32%** |
| Refunds | 3% | **6%** |
| Repeat Purchase Rate | 26% | **28%** |

---

# 1. 🚦 Initial Product Assessment

My first reaction would be:

> **The feature is showing strong customer value and promising business results, but I would not scale it to 100% yet.**

There are several positive signals:

- Express adoption reached 31%
- Checkout conversion increased from 18% to 21%
- Completed orders increased from 9% to 11%
- Customer satisfaction increased from 3.7 to 4.2/5
- Delivery-related cancellations decreased from 8% to 5%
- Express Delivery generated $180K/month in additional fee revenue
- Repeat purchase rate increased from 26% to 28%

These results suggest that customers value faster delivery.

However, there are also significant warning signs:

- Only **84% of Express orders are delivered on time**
- Courier utilization increased to **96%**
- Fulfillment cost/order increased from **$4.10 to $5.30**
- Support contacts increased by **32%**
- Refunds increased from **3% to 6%**

This means the feature may be solving the customer problem while creating **operational and financial pressure behind the scenes**.

---

# 2. 📈 Positive Signals

## Customer Adoption

Express Delivery reached **31% adoption** among eligible customers.

This indicates meaningful customer demand for faster delivery.

However, adoption alone does not prove that the feature is profitable or operationally sustainable.

---

## Checkout Conversion

Checkout conversion increased:

**18% → 21%**

This is a positive signal that Express Delivery may be reducing delivery-related hesitation during checkout.

I would still validate this through a controlled experiment to understand the incremental impact of the feature.

---

## Completed Orders

Completed orders increased:

**9% → 11%**

This suggests that the feature may be contributing to additional completed purchases.

---

## Customer Satisfaction

Customer satisfaction increased:

**3.7 → 4.2/5**

This is particularly encouraging because faster delivery appears to improve the customer experience.

---

## Delivery-Related Cancellations

Cancellations decreased:

**8% → 5%**

This suggests that faster delivery may be reducing one of the reasons customers cancel orders.

---

## Additional Revenue

Express Delivery generated:

**+$180K/month**

This is an important business opportunity.

However, I would not consider the $180K additional revenue to be equivalent to additional profit.

The incremental cost of providing Express Delivery needs to be calculated first.

---

# 3. ⚠️ Warning Signs

## Courier Utilization Increased to 96%

This is one of the biggest operational concerns.

A 96% utilization rate could indicate that courier capacity is becoming constrained.

However, I would not immediately assume that the company needs to hire more couriers.

I would first investigate:

- Whether 96% utilization is sustained
- Whether it happens only during peak hours
- Which cities/zones are affected
- Whether delays correlate with high utilization
- Whether couriers are experiencing excessive workload
- Whether warehouse delays are actually the bottleneck

If the data confirms a sustained capacity shortage, then I would work with Operations on increasing courier capacity.

---

## Support Contacts Increased by 32%

This is another major warning sign.

Customers are paying an additional **$4** for a specific delivery promise.

If the order arrives late, customers may feel that they paid for a service they did not receive.

I would categorize Support tickets to identify the most common reasons.

For example:

- Express order delivered late
- Incorrect delivery estimate
- Confusing SLA
- Order was not eligible
- Customer charged the wrong amount
- Warehouse delay
- Courier delay
- Seller delay
- Cancellation after SLA breach

---

## Refunds Increased from 3% to 6%

This is particularly concerning.

A possible explanation is that customers are requesting refunds or compensation because they paid for Express Delivery but did not receive it within the promised timeframe.

I would investigate the relationship between:

**SLA breach → Support contact → Refund**

This would help identify whether late Express deliveries are directly driving the increase in refunds.

---

## Fulfillment Cost Increased

Average fulfillment cost per order increased:

**$4.10 → $5.30**

This is a **$1.20 increase per order**.

That means the additional $4 Express fee cannot automatically be considered profit.

I need to understand the full incremental cost of Express Delivery.

---

# 4. 🔍 Root-Cause Hypotheses

I would create several hypotheses across different parts of the operation.

## Hypothesis 1 — Courier Capacity

Express demand may be exceeding courier capacity in certain locations or periods.

This could result in:

- Delayed deliveries
- High courier utilization
- Increased refunds
- Increased Support contacts

---

## Hypothesis 2 — Warehouse Processing

The warehouse may not be able to prioritize Express orders effectively.

For example:

**Express order received → warehouse queue → standard fulfillment process → courier receives order too late**

In this case, adding more couriers would not solve the actual problem.

---

## Hypothesis 3 — Inventory Availability

Some products may be technically eligible for Express Delivery but difficult to fulfill quickly because of:

- Low inventory
- Inventory stored far from the customer
- Multiple warehouse transfers
- Picking/packing delays

---

## Hypothesis 4 — Delivery Zones

Some geographic areas may have insufficient courier capacity.

Express may work well in central/high-density areas but perform poorly in more difficult delivery zones.

---

## Hypothesis 5 — Peak-Hour Capacity

The feature may perform well during normal hours but fail during:

- Lunch peaks
- Evening peaks
- Weekends
- Campaign periods
- High-demand events

---

## Hypothesis 6 — Seller Performance

Some sellers may consistently take too long to prepare Express orders.

The marketplace could technically offer Express Delivery while the seller is unable to meet the required SLA.

---

## Hypothesis 7 — SLA Calculation

The estimated delivery time may be incorrectly calculated.

For example, the system might promise:

> “Delivery within 24 hours”

without correctly considering:

- Warehouse processing time
- Seller preparation time
- Courier availability
- Cut-off times
- Weekends/holidays
- Customer location

---

## Hypothesis 8 — UX / Customer Expectations

The UI may not clearly explain the Express Delivery promise.

Customers may misunderstand:

- What “24 hours” means
- The exact delivery deadline
- Cut-off times
- Eligible products
- Eligible areas
- Additional fees
- What happens if the SLA is missed

---

# 5. 🧑‍🤝‍🧑 Segmentation

I would segment the data before deciding on the solution.

## Geographic

- Country
- City
- Delivery zone
- Urban vs. less dense areas

## Customer

- New vs. existing
- First-time vs. repeat users
- Frequent vs. occasional customers

## Product

- Product category
- Order value
- Product size/weight
- Express vs. Standard eligibility

## Seller

- Seller
- Seller performance
- Seller preparation time
- Seller location

## Warehouse

- Warehouse
- Warehouse processing time
- Inventory availability
- Picking/packing time

## Operational

- Peak vs. off-peak
- Courier availability
- Courier utilization
- Delivery distance
- Order volume

## Behavioral

- Express vs. Standard users
- First-time Express users
- Repeat Express users
- Customers who experienced an SLA breach

This segmentation would help determine whether the problem is **global or concentrated in specific segments**.

---

# 6. 🧑‍💻 Customer Experience

Customers are paying **$4 extra** for a faster delivery promise.

Therefore, the product promise must be very clear and reliable.

I would investigate:

- What percentage of Express orders miss the SLA?
- Where do the delays happen?
- How many customers contact Support after a delay?
- How many customers request refunds?
- Do customers understand the 24-hour promise?
- Are customers informed when their order is at risk of missing the SLA?

### UX Improvements

The checkout page should clearly communicate:

> 🚚 **Express Delivery — $4**  
> Get your order within 24 hours.

If there are conditions:

> Available for eligible products and delivery areas.  
> Orders placed after the daily cut-off may be delivered the following day.

If an order is delayed, the customer should receive proactive communication instead of discovering the problem themselves.

For example:

> ⚠️ **Your Express Delivery is delayed**  
> We're sorry. Your order is now expected by [updated time].  
> [Track Order]

This can help reduce uncertainty and unnecessary Support contacts.

---

# 7. 🚚 Operations & Scalability

Courier utilization increased:

**81% → 96%**

I would **not immediately hire more couriers**.

First, I would determine whether the capacity problem is:

- Structural
- Temporary
- Peak-hour specific
- Zone-specific
- Campaign-related

I would also identify the actual bottleneck.

The bottleneck could be:

**Seller → Warehouse → Picking/Packing → Courier Assignment → Delivery**

Adding couriers will not solve a warehouse bottleneck.

### If the data confirms a courier shortage

Then I would consider:

- Increasing courier capacity
- Hiring additional couriers
- Using third-party delivery partners
- Adjusting courier incentives
- Restricting Express availability during capacity-constrained periods

The goal is to increase capacity **based on demand patterns**, rather than simply increasing headcount.

---

# 8. 💰 Business & Unit Economics

The company generated:

**+$180K/month in Express Delivery revenue**

But fulfillment cost increased from:

**$4.10 → $5.30 per order**

The important question is:

> **Does the additional Express revenue cover the incremental cost of providing the Express service?**

I would calculate the **incremental contribution margin per Express order**.

### Example

If Express generates:

**+$4 additional revenue**

but requires:

- +$1.20 fulfillment cost
- Additional courier incentives
- Additional warehouse cost
- Additional refunds
- Additional Support cost

then the actual incremental profit could be much lower than $4.

Therefore, I would analyze:

- Express fee revenue
- Incremental fulfillment cost
- Courier cost
- Warehouse cost
- Refund cost
- Support cost
- Compensation for SLA breaches
- Contribution margin per Express order

### Key Business Metric

**Incremental Contribution Margin per Express Order**

This would help determine whether the feature is financially sustainable.

---

# 9. 📊 Metrics Framework

## 🎯 Primary Metric

### On-Time Express Delivery Rate

The core customer promise is faster delivery.

Therefore, I would make **On-Time Express Delivery Rate** the primary operational/product metric.

The current level of **84%** means there is still a significant gap to address.

---

## 📈 Secondary Metrics

- Express Delivery adoption
- Checkout conversion
- Completed orders
- Customer satisfaction
- Delivery-related cancellation rate
- Repeat purchase rate
- Express order volume

---

## 🛡️ Guardrail Metrics

- Refund rate
- Support contacts
- Customer complaints
- Courier utilization
- Late delivery rate
- SLA breach rate
- Customer satisfaction

---

## 💰 Business Metrics

- Express fee revenue
- Incremental fulfillment cost
- Courier cost
- Refund/compensation cost
- Support cost
- Contribution margin per Express order
- Incremental revenue per Express customer

---

# 10. 🧪 Experimentation

I would use controlled experiments to identify the best way to scale Express Delivery sustainably.

## Experiment 1 — Capacity-Based Eligibility

Only show Express Delivery when sufficient operational capacity exists.

For example:

> Express available ✅

or:

> Express unavailable right now due to capacity constraints.

This could protect the SLA during high-demand periods.

---

## Experiment 2 — Peak-Hour Availability

Test limiting Express Delivery during periods where courier utilization is extremely high.

Compare:

**Always available**

vs.

**Available only when capacity is sufficient**

Measure:

- On-time delivery
- Conversion
- Adoption
- Revenue
- Support
- Refunds
- Contribution margin

---

## Experiment 3 — Express Pricing

Test different Express prices in selected segments.

For example:

- $3
- $4
- $5

The objective would be to determine the optimal balance between:

**Demand + Conversion + Customer Value + Profitability**

---

## Experiment 4 — SLA Communication

Test clearer delivery messaging.

For example:

**Control:**  
“Express Delivery — 24 hours”

**Treatment:**  
“Order by 4 PM and receive your order by tomorrow.”

Measure:

- Conversion
- Customer understanding
- Support contacts
- Refunds
- SLA complaints

---

## Experiment 5 — Warehouse Prioritization

Test whether prioritizing Express orders in warehouse processing improves:

- Fulfillment time
- On-time delivery
- Cancellation rate
- Customer satisfaction

---

# 11. 🚀 Rollout Decision

## Option A — Roll Out to 100%

❌ **I would not choose this yet.**

Although the feature has strong customer and business signals, scaling immediately could:

- Push courier utilization beyond sustainable levels
- Increase SLA failures
- Increase refunds
- Increase Support volume
- Increase operational costs
- Reduce customer trust

---

## Option B — Stop the Feature

❌ **I would not choose this either.**

The feature is clearly providing value:

- Conversion increased
- Completed orders increased
- Satisfaction increased
- Cancellations decreased
- Customers are adopting the feature
- Additional revenue is being generated

There is no reason to kill a feature that is solving a real problem.

---

## Option C — Keep It Controlled, Fix the Issues, and Re-Test

✅ **This would be my decision.**

I would:

1. Identify the operational bottleneck.
2. Analyze SLA breaches by zone, warehouse, seller, and peak period.
3. Investigate Support and refund reasons.
4. Validate the true incremental cost of Express Delivery.
5. Improve SLA communication.
6. Introduce capacity-based eligibility if necessary.
7. Run controlled experiments.
8. Monitor contribution margin and customer experience.
9. Gradually increase exposure when operational capacity and economics support it.

---

# 12. 🤝 Stakeholder Management

I would not tell stakeholders:

> “The feature isn't working.”

Because it **is** generating meaningful value.

Instead, I would communicate the situation using both the opportunities and the risks.

### To Growth

> “Adoption and conversion are strong, so there is clear customer demand. However, we need to solve capacity and SLA issues before increasing exposure.”

### To Finance

> “The feature generates $180K/month in fee revenue, but I want to validate incremental contribution margin after fulfillment, courier, refund, and Support costs.”

### To Operations

> “The 96% courier utilization suggests capacity pressure. Let's identify whether this is structural or concentrated in specific zones and peak periods before deciding on additional capacity.”

### To Support

> “Let's categorize the +32% Support increase and identify whether most contacts are related to SLA breaches, pricing, eligibility, or communication.”

### To Leadership

> “The feature is promising and clearly solving a customer need, but scaling now could amplify operational and financial problems. I recommend a controlled rollout while we address SLA reliability, capacity, and unit economics.”

---

# 🧠 Final Product Decision

> **“Express Delivery is showing strong customer value and promising business results, but I would not scale it to 100% yet. The increase in courier utilization, Support contacts, refunds, and fulfillment costs indicates that the operational model is under pressure. I would first identify the bottleneck, validate the incremental economics, improve SLA reliability and customer communication, and then use controlled experiments to determine the right pricing and eligibility model. Once the customer experience, operational capacity, and contribution margin are sustainable, I would gradually scale the feature.”**

---

# 💡 Key Product Takeaway

A product feature doesn't exist in isolation.

You can have:

📈 Higher conversion  
📈 More completed orders  
📈 Better customer satisfaction  
📈 Lower cancellations  
💰 Higher revenue  

while simultaneously creating:

⚠️ Operational overload  
⚠️ Higher fulfillment costs  
⚠️ More refunds  
⚠️ More Support contacts  
⚠️ Unsustainable courier utilization  

The Product Owner's job is not simply to maximize adoption.

It is to make sure that **customer value, operational scalability, and business economics can grow together.**

> **A feature is ready to scale when the whole system can support its success — not just when the dashboard looks good.**
