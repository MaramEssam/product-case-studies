# 🍔 Case Study #2 — Should We Build Scheduled Delivery?

> **30 Product Case Studies — Case #2**
> A hypothetical product case created as part of my Product Management learning journey.

---

## 📌 Overview

A food delivery app's Customer Support team reports **thousands of customer requests** for a Scheduled Delivery option.

At first glance, this sounds like a clear feature opportunity.

However, the feature is estimated to require **3 months of engineering effort**, while the team is already committed to other initiatives.

The key Product question is:

> **Is this feature valuable enough to justify the investment?**

Rather than immediately deciding to build it, I would first validate the problem, understand the potential business impact, and assess the technical effort.

---

# 🚨 The Problem

### Customer Signal

Customer Support reports thousands of requests for:

> **"I want to schedule my delivery for a specific time."**

### Current Constraints

* Engineering estimates **3 months** to build the feature.
* The team already has committed initiatives.
* We don't yet know how many customers would actually use the feature.
* We don't know how frequently customers experience the underlying problem.
* The business impact has not yet been quantified.

---

# 🎯 Product Goal

My goal would not be to answer:

> **"Should we build Scheduled Delivery?"**

Instead, I would first answer:

> **"Is there a meaningful customer problem here, and is solving it worth the opportunity cost of 3 months of engineering capacity?"**

---

# 🔎 1. Understand the Problem

The first thing I would investigate is **why customers are asking for scheduled delivery**.

Potential use cases could include:

* Customers who are not available to receive orders immediately
* Employees who want deliveries around their work schedules
* Students with limited availability
* Customers planning meals in advance
* Customers who want more control over delivery timing

These are potential use cases, not confirmed problems.

I would validate them before making a product decision.

---

# 📊 2. Questions I Would Investigate

### Customer Demand

* How many unique customers requested the feature?
* What percentage of active customers does this represent?
* How frequently do customers encounter this problem?
* Are requests concentrated among specific customer segments?
* Are these customers new, returning, or high-value customers?

### Customer Impact

* Does the lack of scheduled delivery cause cancellations?
* Does it lead to failed or missed deliveries?
* Does it negatively affect customer satisfaction?
* Are customers switching to competitors because of this limitation?
* Are customers contacting Support because they cannot control delivery timing?

### Business Impact

* Could scheduled delivery increase order frequency?
* Could it improve customer retention?
* Could it reduce failed deliveries?
* Could it reduce Customer Support contacts?
* Could it increase conversion or average order frequency?

---

# 👥 3. Customer Segmentation

I would avoid looking only at the **number of requests**.

I'd also understand **who is requesting the feature**.

For example:

| Segment              | Questions                                                |
| -------------------- | -------------------------------------------------------- |
| New Customers        | Is this an onboarding or expectation issue?              |
| Returning Customers  | Is scheduling related to repeat purchasing behavior?     |
| High-Value Customers | Could this feature improve retention or order frequency? |
| Occasional Customers | Is demand too infrequent to justify the investment?      |
| Customer Location    | Are some areas more affected by delivery availability?   |

A request from a high-value, frequently ordering customer segment may have a different business impact than the same request coming primarily from occasional users.

---

# 🧪 4. Validate Demand Before Building

Before committing **3 months of engineering capacity**, I would consider lightweight validation.

## Option 1 — Fake Door Test

Expose a **"Schedule Delivery"** option to a controlled percentage of users.

When users select it, instead of actually scheduling the order, we could explain that the capability is not yet available and optionally collect interest.

### What this can tell us

* Feature interest
* Interest by customer segment
* Interest by order type
* Potential demand volume

However:

> **A click is only a signal — not proof that customers will use the feature repeatedly.**

So I would combine this with additional research.

---

## Option 2 — Customer Interviews

Interview customers who:

* Requested the feature
* Frequently contact Support
* Frequently order food
* Have previously abandoned or cancelled orders

Questions could focus on:

* When do you need scheduled delivery?
* How do you currently solve this problem?
* How often does this happen?
* What happens when you cannot schedule delivery?
* Would you change your ordering behavior if scheduling were available?

The goal is to understand the **underlying problem**, not simply ask:

> "Would you use this feature?"

---

## Option 3 — Behavioral Data

I would analyze existing product data for signals such as:

* Failed deliveries
* Cancellations
* Delivery timing complaints
* Support contacts
* Order frequency
* Customer retention
* Orders placed during specific time windows

This helps connect the feature request to measurable customer and business outcomes.

---

# ⚙️ 5. Understand the Technical Complexity

The **3-month estimate** should not be treated as a black box.

I would work with Engineering to understand what is driving the effort.

Potential complexity could include:

### Backend

* New scheduling logic
* Order state management
* Time-slot management

### Logistics

* Driver allocation
* Delivery capacity
* Time-slot availability
* Restaurant preparation timing

### Integrations

* Order Management System
* Dispatch / logistics systems
* Notifications
* Payment flows

### Customer Experience

* Selecting a delivery slot
* Editing or cancelling scheduled orders
* Notifications and reminders
* Handling unavailable time slots

This conversation could reveal opportunities to reduce scope and build a smaller MVP.

---

# 🧩 6. Explore an MVP

Instead of building a fully flexible scheduling system immediately, I would explore whether we can solve the core problem with a smaller version.

### Example MVP

Instead of:

> "Choose any exact delivery time."

Start with:

> **Choose from 2–3 available delivery windows.**

For example:

**12–2 PM | 2–4 PM | 6–8 PM**

This could significantly reduce complexity while still testing whether customers value the underlying capability.

---

# 🚀 7. Controlled Rollout

If initial validation shows strong demand, I would not necessarily launch to everyone immediately.

A possible approach:

**MVP → Limited Rollout → Measure → Iterate → Scale**

Start with a controlled segment or specific delivery area, then evaluate the results before expanding.

---

# 📈 8. Success Metrics

I would define success before launching.

### Customer Metrics

* Scheduled Delivery adoption rate
* Repeat usage
* Customer satisfaction
* Cancellation rate
* Failed delivery rate

### Business Metrics

* Order frequency
* Retention
* Conversion
* Revenue per customer
* Customer Support contacts

### Operational Metrics

* On-time delivery rate
* Delivery capacity utilization
* Driver efficiency
* Scheduling-related failures

---

# 🎯 9. Prioritization Framework

The final decision should consider more than customer demand.

I would evaluate:

### Customer Value

How significant is the problem?

### Business Impact

What measurable outcome could solving it improve?

### Confidence

How strong is the evidence supporting the opportunity?

### Engineering Effort

How much time and complexity are required?

### Opportunity Cost

What other valuable initiatives would we delay by spending 3 months on this?

A simple way to think about the decision:

```text
High Value + High Impact + High Confidence + Low/Manageable Effort
                              ↓
                         Strong Candidate
```

Whereas:

```text
High Demand
     +
Low Business Impact
     +
High Engineering Effort
     ↓
Not necessarily a priority
```

---

# 🧠 10. My Decision Framework

I would **not** make the decision based solely on:

> "Thousands of customers requested it."

Instead, I would move through:

```text
Customer Request
       ↓
Understand the Underlying Problem
       ↓
Measure the Size of the Problem
       ↓
Identify Affected Segments
       ↓
Validate Demand
       ↓
Estimate Business Impact
       ↓
Understand Technical Effort
       ↓
Explore MVP
       ↓
Compare Against Other Opportunities
       ↓
Prioritize
```

---

# 💭 Key Takeaway

One of the biggest lessons from this case is:

> **A feature request is not automatically a product priority.**

Customers can ask for a feature, but as Product Managers, we still need to understand:

**Why do they want it?**

**How big is the problem?**

**Who experiences it?**

**What business outcome could solving it create?**

**And is that value worth the engineering investment and opportunity cost?**

The goal isn't to build the most requested feature.

**The goal is to solve the most valuable problems.**

---

## 🧩 Skills Practiced

* Product Discovery
* Customer Problem Validation
* Feature Validation
* Fake Door Testing
* Customer Interviews
* Customer Segmentation
* Business Impact Analysis
* MVP Definition
* Technical Feasibility
* Prioritization
* Opportunity Cost
* Product Metrics
* Experimentation
* Cross-functional Collaboration

---

## 📚 About This Series

This is **Case Study #2 of 30 hypothetical Product Case Studies** I'm working through as part of my Product Management learning journey.

The cases are designed to help me practice applying Product concepts to realistic scenarios rather than only studying frameworks theoretically.

### Areas covered throughout the series:

* Product Thinking
* Product Analytics
* Discovery & UX
* Prioritization
* Technical Product Management
* Agile Product Delivery
* AI Product Management

**30 cases. 30 problems. One goal: become a better Product thinker. 🚀**

---

## ⚠️ Disclaimer

This is a **hypothetical case study** created for learning and portfolio purposes.

The scenario, customer requests, timelines, and business context are fictional and are not presented as real company data or confidential work experience.
