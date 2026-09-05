# Case Study 13 — Buy Now, Pay Later (BNPL)

## Product Discovery, Customer Research & Prioritization

---

## 📌 Case Overview

**Industry:** E-commerce  
**Role:** Product Owner  
**Product Area:** Payments / Checkout  
**Focus Areas:** Product Discovery, Customer Research, Prioritization, MVP, Risk Assessment, Stakeholder Management

---

## 🧩 The Challenge

An e-commerce platform is considering introducing a **Buy Now, Pay Later (BNPL)** option that allows customers to split their purchases into installments.

The Commercial team strongly supports the idea because they believe BNPL could:

- Increase checkout conversion
- Increase Average Order Value (AOV)
- Attract new customers
- Improve competitiveness
- Reduce price-related cart abandonment

However, the proposal comes with several uncertainties and risks.

The Product Owner needs to decide:

> **Should BNPL be prioritized now, or should the team focus on another initiative with stronger evidence of customer value?**

---

# 📊 Current Data

The following information is available:

| Metric / Constraint | Current Situation |
|---|---|
| Customers using Cash on Delivery | 60% |
| Cart abandonment due to high total price | 25% |
| Support requests asking for installments | 8% |
| Full BNPL integration | ~10 weeks |
| Legal / Compliance | Additional review required |
| Finance | Concerned about default risk |
| Competitors | Several competitors already offer BNPL |

---

# 👥 Stakeholder Perspectives

### Commercial

> "Competitors already have BNPL, and we're losing customers because we don't."

Commercial expects BNPL to improve conversion, AOV, and customer acquisition.

### Finance

Finance is concerned about **credit/default risk** and wants to understand who would carry the financial risk.

### Engineering

Engineering estimates approximately **10 weeks** for a full BNPL integration.

### Legal & Compliance

Additional regulatory and compliance review is required before implementation.

### Marketing

Marketing sees BNPL as a potential opportunity for a customer acquisition campaign.

### Leadership

Leadership wants to understand whether customers genuinely want installments before making a significant investment.

---

# 🔎 Step 1 — Understand the Customer Problem

My first step would **not** be to immediately add BNPL to the roadmap.

I would first understand whether there is a meaningful customer problem behind the request.

The 25% price-related cart abandonment is an interesting signal.

However:

> **Price-related abandonment does not automatically mean BNPL is the solution.**

Customers could be abandoning because:

- The product is too expensive
- Shipping increases the total price
- The customer found a cheaper competitor
- Unexpected fees appear at checkout
- The customer does not have enough money at the moment
- The customer doesn't trust the available payment methods
- The customer simply changed their mind

Therefore, I would investigate the underlying reason rather than assuming BNPL solves the problem.

---

# 📊 Step 2 — Analyze Existing Customer Evidence

The available data gives us several useful signals.

### 60% use Cash on Delivery

This tells us that payment behavior is important.

However, it does **not** automatically mean that BNPL will be attractive to the remaining 40%.

I would segment customers by:

- Payment method
- Customer type
- New vs. existing customers
- Order value
- Country / market
- Device
- Purchase frequency
- Product category

The goal would be to identify which customer segments experience the problem most strongly.

---

### 25% abandon because of price

This is potentially the strongest customer-problem signal.

I would investigate:

**Price-related abandonment → Customer segment → Order value → Product category → Payment behavior**

For example:

If customers placing high-value orders are significantly more likely to abandon because of price, BNPL could potentially solve a meaningful problem for that segment.

---

### 8% Support requests mention installments

This is useful evidence, but it should not be treated as the total demand for BNPL.

Customers may:

- Never contact Support
- Not know BNPL is possible
- Not know how to request it
- Abandon before contacting Support
- Use different language when describing the problem

Therefore:

> **The 8% Support requests are a signal, but they are not enough to estimate total customer demand.**

---

# 🗣️ Step 3 — Customer Research

Before committing 10 weeks of Engineering capacity, I would conduct lightweight Product Discovery.

### Customer Interviews

I would ask customers who abandoned high-value carts:

- Why did you abandon your purchase?
- Was the total price the main reason?
- Would installment payments have changed your decision?
- How often do you use installment services?
- What concerns would you have about BNPL?
- Would you trust BNPL provided through the platform?

---

### 📋 Surveys

A survey could help quantify:

- Interest in installments
- Preferred payment methods
- Maximum acceptable installment amount
- Customer concerns
- Expected usage frequency

---

### 🎧 Support Analysis

I would analyze Support conversations for themes such as:

- "Too expensive"
- "Can't afford the full amount"
- "Need installments"
- "Payment failed"
- "Unexpected fees"
- "Found a cheaper option"

This would help determine whether the actual problem is affordability, payment friction, or something else.

---

# 🧪 Step 4 — Fake Door Experiment

Before building the complete BNPL infrastructure, I would consider a **fake-door experiment**.

For example:

Add a clearly labeled:

> **"Pay in installments"**

option at checkout for a controlled group.

When customers click it, instead of completing a real BNPL transaction, we could explain:

> "Installment payments are coming soon. Would you like to be notified?"

We could measure:

- BNPL option impressions
- Click-through rate
- Customer interest
- Segment-level demand
- Order value of interested customers
- Conversion behavior

This would give us stronger evidence before committing to a 10-week integration.

---

# 🏆 Step 5 — Competitor Analysis

Commercial's competitor argument is important, but I would not use it as the only justification.

The statement:

> "Our competitors have BNPL."

does not prove:

> "Customers are leaving us because we don't have BNPL."

I would investigate:

- Are customers actually switching because of BNPL?
- Which competitors are winning these customers?
- Which customer segments are affected?
- Does BNPL materially improve their conversion?
- What transaction values are most common?
- What financial risks do those models carry?

### Product Principle

**Competitor parity is a signal for discovery, not automatic roadmap prioritization.**

---

# ⚠️ Step 6 — Understand the Risks

BNPL introduces risks that need to be understood before implementation.

## 💰 Credit / Default Risk

This is different from security risk.

Key questions include:

- Who provides the credit?
- Who carries the default risk?
- What happens if the customer doesn't repay?
- Who manages collections?
- What customers are eligible?
- What is the maximum transaction value?
- What happens if repayment fails?
- What fees or penalties apply?

---

## ⚖️ Legal & Compliance Risk

The Product team should work with Legal and Compliance to understand:

- Regulatory requirements
- Customer disclosures
- Eligibility rules
- Terms and conditions
- Required consent
- Cancellation and refund rules
- Data requirements

---

## 🔐 Security & Privacy

Security is also important, but it is a separate risk area.

Questions include:

- What customer data is shared with the BNPL provider?
- How is payment information protected?
- What authentication is required?
- What data retention rules apply?

---

# 🧪 Step 7 — MVP Strategy

If Product Discovery confirms strong demand, I would not immediately launch BNPL to 100% of customers.

I would propose a controlled MVP.

### Potential MVP

Start with:

- One BNPL provider
- One market
- A limited customer segment
- Selected product categories
- A transaction-value limit
- A controlled percentage of eligible customers

For example:

> Customers making higher-value purchases could be the first target segment.

This allows us to test whether BNPL actually improves behavior while limiting financial and operational risk.

---

# 📈 Step 8 — Define Success Metrics

Before launching an MVP, I would define success criteria.

## 🎯 Primary Metrics

### BNPL Adoption Rate

Percentage of eligible customers who choose BNPL.

### BNPL Conversion Rate

Percentage of customers using BNPL who successfully complete their purchase.

---

## 📊 Secondary Metrics

- Overall checkout conversion
- Completed orders
- Average Order Value (AOV)
- Revenue per user
- New customer acquisition
- Repeat purchase rate
- Customer retention

---

## 🚨 Guardrail Metrics

Because BNPL introduces financial risk, guardrails are particularly important.

### Financial

- Default rate
- Repayment rate
- Contribution margin
- BNPL transaction cost

### Customer Experience

- Cancellation rate
- Refund rate
- Complaints
- Support contacts
- Payment failures

### Risk

- Fraud rate
- Failed repayments
- Provider failures

---

# ⚖️ Step 9 — Prioritization

The company can only deliver **one initiative** during the available period.

The three main options are:

### Option A — BNPL

**Estimated effort:** 10 weeks

**Potential impact:** High

**Evidence:** Not yet validated

**Risks:** High

- Financial risk
- Regulatory risk
- Operational risk
- Customer demand uncertainty

---

### Option B — Checkout Optimization

**Estimated effort:** 5 weeks

**Potential impact:** High

**Evidence:** Strong

There is already clear evidence of checkout abandonment.

This initiative addresses an existing customer problem with less uncertainty.

---

### Option C — Search Improvement

**Estimated effort:** 4 weeks

**Potential impact:** Medium

**Evidence:** Strong customer complaints

Search improvement is valuable, but the expected business impact appears lower than checkout optimization based on the current information.

---

# 🧠 My Prioritization Decision

I would prioritize:

## 🥇 Checkout Optimization

Why?

### 1. Stronger evidence

We already have evidence of a meaningful checkout problem.

### 2. Lower uncertainty

We understand the problem better than we understand BNPL demand.

### 3. Faster time to value

The estimated effort is around 5 weeks versus 10 weeks for BNPL.

### 4. Lower risk

BNPL introduces additional financial and regulatory complexity.

### 5. Clearer measurement

We can directly measure improvements in checkout conversion and completed orders.

---

# 💳 What Happens to BNPL?

I would **not reject BNPL permanently**.

Instead:

> **BNPL should move into Product Discovery while Checkout Optimization is prioritized for delivery.**

During that time, Product can:

1. Conduct customer research
2. Analyze Support data
3. Run a fake-door experiment
4. Validate demand
5. Work with Finance on default risk
6. Work with Legal on compliance
7. Evaluate potential BNPL providers
8. Define an MVP

If the evidence is strong, BNPL can then move into the roadmap with significantly less uncertainty.

---

# 🤝 Stakeholder Management

I would communicate the decision differently to each stakeholder.

### Commercial

"We're not rejecting BNPL. We need to validate whether it is actually driving customer demand before committing 10 weeks of Engineering capacity."

### Finance

"We'll investigate default exposure, repayment behavior, and financial impact before moving to an MVP."

### Engineering

"We'll use Discovery to clarify requirements and reduce uncertainty before asking for a full integration."

### Legal

"We'll involve Compliance early rather than waiting until development is underway."

### Marketing

"We can prepare potential acquisition experiments once demand and eligibility are validated."

### Leadership

"We have a clear customer problem today that we can address in 5 weeks. BNPL has high potential, but its demand and risks are not yet sufficiently validated. We'll continue discovery so we can make a stronger investment decision."

---

# 🎯 Final Product Decision

### Decision:

**Prioritize Checkout Optimization for delivery.**

### BNPL:

**Keep in Product Discovery and validate before committing to full implementation.**

If discovery demonstrates:

- Strong customer demand
- Meaningful conversion potential
- Acceptable default risk
- Acceptable financial impact
- Legal and regulatory feasibility

then proceed with a **controlled BNPL MVP**.

---

# 🔄 Product Decision Framework

My approach would be:

```text
Customer Problem
       ↓
Existing Evidence
       ↓
Customer Discovery
       ↓
Demand Validation
       ↓
Risk Assessment
       ↓
MVP / Experiment
       ↓
Measure Results
       ↓
Prioritize & Scale
