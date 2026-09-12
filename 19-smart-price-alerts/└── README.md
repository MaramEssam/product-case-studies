# Case Study #19 — Smart Price Alerts: When Adoption Increases but Trust Becomes a Problem

## 📌 Overview

An e-commerce marketplace launched a new **Smart Price Alerts** feature.

Customers can select a product and receive a notification when its price drops.

For example:

> 🔔 “Nike Running Shoes dropped from $95 to $79.”

### 🎯 Goals

The feature was designed to:

- Increase repeat visits
- Encourage customers to return to products they are interested in
- Increase purchase conversion
- Help customers find better prices
- Increase engagement
- Drive incremental purchases

After 8 weeks, the feature was available to **60% of eligible customers**.

At first glance, the results looked positive. However, deeper analysis revealed several **customer trust, UX, and business risks**.

---

## 📊 Results After 8 Weeks

| Metric | Result |
|---|---:|
| Price Alert Adoption | **34%** |
| Alert Open Rate | **61%** |
| Product Page Visits | **+38%** |
| Add-to-Cart | **11% → 15%** |
| Checkout Initiation | **7% → 9%** |
| Completed Orders | **5% → 6%** |
| AOV | **$48 → $43** |
| 30-Day Retention | **30% → 32%** |
| Support Contacts | **+35%** |
| Alert Unsubscribe Rate | **18%** |
| Refund Requests | **3% → 5%** |

---

# 1. 🚦 Initial Product Assessment

My first reaction would be:

> **The feature shows promising engagement and conversion signals, but I would not consider it fully successful yet.**

There are clear positive signals:

- 34% adoption
- 61% alert open rate
- 38% increase in product page visits
- Add-to-cart increased from 11% to 15%
- Checkout initiation increased from 7% to 9%
- Completed orders increased from 5% to 6%
- 30-day retention increased from 30% to 32%

However, there are also important warning signs:

- AOV decreased from $48 to $43
- Support contacts increased by 35%
- Refund requests increased from 3% to 5%
- Unsubscribe rate reached 18%

The biggest concern is that some customers received an alert showing one price but saw a different price when opening the product.

This creates a **customer trust problem**, which is particularly serious for a price-related feature.

---

# 2. 📈 Positive Signals

The feature appears to be generating genuine customer interest.

### Engagement

The **34% adoption rate** indicates that a meaningful portion of eligible customers are interested in receiving price alerts.

The **61% open rate** is also a strong engagement signal.

### Customer Re-engagement

Product page visits increased by **38%**, suggesting that the alerts are successfully bringing customers back to the marketplace.

### Funnel Movement

The purchasing funnel also improved:

**Product Page → Add-to-Cart → Checkout → Completed Order**

- Add-to-cart: 11% → 15%
- Checkout initiation: 7% → 9%
- Completed orders: 5% → 6%

These results suggest that the feature has potential to influence purchasing behavior.

However, I would still validate whether these improvements are actually **caused by the feature** rather than simply correlated with it.

---

# 3. ⚠️ Warning Signs

The most important warning signs are related to **trust, profitability, and customer experience**, not just engagement.

## AOV Decreased

AOV dropped from:

**$48 → $43**

This is approximately a **10.4% decrease**.

I would not immediately assume that Price Alerts caused the decline.

I would investigate whether customers are:

- Buying cheaper products
- Waiting for discounts
- Using more discounted products
- Purchasing fewer products per order
- Changing their purchasing behavior because of the alerts

AOV alone is not enough to determine whether the feature is financially successful.

---

## Support Contacts Increased by 35%

This is a major warning sign.

If customers receive:

> “Price dropped to $79”

but then see:

> “Current price: $89”

they may feel that the marketplace is misleading them.

I would categorize Support tickets to understand the main reasons behind the increase.

Possible categories:

- Price mismatch
- Expired promotion
- Product unavailable
- Seller changed the price
- Notification received too late
- Confusion about discount conditions
- Wrong product or variant
- Technical issue

---

## Refund Requests Increased

Refund requests increased from:

**3% → 5%**

I would investigate whether customers are purchasing because of the alert and then discovering that:

- The price was different
- The offer was no longer valid
- The product condition changed
- The product was unavailable
- The alert information was inaccurate

---

## Alert Unsubscribe Rate

An **18% unsubscribe rate** is another important signal.

I would investigate whether users unsubscribe because:

- They receive too many notifications
- The alerts are no longer relevant
- The price shown in the notification is inaccurate
- They feel the notifications are misleading
- They are waiting for discounts but not finding useful ones

---

# 4. 🔍 Key Hypotheses

I would create several hypotheses rather than assuming there is only one root cause.

## Hypothesis 1 — Price Synchronization Issue

The notification system may be using outdated pricing data.

Possible flow:

**Product price changes → Marketplace database updates → Notification system still has old price → Customer receives outdated alert**

---

## Hypothesis 2 — Notification Delay

The notification may be generated correctly but delivered too late.

For example:

- 10:00 AM — Product price becomes $79
- 10:05 AM — Alert is generated
- 10:20 AM — Promotion ends
- 10:30 AM — Customer receives the notification
- Customer opens the product and sees $89

The notification may have been technically correct when generated but incorrect when the customer acted on it.

---

## Hypothesis 3 — Limited-Quantity Promotion

The discounted price may only apply to a limited quantity.

For example:

- First 20 customers get the $79 price
- Customer #21 receives the alert
- The discounted quantity is already sold out
- Customer sees the normal $89 price

This would create a poor customer experience unless the limitation is clearly communicated.

---

## Hypothesis 4 — Seller or Variant Differences

The alert might refer to a specific seller, size, color, or product variant.

The customer could open the product page and see a different price for another seller or variant.

---

## Hypothesis 5 — Customers Become Discount-Dependent

Price Alerts may unintentionally encourage customers to wait for discounts.

Instead of:

> “I want this product, so I'll buy it.”

the customer may start thinking:

> “I'll wait. Maybe the price will drop again.”

This could potentially affect purchasing behavior and AOV.

However, this is only a **hypothesis** and needs behavioral data to validate.

---

# 5. 🧑‍🤝‍🧑 Customer Segmentation

I would segment the data to identify where the problem is concentrated.

### Customer Segments

- New vs. existing customers
- First-time vs. repeat purchasers
- Frequent vs. occasional buyers
- Alert users vs. non-alert users
- Alert openers vs. non-openers
- Customers who purchase after an alert vs. open-only users

### Product Segments

- Product category
- Price range
- Discount percentage
- High-demand vs. low-demand products
- Products with limited inventory
- Products with frequent price changes

### Seller Segments

- Seller
- Seller rating
- Sellers with dynamic pricing
- Sellers with frequent stock changes

### Behavioral Segments

- Number of alerts received
- Alert frequency
- Time between alert and purchase
- Time between alert and product-page visit
- Customers who wait for multiple price drops

### Technical Segments

- Country
- Device type
- Operating system
- App version
- Notification delivery time

---

# 6. 🔐 Customer Trust & UX

The biggest Product concern is **price accuracy**.

If the customer receives:

> 🔔 **“Price dropped from $95 to $79”**

but sees:

> **$89**

on the product page, customer trust can decrease quickly.

I would investigate:

- Is the notification price the latest price?
- How frequently is pricing data refreshed?
- Is the price seller-specific?
- Is the price variant-specific?
- Is the promotion still active?
- Is inventory still available?
- Is there a delay between price change and notification delivery?

### UX Improvements

The notification should clearly communicate the conditions.

For example:

> 🔔 **Price dropped to $79**  
> Available while supplies last.

Or, if the price has already changed:

> 🔔 **The price changed**  
> The item was $79 when your alert was sent. The current price is $89.

I would also consider:

- “Why did I receive this alert?”
- Clear price history
- Clear promotion conditions
- Easy alert management
- Adjustable notification frequency
- Minimum discount threshold
- Easy unsubscribe/manage preferences

---

# 7. 💰 Business Impact

I would not evaluate the feature using AOV alone.

I would analyze:

### Revenue

- Revenue per alerted user
- Incremental revenue
- Incremental orders
- Revenue from alert-assisted purchases

### Profitability

- Gross margin
- Contribution margin
- Discount cost
- Margin per order
- Notification cost

### Customer Value

- Repeat purchase rate
- 30/60/90-day retention
- Customer Lifetime Value (CLV)

The key business question is:

> **Are Price Alerts generating incremental profitable purchases, or are they simply encouraging customers to wait for lower prices?**

---

# 8. 📊 Metrics Framework

## 🎯 Primary Metric

**Alert-Assisted Purchase Conversion Rate**

This measures how effectively a price alert leads to a completed purchase.

I would also monitor:

**Incremental Contribution Margin per Alerted User**

to understand the actual financial value of the feature.

---

## 📈 Secondary Metrics

- Price Alert adoption
- Alert open rate
- Product page visits
- Add-to-cart rate
- Checkout initiation
- Completed orders
- Revenue per user
- AOV
- Repeat purchase rate
- Retention

---

## 🛡️ Guardrail Metrics

- Price accuracy
- Support contacts
- Refund rate
- Cancellation rate
- Complaints
- Unsubscribe rate
- Customer satisfaction

---

## 🤝 Trust Metrics

I would specifically track:

- Price mismatch rate
- Percentage of alerts opened after the price changed
- Incorrect/outdated alert rate
- “Why is the price different?” Support contacts
- Unsubscribe rate after receiving an alert
- Refunds following alert-assisted purchases

---

# 9. 🧪 Experimentation

I would **not roll the feature out to 100% immediately**.

First, I would identify and fix the price accuracy and trust issues.

Then I would run controlled experiments.

## Experiment 1 — Real-Time Price Validation

Compare:

**Control:** Existing price-alert system

**Treatment:** Real-time price validation immediately before sending the notification

Measure:

- Conversion
- Price mismatch rate
- Support contacts
- Refunds
- Unsubscribe rate

---

## Experiment 2 — Minimum Price Drop Threshold

Instead of notifying customers for every small price change, test different thresholds.

For example:

- 5% price drop
- 10% price drop
- 15% price drop

The goal is to find the balance between **usefulness and notification fatigue**.

---

## Experiment 3 — Alert Frequency

Test different notification frequencies:

- Every qualifying price drop
- Maximum one alert per day
- Maximum one alert per product per week

The goal is to balance usefulness with notification fatigue.

---

## Experiment 4 — Personalized Price Threshold

Allow customers to define their preferred threshold.

For example:

> “Notify me when this product drops below $80.”

This gives customers more control and makes the alert more relevant.

---

# 10. 🚀 Rollout Decision

### Option A — Roll out to 100%

❌ **I would not choose this yet.**

There are unresolved trust, refund, support, and price accuracy concerns.

---

### Option B — Stop the Feature Completely

❌ **I would also not choose this.**

The feature has strong engagement signals and appears to generate additional customer activity.

There is still potential value.

---

### Option C — Keep It Controlled, Fix the Issues, and Re-Test

✅ **This would be my decision.**

I would:

1. Investigate price mismatch and notification timing.
2. Analyze Support and refund reasons.
3. Segment customer and product behavior.
4. Validate whether customers are actually delaying purchases for discounts.
5. Improve price accuracy and messaging.
6. Run a controlled A/B test.
7. Monitor conversion and profitability/trust guardrails.
8. Gradually expand only if the experiment demonstrates sustainable value.

---

# 11. 🧠 Final Product Decision

I would summarize my decision to stakeholders like this:

> **“Smart Price Alerts show strong engagement and promising conversion signals, but I would not scale the feature yet. The increase in Support contacts, refunds, unsubscribes, and the price mismatch issue indicate a potential trust problem. I would first validate the root cause, improve price accuracy and transparency, then run a controlled experiment to determine whether the feature generates incremental and sustainable customer and business value.”**

---

# 💡 Key Product Takeaway

**High adoption does not automatically mean product success.**

A feature can have:

📈 High adoption  
📈 High open rates  
📈 More product visits  
📈 Higher conversion  

and still create problems if it:

⚠️ Reduces customer trust  
⚠️ Increases refunds  
⚠️ Increases Support volume  
⚠️ Changes purchasing behavior negatively  
⚠️ Reduces profitability  

For price-related products especially:

> **Accuracy and trust are not secondary details — they are part of the product itself.**

---

## 📁 GitHub Structure

```text
19-smart-price-alerts/
└── README.md
